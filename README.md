# 📝 Markdown Notepad

A beautiful, feature-rich Markdown editor built as a single-page HTML application. No external dependencies required.

![Preview](https://img.shields.io/badge/Status-Stable-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

### Core Functionality
- **Real-time Markdown Preview** - Split-pane view with live rendering
- **Auto-save** - Automatically saves your work to browser localStorage
- **File Import/Export** - Import `.md`, `.txt`, `.markdown` files (via button or drag-and-drop) and export your work
- **Word/Character/Line Count** - Live statistics in the status bar

### Markdown Support
- **Smart Lists** - Auto-continuation of ordered, unordered, and task lists on new lines
- **Headings** (H1-H6)
- **Text Formatting** - Bold, italic, strikethrough, bold+italic
- **Lists** - Ordered, unordered, and task lists with checkboxes
- **Code** - Inline code and fenced code blocks with syntax highlighting
- **Blockquotes** - Multi-level nested quotes
- **Tables** - Full table support with alignment options
- **Links & Images** - Hyperlinks and embedded images
- **Horizontal Rules** - Multiple separator styles

### Toolbar Tools
- Quick formatting buttons for bold, italic, strikethrough, code
- Blockquote and list insertion
- Horizontal rule insertion
- Built-in Markdown cheat sheet reference

### Keyboard Shortcuts
| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New file |
| `Ctrl+O` | Import file |
| `Ctrl+S` | Export file |
| `Ctrl+P` | Toggle preview pane |
| `Ctrl+Shift+P` | Export to PDF / Print |
| `Ctrl+B` | Bold text |
| `Ctrl+I` | Italic text |
| `Tab` | Insert 2 spaces |
| `Escape` | Close modal |

## 🎨 Design

### Dark Theme
Modern dark color scheme with:
- Deep purple/gray backgrounds
- Vibrant accent colors
- Custom scrollbars
- Smooth transitions and hover effects

### Responsive Layout
- Flexible toolbar with wrap support
- Resizable editor and preview panes
- Mobile-friendly modal dialogs
- Optimized for all screen sizes

## 🚀 Usage

### Getting Started
1. Open `notepad.html` in any modern web browser
2. Start writing Markdown in the editor pane
3. Toggle preview with `Ctrl+P` or the Preview button
4. Your work is automatically saved

### Import a File
- Click the **Import** button or press `Ctrl+O`
- Select a `.md`, `.txt`, or `.markdown` file
- Content will load into the editor

### Export Your Work
- Click the **Export** button or press `Ctrl+S`
- File will download with the current filename

### Export to PDF / Print
- Click the **Export PDF** button or press `Ctrl+Shift+P`
- Opens the browser's print dialog
- Choose "Save as PDF" or select a physical printer
- Preview pane automatically shows for printing
- Optimized print styles remove UI elements and use printer-friendly colors

### Start Fresh
- Click the **New** button or press `Ctrl+N`
- Confirms before discarding unsaved content

## 📋 Markdown Cheat Sheet

### Headings
```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

### Emphasis
```markdown
**bold** or __bold__
*italic* or _italic_
***bold italic***
~~strikethrough~~
```

### Lists
```markdown
- Unordered item
* Also unordered
+ Another variant

1. Ordered item
2. Second item

- [ ] Task item
- [x] Completed task
```

### Code
```markdown
Inline `code` here

```python
def hello():
    print("Hello, World!")
```
```

### Links & Images
```markdown
[Link text](https://example.com)
![Alt text](image.png)
```

### Blockquotes
```markdown
> This is a quote
> > Nested quote
```

### Tables
```markdown
| Left | Center | Right |
|:-----|:------:|------:|
| A    | B      | C     |
```

### Horizontal Rules
```markdown
---
***
___
```

## 🛠️ Technical Details

### Built-in Markdown Parser
The application includes a custom Markdown parser with no external dependencies, supporting:
- Full CommonMark specification features
- Task lists with checkbox rendering
- Table alignment support
- Nested list handling
- Syntax-highlighted code blocks

### Browser Storage
- Content auto-saved to `localStorage` every 700ms
- Filename preserved across sessions
- No server required - works completely offline

### Browser Compatibility
Works in all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## 📁 File Structure

```
notepad_md_html/
└── notepad.html    # Single-file application (HTML + CSS + JS)
```

## 🎯 Tips

1. **Use the Cheat Sheet** - Click the "Cheat Sheet" button for quick Markdown reference
2. **Tab for Indentation** - Press Tab to insert 2 spaces instead of changing focus
3. **Live Preview** - Toggle preview mode to see rendered output in real-time
4. **Status Bar** - Monitor word count, character count, and line count as you write
5. **Safe Navigation** - You'll be prompted before discarding unsaved content
6. **PDF Export** - Use `Ctrl+Shift+P` to open print dialog and save as PDF

## 📝 License

MIT License - Feel free to use, modify, and distribute.

## 🙏 Acknowledgments

Built with:
- Pure HTML5, CSS3, and Vanilla JavaScript
- No external libraries or frameworks
- Custom Markdown parsing engine
- Modern CSS Flexbox layout

---

**Happy Writing!** ✍️
