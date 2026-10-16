# Convertidor de Archivos

Herramienta web para convertir imágenes, audio, video, PDF y extraer texto (OCR) **directamente en el navegador**. Sin subir nada a ningún servidor. Sin registro. Sin límites impuestos.

## ✨ Características

- 🖼️ **Imágenes**: JPG, PNG, WEBP, AVIF, BMP. Redimensionar, ajustar calidad y convertir por lotes.
- 🎵 **Audio**: MP3, WAV, OGG, M4A, AAC, FLAC. Conversión por lotes y vista previa.
- 🎬 **Video**: MP4, WEBM, GIF.
- 📄 **PDF**: Unir imágenes en un PDF o extraer páginas como JPG.
- 🔍 **OCR**: Extraer texto de imágenes en español e inglés.
- 🌙 **Modo oscuro** con preferencia guardada.
- 📱 **PWA instalable**: funciona como app y offline.
- 📦 **Sin subidas**: todo ocurre en tu dispositivo.
- 🆓 **100% gratis** y sin registro.

## 🔒 Privacidad

**Tus archivos nunca salen de tu dispositivo.**

Toda la conversión ocurre dentro del navegador usando Canvas API, WebAssembly (FFmpeg) y librerías de código abierto. No se envía, no se guarda, no se comparte nada. Puedes desconectar el WiFi después de cargar la página y seguirá funcionando.

## 🛠️ Tecnologías

- HTML, CSS y JavaScript puro
- Canvas API para imágenes
- FFmpeg.wasm para audio y video
- pdf-lib y pdf.js para PDF
- Tesseract.js para OCR
- Service Worker para PWA

## 🚀 Uso

1. Abre la web.
2. Elige el tipo de archivo (Imágenes, Audio, Video, PDF u OCR).
3. Carga uno o varios archivos.
4. Selecciona el formato de salida.
5. Pulsa **Convertir**.
6. Descarga el resultado.

## ⚠️ Notas

- La conversión de audio y video con FFmpeg descarga ~30 MB la primera vez (queda en caché).
- El OCR descarga ~15 MB la primera vez.
- En móviles con poca memoria, algunos formatos pueden fallar. La web lo advierte automáticamente.
- La primera carga puede tardar según tu conexión.

## 💬 Comunicación

Contacto: [discord.gg/gGUgTDWy](https://discord.gg/gGUgTDWy)

## 👤 Créditos

Creado por **zerk**.

Funciona con Canvas API, WebAssembly (FFmpeg), pdf-lib, pdf.js y Tesseract.js.

---
