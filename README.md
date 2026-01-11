[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/grok-automation-grokcom-a/kpeloeongamilgpjaibcdmldenfmdngp?authuser=2&hl=vi)

# 🚀 Grok Automation v1.0.5 - Grok.com AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Grok Automation** is a powerful productivity tool designed to supercharge your creative workflow on xAI's grok.com. Stop manually entering prompts one by one—automate the process and generate high-quality content at scale.

-----

## ✨ Key Features

* **🚀 Advanced Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle the submission and generation automatically.
* **🎬 Text-to-Video Automation:** Generate stunning videos from text descriptions. Supports **"Concat"** mode to combine multiple prompts into longer video sequences.
* **🖼️ Frame-to-Video:** Use a static image and add automatic motion effects to create dynamic videos.
* **🎨 Components-to-Video:** Specifically designed to animate UI components and interface elements into high-quality video.
* **🖼️ Text-to-Image Batching:** Create multiple images simultaneously with support for various aspect ratios (16:9, 9:16, 1:1, 2:3, 3:2).
* **🔄 Image-to-Image:** Transform and enhance existing images using AI with text prompts.
* **⚙️ Professional Control Suite:**
    * **Smart Delays:** Set custom intervals between prompts to manage rate limits effectively.
    * **Auto-Upscale & Download:** Automatically trigger upscaling and save the final results to your computer.
* **📊 Real-time Queue Management:** Monitor your generation progress with a visual status bar and active prompt list in the Side Panel.
* **📂 Organized File Management:** Automatically sorts downloads into project-specific folders to keep your workspace clean.
* **🌐 Multi-language Support:** Available in English, Vietnamese, and Chinese.

-----

## 📥 Installation

### Method 1: Chrome Web Store (Recommended)
1. Visit the [Chrome Web Store](https://chromewebstore.google.com/detail/grok-automation-grokcom-a/kpeloeongamilgpjaibcdmldenfmdngp?authuser=2&hl=vi)
2. Click **Add to Chrome**.

---

## 📖 User Guide

### Getting Started

1. **Navigate to Grok.com**
   - Open [grok.com/imagine](https://grok.com/imagine)
   - The extension only works on Grok "Imagine" pages.

2. **Open the Extension**
   - Click the extension icon in Chrome toolbar. Pin it for easier access!

3. **Select a Mode**
   - Choose from 5 generation modes in the **Control** tab.
   - Each mode is tailored for different creative needs.

### 1. Text-to-Video Mode

1. Select **Text to Video** mode.
2. Enter prompts into the input box (separate each prompt with a **blank line**).
3. Alternatively, click **Upload .txt file** to import a list of prompts.
4. Choose duration: **8s** for individual clips or **Concat** to combine with the next prompt.
5. Click **Run** to start the batch.

**Example Prompt:**
```
A futuristic cyberpunk city with neon lights reflecting in the rain.
The camera glides through the narrow alleys.

A peaceful Japanese garden with cherry blossoms falling into a pond.
A slow zoom into the koi fish swimming below.
```

### 2. Frame-to-Video Mode

1. Select **Frame to Video** mode.
2. Click to upload or drag & drop source images.
3. Enter prompts (separate with blank lines). Each image will be processed with each prompt.
4. Click **Run**.

### 3. Components-to-Video Mode

1. Select **Components to Video** mode.
2. Upload your UI/Component images.
3. Enter descriptive prompts.
4. Enable **"Auto-add character images"** to automatically match images based on filenames mentioned in your prompts.
5. Click **Run**.

### 4. Text-to-Image Mode

1. Select **Text to Image** mode.
2. Enter detailed descriptions for your images.
3. Configure the desired **Aspect Ratio** in the Settings tab.
4. Click **Run**.

### 5. Image-to-Image Mode

1. Select **Image to Image** mode.
2. Upload source images you want to transform.
3. Enter transformation prompts.
4. Use **"Auto-add character images"** if you want to use specific reference images for characters.
5. Click **Run**.

---

## ⚙️ Settings Configuration

Access the **Setting** tab to customize your automation experience:

* **Default Mode:** Set which mode opens by default.
* **Default Aspect Ratio:** Choose from 16:9, 9:16, 1:1, 2:3, or 3:2.
* **Outputs per Prompt:** Set how many videos (1-4) or images (1-50) to generate per prompt.
* **Concurrent Prompts:** Number of prompts to process simultaneously.
* **Prompt Delay:** Adjust the wait time between submissions (seconds).
* **Model Selection:** Choose between Grok 3.1 (Fast/Quality) or Grok 2 (Fast/Quality).
* **Auto Download Upscale:** Enable automatic downloading of the upscaled versions.
* **Language:** Switch between English, Tiếng Việt, and 中文.

---

## 💡 Tips & Best Practices

1. **Wait Times:** If you encounter rate limits, increase the **Prompt Delay** in Settings.
2. **File Organization:** Use descriptive project names to keep your downloads organized in separate folders.
3. **Prompting:** Be specific! Detailed prompts lead to better AI generations. Separate multiple prompts with a clear blank line.
4. **Auto-Matching:** For Component modes, name your files clearly (e.g., `hero.png`) and use that name in your prompt to use the **Auto-add character images** feature.

---

## 🔧 Troubleshooting

| Issue | Solution |
| :--- | :--- |
| **Extension not active** | Ensure you are on [grok.com/imagine](https://grok.com/imagine). Refresh the page if needed. |
| **Generation Errors** | Grok might be busy. The extension will automatically retry based on your **Max Retries** setting. |
| **Downloads not working** | Ensure "Ask where to save each file before downloading" is **OFF** in Chrome Settings. |
| **Login Required** | Make sure you are logged into your Grok.com account. |

---

## 🔒 Privacy & Data

* **Local Processing:** All automation logic runs locally in your browser.
* **No Data Collection:** We do not store or collect your prompts, images, or account data.
* **Secure Storage:** Settings are saved only in your browser's local storage.

---

## 📞 Support

- **Author:** Trường Nguyễn
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Feedback:** Use the "Report a bug" link in the extension.

---

## 📦 Version

Current version: **1.0.5**

---

## 📜 License

Copyright © 2026 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary. Unauthorized copying or distribution is prohibited.

---

**Made with ❤️ by Trường Nguyễn**
