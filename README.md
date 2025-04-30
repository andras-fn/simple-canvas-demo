# Simple Canvas Drawing Demos

This project contains three simple HTML demos for drawing on a canvas in the browser.  
Each demo is in its own folder with an `index.html` file.  
Open any `index.html` file in your web browser to use it—no installation required.

---

## Folder & File List

### 1. `simple-canvas-demo/index.html` — Simple Drawing Canvas

**Features:**
- Draw freehand lines or black rectangles on a blank canvas.
- Switch between "Freehand" and "Rectangle" modes using the buttons.

**How to use:**
1. Open `simple-canvas-demo/index.html` in your browser.
2. Click **Freehand** to draw lines, or **Rectangle** to draw filled rectangles.
3. Click and drag on the canvas to draw.

---

### 2. `simple-canvas-image-demo/index.html` — Drawing Canvas with Image Upload and Save

**Features:**
- Upload an image to use as the canvas background (image is scaled to fit your screen height).
- Draw freehand lines or black rectangles over the image.
- Save your drawing (including the background image) as a PNG file.

**How to use:**
1. Open `simple-canvas-image-demo/index.html` in your browser.
2. Click **Freehand** or **Rectangle** to choose a drawing mode.
3. Click **Choose File** to upload an image (the canvas will resize to fit the image).
4. Draw on the canvas as in the first demo.
5. Click **Save** to download your drawing as a PNG.

---

### 3. `simple-canvas-fabric-demo/index.html` — Simple Fabric.js Demo

**Features:**
- Uses [Fabric.js](http://fabricjs.com/) for easy object-based drawing.
- Draw rectangles, freehand lines, or select/move objects.
- Objects can be selected and moved after drawing.

**How to use:**
1. Open `simple-canvas-fabric-demo/index.html` in your browser.
2. Click **Draw Rectangle** to draw rectangles (click and drag).
3. Click **Free Draw** to draw freehand lines.
4. Click **Select/Move** to select and move objects on the canvas.

---

## Notes

- All files are self-contained and require no dependencies except for `simple-canvas-fabric-demo/index.html`, which loads Fabric.js from a CDN.
- For best results, use a modern browser (Chrome, Firefox, Edge, Safari).
- No data is sent to any server; everything runs locally in your browser.

---

Enjoy drawing!  
Feel free to modify or extend these demos for your own projects.
