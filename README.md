# 🎨 Bondi - Responsive Template Design

A modern, fully responsive HTML and CSS template design built with **Bootstrap**, perfect for creating beautiful and professional web projects. Bondi is designed with a mobile-first approach to ensure optimal viewing across all devices.

## 📋 Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Responsive Design](#responsive-design)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## ✨ Features

- ✅ **Fully Responsive** - Works seamlessly on mobile, tablet, and desktop devices
- ✅ **Bootstrap Framework** - Built on Bootstrap 5 for consistent, professional styling
- ✅ **Clean HTML5** - Semantic and well-structured HTML markup
- ✅ **Custom CSS** - Tailored styling to complement Bootstrap components
- ✅ **Mobile-First Design** - Optimized for mobile devices first, then scaled up
- ✅ **Cross-Browser Compatible** - Tested across all modern browsers
- ✅ **Easy to Customize** - Well-organized code structure for quick modifications
- ✅ **Modern Design** - Contemporary UI/UX patterns and best practices

## 🚀 Getting Started

### Prerequisites

No complex setup required! Just a modern web browser.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AyaMohamedNassar/Bondi.git
   cd Bondi
   ```

2. **Open in browser:**
   - Simply open `index.html` in your favorite web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. **View the template:**
   - Navigate to `http://localhost:8000` in your browser

## 📁 Project Structure

```
Bondi/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Custom CSS styling
├── js/
│   └── script.js       # Custom JavaScript (if applicable)
├── images/             # Image assets
├── README.md           # This file
└── LICENSE             # License information
```

## 🛠 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Semantic markup and structure (80.7%) |
| **CSS3** | Styling and animations (19.3%) |
| **Bootstrap 5** | Responsive grid system and components |

### Bootstrap Integration

This template leverages Bootstrap 5's powerful features:
- **Grid System** - 12-column responsive layout
- **Components** - Navbar, buttons, cards, forms, etc.
- **Utilities** - Spacing, display, text utilities
- **Responsive Classes** - Breakpoints for different screen sizes

## 📱 Responsive Design

Bondi is optimized for all screen sizes:

- **Mobile (Extra Small):** < 576px
- **Small:** ≥ 576px
- **Medium (Tablet):** ≥ 768px
- **Large:** ≥ 992px
- **Extra Large:** ≥ 1200px
- **XXL:** ≥ 1400px

The design automatically adjusts layout, typography, and spacing based on viewport size.

## 🎯 Customization

### Modifying Colors

Edit the custom CSS variables in `css/styles.css`:

```css
:root {
  --primary-color: #your-color;
  --secondary-color: #your-color;
  --text-color: #your-color;
}
```

### Changing Content

Simply edit the HTML in `index.html` to add your own:
- Replace text content
- Update images
- Modify section layouts
- Add new Bootstrap components

### Customizing Bootstrap

Import Bootstrap and override variables in your `css/styles.css`:

```css
/* Override Bootstrap defaults */
@import url('https://cdn.jsdelivr.net/npm/bootstrap@5.x.x/dist/css/bootstrap.min.css');

/* Your custom styles */
```

## 🌐 Browser Support

Bondi is tested and supported on:

- ✅ Chrome (latest versions)
- ✅ Firefox (latest versions)
- ✅ Safari (latest versions)
- ✅ Edge (latest versions)
- ✅ Opera (latest versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile, Firefox Mobile)

## 📖 Best Practices Implemented

- Semantic HTML5 elements for better SEO
- Mobile-first responsive approach
- Bootstrap best practices for consistency
- Clean, maintainable code structure
- Accessibility-friendly markup
- Performance-optimized assets

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeatureName`)
3. Commit your changes (`git commit -m 'Add YourFeatureName'`)
4. Push to the branch (`git push origin feature/YourFeatureName`)
5. Open a Pull Request

## 👩‍💻 Author

**Aya Mohamed Nassar**

- GitHub: [@AyaMohamedNassar](https://github.com/AyaMohamedNassar)
- Repository: [Bondi](https://github.com/AyaMohamedNassar/Bondi)

## 📄 License

This project is open source and available under the MIT License.

---

## 💡 Tips for Usage

- **Inspect elements** using browser DevTools to understand the Bootstrap grid structure
- **Customize Bootstrap** by downloading your own theme from [Bootstrap Customize](https://getbootstrap.com/docs/5.0/customize/overview/)
- **Refer to [Bootstrap Documentation](https://getbootstrap.com/docs/)** for advanced customization options
- **Test responsiveness** using browser DevTools device emulation

## 📞 Support

If you have questions or encounter issues, feel free to:
- Open an [Issue](https://github.com/AyaMohamedNassar/Bondi/issues)
- Contact the author

---

**Happy Designing! 🎉**