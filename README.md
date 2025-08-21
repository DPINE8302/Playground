# Playground

# CSS Animation Playground 🔧

A live, in-browser editor that lets users write HTML/CSS code and see their CSS animations, transitions, and transforms instantly. Experiment, save your creations as presets, and easily export your code.

## 🌟 Core Features

*   **📝 Dual Code Editors:** Separate text areas for HTML and CSS.
*   **👁️ Live Preview:**
    *   Instantly renders the HTML structure with applied CSS animations in a sandboxed iframe.
    *   **Fullscreen Mode:** View your animation in an immersive, distraction-free fullscreen preview.
*   **💾 Preset Management:**
    *   **Save:** Store your HTML and CSS combinations as named presets in `localStorage`.
    *   **Load:** Quickly load saved presets from a dropdown menu.
    *   **Delete:** Remove presets you no longer need.
    *   **Import/Export:** Share your creations by exporting presets as JSON and importing them later.
*   **📤 Code Export:**
    *   **Copy:** One-click copy HTML or CSS to your clipboard.
    *   **Download:** Download your animation as a self-contained `.html` file or just the `.css` styles.
*   **🌈 Theme Toggle:** Switch between light and dark modes for comfortable viewing, inspired by modern OS aesthetics.
*   **🔄 Session Persistence:** Your current HTML and CSS code is saved in `localStorage` so you don't lose your work if you accidentally close the tab.
*   **🚀 Built-in Examples:** A few pre-loaded animation examples to get you started quickly.
*   **🖋️ Apple-Inspired UI:** Clean, minimalist design for a pleasant user experience.

## 🤔 How It Works

The application is built entirely with client-side HTML, CSS, and JavaScript:

1.  **Input:** Users type HTML and CSS into dedicated `<textarea>` elements.
2.  **Live Update:** JavaScript listens for input changes and, after a short debounce period, updates the content of an `<iframe>`.
    *   The HTML content is directly injected.
    *   The CSS content is embedded within a `<style>` tag in the iframe's `<head>`.
3.  **Fullscreen Preview:** A button toggles a class on the `<body>` element. CSS rules associated with this class hide non-preview elements and expand the preview iframe to fill the viewport. The `Escape` key also exits fullscreen mode.
4.  **Presets:** Animation presets (name, HTML, CSS) are stored as JSON objects in the browser's `localStorage`.
5.  **Theming:** CSS variables are used for styling, allowing for an easy switch between light and dark themes by toggling a class on the `<body>` element. Theme preference is also saved in `localStorage`.

## 🛠️ Technologies Used

*   **HTML5**
*   **CSS3** (including CSS Variables and Flexbox/Grid for layout)
*   **Vanilla JavaScript (ES6+)**
    *   No external libraries or build tools are required for the core functionality.

## 🚀 How to Use

1.  Clone this repository or download the `css_playground.html` (or your chosen filename).
2.  Open the `css_playground.html` file in any modern web browser (e.g., Chrome, Firefox, Edge, Safari).
3.  Start typing your HTML and CSS, and see the magic happen in the live preview pane!
4.  Click the "Fullscreen" button on the preview panel to see your animation take over the screen.
5.  Here's the page [Terminal.](https://dpine8302.github.io/Playground/)


## ✨ Bonus Ideas (Potential Future Enhancements)

*   ✅ **Preset Tabs:** Add tabs for common animation styles (e.g., fade, slide, rotate) as quick starters.
*   ⌛ **Time Scrubber:** Implement a delay/time scrubber to preview animation speed or pause/play animations.
*   🎁 **Shareable URLs:** Generate shareable links by encoding the HTML/CSS code in base64 within the URL.
*   📚 **CSS Animation Cheat Sheet:** Include a slide-in sidebar with a quick reference guide to CSS animation properties.
*   🎨 **Syntax Highlighting:** Integrate a lightweight library like Prism.js for better code readability in the editors.
*   📦 **Export as ZIP:** Allow exporting HTML and CSS together in a ZIP file.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/YOUR_USERNAME/Terminal./issues) (if you've created one).

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

---
<p align="center">
  Created with ❤️ by Kirati Rattanaporn (Win)
</p>
<p align="center">
  ©2025 Wiqnnc_. All Rights Reserved.
</p>
