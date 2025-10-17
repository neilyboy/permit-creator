# Changelog

## Latest Update - Icon Expansion + Rotation & Scale 🎨 (Oct 17, 2025)

### Massive Icon Library Expansion

#### **200+ Icons Available!** 📚
- ✅ **Expanded from 50 to 200+ icons**
- ✅ **New Categories:**
  - Shapes & Basic (circles, squares, triangles, hexagons, stars)
  - Construction & Equipment (expanded tools, machinery)
  - Roads & Transportation (highways, traffic, signs)
  - Connection & Junction (branch, merge, swap)
  - Comprehensive Arrows (all directions, bold, diagonal)
  - Extensive Alerts & Symbols (25+ variations)
  - Plus/Minus/Math symbols

### Icon Rotation & Scale Controls

#### **Rotation Control** 🔄
- ✅ **Rotate icons 0-360 degrees** using slider
- ✅ **Select icon layer** → rotation control appears
- ✅ **Real-time preview** - see rotation instantly
- ✅ **Perfect for arrows** - point in any direction
- ✅ **Equipment orientation** - match actual positions

#### **Scale Control** 📏
- ✅ **Scale icons 50%-300%** of original size
- ✅ **Select icon layer** → scale control appears  
- ✅ **Visual hierarchy** - make important icons larger
- ✅ **Subtle markers** - scale down for details
- ✅ **Real-time preview** - instant size updates

#### **Combined Power** ⚡
- ✅ Rotate AND scale any icon independently
- ✅ Controls in layers panel when icon selected
- ✅ Full export support (JSON & PDF)
- ✅ Undo/redo compatible
- ✅ Per-icon customization

See [ICON_EXPANSION.md](ICON_EXPANSION.md) for complete guide!

---

## Previous Update - Icons & Recent Colors 🎨 (Oct 16, 2025)

### Major New Features

#### 1. **Recent Colors Palette** 🎨
- ✅ **Automatically tracks** the last 10 colors you use
- ✅ **Quick-access swatch** below color picker
- ✅ **One-click selection** to reuse colors
- ✅ **Perfect for workflow** - Draw duct (blue), draw vaults (green), back to duct? Click blue!
- ✅ **Smart ordering** - Most recent colors first

#### 2. **MDI Icons Tool** 🎯
- ✅ **50+ professional icons** for utility mapping
- ✅ **Searchable library** - Type "vault", "fiber", "power", etc.
- ✅ **Fully customizable** - Size (20-80px), color, position
- ✅ **Drag and drop** - Position anywhere on map
- ✅ **Categories included**:
  - Network/Telecom (routers, servers, antennas)
  - Electric/Power (towers, switches, lightning)
  - Water/Gas (hydrants, pumps, valves, pipes)
  - Markers (vaults, manholes, equipment locations)
  - Buildings (offices, homes, warehouses)
  - Alerts & Symbols (warnings, info, directions)

#### 3. **Icon Features** ✨
- ✅ Press **`I`** key to open icon picker
- ✅ **Real-time search** filtering
- ✅ **Size slider** control
- ✅ **Color integration** - Uses current color
- ✅ **Auto-adds to recent colors** when placed
- ✅ **Tool stays active** - Add multiple icons in a row
- ✅ **Rename, hide, delete** - Full layer management
- ✅ **Export compatible** - JSON and PDF support

See [ICONS_AND_COLORS.md](ICONS_AND_COLORS.md) for complete documentation!

---

## Previous Update - Bug Fix: Multiple Shape Drawing 🐛 (Oct 16, 2025)

### Critical Bug Fixed

#### **Fixed: Multiple Shapes Drawing Simultaneously**
- ✅ **Problem:** Switching tools (e.g., circle → rectangle) would draw BOTH shapes at once
- ✅ **Root Cause:** Previous draw handler wasn't being disabled
- ✅ **Solution:** Now properly disables old handler before enabling new one
- ✅ **Bonus:** Tool now stays active after drawing (draw multiple shapes in a row!)

### Improvements

#### **Tool Stays Active After Drawing** 🔄
- ✅ Draw multiple rectangles without re-selecting tool
- ✅ Draw multiple circles for vaults in one go
- ✅ Much faster workflow for repetitive shapes
- ✅ Press `P` to return to pan mode when done

#### **Cleaner Tool Switching** 🎯
- ✅ Only one tool active at a time
- ✅ No overlapping handlers
- ✅ Predictable behavior
- ✅ Professional tool management

See [BUGFIX_MULTIPLE_SHAPES.md](BUGFIX_MULTIPLE_SHAPES.md) for technical details!

---

## Previous Update - Multi-Point Line Tool 🎯 (Oct 16, 2025)

### New Feature: Multi-Point Polyline Drawing

#### **Multi-Point Line Tool (M key)** 📐
- ✅ **Single click** to start the line
- ✅ **Single click** to add each point/vertex
- ✅ **Double-click** to finish the line
- ✅ Perfect for fiber runs with **multiple bends and turns**
- ✅ Draw complex routes without creating multiple segments
- ✅ Keyboard shortcut: **M** key

#### Use Cases:
- **Fiber routes** that follow streets with multiple turns
- **Duct banks** that navigate around obstacles
- **Underground utilities** with complex paths
- **Aerial runs** that go around multiple poles

