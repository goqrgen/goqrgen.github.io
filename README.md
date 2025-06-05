# 🔲 QR Code Generator Tool

The **QR Code Generator Tool** is a fast, easy-to-use, and responsive web application that lets you create customizable QR codes for various types of data — including URLs, text, phone numbers, emails, Wi-Fi credentials, and more. Designed with a sleek modern UI and enhanced features, it’s perfect for personal or professional use.

🌐 Live Demo: [QR Code Generator Tool](https://goqrgen.com)

---

## 🚀 Features

- ✅ Generate QR codes for:
  - URLs
  - Plain Text
  - Email addresses
  - Phone numbers
  - SMS
  - Wi-Fi connections
  - vCards / Contacts
- 🎨 Customizable design options (size, color, margin)
- 📥 Download as PNG, SVG, or JPEG
- 🔍 Built-in QR code scanner (camera-based)
- 📱 Fully responsive and mobile-friendly UI
- 🧠 Real-time preview
- 💾 Batch QR Code Generator (optional module)
- 🧪 Error correction support (L, M, Q, H)

---

## 📖 How to Use

1. **Choose Data Type**: Select what type of data you want to encode.
2. **Enter Details**: Fill in the required fields.
3. **Customize** *(Optional)*: Set size, colors, and margins.
4. **Generate QR Code**: Click the "Generate" button.
5. **Download or Scan**: Save the QR or test it using the scanner.

---

## 🧑‍💻 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Libraries**:
  - `qrcode.js` / `QRCodeStyling.js`
  - `html2canvas` (for downloads)
  - `WebRTC` (for camera-based scanner)

---

## 📁 Project Structure

```bash
qr-code-generator/
├── index.html
├── style.css
├── script.js
├── scanner.js
├── preview-image.png
├── assets/
│   └── icons, logos
└── README.md
