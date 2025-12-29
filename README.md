# 🎬 VEO Automation - Google Flow AI VEO Automation

**VEO Automation** is a powerful Chrome extension that automates batch video and image generation on Google Flow AI VEO3. Process multiple prompts simultaneously, configure your workflow, and automatically download generated content with ease.

[Tiếng Việt](README_vi.md) | [中文](README_zh.md)

---

## ✨ Key Features

* **🚀 Smart Queue:** Add a batch of prompts or images to the waiting list. The tool will automatically process tasks one by one.
* **📝 Text-to-Video:** Support importing `.txt` files containing hundreds of prompts.
* **🖼️ Image-to-Video:** Automatically upload images, crop aspect ratios, and generate motion.
* **🎨 Components-to-Video:** Animate UI components and interface elements into videos.
* **🖼️ Text-to-Image:** Generate images from text descriptions.
* **🔄 Image-to-Image:** Transform and enhance images using AI with text prompts.
* **💾 Auto Download:** Automatically save videos and images to your machine immediately after rendering finishes. Supports folder organization by project name.
* **🛡️ Retry Mechanism:** Automatically retry when encountering network errors or when Google's queue is full.
* **⚙️ Deep Customization:**  
   * Select Model (Veo 2, Veo 3.1...).  
   * Select Aspect Ratio (16:9, 9:16, 1:1).  
   * Set number of video variants per prompt (1-4 variants).
   * Configure concurrent prompts (1-6 simultaneous).
   * Set prompt delay (0-300 seconds).

---

## 📥 Installation

### Method 1: Chrome Web Store (Recommended)
1. Visit the Chrome Web Store
2. Search for "VEO Automation"
3. Click "Add to Chrome"

### Method 2: Manual Installation
1. Download the extension ZIP file
2. Extract the ZIP file
3. Open Chrome and navigate to `chrome://extensions/`
4. Enable "Developer mode" (toggle in top-right)
5. Click "Load unpacked"
6. Select the extracted folder

---

## 📖 User Guide

### Getting Started

