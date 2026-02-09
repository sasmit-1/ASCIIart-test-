Pixel to Text | ASCII Art Generator

A lightweight, single-file web application that converts images into ASCII art directly in your browser. This tool emphasizes privacy and speed by performing all image processing client-side using the HTML5 Canvas API.

🚀 Features

Real-time Conversion: See changes instantly as you adjust settings.

Privacy First: No images are uploaded to a server. All processing happens locally in your browser.

Drag & Drop: Simply drag an image file onto the drop zone to begin.

Fine-Grained Control:

Resolution: Adjust the character width to balance detail vs. size.

Contrast: Enhance washed-out images to make the ASCII characters pop.

Invert Mode: Toggle between mappings for dark or light backgrounds.

Multiple Character Sets: Choose from Standard, Complex, Simple, Block characters, or Binary.

Zoom Controls: Increase or decrease the font size for better viewing.

One-Click Copy: Easily copy the generated art to your clipboard.

🛠️ Installation & Usage

Since this is a single-file application, no build process or server installation is required.

Download: Save the ascii_generator.html file to your computer.

Run: Double-click the file to open it in your default web browser.

Use:

Click "Load Sample" or drop an image into the upload box.

Adjust sliders to taste.

Click "Copy Text" to use your art in code comments, text files, or social media.

💻 Tech Stack

HTML5 & CSS3: Core structure and styling.

JavaScript (ES6+): Logic and Canvas API manipulation.

Tailwind CSS: Utility-first styling (loaded via CDN).

Google Fonts: Fira Code for monospaced rendering.

🎨 Customization

The code is contained entirely within ascii_generator.html. To customize the character sets, look for the CHAR_SETS object in the <script> section:

const CHAR_SETS = {
    standard: "Ñ@#W$9876543210?!abc;:+=-,._ ",
    // ... add your own sets here
};


You can modify these strings to change which characters are used for different brightness levels (darkest to lightest).

📄 License

Open source. Feel free to modify and distribute.
