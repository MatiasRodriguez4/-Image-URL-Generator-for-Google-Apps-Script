# -Image-URL-Generator-for-Google-Apps-Script
Descripción: Script para generar URLs en formato lh3.googleusercontent.com  * a partir de imágenes en carpetas de Google Drive. Ideal para alimentar  * bots, sistemas de documentación o galerías de imágenes. Basado en el desarrollo de https://github.com/CrisLugg/Sacar-imagenes-de-drive . 
# 📸 Image URL Generator for Google Apps Script (con Sub carpetas :D)

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Script para generar URLs en formato `lh3.googleusercontent.com` a partir de imágenes en carpetas de Google Drive. Ideal para alimentar bots, sistemas de documentación o galerías de imágenes.

**Autor:** Matias Rodriguez ([@MatiasRodriguez4](https://github.com/MatiasRodriguez4) / [@MatiasRunamatic](https://github.com/MatiasRunamatic))

## 🚀 Características

- Recorre carpetas y subcarpetas recursivamente
- Genera URLs en formato `lh3.googleusercontent.com`
- Soporta múltiples formatos: JPG, PNG, WEBP, GIF, BMP, SVG
- Tamaños configurables: s500, s1000, s1600, s2200
- Guarda resultados en Google Sheets
- Genera prompt listo para copiar a bots
- Procesamiento automático programable
- Exportable a webhook

## 📦 Requisitos

- Google Account
- Google Drive con carpeta de imágenes
- Google Sheets (opcional, para guardar resultados)

## 🔧 Instalación

1. Crear un nuevo Google Sheets
2. Extensiones → Apps Script
3. Pegar el código
4. Configurar `ID_CARPETA_IMAGENES` con el ID de tu carpeta
5. Guardar como "Image URL Generator"

## 📖 Uso

### Obtener ID de carpeta de Google Drive
