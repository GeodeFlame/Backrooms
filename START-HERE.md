# ⚡ QUICK START - Offline Mode

**Just open `backrooms` file in your browser** - that's it!

## How It Works

Simply:
1. **Open** the file named `backrooms` (no extension) in a web browser
   - Windows: Double-click it
   - Mac: Right-click → Open With → Your Browser  
   - Linux: Double-click or open with your browser
2. **Wait** 1-2 minutes for first load (Unity compiles WebAssembly)
3. **Play!** Completely offline, no internet needed

## Files Needed

All of these must be in the **same folder**:
```
backrooms                    ← Open this file
index.html                   
Build/                       ← All files inside needed
TemplateData/               ← All files inside needed
```

## Troubleshooting

**"Cannot find file" or "Page not loading"**
- Make sure ALL files were downloaded to the same folder
- The `Build/` and `TemplateData/` folders must exist with all files inside

**Game takes forever to load**
- Normal! First launch compiles WebAssembly (1-2 minutes)
- Subsequent loads are faster (loads from browser cache)

**"Loading page with loading bar but game never appears"**
- Wait another minute - it's still compiling
- Check browser console (F12) for errors

**Loading bar fills but game crashes**
- Try refreshing the page (F5)
- Try a different browser (Chrome, Firefox, or Edge)
- Make sure the `cache/` `data/` and `StreamingAssets/` folders exist

**Still doesn't work?**
See `README-OFFLINE.md` for alternative methods

---

## What's Happening Behind The Scenes

This works by:
1. Patching the browser's security to allow local file access
2. Intercepting file requests and serving them locally
3. Loading Unity WebGL completely offline
4. All game assets come from local files (no internet!)

**This is real offline play** - no server, no terminal, no scripts needed.
