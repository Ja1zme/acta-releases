<picture>
  <source media="(prefers-color-scheme: dark)" srcset="logo-horizontal-dark.png">
  <img src="logo-horizontal-light.png" alt="Acta" width="300">
</picture>

# Acta: descargas

Acta graba tus reuniones y las convierte en actas en tu propio equipo: transcripción, quién habló, resumen, decisiones y tareas. Nada sale a la nube.

Este repositorio solo guarda los instaladores firmados. El código no se publica.

## Windows

Graba las reuniones de Teams, Google Meet, Zoom y otras apps: tu micrófono y lo que se oye en el equipo. También importa grabaciones y vigila una carpeta.

- **Descarga:** `Acta_x.y.z_x64-setup.exe` de la [última versión](https://github.com/Ja1zme/acta-releases/releases/latest).
- **Pide:** Windows 10 (21H2 o posterior) u 11, de 64 bits. La primera vez descarga sus modelos según tu equipo: con una tarjeta NVIDIA usa la gráfica; sin ella, el procesador.
- **Actualizaciones:** Acta lee aquí `latest.json` y se actualiza sola cuando no hay nada grabándose ni procesándose.

## Android

Graba reuniones presenciales, también con la pantalla apagada, y las transcribe en el teléfono. Emparejado con Acta del PC por la red local, recibe tus actas y le manda lo que grabas para que lo resuma.

- **Descarga:** `Acta-x.y.z-arm64-v8a.apk` de las versiones que empiezan por `movil-v` en [Releases](https://github.com/Ja1zme/acta-releases/releases). La guía de instalación va adjunta en cada una (`INSTALAR-ANDROID.md`).
- **Pide:** Android 7 o posterior, de 64 bits. Para emparejarlo, Acta para Windows 0.9.0 o posterior en la misma red.
- **Actualizaciones:** de momento, a mano: instala el APK nuevo encima y se conservan tus actas.

## Comprobar lo que descargas

GitHub muestra la huella SHA-256 de cada fichero junto a su enlace de descarga (`sha256:…`). Compárala con la del fichero que bajaste antes de instalar. En Windows:

```text
certutil -hashfile Acta_x.y.z_x64-setup.exe SHA256
```
