# Permit Map Editor Pro 🗺️

A professional, modern web-based tool for creating permit maps with annotations, legends, and PDF export capabilities.

> **🔥 NEWEST!** 200+ Icons + Rotation & Scale! Rotate icons 0-360°, scale 50%-300%. Shapes, construction, network, arrows & more! See [ICON_EXPANSION.md](ICON_EXPANSION.md)  
> **🎉 NEW!** Icons & Recent Colors - Add professional utility icons (vaults, equipment, infrastructure) + auto-tracked color palette! Press **I** for icons. See [ICONS_AND_COLORS.md](ICONS_AND_COLORS.md)  
> **✨ NEW!** Multi-point line tool - single click to add points, double-click to finish! Perfect for fiber routes with multiple bends. Press **M** key. See [MULTIPOINT_GUIDE.md](MULTIPOINT_GUIDE.md)  
> **✨ NEW!** Text now displays properly (not vertically!), adjustable font sizes, and drag-to-move text! See [TEXT_FEATURES.md](TEXT_FEATURES.md)  
> **✨ NEW!** Advanced layer management features added! See [FEATURES.md](FEATURES.md) for details on renaming layers, changing colors, and visibility controls.

## 🚀 Major Improvements Over Previous Version

### 1. **Individual Layer Selection & Management**
- ✅ Click any drawn item to select it
- ✅ Delete specific items (not just the last one!)
- ✅ Visual layer panel showing all drawings
- ✅ Layer highlighting on selection
- ✅ Quick access to layer actions

### 2. **Modern, Professional UI**
- 🎨 Clean, intuitive interface with modern design
- 🎨 Organized tool panels with clear sections
- 🎨 Better color scheme and visual hierarchy
- 🎨 Responsive and mobile-friendly layout
- 🎨 Smooth animations and transitions

### 3. **Enhanced Drawing Tools**
- ✏️ Pan, Line, Rectangle, Circle, Polygon, and Text tools
- 🎨 Real-time color picker with visual feedback
- 🔄 Undo/Redo functionality (Ctrl+Z / Ctrl+Y)
- ⌫ Delete selected items with Delete key
- 🖱️ Keyboard shortcuts for faster workflow

### 4. **Advanced Layer Management Panel** 📋
- **Rename layers** - Double-click or click edit button
- **Change colors** - Click color square to pick from legend colors
- **Toggle visibility** - Hide/show layers without deleting
- **Smart organization** - Auto-numbered names, fully customizable
- **PDF control** - Only visible layers appear in exports
- **Click to select** - Focus and zoom to any layer
- **Individual actions** - Edit, hide, or delete any layer

### 5. **Better State Management**
- 💾 Auto-save to localStorage
- 🔄 Undo/Redo stack (up to 50 actions)
- 📦 Complete project import/export
- 🔐 Persistent state across sessions

### 6. **Improved PDF Export**
- 📄 Professional PDF layout
- 🎨 Desaturated base map with full-color annotations
- 🧭 Compass rose indicator
- 📝 Legend with color boxes
- 🏢 Company logo and info display
- 📊 Page numbering and metadata

## 🎯 How to Use

### Getting Started
1. Open `permit_maker_pro.html` in your web browser
2. Search for a location using the search bar
3. Start drawing on the map using the tool panel

### 🔧 Perfect for Utility Work
Two specialized tools for utility permit work:

**Straight Line (L key)** - For direct runs:
- ✅ Vault-to-vault fiber optic runs
- ✅ Simple 2-click operation
- ✅ Auto-finishes after 2 points

**Multi-Point Line (M key)** - For complex routes:
- ✅ Fiber runs with multiple turns/bends
- ✅ Following streets or existing infrastructure  
- ✅ Single click to add points, double-click to finish
- ✅ Perfect for routes around obstacles

