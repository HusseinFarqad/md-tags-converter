# 🏷️ MD Tags Converter

A beautiful, fast, and intuitive web tool to adjust markdown header levels instantly. Perfect for content creators, developers, and anyone working with markdown files.

## ✨ Features

- 🚀 **Instant Conversion** - Real-time header adjustment as you type
- 🎯 **Smart Algorithm** - Automatically maintains header hierarchy
- 📋 **One-Click Copy** - Copy results to clipboard instantly
- 💾 **Download Option** - Save as `.md` file with one click
- 🎨 **Beautiful UI** - Modern, responsive design with smooth animations
- 📱 **Mobile Friendly** - Works perfectly on all devices
- 🔒 **Privacy First** - 100% client-side, no data sent to servers
- ⚡ **Zero Dependencies** - Single HTML file, works offline
- 🌍 **Works Everywhere** - No installation needed, just open in browser

## 🎯 Use Cases

- Converting documentation header levels for different platforms
- Adjusting markdown files for Obsidian, Notion, or other note-taking apps
- Standardizing header levels across multiple markdown files
- Preparing markdown content for publishing
- Quick header level adjustments without editing files manually

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
Visit the live demo: **[MD Tags Converter](https://husseinfargad.github.io/md-tags-converter)**

### Option 2: Download & Use Locally
1. Download `md-tags-converter.html`
2. Double-click to open in your browser
3. Start converting! (Works 100% offline)

### Option 3: Deploy Your Own
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/HusseinFargad/md-tags-converter)

## 📖 How to Use

1. **Paste** your markdown content in the left panel
2. **Select** the target header level for the first header (e.g., `###`)
3. **Convert** - Results appear instantly in the right panel
4. **Copy** or **Download** your adjusted markdown

### Example

**Input** (First header is `#`):
```markdown
# Main Header
## Sub Header 1
### Sub sub header
## Sub Header 2
```

**Convert to `###`** (First header becomes `###`):
```markdown
### Main Header
#### Sub Header 1
##### Sub sub header
#### Sub Header 2
```

All headers maintain their relative hierarchy! 🎯

## 🎨 Screenshot

![MD Tags Converter Interface](screenshot.png)

## 💡 How It Works

The converter:
1. Finds the first header level in your markdown
2. Calculates the difference between current and target level
3. Adjusts all headers proportionally
4. Preserves the document structure and hierarchy

**Algorithm Example:**
- If first header is `#` (level 1) and you want `###` (level 3)
- Difference = 3 - 1 = 2
- All headers increase by 2 levels:
  - `#` → `###`
  - `##` → `####`
  - `###` → `#####`

## 🛠️ Technical Details

- **Single File**: Everything in one HTML file
- **No Build Process**: No npm, webpack, or complicated setup
- **Pure JavaScript**: Vanilla JS, no frameworks
- **Modern CSS**: Flexbox, Grid, CSS animations
- **Responsive**: Works on desktop, tablet, and mobile
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)

## 📝 Code Structure

```
md-tags-converter.html
├── HTML Structure
├── CSS Styling (embedded)
│   ├── Modern gradient design
│   ├── Smooth animations
│   └── Responsive layout
└── JavaScript Logic (embedded)
    ├── Header detection algorithm
    ├── Level adjustment function
    ├── Clipboard API integration
    └── File download handler
```

## 🤝 Contributing

Contributions are welcome! Here are some ways you can help:

- 🐛 Report bugs
- 💡 Suggest new features
- 📖 Improve documentation
- 🎨 Enhance UI/UX
- 🔧 Submit pull requests

### Development

Since this is a single HTML file, development is straightforward:

1. Fork the repository
2. Edit `md-tags-converter.html`
3. Test in your browser
4. Submit a pull request

## 📄 License

MIT License - feel free to use this tool for any purpose!

## 🙏 Credits

Created with ❤️ by [Hussein Fargad](https://github.com/HusseinFargad)

## 📮 Feedback

Have suggestions or found a bug? 
- Open an [issue](https://github.com/HusseinFargad/md-tags-converter/issues)
- Or reach out on [GitHub](https://github.com/HusseinFargad)

## ⭐ Show Your Support

If this tool helped you, consider giving it a star! It helps others discover the project.

---

**Made for markdown enthusiasts, by markdown enthusiasts** 📝✨
