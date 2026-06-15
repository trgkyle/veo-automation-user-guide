[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/VEO%20Automation%20-%20Google%20Flow%20AI%20VEO%20Automation/fnmijgmnjpealnnadjpjilaanhhambeb)

# 🎬 VEO Automation v3.1.6 - Google Flow AI VEO Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**VEO Automation** is a powerful Chrome extension that automates batch video and image generation on Google Flow AI VEO3. Process multiple prompts simultaneously, configure your workflow, and automatically download generated content with ease.

-----

## ✨ Key Features

* **🚀 Queue Support:** Add multiple prompts to the waiting list instead of manually operating each prompt. The tool will automatically process tasks one by one.
* **📝 Text-to-Video:** Import `.txt`, `.xlsx`, or `.csv` files containing hundreds of prompts to create videos from text.
* **🖼️ Frame-to-Video:** Use a static image and add automatic motion effects. Supports using Start frame or both Start & End frames per prompt.
* **🎨 Ingredients-to-Video:** Animate UI components, interface elements, or characters into videos. Supports auto-matching character images based on filenames.
* **🖼️ Text-to-Image:** Generate images from text descriptions.
* **🔄 Image-to-Image:** Transform and enhance images using AI with text prompts.
* **🤖 Agent Automation:** Automate tasks using advanced agent controls with Google Flow's AI agent.
* **📂 Spreadsheet Import:** Directly import lists of prompts from spreadsheet files (`.xlsx` or `.csv`) with sheet/column preview.
* **💾 Auto Download:** Automatically save videos (720p, 1080p, 4K) and images (1k, 2k, 4k) directly to your machine. Supports folder organization by project name.
* **🛡️ Retry Mechanism:** Automatically retry when encountering network errors or Google creation errors (configurable up to 20 attempts).
* **🌐 Multilingual UI:** Supports 20 languages including English, Tiếng Việt, 中文, and more.

-----

## 📥 Installation

### Method 1: Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](https://chromewebstore.google.com/detail/VEO%20Automation%20-%20Google%20Flow%20AI%20VEO%20Automation/fnmijgmnjpealnnadjpjilaanhhambeb) and click **Add to Chrome**.

---

## 📖 User Guide

### Getting Started

