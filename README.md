# 📸 Snap2PDF

A lightweight, browser-based tool to convert images into a single PDF — no uploads, no server, no installs. Everything runs locally in your browser.

🔗 **Live Demo:** [snap2doc.vercel.app](https://snap2doc.vercel.app)

-----

## ✨ Features

- **Upload up to 20 images** — JPG, JPEG, PNG, and WEBP supported (max 20 MB)
- **Drag & drop** or click-to-upload support
- **Auto smart layout** — automatically arranges 1–8 images per page in an optimized grid
- **Portrait & Landscape** orientation toggle
- **Auto-rotation** — portrait (vertical) images are automatically rotated to landscape for better fit
- **Subject name field** — label your PDF with a subject name before exporting
- **Save to Device** — download the generated PDF directly
- **Share to WhatsApp** — uses the native share sheet on mobile; desktop falls back to download + prefilled WhatsApp message
- **Progress indicator** — live progress bar while generating the PDF
- **Fully client-side** — your images never leave your device

-----

## 🛠️ Tech Stack

|Technology                                      |Purpose                        |
|------------------------------------------------|-------------------------------|
|HTML / CSS / JavaScript                         |Core frontend (single-file app)|
|[jsPDF 2.5.1](https://github.com/parallax/jsPDF)|PDF generation in the browser  |
|Google Fonts (Nunito)                           |Typography                     |
|Vercel                                          |Hosting & deployment           |

-----

## 🚀 Getting Started

No build step required. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/JackByteBack/Snap2pdf-.git
cd Snap2pdf-
# Open index.html in your browser
open index.html
```

Or deploy instantly to Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/JackByteBack/Snap2pdf-)

-----

## 📂 Project Structure

```
Snap2pdf-/
├── index.html      # Entire app — HTML, CSS, and JS in one file
└── README.md
```

-----

## 📱 How to Use

1. Open the app in your browser
1. Upload images by clicking **Upload** or dragging and dropping them
1. *(Optional)* Enter a subject name
1. Choose **Portrait** or **Landscape** orientation
1. Click **Convert to PDF**
1. Download with **Save to Device** or send via **Share to WhatsApp**

-----

## 🤝 Contributing

Pull requests are welcome! Feel free to open an issue for bugs or feature suggestions.

-----

## 👤 Author

Made with ❤️ by [JackByteBack](https://github.com/JackByteBack)
