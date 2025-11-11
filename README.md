# 🎨 Auto Drawing Bot

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Dmcbx)

Welcome to Auto Drawing Bot! 👋 This fun little tool takes any image you give it, analyzes its colors and shapes, and then automatically draws it in any painting program (like MS Paint, Photoshop, etc.) by controlling your mouse.

It's perfect for creating fun time-lapse videos or just watching a robot artist at work! 🤖

## 🖼️ Preview

(Here's a quick look at the app in action!)

*(You should record a GIF or take a screenshot of your app, upload it to your GitHub repo, and replace the link below)*
![Auto Drawing Bot Preview GIF](https://github.com/dmcbx/AUTO-DRAW-BOT/blob/main/your-preview-image.png?raw=true)

## ✨ Features

* **Multiple Drawing Modes:**
    * 🎨 **Full Mode:** Simplifies the image into colored layers and draws it line-by-line.
    * ✍️ **Contour Mode:** Detects the edges and sketches the outline of the image.
    * 🖌️ **New Mode (Color-Aware):** Intelligently draws the outlines *and* fills for each color.
* **Total Control:** Adjust the number of colors, drawing speed, and level of detail.
* **Cool Interface:** A custom, modern UI with a moving animated gradient background.
* **Easy to Use:** Simple, step-by-step interface.

## 🚀 Getting Started

You have two ways to get the app:

### 1. For Regular Users (Easy Way) ✅

Just download the latest setup file and install it.

1.  Go to the **[Releases Page](https://github.com/dmcbx/AUTO-DRAW-BOT/releases)**.
2.  Download the `AutoDrawingBot-Setup-v1.0.exe` file.
3.  Run the installer. It will install the app, add it to your Start Menu, and create a Desktop shortcut.

### 2. For Developers (Running from Source) 🧑‍💻

If you want to run the Python script directly or make your own changes:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/dmcbx/AUTO-DRAW-BOT.git](https://github.com/dmcbx/AUTO-DRAW-BOT.git)
    cd AUTO-DRAW-BOT
    ```
2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    .\venv\Scripts\activate
    ```
3.  **Install the required libraries:**
    ```bash
    pip install pyqt5 pyautogui opencv-python numpy mouse keyboard pillow
    ```
4.  **Run the app:**
    ```bash
    python main.py
    ```

## 📖 How to Use

1.  Open your drawing program (like MS Paint, Krita, etc.) with a blank canvas.
2.  Run the **Auto Drawing Bot**.
3.  Click **"📂 1. Load Image"** and choose the picture you want to draw.
4.  Click **"⛶ 2. Select Area"**. The app will hide. Click and drag your mouse to draw a box around your blank canvas area.
5.  Choose your settings:
    * **Mode:** `Full`, `Contour`, or `New`.
    * **Colors:** How many colors to simplify the image to.
    * **Speed:** How fast the mouse moves (0.01 is fast, 0.1 is slow).
6.  Click **"🚀 START"**.
7.  **HANDS OFF!** 👐 Do not touch your mouse or keyboard. The bot is now drawing.

### 🛑 HOW TO STOP THE BOT

**To stop the bot at ANY time, just press the `Esc` key on your keyboard!**

## ⚠️ Disclaimer & Warning

This is a bot. It takes control of your mouse and keyboard to draw.

* **DO NOT** leave this bot running unattended.
* **SAVE YOUR WORK** in all other programs before running this.
* The creator (Dmcbx) is **NOT responsible** for any lost work, messed-up drawings, or any other issues that happen while this bot is running.

**You are using this software entirely at your own risk.**

## ❤️ Support & Contact

Found a bug or have a cool idea? Let me know!

* **Facebook:** [Find me on Facebook](https://www.facebook.com/lucy.dragneel.756412)
* **GitHub:** [Open an Issue](https://github.com/dmcbx/AUTO-DRAW-BOT/issues)

If you like this tool, please consider supporting its development! ☕

[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Dmcbx)
