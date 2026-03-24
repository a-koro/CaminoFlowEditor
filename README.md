# Camino Flow Editor

A lightweight, zero-dependency visual flow editor built with vanilla HTML, CSS, and JavaScript. Camino Flow Editor is designed to help developers and system architects map out business logic, action handlers, and conditional routing (with MVEL expressions) in a clean, drag-and-drop infinite canvas.

## ✨ Features

* **Compact Canvas:** Blocks are kept visually compact to prevent cognitive overload. All heavy configuration is tucked away in a dedicated modal window.
* **Dynamic Orthogonal Routing:** Connections between blocks are drawn automatically with smart, rounded orthogonal paths.
* **Vertical & Horizontal Modes:** Toggle the entire flow visualization between top-down (vertical) and left-right (horizontal) layouts with a single click.
* **Advanced Intersection Logic:** Configure multiple conditional routes using MVEL expressions, and set fallback "Default" paths.
* **Robust Undo/Redo Engine:** Make a mistake? Full history tracking supports undoing and redoing block creations, deletions, movements, and property changes.
* **JSON Import & Export:** Save your flow topology directly to a `.json` file and load it back up anytime.
* **Zero Dependencies:** No React, no Vue, no NPM install. Just open the HTML file in your browser and start building.

## 🚀 Getting Started

Since Camino Flow Editor is built entirely with vanilla web technologies, there are no build steps or package managers required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/camino-flow-editor.git](https://github.com/yourusername/camino-flow-editor.git)

2. Navigate to the project folder.

3. Open index.html in any modern web browser.

## 🖱️ How to Use

Managing Blocks
Add a Block: Click the + START, + ACTION, + INTERSECTION, or + END buttons in the top toolbar.

Move a Block: Click and drag the header of any block to reposition it on the canvas.

Configure a Block: Double-click a block's header (or click the ⚙️ icon) to open the configuration modal. Here you can set block names, action handlers, target next-blocks, and routing conditions.

Delete a Block: Click the ✖ icon on the block.

## Keyboard Shortcuts

Undo: Ctrl + Z (or Cmd + Z on Mac)
Redo: Ctrl + Shift + Z (or Cmd + Shift + Z / Cmd + Y on Mac)
