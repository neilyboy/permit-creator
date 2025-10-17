# 🎯 Multi-Point Line Tool Guide

## Perfect for Complex Fiber Routes!

The **Multi-Point Line Tool** is designed specifically for drawing utility runs that have **multiple turns and bends**.

---

## ✨ How It Works

### The Perfect Workflow:

1. **Press `M`** (or click the Multi-Point Line tool)
2. **Single click** on the map to start your line
3. **Single click** again to add each point/bend/turn
4. **Keep clicking** to add as many points as you need
5. **Double-click** on the last point to finish the line

### Example: Drawing a Fiber Run

```
Start → Click
  ↓
Bend → Click
  ↓
Turn → Click
  ↓
Bend → Click
  ↓
End → Double-Click (finishes!)
```

---

## 🔄 Tool Comparison

### When to Use Each Tool:

#### **Straight Line Tool (L key)** ✅
- **Direct vault-to-vault runs**
- **No bends or turns**
- **Quick 2-click operation**
- Auto-finishes after 2 points

**Example:**
```
Vault A ──────────────── Vault B
(Simple straight run)
```

#### **Multi-Point Line Tool (M key)** ✅
- **Routes with multiple turns**
- **Following streets with bends**
- **Around obstacles**
- **Complex paths**
- Click each point, double-click to finish

**Example:**
```
        ┌────────┐
Vault A │        │ Vault B
        │  Bldg  │
        └────────┘
(Route goes around building)
```

---

## 🎯 Real-World Use Cases

### 1. **Street-Following Fiber Run**
Drawing fiber that follows multiple streets:
```
1. Press M
2. Click at starting vault
3. Click at each intersection/corner
4. Click at each pole or manhole
5. Double-click at ending vault
```

### 2. **Avoiding Obstacles**
Route around buildings, parks, or restricted areas:
```
1. Start at point A
2. Click before obstacle
3. Click to go around
4. Click after obstacle
5. Double-click at destination
```

### 3. **Following Existing Infrastructure**
Trace along existing conduit or utility paths:
```
1. Click at connection point
2. Click at each junction box
3. Click at each pull point
4. Click at each splice point
5. Double-click at termination
```

### 4. **Aerial Runs with Multiple Poles**
Map pole-to-pole aerial fiber:
```
1. Start at first pole
2. Click at each subsequent pole
3. Click at any strain relief points
4. Double-click at last pole
```

---

## ⌨️ Tips & Tricks

### 1. **Zoom In First**
Zoom to the appropriate level before starting. Easier to click accurately.

### 2. **Use Pan Between Clicks**
- If you need to pan to see the next point, just scroll or pan normally
- Your drawing stays active
- Resume clicking when ready

### 3. **Undo Last Point**
- Press **Backspace** or **Delete** while drawing
- Removes the last point added
- Keep your line going without starting over

### 4. **Cancel Drawing**
- Press **Escape** to cancel current drawing
- Starts fresh if you make a mistake

### 5. **Straight Segments**
- Each segment between clicks is perfectly straight
- Great for professional-looking diagrams
- No wobbly or curved lines

### 6. **Double-Click Carefully**
- Make sure your last click is where you want it
- Then double-click *on the same spot*
- Or just double-click to finish at current position

---

## 📊 Common Patterns

### "L" Shape (2 bends)
```
Start ──────┐
            │
            │
            └────── End
            
Clicks: 3 (start, corner, end with double-click)
```

### "U" Shape (3 bends)
```
Start ──────┐
            │
            │
            │
        ┌───┘
        │
End ────┘

Clicks: 4 (start, 2 corners, end with double-click)
```

### "S" Shape (multiple bends)
```
        ┌───────┐
Start ──┘       │
                │
        ┌───────┘
        │
End ────┘

Clicks: 5+ (start, each bend, end with double-click)
```

---

## 🎨 Styling Your Lines

After drawing, you can:
1. **Change color** - Click the color square in layers panel
2. **Rename** - Double-click layer name (e.g., "Main Trunk Line")
3. **Edit** - Click the line to enable edit mode, drag vertices
4. **Move** - In edit mode, drag vertices to adjust path

---

## 🚫 Common Mistakes

### ❌ Forgetting to Double-Click
**Problem:** Single-clicking on last point doesn't finish
**Solution:** Remember to **double-click** on the final point

### ❌ Clicking Too Fast
**Problem:** Accidental double-click finishes line early
**Solution:** Take your time between clicks

### ❌ Wrong Tool Selected
**Problem:** Line auto-finishes after 2 points
**Solution:** Make sure you're using **Multi-Point (M)**, not **Straight Line (L)**

### ❌ Can't Pan While Drawing
**Problem:** Need to see more of the map
**Solution:** You CAN pan! Scroll or drag normally, then resume clicking

---

## 💡 Pro Workflow

### For a Typical Fiber Route:

1. **Plan your route** - Look at the map first
2. **Press M** to activate tool
3. **Click at starting point** (vault, building, etc.)
4. **Click at each turn point:**
   - Corners
   - Poles
   - Junction boxes
   - Direction changes
5. **Double-click at endpoint** to finish
6. **Rename the layer** immediately (e.g., "Vault 12 to Building A")
7. **Change color** to match legend (e.g., blue = underground)

---

## 📏 Precision Tips

### For Accurate Placement:

1. **Zoom in close** before clicking
2. **Click once** - don't rush
3. **Verify position** before next click
4. **Use edit mode** after to fine-tune if needed

### Measuring:
While drawing, Leaflet shows:
- Distance of current segment
- Total length of line
- Mouse position

---

## 🔄 Editing After Creation

Made a mistake? No problem!

1. **Switch to Pan mode** (P key)
2. **Click your line** to select it
3. **Edit mode activates** automatically
4. **Drag vertices** to adjust points
5. **Click map** elsewhere to finish editing

---

## 📦 Export Compatibility

Your multi-point lines are fully compatible with:
- ✅ **JSON export** - All points preserved
- ✅ **PDF export** - Renders perfectly
- ✅ **Undo/Redo** - Full support
- ✅ **Layer management** - Rename, color, hide/show
- ✅ **Import** - Reloads with all points intact

---

## 🎯 Quick Reference

| Action | Method |
|--------|--------|
| **Start line** | Single click |
| **Add point** | Single click |
| **Finish line** | Double-click |
| **Undo last point** | Backspace/Delete (while drawing) |
| **Cancel** | Escape |
| **Pan map** | Scroll/drag normally |
| **Edit line** | Click line in pan mode |

---

## 🚀 Get Started Now!

### Try This:

1. **Press M**
2. **Click 5 times** on different spots on the map
3. **Double-click** on the 6th spot
4. You've created your first multi-point line! 🎉

**Perfect for complex utility routes!** 🎊

---

## ❓ FAQ

**Q: How many points can I add?**  
A: Unlimited! Add as many as you need.

**Q: Can I edit the points after drawing?**  
A: Yes! Click the line in pan mode to enable editing.

**Q: What's the difference from the Polygon tool?**  
A: Lines don't close/connect. Polygons create a closed shape.

**Q: Can I measure the total length?**  
A: Yes! The tool shows length while drawing (future feature: permanent display).

**Q: What if I make a mistake?**  
A: Press Backspace to remove last point, or Escape to cancel and start over.

---

**Happy drawing!** This tool makes complex fiber routes a breeze! 📐✨