### Drawing Tools
- **Pan (P)**: Navigate the map
- **Straight Line (L)**: Draw simple 2-point straight lines (perfect for vault-to-vault fiber/duct runs)
- **Multi-Point Line (M)**: Click to add points, double-click to finish - perfect for drawing runs with multiple bends
- **Rectangle (R)**: Draw rectangular areas
- **Circle (C)**: Draw circular areas
- **Polygon (G)**: Draw custom polygons
- **Text (T)**: Add text annotations with adjustable size
- **Icons (I)**: Add professional utility icons (vaults, equipment, infrastructure, markers) - 50+ searchable icons!

### Layer Management
1. **Select a Layer**: Click on any layer in the Layers panel
2. **Delete a Layer**: Click the trash icon next to the layer or press Delete key when selected
3. **Focus on Layer**: Click a layer to pan/zoom to it

### Keyboard Shortcuts
- `P` - Pan tool
- `L` - Straight Line tool (2-point lines for vault-to-vault)
- `M` - Multi-Point Line tool (click points, double-click to finish)
- `R` - Rectangle tool
- `C` - Circle tool
- `G` - Polygon tool
- `T` - Text tool
- `I` - Icon tool (add utility icons)
- `Delete` - Delete selected layer
- `Ctrl+Z` - Undo
- `Ctrl+Y` - Redo

### Managing Projects
1. **Export Project**: Save all your work as a JSON file
2. **Import Project**: Load a previously saved project
3. **Export PDF**: Generate a professional PDF document

### Creating a Legend
1. Click "Add Legend Item"
2. Enter a description for the legend entry
3. The color matches your current drawing color
4. Remove items using the × button

### Adding Company Logo
1. Upload a logo file, or
2. Select from previously saved logos
3. Logo appears in PDF exports

## 📦 Hosting on GitHub Pages

1. Create a new repository on GitHub
2. Upload `permit_maker_pro.html` to the repository
3. Rename it to `index.html`
4. Enable GitHub Pages in repository settings
5. Your permit maker will be available at: `https://[username].github.io/[repo-name]/`

## 🔧 Technical Details

### Technologies Used
- **Leaflet.js** - Interactive map library
- **Leaflet.draw** - Drawing tools
- **jsPDF** - PDF generation
- **html2canvas** - Map screenshot capture
- **Font Awesome** - Icons
- **OpenStreetMap** - Map tiles
- **Nominatim** - Geocoding service

### Browser Compatibility
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ⚠️ Internet Explorer not supported

### File Structure
```
permit_maker_pro.html  # Self-contained single file (HTML + CSS + JS)
```

## 🎨 Features

### Project Information
- Project name
- Description
- Page numbering

### Company Information
- Company name
- Address
- Drawn by
- Date
- Logo upload

### Drawing Features
- Multiple shape types
- Custom colors
- Text annotations
- Undo/Redo
- Layer management

### Export Options
- JSON project files
- PDF documents with:
  - Title header
  - Map with annotations
  - Compass rose
  - Legend
  - Company information
  - Metadata footer

## 🐛 Known Limitations

- Very large projects (100+ layers) may impact performance
- PDF generation requires modern browser with good canvas support
- Map tiles require internet connection
- LocalStorage has ~5-10MB limit per domain

## 💡 Tips

1. **Save Often**: Use Export Project to backup your work
2. **Use Layers Panel**: Easier to manage complex drawings
3. **Color Coding**: Use consistent colors for different utilities
4. **Legend**: Keep legend entries clear and concise
5. **Testing**: Preview PDF before finalizing

## 🔒 Privacy

All data is stored locally in your browser. No information is sent to external servers except:
- Map tiles from OpenStreetMap
- Geocoding requests to Nominatim

## 📝 License

Free to use and modify. Attribution appreciated but not required.

## 🤝 Support

For issues or questions, check that:
1. You're using a modern browser
2. JavaScript is enabled
3. You have internet connection for map tiles

---

**Made with ❤️ for better permit documentation**
