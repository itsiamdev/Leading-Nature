# Leading Nature Photo Gallery

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Here-brightgreen)](https://itsiamddev.github.io/Leading-Nature/)

A responsive photo gallery website featuring an interactive image slider that showcases stunning landscape photography. The gallery displays a collection of high-quality nature images with smooth hover effects and a clean, modern design. Built entirely with HTML5 and CSS3 for optimal performance and accessibility.

## 🌐 Live Demo

Experience the gallery live at: [https://itsiamdev.github.io/Leading-Nature/](https://itsiamdev.github.io/Leading-Nature/)

## ✨ Features

- **Interactive Image Slider**: Displays multiple landscape images in a responsive grid layout
- **Smooth Hover Effects**: Images scale up elegantly on hover for enhanced user interaction
- **Fully Responsive Design**: Adapts seamlessly to different screen sizes using CSS Flexbox
- **Modern UI/UX**: Clean design with rounded corners, subtle shadows, and smooth CSS transitions
- **Lightweight & Fast**: Built with pure HTML and CSS for optimal loading performance
- **Accessibility Focused**: Semantic HTML structure and proper alt attributes for images
- **No Dependencies**: Zero external libraries or frameworks required

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for structure and accessibility
- **CSS3**: Modern styling with Flexbox, CSS Grid, transitions, and responsive design
- **No JavaScript**: Pure CSS implementation for better performance and reduced complexity

## 📁 Project Structure

```
Leading-Nature/
├── index.html          # Main HTML file with gallery markup
├── style.css           # CSS styles for layout, animations, and responsive design
├── landscape.png       # Favicon image
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/iam269/Leading-Nature.git
   cd Leading-Nature
   ```

2. **Open in browser:**
   - Double-click `index.html` or
   - Right-click `index.html` and select "Open with" your preferred browser

3. **Enjoy the photo gallery!**

### Local Development

For development, you can serve the files using any static server:

```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Then open http://localhost:8000 in your browser
```

## 🎨 Customization

### Changing Images

Edit the image sources in `index.html`:

```html
<div class="slide">
  <img src="https://picsum.photos/id/1015/600/400" alt="Your Custom Alt Text">
</div>
```

Replace the Picsum URLs with your own image URLs.

### Styling Modifications

Modify `style.css` to customize:

- **Layout**: Adjust `.slider-container` properties
- **Image Effects**: Modify `.slide` and `.slide img` styles
- **Colors**: Change `background-color` in `body`
- **Spacing**: Update margins and padding values

### Adding More Images

Simply add more `.slide` divs in `index.html`:

```html
<div class="slide">
  <img src="your-image-url.jpg" alt="Description">
</div>
```

## 📱 Responsive Breakpoints

The gallery is optimized for:
- **Desktop**: > 768px (full grid layout)
- **Tablet**: 480px - 768px (adjusted spacing)
- **Mobile**: < 480px (stacked layout)

## 🌍 Browser Support

Works in all modern browsers that support CSS3 features:

| Browser | Minimum Version |
|---------|-----------------|
| Chrome  | 60+             |
| Firefox | 55+             |
| Safari  | 12+             |
| Edge    | 79+             |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**iam269**
- GitHub: [@iam269](https://github.com/iam269)

## 🙏 Acknowledgments

- Images sourced from [Picsum Photos](https://picsum.photos/) - Free stock photos
- Inspired by modern web design principles
- Built with love for nature photography

---

⭐ If you found this project helpful, please give it a star on GitHub!
