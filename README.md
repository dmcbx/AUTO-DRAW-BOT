🎨 Auto Drawing Bot 🎨
Welcome! 👋 This is a fun little application that automatically draws any image you give it onto your screen. It's perfect for drawing in games, MS Paint, or any digital canvas you can think of.

This bot works by taking your image, simplifying it into different color layers (or just finding its outlines), and then taking control of your mouse to draw it for you, line by line!

🖼️ Preview
Here's what the app looks like in action!

(Note: To make this work, you need to take a screenshot or record a GIF of your app. Upload it to a site like Imgur and paste the link here to replace the placeholder.)

✨ Features
🖌️ Multiple Drawing Modes:

Full Mode: Simplifies the image into colored layers and draws it.

Contour Mode: Finds the edges/outlines of your image and draws just the sketch.

New Mode: The best of both! Outlines and fills the colored areas.

💫 Animated UI: A beautiful, animated, multi-color gradient background.

⚙️ Customizable Settings: Control the drawing speed, number of colors, and level of detail.

🛑 Full Stop Control: Easily pause or stop the bot at any time with hotkeys.

🚀 How to Get It
You have two ways to get the bot.

Method 1: The Easy Way (Recommended) 👍
This is for most users. Just download the installer and run it!

Go to the Releases page of this project.

Download the latest AutoDrawingBot-Setup-vX.X.exe file.

Run the installer. It will set up everything you need, including the required Microsoft files and a Desktop shortcut.

That's it! 🎉 Find the "Auto Drawing Bot" on your desktop and run it.

Method 2: The Developer Way (from Source) 🧑‍💻
If you are a developer and want to run the raw Python script:

Install Git: Make sure you have Git installed.

Install Python: Make sure you have Python 3.11+ installed (make sure to check "Add Python to PATH" during installation).

Clone the repository: Open your cmd or terminal and type:

Bash

git clone https://github.com/dmcbx/AUTO-DRAW-BOT.git
cd AUTO-DRAW-BOT
Install libraries: This app needs a few special libraries.

First, create a file named requirements.txt in the AUTO-DRAW-BOT folder.

Copy and paste the following lines into that new file:

Plaintext

PyQt5
opencv-python
numpy
pyautogui
keyboard
mouse
Pillow
Now, install them all by running this command in your terminal:

Bash

pip install -r requirements.txt
Run the app:

Bash

python main.py
🎮 How to Use the Bot
Using the bot is super easy:

Open your canvas: Open MS Paint, a drawing game, or whatever you want to draw on. Make sure it's visible.

Run Auto Drawing Bot: Start the app (it stays on top of other windows).

📂 1. Load Image: Click this to load the picture you want to draw.

⛶ 2. Select Area: Click this. Your screen will dim. Click and drag a box over the exact area you want the drawing to appear (your canvas).

⚙️ Choose Settings:

Mode: Full, Contour, or New.

Colors: (For Full mode) How many colors to simplify to (e.g., 20).

Speed: How fast the mouse moves. 0.01 is fast, 0.001 is very precise.

🚀 START: Click the big START button!

🚨 HANDS OFF! Do not touch your mouse or keyboard. The bot is now in control.

STOPPING:

To PAUSE the drawing, press the P key. (Click Continue in the app to resume).

To STOP the drawing completely, press the Esc key.

⚠️ Disclaimer ⚠️
This is a bot that takes control of your mouse and keyboard. It's meant for fun and creative purposes.

I (the author, Azouz Zohir) am not responsible for anything you do with this bot. Use it entirely at your own risk.

Using this in online games or on platforms where it's not allowed could get your account banned. You have been warned!

Always be ready to stop the bot with the Esc key.

❤️ Support & Connect
Hey, I'm Azouz Zohir! I had a lot of fun building this.

If you liked this project, found a bug, or just want to say hi, you can find me here:

Facebook: Find me on Facebook!

GitHub: Follow me on GitHub

If you really loved it and want to support my work, you can buy me a coffee! ☕

<a href="https://ko-fi.com/Dmcbx"> <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Buy Me a Coffee on Ko-fi"> </a>
