# 🎨 Icons & Recent Colors Features

## Two Powerful New Features!

1. **MDI Icons** - Add professional Material Design Icons to your map
2. **Recent Colors Palette** - Quick access to previously used colors

---

## 🎨 Recent Colors Palette

### What It Does
Automatically tracks the colors you use and displays them as a quick-access swatch below the color picker.

### How It Works
- **Automatically tracks** every color you use when drawing
- **Keeps last 10 colors** in order of most recent
- **Quick click** to switch back to any recent color
- **Appears automatically** after you use your first color

### Perfect For Your Use Case!
> "I may draw a bunch of duct and then go back to draw vaults a different color but then have to go back to duct again..."

**Now you can:**
1. Draw duct in blue → Blue added to recent colors
2. Draw vaults in green → Green added to recent colors
3. Need more duct? → **Just click blue in recent colors!**
4. No need to remember hex codes or use the color picker again!

### Visual Example
```
Color Picker: [🎨]

Recent Colors:
┌─────┬─────┬─────┬─────┬─────┐
│ 🔵  │ 🟢  │ 🔴  │ 🟡  │ 🟣  │  ← Click any to select
└─────┴─────┴─────┴─────┴─────┘
```

### Features
- ✅ **Auto-population** - No setup needed
- ✅ **Smart ordering** - Most recent first
- ✅ **Hover tooltips** - Shows hex code
- ✅ **Visual feedback** - Highlights on hover
- ✅ **Persists** in session

---

## 🎯 MDI Icons Tool

### What Are MDI Icons?
**Material Design Icons** - Professional, scalable vector icons perfect for utility mapping!

### Icon Library Includes:
- 📡 **Network/Telecom**: Routers, servers, antennas, access points
- ⚡ **Electric**: Power towers, switches, transformers
- 💧 **Water**: Hydrants, pumps, valves, pipes
- ⛽ **Gas**: Meters, stations, pipes
- 📍 **Markers**: Various marker styles for vaults, manholes, equipment
- 🏗️ **Buildings**: Homes, offices, warehouses, structures
- ⚠️ **Alerts**: Warning, info, attention symbols
- ➡️ **Arrows**: Direction indicators, flow markers
- 🔧 **Utility**: Gauges, equipment, infrastructure

**50+ utility-focused icons included!**

---

## 🚀 How to Use Icons

### Quick Start:
1. **Press `I`** or click the Icon tool (shape icon)
2. **Search** for an icon (e.g., "vault", "fiber", "power")
3. **Click an icon** to select it
4. **Adjust size** (20-80px) with the slider
5. **Icon appears** at map center
6. **Drag to position** wherever you need it
7. **Tool stays active** - add more icons!

### Step-by-Step Example:

#### Marking Vaults:
```
1. Press 'I' (Icon tool)
2. Search: "marker"
3. Select map-marker icon
4. Set size: 32px
5. Pick color: Green
6. Click anywhere on icon grid
7. Icon appears on map
8. Drag to vault location
9. Repeat for more vaults!
```

---

## 🎨 Icon Features

### Fully Customizable
- ✅ **Color** - Match your legend colors
- ✅ **Size** - 20px to 80px
- ✅ **Position** - Drag anywhere
- ✅ **Rename** - Double-click layer name
- ✅ **Hide/Show** - Toggle visibility
- ✅ **Delete** - Remove when not needed

### Smart Behaviors
- **Draggable** - Click and drag to reposition
- **Color-aware** - Uses current color selection
- **Recent colors** - Color automatically added to palette
- **Tool persistence** - Stays active for adding multiple icons
- **Full export support** - Saves in JSON and renders in PDF

---

## 🔍 Icon Search

### How Search Works:
Type keywords to filter icons instantly:

**Search Examples:**
- `"phone"` → Phone icons
- `"network"` → Network equipment
- `"fiber"` → Fiber/cable icons
- `"vault"` → Marker icons (use for vaults)
- `"power"` → Electric utilities
- `"water"` → Water utilities
- `"alert"` → Warning symbols

