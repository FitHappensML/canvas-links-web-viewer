
# 🕸️ Canvas Viewer: Web Links

![Promo Image](assets/image_01.png)

A lightweight, **single-file** interactive viewer for Obsidian Canvas files (`.canvas`) that runs entirely in your browser. No server required.

## 💡 The Idea: Order from Chaos

> *"I run many projects in parallel. With 20+ tabs open, working now is fine. But a week later? It's impossible to remember what was what. Tabs turn into a graveyard."*

This viewer solves "Tab Fatigue" by putting your entire project context on a **Big Infinite Sheet**.

*   **See the Structure**: Don't just list links—map out *how* they relate to each other.
*   **Instant Clarity**: Open one file and immediately grasp the project's state, even months later.
*   **100% Portable**: It's just a file. Copy it to a flash drive, sync it via Git/Syncthing, or email it.
*   **No Cloud Required**: Your data stays yours. No "Sign up to view."

### 🚀 Key Features

*   **Zero Install**: Everything is contained in one `canvas_viewer.html` file.
*   **Vault Integration**: Connect your Obsidian Vault folder to preview linked markdown notes directly in the canvas.
*   **Rich Link Previews**:
    *   **Arxiv Papers**: Automatically fetches Title & Abstract (with CORS proxy support).
    *   **YouTube**: Embeds videos directly.
    *   **Images**: Renders image links inline.
*   **Smart History**: Remembers your recent files and vaults for one-click reconnection.
*   **Search & Zoom**: Full pan/zoom controls and text search for large canvases.

---

### 📸 Screenshots

| Obsidian Original | Canvas Web Viewer |
| :---: | :---: |
| ![Obsidian Screenshot](assets/image_02.png) | ![App Screenshot](assets/image_03.png) |
| *Your canvas in Obsidian* | *The same canvas in any browser* |

---

### 📦 How to Use

1.  **Download**: Get the [canvas_viewer.html](canvas_viewer.html) file.
2.  **Open**: Double-click to open it in Chrome, Edge, or Firefox.
3.  **Load Canvas**: Click **"Open File"** to select a `.canvas` or drag-and-drop it.
4.  **Connect Vault (Optional)**: Click **"Select Vault Folder"** to enable markdown note previews.

> **Note**: For the best experience, use a modern browser that supports the File System Access API (Chrome/Edge) to enable persistent file access.

### 🛠️ Configuration
No configuration needed! All settings (like zoom level, recent files) are stored locally in your browser.

---

### 📄 License

This project is licensed under the [MIT License](LICENSE).
