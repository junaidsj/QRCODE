## 📷 QR Code Generator with Python

This Python script generates a customized QR code image from any URL. It allows you to:

- ✅ Encode URLs (like your Instagram profile)
- 🎨 Customize QR code color (e.g., dark blue on white)
- 🖼️ Optionally embed a logo image at the center of the QR code
- 💾 Save the generated QR code as a PNG file
- 🖥️ Preview the QR code image instantly

### 🛠️ Features
- Built using `qrcode` and `Pillow` libraries
- URL-safe filename creation
- Error correction level set to `H` (High) to support logos
- Logo auto-resizing and placement
- CLI-friendly with automatic image display

### 📦 Requirements
Make sure you have these installed:

```bash
pip install qrcode[pil] pillow
