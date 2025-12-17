# ProEdit: Professional Document Suite
A feature-rich, professional document editor built with wxPython, offering a modern UI with extensive formatting capabilities, multi-format support, and advanced search functionality.
## ✨ Features

### 🎨 Modern User Interface
- **Custom-drawn components** with smooth animations and hover effects
- **Dark Mode** with beautiful color schemes
- **Rounded panels** and modern button styles
- **Multi-tab interface** for managing multiple documents simultaneously
- **Responsive toolbar** with intuitive controls

### 📝 Rich Text Editing
- Full **rich text formatting** support
- **Bold, Italic, Underline** styling
- **Font family** and **size** selection
- **Text color** and **highlighting**
- **Text alignment** (Left, Center, Right)
- **Keyboard shortcuts** for quick formatting

### 📁 File Format Support
- **Plain Text** (.txt)
- **Rich Text Format** (.rtf)
- **Microsoft Word** (.docx) - requires `python-docx`
- **PDF Export** via printing functionality

### 🔍 Advanced Search & Replace
- **Standard text search** with case sensitivity option
- **Regular expression (Regex)** support
- **Replace** single occurrence
- **Replace All** for batch replacements
- **Animated highlighting** of search results
- **Match counter** showing current position

### 💾 Smart File Management
- **Auto-save** functionality with configurable intervals
- **Recent files** menu for quick access
- **Unsaved changes** protection with prompts
- **Multiple documents** open simultaneously

### 📊 Document Statistics
- Real-time **word count**
- Real-time **character count**
- Status bar updates

### ⚙️ Customization
- **Preferences dialog** for settings
- **Configurable auto-save** interval
- **Default font** settings
- **Theme toggle** (Light/Dark mode)
- **Persistent settings** saved to JSON

## 🚀 Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Required Dependencies
```bash
pip install wxPython
```

### Optional Dependencies
For Microsoft Word (.docx) support:
```bash
pip install python-docx
```

### Download and Run
1. Clone or download the repository
2. Navigate to the project directory
3. Run the application:
```bash
python proedit.py
```

## 📖 Usage

### Basic Operations

#### Creating Documents
- Click **New** button or press `Ctrl+N`
- Start typing in the editor

#### Opening Files
- Click **Open** button or press `Ctrl+O`
- Select a file (.txt, .rtf, or .docx)
- Use **Recent Files** menu for quick access

#### Saving Documents
- Click **Save** button or press `Ctrl+S`
- For new documents, use **Save As** (`Ctrl+Shift+S`)

### Formatting Text

#### Font Styling
- **Bold**: Click B button or press `Ctrl+B`
- **Italic**: Click I button or press `Ctrl+I`
- **Underline**: Click U button or press `Ctrl+U`

#### Font Selection
- Use the **font dropdown** in the toolbar
- Use the **size spinner** to adjust font size
- Press `Ctrl+=` to increase font size
- Press `Ctrl+-` to decrease font size

#### Text Color
- Click **Color** button
- Select desired color from the color picker

#### Alignment
- Click **L** for left alignment
- Click **C** for center alignment
- Click **R** for right alignment

### Search & Replace

#### Basic Search
1. Enter search term in the **Find** field
2. Click **Find Next** or press `Enter`
3. Use **Match Case** checkbox for case-sensitive search

#### Regular Expression Search
1. Check the **Regex** checkbox
2. Enter a regex pattern in the Find field
3. Click **Find Next**

#### Replace Operations
1. Enter replacement text in the **Replace** field
2. Click **Replace** to replace current match
3. Click **Replace All** to replace all occurrences

### Dark Mode
- Go to **View** → **Toggle Dark Mode**
- Or use **Preferences** to set as default

## ⌨️ Keyboard Shortcuts

### File Operations
- `Ctrl+N` - New tab
- `Ctrl+O` - Open file
- `Ctrl+S` - Save file
- `Ctrl+Shift+S` - Save as

### Editing
- `Ctrl+Z` - Undo
- `Ctrl+Y` - Redo
- `Ctrl+X` - Cut
- `Ctrl+C` - Copy
- `Ctrl+V` - Paste

### Formatting
- `Ctrl+B` - Bold
- `Ctrl+I` - Italic
- `Ctrl+U` - Underline
- `Ctrl+=` - Increase font size
- `Ctrl+-` - Decrease font size

## 📂 Configuration

ProEdit saves your preferences in `editor_config.json` in the application directory.

### Configuration Options
```json
{
  "recent_files": [],
  "dark_mode": false,
  "auto_save": true,
  "auto_save_interval": 60,
  "font_size": 11,
  "font_face": "Segoe UI",
  "window_size": [1200, 850],
  "maximized": false
}
```

### Auto-save Files
When auto-save is enabled, backup files are created with `.autosave` extension.

## 🐛 Debugging

ProEdit maintains a debug log file `editor_debug.log` in the application directory. Check this file for:
- Error messages
- Stack traces
- Application events

## 🛠️ Advanced Features

### Custom UI Components
- **RoundedPanel**: Panels with smooth rounded corners
- **ModernButton**: Interactive buttons with hover effects
- **IconButton**: Compact toolbar buttons
- **AnimationHandler**: Animated search result highlighting

### Theme System
- Comprehensive color palette management
- Automatic UI updates on theme change
- Custom color definitions for all elements

## 📋 System Requirements

### Minimum Requirements
- **OS**: Windows, macOS, or Linux
- **Python**: 3.7+
- **RAM**: 512 MB
- **Disk Space**: 50 MB

### Recommended Requirements
- **OS**: Windows 10/11, macOS 10.14+, Ubuntu 20.04+
- **Python**: 3.9+
- **RAM**: 1 GB
- **Disk Space**: 100 MB

## 🤝 Contributing

Contributions are welcome! Areas for improvement:
- Additional file format support
- More formatting options
- Plugin system
- Spell checking
- Collaborative editing
- Cloud storage integration

## 📝 License

This project is open source. Feel free to use, modify, and distribute.

## 🙏 Acknowledgments

Built with:
- [wxPython](https://wxpython.org/) - GUI framework
- [python-docx](https://python-docx.readthedocs.io/) - Word document support

## 📞 Support

For issues, questions, or suggestions:
- Check the debug log file
- Review the documentation
- Submit an issue report

## 🔄 Version History

### Version 3.1.0-Ultimate
- Custom UI components
- Dark mode support
- Advanced search with regex
- Multi-tab interface
- Auto-save functionality
- Rich text editing
- PDF export capability
- Modern, polished interface

---

**ProEdit** - Professional document editing made simple and beautiful. 🎨✍️
