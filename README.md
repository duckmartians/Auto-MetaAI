# 🎨 Auto Meta - Automation for Meta AI [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![English](https://img.shields.io/badge/English-blue)](README.md) 

Auto Meta is a Chrome browser extension that automates your bulk video creation workflow on Meta AI Media (`meta.ai/media`), saving you time and accelerating your creativity.

## ✨ Key Features

* **Two Smart Operation Modes**:
    1.  **Image-to-Video**: Activates automatically when you select images. Uses 1 image + 1 prompt to create a video.
    2.  **Text-to-Video**: Activates automatically when you do *not* select images. Uses only 1 prompt to create a video.
* **Bulk Image Upload**: Select multiple images at once to add to the queue.
* **Image Sorting**: Sort your image list by A-Z, Z-A, Newest, or Oldest.
* **Import Prompts from File**: Supports bulk importing prompts from a `.txt` file.
* **Auto-Download**: Automatically scans for and downloads newly created videos.
* **Flexible Settings**: Configure wait times and the starting position to fit your needs.
* **Multi-language Interface**: Supports both Vietnamese and English.

## 🚀 Installation

1.  Go to the Chrome Web Store.
2.  Search for "**Auto Meta - Automation for Meta AI**".
3.  Click "Add to Chrome".

[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/bchhcfjoloinebjpbfklckgohpjehdmf)

## 📖 How to Use

### Step 1: Navigate

Open Chrome and go to the Meta AI Media page:
**`https://www.meta.ai/media`**

The extension will only work on this page. If you are on a different page, the extension panel will show a "Go to Meta AI" button.

### Step 2: Open the Extension

Click the Auto Meta icon (the duck) on your Chrome toolbar to open the control panel.

### Step 3: Choose Mode and Input Data

You have two ways to run the tool:

#### Method 1: Image-to-Video Mode 

This mode is enabled automatically when you have images selected.

1.  In the **Control** tab, click **"Select multiple images"** and choose all the images you want to process.
2.  **Sort** (Optional): Choose the processing order for your images (A-Z, Newest, etc.).
3.  In the **Prompt List** box, enter your prompts.
    * **Note:** The tool takes 1 image + 1 prompt. If your prompt list is shorter than your image list, the prompts will be reused (cycled).
4.  Click **"Start"**.

#### Method 2: Text-to-Video Mode (Prompts Only)

This mode is enabled automatically when you have **NO** images selected.

1.  Ensure the counter says "Selected: 0" (no images).
2.  In the **Prompt List** box, enter your prompts.
    * **Note:** Each prompt must be separated by a **blank line**. The tool will create 1 video per prompt.
3.  Click **"Start"**.

### Step 4: Settings (Optional)

Go to the **Settings** tab to fine-tune:

* **Start from...**: Enter the number (Image or Prompt) you want the tool to start from.
* **Wait time**: The tool automatically suggests different wait times (in seconds) for each mode (10-20s for Image-to-Video, 15-30s for Text-to-Video). You can adjust this manually.
* **Auto-download videos**: Enable this to have the tool automatically scan for and download new videos.

### 💡 Important Tip (For Auto-Download)

To ensure videos download automatically without asking, you must disable Chrome's "Ask where to save..." setting:
1.  Go to `chrome://settings/downloads`.
2.  Turn **OFF** the option **"Ask where to save each file before downloading"**.

## 👨‍💻 Author

Developed by **Đặng Minh Đức (duckmartians)**.

## 📜 License

This source code is licensed under the terms of the MIT License. Please see the `LICENSE.md` file for details.
