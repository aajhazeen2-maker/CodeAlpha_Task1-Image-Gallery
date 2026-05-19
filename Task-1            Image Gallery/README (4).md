# 🖼️ Image Gallery

A responsive image gallery built with HTML and CSS, featuring a lightbox popup effect using the Lightbox2 library.

## 📸 Preview

> A clean grid-based image gallery where clicking any image opens it in a fullscreen lightbox viewer with captions and navigation.

## ✨ Features

- Grid layout displaying 12 images
- Lightbox popup on image click
- Image captions support
- Navigate between images inside the lightbox
- Grouped images under a single lightbox album (`perfumes`)

## 🛠️ Built With

- **HTML** — structure
- **CSS** — styling
- **[Lightbox2](https://lokeshdhakar.com/projects/lightbox2/)** — lightbox popup effect (via `lightbox.css` + `lightbox-plus-jquery.js`)

## 📁 Project Structure

```
image-gallery/
├── index.html                  # Main HTML file
├── Style.css                   # Custom styles
├── lightbox.css                # Lightbox2 CSS
├── lightbox-plus-jquery.js     # Lightbox2 JS (includes jQuery)
└── Images/
    ├── Img1.jpg
    ├── Img2.jpg
    ├── Img3.jpg
    └── ... (up to Img12.jpg)
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/image-gallery.git
   ```
2. Add your images into the `Images/` folder and name them `Img1.jpg` through `Img12.jpg`.
3. Open `index.html` in your browser — no build tools needed!

## 📦 Dependencies

- [Lightbox2](https://lokeshdhakar.com/projects/lightbox2/) — already included in the project files.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
