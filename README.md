# CSV Table Viewer - AI/ML Concepts

A responsive, interactive table viewer for AI/ML concepts with real-time search functionality.

## 🚀 Live Demo

Visit the live application: [GitHub Pages URL will be here after deployment]

## ✨ Features

- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **🔍 Real-time Search**: Filter concepts instantly as you type
- **🎨 Material UI Design**: Clean, modern interface with Google's Material Design principles
- **🔗 Interactive Links**: Documentation links open in new tabs with security attributes
- **⚡ Fast Loading**: Data prefetching for optimal performance
- **♿ Accessible**: Keyboard navigation and screen reader friendly

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Material UI styling with responsive design
- **Vanilla JavaScript**: No external dependencies
- **JSON**: Structured data format
- **Google Fonts**: Roboto font family

## 📊 Data

The application displays 35 AI/ML concepts including:
- Machine Learning fundamentals (Supervised, Unsupervised, Reinforcement Learning)
- Deep Learning and Neural Networks
- Modern AI concepts (LLMs, RAG, Agents)
- Cloud AI services (AWS, Azure, Google Cloud)
- Popular frameworks and libraries

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Go to Settings → Pages
3. Select "Deploy from a branch" → "main" → "/ (root)"
4. Your site will be available at `https://yourusername.github.io/repository-name/`

### Option 2: Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/csv-table-viewer.git
   cd csv-table-viewer
   ```

2. Start a local web server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
   
   # Node.js
   npx serve .
   
   # PHP
   php -S localhost:8000
   ```

3. Open your browser and navigate to `http://localhost:8000`

## 📁 Project Structure

```
csv-table-viewer/
├── index.html          # Main application file
├── data.json          # AI/ML concepts data
├── .gitignore         # Git ignore rules
├── README.md          # Project documentation
├── .kiro/             # Kiro IDE specifications
└── .vscode/           # VS Code settings
```

## 🎯 Features in Detail

### Search Functionality
- **Case-insensitive**: Search works regardless of letter case
- **Real-time filtering**: Results update as you type
- **Partial matching**: Find concepts with partial terms
- **No results handling**: Clear messaging when no matches found

### Responsive Design
- **Mobile-first**: Optimized for mobile devices
- **Breakpoints**: 480px (mobile), 768px (tablet), 1200px+ (desktop)
- **Horizontal scrolling**: Table remains usable on narrow screens
- **Touch-friendly**: Appropriate touch targets and spacing

### Performance Optimizations
- **Data prefetching**: JSON data loads in background
- **Efficient rendering**: Dynamic table generation
- **Minimal dependencies**: No external JavaScript libraries
- **Optimized CSS**: Efficient selectors and animations

## 🔧 Customization

### Adding New Data
Edit `data.json` to add new concepts:
```json
{
  "concept": "Your Concept Name",
  "definition": "Detailed definition here",
  "example": "Real-world examples",
  "documentationLinks": "https://example.com/docs"
}
```

### Styling Changes
Modify CSS variables in `index.html`:
```css
:root {
  --primary-color: #1976d2;  /* Change primary color */
  --surface-color: #ffffff;   /* Change background */
  /* ... other variables */
}
```

## 🧪 Testing

The application has been thoroughly tested for:
- ✅ Search functionality (case-insensitive, real-time, edge cases)
- ✅ Documentation links (clickable, new tab, security)
- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Performance (load time, search response)
- ✅ Accessibility (keyboard navigation, screen readers)
- ✅ Browser compatibility (Chrome, Firefox, Safari)

## 📱 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Make your changes
4. Test thoroughly
5. Commit: `git commit -m 'Add feature-name'`
6. Push: `git push origin feature-name`
7. Create a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Material Design**: Google's Material Design principles
- **Roboto Font**: Google Fonts
- **AI/ML Community**: For the comprehensive concept definitions

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](../../issues) page
2. Create a new issue with detailed information
3. Include browser version and steps to reproduce

---

**Made with ❤️ for the AI/ML community**