1. **Navigate to Google Flow**
   - Open [Google Labs Flow](https://labs.google/fx/tools/flow)
   - The extension only works on Flow project pages

2. **Open the Extension**
   - Click the extension icon in Chrome toolbar
   - Or use the side panel (if enabled)

3. **Select a Mode**
   - Choose from 5 generation modes in the Control tab
   - Each mode has specific features and requirements

### 1. Text-to-Video Mode

1. Select **Text-to-Video** mode in the Control tab.
2. Enter prompts into the empty box (each prompt separated by a blank line) OR click the **Import file (.txt)** button to upload a list of prompts.
3. Set the number of videos and aspect ratio.
4. Click **Run** to start batch processing.
5. Monitor progress in the progress section.

**Example Prompt:**
```
A serene sunset over a calm ocean with gentle waves.
The camera slowly pans across the horizon.

A bustling city street at night with neon lights.
Cars and pedestrians moving through the scene.
```

### 2. Image-to-Video Mode

1. Select **Image-to-Video** mode.
2. Click **Select images** to upload (supports selecting multiple images at once).
3. Enter prompts for each image (separate with blank lines).
4. Configure duration settings (8s or Concat).
5. Click **Run** to process.

**Tips:**
- Images are processed with each prompt
- Sort images by name, date, or custom order
- Maximum 2 images per prompt (configurable in settings)

### 3. Components-to-Video Mode

1. Select **Components-to-Video** mode.
2. Upload component images.
3. Enable "Auto-add character images" (optional) - automatically matches character images based on filenames.
4. Enter prompts describing the animation.
5. Click **Run** to generate videos.

**Features:**
- Auto-matches character images based on filenames
- Supports up to 3 images per prompt
- Perfect for animating UI components

### 4. Text-to-Image Mode

1. Select **Text-to-Image** mode.
2. Enter detailed image descriptions.
3. Configure aspect ratio and image model in Settings.
4. Click **Run** to generate images.

### 5. Image-to-Image Mode

1. Select **Image-to-Image** mode.
2. Upload source images.
3. Enter transformation prompts.
4. Configure settings (up to 10 images per prompt).
5. Click **Run** to transform images.

### Queue Management

* View the list of pending tasks in the Prompt Queue section.
* You can **Remove** excess tasks or **Stop** running tasks.
* Monitor real-time progress for each prompt.

---

## ⚙️ Settings Configuration

Access the **Settings** tab to customize:

### General Settings
- **Default Mode**: Set your preferred generation mode
- **Default Aspect Ratio**: Choose 16:9, 9:16, or 1:1
- **Outputs per Prompt**: 1-4 outputs
- **Concurrent Prompts**: 1-6 simultaneous prompts
- **Prompt Delay**: Wait time between prompts (0-300 seconds)

### Model Selection
- **Video Model**: Choose from Veo 3.1 or Veo 2 variants
- **Image Model**: Select AI model for text-to-image

### Download Settings
- **Auto Download Quality (Video)**: 720p, 1080p, or No Download
- **Auto Download Quality (Image)**: 1k, 2k, 4k, or No Download
- Videos are saved to Chrome's Download folder
- Each project has its own folder

### Advanced Settings
- **Max Retries**: 1-20 retry attempts on failure
- **Default Video Frame**: 8 seconds or Concat
- **Max Images per Prompt**: Configure for each mode
- **Language**: English, Vietnamese, or Chinese

---

## 💡 Tips & Best Practices

1. **Prompt Writing**
   - Be specific about style, duration, and visual elements
   - Use clear, descriptive language
   - Separate multiple prompts with blank lines

2. **Batch Processing**
   - Start with fewer concurrent prompts to test
   - Adjust delay based on your needs
   - Monitor the progress section for status

3. **Image Management**
   - Name images clearly for auto-matching
   - Use supported formats (PNG, JPG, GIF)
   - Keep file sizes under 10MB

4. **Performance**
   - Lower concurrent prompts = more stable
   - Higher delay = less server load
   - Use appropriate quality settings for downloads

---

## 🔧 Troubleshooting

| Issue                     | Cause & Solution                                                                                                                                                             |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Extension not working** | Ensure you're on a Google Flow project page. Check that the extension is enabled. Refresh the page and try again.                                                           |
| **"Queue Full" Error**    | Google Flow limits the number of videos processed simultaneously. **Don't worry**, the Extension will automatically wait and retry every 30s until a slot becomes available. |
| **Video not downloading** | Go to Chrome Settings -> Downloads -> **Turn off** _"Ask where to save each file before downloading"_. Check download settings in the Settings tab.                        |
| **"Policy Error"**        | Your prompt or image violates Google's content policy. The tool will automatically skip this task and proceed to the next one.                                               |
| **Generation fails**      | Check your internet connection. Verify prompts are valid. Review retry settings. Check browser console for errors.                                                          |
| **Screen Zoomed Out**     | This is an automatic feature of the tool to cover the interface and locate buttons accurately. Please do not adjust the zoom manually while the tool is running.             |

---

## 🔒 Privacy & Data

* **Local Operation:** VEO Automation runs entirely on your browser.
* **No Data Collection:** We do not collect your prompts, images, or videos. All data is stored only in your own `Chrome Local Storage` to remember settings.
* **Permissions:** The extension only requests access to `labs.google/*` pages to perform automation tasks.

---

## 📞 Support

- **Author**: Trường Nguyễn
- **Website**: [kylenguyen.me](https://kylenguyen.me)
- **Report Issues**: Use the "Report a bug" link in the extension

---

## 📦 Version

Current version: **2.1.2**

---

## 📜 License

Copyright © 2025 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary property. Unauthorized copying, modification, distribution of source code, or resale in any form without written permission from the author is strictly prohibited.

---

_Disclaimer: This extension is an independent project and is not affiliated with, endorsed by, or connected to Google or the Google Flow team._

**Made with ❤️ by Trường Nguyễn**
