# Bitmap Gallery Builder

The Bitmap Gallery Builder was created to empower users to build highly customized, interactive online portfolios or "linktree-style" pages without writing a single line of code. It bridges the gap between powerful design tools and simple website builders by offering a flexible, canvas-based editing experience with a focus on a simple, powerful final output.

The entire application runs in a single HTML file, and the final export is a self-contained static website, making it incredibly easy to host on platforms like Netlify, Vercel, or GitHub Pages.

---

## Key Features

* **Visual, Canvas-Based Editor:** Drag, drop, resize, and rotate elements freely on an 800x800 canvas with intuitive pan and zoom controls.
* **Rich Content Blocks:** Create "Blocks" that act as powerful containers for various media types:
    * Images & Videos (from URL or local upload)
    * Formatted Text
    * YouTube & X (Twitter) embeds
    * Customizable hyperlinks
* **Vector Tools:** Add standalone text and free-form doodle shapes to complement your gallery.
* **Robust Progress Management:**
    * **Browser Cache:** Automatically saves your work to the browser's local storage, allowing you to resume your session after closing or refreshing the page.
    * **Import/Export Drafts:** Save your entire canvas state to a `.json` file to create backups or move your work between computers.
* **One-Click Website Export:** Package your entire creation into a self-contained `.zip` file, including a static `index.html` and all necessary assets, ready for immediate deployment.
* **Undo/Redo History:** A reliable undo/redo system (`Ctrl+Z`) tracks every action for a stress-free editing experience.
* **Advanced Customization:** Use the context-aware properties panel to edit titles, descriptions, and even apply decoration overlays to your blocks with real-time controls for opacity, scale, and corner radius.

---

## Getting Started: A Simple Usage Guide

The Bitmap Gallery Builder is designed to be intuitive. Here’s how to get started in 5 simple steps:

### **Step 1: Open the Application**

Simply open the `gallery-build.html` file in your web browser (like Chrome or Firefox).

### **Step 2: Add Elements to Your Canvas**

Use the main control buttons to add your first elements:
* Click **"Add Block"** to create a new content block.
* Click **"T+ Add Text"** to add standalone text.
* Click **"✏️ Doodle"** to enter drawing mode and create free-form lines.

### **Step 3: Customize Your Elements**

* **Select an element** by clicking on it. A transformer tool will appear, allowing you to drag, resize, and rotate it.
* With an element selected, the **Properties Panel** on the right will activate. Here you can:
    * For **Blocks**: Change the title, description, and add content like images, videos, or links. Switch to the "Decoration" tab to add a stylish image overlay.
    * For **Text**: Change the text content, font size, and color.

### **Step 4: Save Your Progress**

You have two ways to save your work:
1.  **Save to Cache:** Click the **"Save to Local Cache"** button. Your work is now saved in the browser. If you refresh the page, it will automatically reload.
2.  **Export Draft:** Click the **"Export Draft"** button to save your entire project as a `gallery-draft.json` file. This is useful for creating backups. You can load it back anytime using the **"Import Draft"** button.

### **Step 5: Export Your Final Website**

Once you are happy with your design, click the **"📁 Export as .zip"** button. This will generate a `.zip` file containing your finished, interactive website. Unzip it and upload the contents to any static web host to share your gallery with the world!

---

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

---

## Contact

Created by: [@Evan_XYZ_](https://x.com/Evan_XYZ_) on X