### Search Tips:
- Search is **instant** - no need to press Enter
- Matches icon **name** and **keywords**
- **Case insensitive**
- Clear search to see all icons again

---

## 💡 Real-World Use Cases

### 1. **Marking Vaults**
```
Icon: mdi-map-marker-circle
Color: Green
Size: 28px
Usage: Click once for each vault location
```

### 2. **Fiber Equipment**
```
Icon: mdi-router-wireless or mdi-server
Color: Blue
Size: 32px
Usage: Mark distribution points, splice locations
```

### 3. **Power Infrastructure**
```
Icon: mdi-transmission-tower or mdi-flash
Color: Red
Size: 36px
Usage: Mark power poles, transformers
```

### 4. **Water/Gas Utilities**
```
Icons: mdi-fire-hydrant, mdi-water-pump, mdi-valve
Colors: Blue (water), Yellow (gas)
Size: 32px
Usage: Mark utility infrastructure
```

### 5. **Buildings/Structures**
```
Icons: mdi-office-building, mdi-home, mdi-warehouse
Color: Gray
Size: 40px
Usage: Show service locations
```

### 6. **Alert/Info Markers**
```
Icons: mdi-alert-octagon, mdi-information
Color: Orange/Red
Size: 32px
Usage: Mark hazards, important notes
```

### 7. **Directional Indicators**
```
Icons: mdi-arrow-right, mdi-arrow-left
Color: Match line color
Size: 24px
Usage: Show flow direction, routing
```

---

## 🎯 Workflow Integration

### Typical Project Workflow:

**Phase 1: Setup**
```
1. Set up legend colors
2. Choose colors for categories:
   - Red = Fiber
   - Blue = Duct
   - Green = Vaults
```

**Phase 2: Drawing**
```
1. Draw duct runs (blue)
   → Blue added to recent colors ✓
   
2. Draw fiber runs (red)
   → Red added to recent colors ✓
   
3. Add vault icons (green)
   → Press 'I'
   → Search "marker"
   → Pick green from recent colors!
   → Add all vaults
```

**Phase 3: Details**
```
1. Need more duct?
   → Click blue from recent colors
   → Draw immediately
   
2. Need to mark equipment?
   → Press 'I'
   → Search "network"
   → Click icon
   → Uses last color automatically
```

---

## 📋 Available Icons Reference

### Network/Telecom
- `mdi-phone` - Telephone
- `mdi-network` - Network
- `mdi-router-wireless` - Router/WiFi
- `mdi-access-point` - Access point
- `mdi-server` - Server/equipment
- `mdi-antenna` - Antenna
- `mdi-cellphone-marker` - Cell tower
- `mdi-lan` - LAN/Ethernet
- `mdi-cable-data` - Cable/Fiber

### Electric/Power
- `mdi-flash` - Electric/Power
- `mdi-transmission-tower` - Power tower
- `mdi-electric-switch` - Switch
- `mdi-flash-circle` - Power (alt)

### Water/Gas
- `mdi-water` - Water
- `mdi-water-pump` - Water pump
- `mdi-fire-hydrant` - Hydrant
- `mdi-gas-station` - Gas
- `mdi-valve` - Valve
- `mdi-pipe` - Pipe/Duct
- `mdi-gauge` - Meter/Gauge

### Markers/Locations
- `mdi-map-marker` - Standard marker
- `mdi-map-marker-circle` - Circle marker
- `mdi-map-marker-radius` - Coverage marker
- `mdi-crosshairs-gps` - GPS/Target

### Buildings/Structures
- `mdi-city` - City/Buildings
- `mdi-office-building` - Office
- `mdi-home` - House
- `mdi-warehouse` - Warehouse
- `mdi-tower-fire` - Tower/Pole
- `mdi-bridge` - Bridge
- `mdi-tunnel` - Tunnel

