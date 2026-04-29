# 🎮 Backrooms Game - TRUE Offline Edition

**Open any of these files in your browser - NO SERVER NEEDED!**

## 🚀 Fastest Way to Play

1. **Open `backrooms` file** in your web browser
2. **Wait** 1-2 minutes for first load (only first time!)
3. **Play!**

That's it. No scripts. No terminal. Just open and play offline.

### How to Open:
- **Windows:** Double-click the `backrooms` file
- **Mac:** Right-click → Open With → Choose Browser (Chrome/Firefox/Safari)
- **Linux:** Double-click or open with your default browser

---

## ✅ What's Included

- **`backrooms`** ← Main entry point (open this!)
- **`index.html`** ← Alternative entry point  
- **`BUILD/`** ← Game engine (required)
- **`TEMPLATEDATA/`** ← Game resources (required)
- **`StreamingAssets/`** ← Game assets
- **`data/`** ← Image and game data
- **`cache/`** ← Cached resources

**All files must stay together in the same folder!**

---

## 🎯 Why This Works

This version patches the browser's security restrictions to allow:
- Loading game assets from local `file://` URLs
- Running Unity WebGL offline without a server
- Direct browser access to all resources

**It's a true offline solution** - nothing needs to be installed!

---

## ⏱️ First Time Loading

- **First launch:** 1-2 minutes (browser compiles WebAssembly)
- **Later launches:** 10-30 seconds (uses cached data)
- **Total download:** ~100-300 MB

---

## 🛠️ Troubleshooting

### "Page shows blank/just loading bar"
- **Wait longer** - Unity is still compiling (can take 2+ minutes)
- Check browser console (F12 → Console tab) for errors

### "Cannot find file" error
- Ensure ALL folders and files are in the **same directory**
- Check that `Build/` and `TemplateData/` folders exist with contents

### Game loads but immediately crashes
- Try **refreshing** (F5)
- Try a **different browser** (Chrome, Firefox, or Edge recommended)
- Check that `cache/` and `data/` folders exist

### "Access denied" or CORS error
- This is normal with `file://` - our patcher should handle it
- If still failing, use `START-GAME.bat` (Windows) or `run-game.sh` (Mac/Linux)

### Game is slow/stuttering
- Close other applications
- Lower browser zoom (Ctrl+Minus)
- Try a faster browser (Chrome is fastest for WebGL)

---

## 📱 Browsers That Work

✅ **Chrome / Chromium** - Best performance  
✅ **Firefox** - Works great  
✅ **Edge** - Works great  
✅ **Safari** - Works (Mac/iPad)  
❌ **Internet Explorer** - Not supported

---

## 🎮 Game Controls

Once the game loads, see the in-game instructions for controls.

Press **F11** or **F** for fullscreen mode.

---

## 📲 Still Need Help?

See other options in:
- **`START-HERE.md`** - Quick start guide  
- **`CHROMEBOOK-SETUP.md`** - For Chromebook users
- **`README-OFFLINE.md`** - This file (alternative methods)

---

## Alternative Methods (if direct doesn't work)

### Windows:
Double-click `START-GAME.bat` - Automatically starts local server

### Mac/Linux:
Run `bash run-game.sh` OR `python3 launch-game.py` OR `python3 -m http.server 8000`

### Chromebook:
See `CHROMEBOOK-SETUP.md` for Crostini or GitHub Pages options

---

Enjoy the game offline!
