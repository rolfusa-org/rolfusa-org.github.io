# 🔳 QR Code Generator & Scanner

A simple, mobile-friendly QR code generator and scanner web application built with vanilla HTML, CSS, and JavaScript.

## ✨ Features

- **🔳 QR Code Generator**: Create QR codes from any text or URL
- **📷 QR Code Scanner**: Scan QR codes using your device camera
- **📱 Mobile-Friendly**: Responsive design that works on all devices
- **🎨 Modern UI**: Clean, intuitive interface with dark mode support
- **🔒 Privacy-First**: All processing done locally - no data sent to servers
- **⚡ Fast & Lightweight**: No external dependencies, works offline

## 🚀 Live Demo

Visit the live demo: [Your GitHub Pages URL will be here]

## 📱 How to Use

### QR Code Generator
1. Enter any text or URL in the input field
2. Click "Generate QR Code"
3. Your QR code will appear instantly
4. Screenshot or save the QR code as needed

### QR Code Scanner
1. Click "Go to Scanner" from the generator page
2. Allow camera access when prompted
3. Point your camera at any QR code
4. The decoded result will appear automatically

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **QR Generation**: [QRCode.js](https://github.com/davidshimjs/qrcodejs) (MIT License)
- **QR Scanning**: [HTML5-QRCode](https://github.com/mebjas/html5-qrcode) (Apache 2.0 License)
- **Styling**: CSS Grid/Flexbox, Mobile-first responsive design

## 📂 Project Structure

```
qr-app/
├── index.html          # QR Code Generator page
├── scan.html           # QR Code Scanner page
├── js/
│   ├── qrcode.min.js      # QR code generation library
│   └── html5-qrcode.min.js # QR code scanning library
└── README.md           # Project documentation
```

## 🔧 Local Development

1. Clone or download this repository
2. Open `index.html` in your browser, or
3. Serve with a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   
   # PHP
   php -S localhost:8000
   ```
4. Navigate to `http://localhost:8000`

## 📱 Browser Compatibility

- ✅ **Chrome** 60+ (Desktop & Mobile)
- ✅ **Firefox** 55+ (Desktop & Mobile)
- ✅ **Safari** 11+ (Desktop & Mobile)
- ✅ **Edge** 79+ (Desktop & Mobile)
- ✅ **Samsung Internet** 8.0+

**Note**: Camera scanning requires HTTPS or localhost for security reasons.

## 🔒 Security & Privacy

- **No Data Collection**: Everything runs locally in your browser
- **No External Requests**: No data sent to third-party servers
- **Secure Libraries**: Uses well-maintained, security-audited libraries
- **Camera Permissions**: Only used locally for QR code scanning

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

### Third-party Licenses:
- QRCode.js: MIT License
- HTML5-QRCode: Apache 2.0 License

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](../../issues) page
2. Create a new issue if needed
3. Provide details about your browser and device

---

Made with ❤️ for the open source community