### Symbols/Indicators
- `mdi-alert-octagon` - Warning
- `mdi-alert-circle` - Alert
- `mdi-information` - Info
- `mdi-help-circle` - Help/Question
- `mdi-checkbox-marked-circle` - Complete/OK
- `mdi-close-circle` - Close/Cancel
- `mdi-plus-circle` - Add/Plus
- `mdi-minus-circle` - Remove/Minus

### Arrows/Directions
- `mdi-arrow-right` - Right arrow
- `mdi-arrow-left` - Left arrow
- `mdi-arrow-up` - Up arrow
- `mdi-arrow-down` - Down arrow

### Utility/Infrastructure
- `mdi-connection` - Connection/Junction
- `mdi-source-branch` - Branch/Split
- `mdi-excavator` - Construction
- `mdi-hard-hat` - Work zone
- `mdi-road` - Road/Street
- `mdi-traffic-light` - Traffic signal

---

## 💾 Export Compatibility

### JSON Export ✅
Everything is saved:
- Icon class (which icon)
- Icon size
- Icon color
- Icon position
- Icon name
- Visibility state

### PDF Export ✅
Icons render perfectly:
- Correct size
- Correct color
- Correct position
- Only visible icons included

### Undo/Redo ✅
Full support:
- Add icon → Undo → Icon removed
- Change icon color → Undo → Color restored
- Move icon → Undo → Position restored

---

## ⌨️ Keyboard Shortcuts

### Icon Tool:
- **`I`** - Open icon picker
- **`Escape`** - Close icon modal (when open)
- **`Delete`** - Remove selected icon
- **`P`** - Return to pan mode

### Color Workflow:
1. **Click color picker** - Choose custom color
2. **Or click recent color** - Instant selection
3. Color updates immediately for next drawing

---

## 🎨 Color + Icon Workflow

### Perfect Combination:
```
1. Choose color → Automatically added to recent colors
2. Draw shapes with that color
3. Add icons with same color
4. Switch colors from recent palette
5. Continue drawing
6. Colors stay in palette for quick access
```

### Example: Multi-Utility Project
```
Legend:
- Red = Electric
- Blue = Water  
- Yellow = Gas
- Green = Fiber

Workflow:
1. Draw electric lines (red) → Red in palette
2. Add power icons (red) → Press I, pick from red
3. Draw water lines (blue) → Blue in palette
4. Add hydrant icons → Click blue in palette, press I
5. Draw gas lines (yellow) → Yellow in palette
6. Switch back to electric → Click red in palette!
```

**No more hunting for colors!** ✨

---

## 🔧 Technical Details

### Icon Implementation:
- Uses **Material Design Icons 7.4.47**
- Vector-based (scalable without quality loss)
- Rendered as Leaflet DivIcons
- Fully draggable markers
- CSS-based coloring

### Color Tracking:
- Automatically tracks on drawing
- Stores last 10 colors
- LIFO queue (most recent first)
- Persists during session
- No duplicates

---

## 💡 Pro Tips

### Icons:
1. **Size by importance** - Larger for main equipment, smaller for details
2. **Color code** - Match legend colors for consistency
3. **Search smart** - Try different keywords if first search doesn't work
4. **Position precisely** - Zoom in before placing icons
5. **Name icons** - Double-click layer to rename (e.g., "Vault 123")

### Colors:
1. **Establish palette early** - Draw one of each category first
2. **Use recent colors** - Faster than color picker
3. **Match legend** - Keep colors consistent with legend items
4. **Recent = quick** - Your workflow gets faster automatically

---

## 🎊 Summary

### Recent Colors:
- ✅ Automatic tracking
- ✅ Last 10 colors
- ✅ One-click selection
- ✅ Perfect for your workflow!

### MDI Icons:
- ✅ 50+ utility icons
- ✅ Fully customizable
- ✅ Searchable library
- ✅ Drag and drop
- ✅ Full export support

**Your mapping workflow just got way more efficient!** 🚀

---

**Press `I` to try icons now!** 🎨