#### Tool Comparison:
| Tool | Icon | Use Case | How to Complete |
|------|------|----------|-----------------|
| **Straight Line (L)** | — | Vault-to-vault direct runs | 2 clicks (auto-finishes) |
| **Multi-Point (M)** | 🔗 | Routes with multiple turns | Single clicks + double-click to finish |

---

## Previous Update - Text & Movement Features 📝 (Oct 16, 2025)

### Major Improvements

#### 1. **Fixed Text Display Bug** 🐛
- ✅ Text now displays **horizontally** (was showing vertically letter-by-letter)
- Added `white-space: nowrap` to prevent line breaks
- Professional text styling with borders and shadows

#### 2. **Adjustable Font Sizes** 🔤
- Slider control from **10px to 36px**
- Real-time size preview
- Font size saved with each text layer
- Perfect for different label types (small notes to large titles)

#### 3. **Drag & Drop Text** 🖱️
- All text is now **fully draggable**
- Click and drag to reposition anywhere on map
- Position automatically saved
- Smooth drag experience with move cursor

#### 4. **Enhanced Text Styling** 🎨
- Clean white background
- Subtle border and drop shadow
- Better padding for readability
- Professional appearance

#### 5. **Shape Editing** ✏️
- Click any shape in pan mode to enable editing
- Drag vertices to reshape
- Move entire shapes by dragging
- Edit handles appear on selection

See [TEXT_FEATURES.md](TEXT_FEATURES.md) for complete documentation!

---

## Previous Update - Advanced Layer Management 🎨

### Major Features Added (Oct 16, 2025)

#### 1. **Layer Renaming** 🏷️
- Double-click any layer name to edit it
- Or click the edit button (✏️)
- Auto-numbered names by default ("Line 1", "Rectangle 2")
- Text layers use their text content as name
- All names fully customizable

#### 2. **Color Changing** 🎨
- Click the color square next to any layer
- Choose from your legend colors
- Instantly updates on the map
- Perfect for reassigning work types

#### 3. **Visibility Toggle** 👁️
- Show/hide layers without deleting them
- Hidden layers excluded from PDF exports
- Perfect for phased work or alternatives
- One-click toggle with eye icon

#### 4. **Enhanced Layer List** 📋
- Color square (click to change color)
- Layer name (double-click to edit)
- Eye icon (toggle visibility)
- Edit icon (rename layer)
- Trash icon (delete layer)

#### 5. **Full Compatibility** ✅
- All features work with JSON export/import
- PDF exports only include visible layers
- Undo/redo supports all new operations
- Backward compatible with old files

See [FEATURES.md](FEATURES.md) for complete documentation!

---

## Previous Update - Straight Line Tool Added

### What Changed
- ✅ **Added dedicated Straight Line tool** - Perfect for vault-to-vault utility runs
- ✅ **Reorganized tool layout** - More logical grouping of drawing tools
- ✅ **Enhanced keyboard shortcuts** - All tools now have hotkeys
- ✅ **Updated documentation** - README now includes utility-specific guidance

### Tool Layout (Updated)
```
Row 1: Pan (P) | Straight Line (L) | Freehand Path
Row 2: Rectangle (R) | Circle (C) | Polygon (G)
Row 3: Text (T)
```

### Straight Line Tool Features
- **Simple 2-click operation**: Click start point → Click end point → Done!
- **Perfect for utility work**: Fiber runs, duct banks, conduit paths
- **Keyboard shortcut**: Press `L` key
- **Max 2 points**: Automatically completes after second click
- **Clean, straight lines**: No accidental curves or bends

### Tool Descriptions
| Tool | Icon | Shortcut | Use Case |
|------|------|----------|----------|
| Pan | ✋ | P | Navigate the map |
| **Straight Line** | **—** | **L** | **Vault-to-vault fiber/duct runs** |
| Freehand Path | ✏️ | - | Multi-point paths and routes |
| Rectangle | ▢ | R | Buildings, work areas |
| Circle | ○ | C | Radial coverage zones |
| Polygon | ⬡ | G | Custom shaped areas |
| Text | T | T | Labels and annotations |

### Why This Matters for Utility Work
When documenting fiber optic or duct installations:
1. You typically need to show **point-to-point connections** (vault to vault)
2. These are always **straight lines** in real installations
3. The old tool (freehand) required clicking finish, which was awkward
4. The new **Straight Line tool automatically completes** after 2 points

### Example Workflow
```
1. Press 'L' to activate Line tool
2. Click on first vault location
3. Click on second vault location
4. Line automatically completes ✓
5. Repeat for next run
```

### Migration from Old Version
If you were using the "pencil tool" for straight lines:
- **Old way**: Click pencil → Click start → Click end → Click finish button
- **New way**: Press 'L' → Click start → Click end (auto-finishes!)

### All Keyboard Shortcuts
- `P` - Pan/Navigate
- `L` - Straight Line (NEW!)
- `R` - Rectangle
- `C` - Circle  
- `G` - Polygon
- `T` - Text
- `Delete` - Delete selected
- `Ctrl+Z` - Undo
- `Ctrl+Y` - Redo

---

**File Updated**: `permit_maker_pro.html`  
**Documentation Updated**: `README.md`  
**Date**: Oct 16, 2025