1. **Navigate to Google Flow**
   - Open [Google Labs Flow](https://labs.google/fx/tools/flow)
   - The extension only works on Flow project pages.

2. **Open the Extension**
   - Click the extension icon in the Chrome toolbar and pin it for easier access.

3. **Select a Mode**
   - Choose from 6 generation modes in the Control tab.

---

### 1. Text-to-Video Mode

1. Select **Text to Video** mode in the Control tab.
2. Enter prompts into the input box (each prompt separated by a blank line) OR click **Upload .txt** or **Upload .xlsx / .csv** to import prompts.
3. Configure duration settings in Settings (e.g., 4s, 6s, 8s, 10s, or Concat modes).
4. Click **Run** to start batch processing.

**Example Prompt:**
```
A serene sunset over a calm ocean with gentle waves.
The camera slowly pans across the horizon.

A bustling city street at night with neon lights.
Cars and pedestrians moving through the scene.
```

---

### 2. Frame-to-Video Mode (formerly Image-to-Video)

1. Select **Frame to Video** mode.
2. Click the upload area to select images (supports selecting multiple images).
3. Enter prompts for each image (separate with blank lines).
4. In Settings, configure whether to use only the Start frame or both Start and End frames per prompt.
5. Click **Run** to process.

---

### 3. Ingredients-to-Video Mode (formerly Components-to-Video)

1. Select **Ingredients to Video** mode.
2. Upload ingredient/character images.
3. Enter prompts describing the animation.
4. **Auto-add upload character images** (optional): Enable to match and add character images to prompts based on matching filenames.
5. **Auto-add character (Google Flow feature ⭐)**: Automatically select project characters if their names are mentioned in the prompt (click **Scan Characters** to sync).
6. **Auto-add voice by speaker**: Automatically select speaker voices when speaker names are mentioned in prompts.
7. Click **Run** to generate.

---

### 4. Text-to-Image Mode

1. Select **Text to Image** mode.
2. Enter detailed image descriptions (one per line/separated by blank lines).
3. Configure aspect ratio and image model in Settings.
4. Click **Run** to generate images.

---

### 5. Image-to-Image Mode

1. Select **Image to Image** mode.
2. Upload source images.
3. Enter transformation prompts.
4. **Auto-add upload character images** (optional): Matches images to prompts automatically based on filenames.
5. Click **Run** to generate.

---

### 6. Agent Automation Mode

1. Select **Agent Automation** mode.
2. Enter prompts describing the agent instructions.
3. Support character controls (Google Flow feature ⭐) and auto-adding voice by speaker based on mentions.
4. Click **Run** to execute agent-based tasks.

---

### 📂 Spreadsheet & File Import

- To import multiple prompts, click **Upload .xlsx / .csv** or **Upload .txt** inside any mode.
- For spreadsheets, a preview dialog will appear allowing you to select the target **Sheet** and **Column** containing the prompts.
- Click **Import prompts** to populate the queue.

---

### Queue Management

* View the list of pending tasks in the **Prompt Queue** section.
* Click **Remove** to discard tasks or **Stop** to cancel the currently running queue.
* Delay countdowns between prompts are shown in real-time.

---

## ⚙️ Settings Configuration

Access the **Settings** tab to customize:

### General Settings
- **Default Mode**: Select your frequently used generation mode.
- **Default Aspect Ratio**: Choose 16:9, 9:16, 1:1, 3:4, or 4:3.
- **Outputs per Prompt**: Set output quantity (1-4 images/videos) per prompt.
- **Concurrent Prompts**: Process 1-6 prompts simultaneously (note: Concat/Agent modes run 1 concurrent task to prevent conflict).
- **Random Delay**: Add wait times between prompt submissions to avoid rate limits.

### Model Selection
- **Model (Video)**: Choose from Veo 3.1 or Veo 2 variants.
- **Image Model**: Select your preferred AI model for image generation.

### Mode-Specific Options
- **Default Video Option**: 4s, 6s, 8s, 10s, or Concat modes (`4s/6s/8s/10s concat`).
  > [!NOTE]
  > Chaining with Concat will combine current and subsequent prompts. The last prompt in a sequence always defaults to standard (non-concat) duration.
- **Default Image Mode Option**: Set to New Image or Last Image (reuses previous prompt's output as input).
- **Max Input Images/Videos**: Customize max images for Frame-to-Video, Ingredients-to-Video, and Image-to-Image.

### Download & Advanced Settings
- **Auto Download Quality**: Configure download resolution for Video (720p, 1080p, 4K) and Image (1k, 2k, 4k). Some qualities require Ultra/Pro plans.
- **Max Retries**: Configure automatic retries on failure (1-20 times).
- **Language**: Choose from 20 supported languages.

---

## 💳 Billing & Plans

VEO Automation offers a **Free plan** and a **Max plan** ($3/month):
- Click **Sign in** in the Plan Banner to log in using your email address (does not need to match your Google Flow account).
- Enter the code or check status to verify your subscription.
- Subscribing unlocks premium settings (1080p/4K downloads, Ultra-exclusive duration options, and higher daily prompt limits).

---

## 💡 Tips & Best Practices

1. **Avoiding Rate Limits**
   - Set concurrent prompts to 2-3 during peak hours.
   - Adjust the random delay to 30 seconds or more.

2. **Image Naming**
   - For auto-matching, name images logically (e.g., `hero_pose.png`) and mention the filename in the prompt.

3. **Unusual Activity Error Fix**
   - Ensure you can manually submit at least 3 prompts in a row on Google Flow without error before launching automation.

---

## 🔧 Troubleshooting

| Issue | Cause & Solution |
| --- | --- |
| **Extension not working** | Ensure you are on a Google Flow project page (`labs.google/fx/tools/flow/project/...`). |
| **Unusual Activity / Verification Error** | 1. Click the **Fix Error** (Clear Cache) button in the Control tab.<br>2. Try creating a new project.<br>3. Try using a new browser profile.<br>4. Ensure your account is not flagged by testing manual creation. |
| **Video/Image not downloading** | Disable Chrome's download prompt: Chrome Settings -> Downloads -> **Turn off** *"Ask where to save each file before downloading"*. |
| **Policy Error** | Google flagged the prompt/image. The tool automatically skips it and continues to the next task. |
| **Screen Zoomed Out** | The extension automatically zooms out to cover and locate UI buttons. Do not adjust browser zoom manually while running. |

---

## 🔒 Privacy & Data

* **Local Execution:** All tasks run entirely inside your browser sandbox.
* **No Data Collection:** Your prompts, assets, and keys are stored locally in `Chrome Local Storage` for settings sync and never sent to external servers.

---

## 📞 Support & License

- **Author**: Trường Nguyễn
- **Website**: [kylenguyen.me](https://kylenguyen.me)
- **Copyright**: Copyright © 2025 Trường Nguyễn. All Rights Reserved. (Proprietary software; unauthorized copying, resale, or distribution is prohibited).

_Disclaimer: This extension is an independent project and is not affiliated with, endorsed by, or connected to Google or the Google Flow team._
