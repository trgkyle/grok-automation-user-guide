[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/grok-automation-grokcom-a/kpeloeongamilgpjaibcdmldenfmdngp?authuser=2&hl=vi)

# 🚀 Grok Automation v2.0.4 - Grok.com AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Grok Automation** is a powerful productivity tool designed to supercharge your creative workflow on xAI's grok.com. Stop manually entering prompts one by one—automate the process and generate high-quality content at scale.

-----

## ✨ Key Features

* **🚀 Advanced Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle the submission and generation automatically.
* **🎬 Text-to-Video Automation:** Generate stunning videos from text descriptions. Supports batch processing with custom delays.
* **🖼️ Frame-to-Video:** Use a static image and add automatic motion effects to create dynamic videos.
* **🧩 Ingredients to Video:** Animate multiple UI components or character images into a single video.
* **🖼️ Text-to-Image Batching:** Create multiple images simultaneously with support for various aspect ratios (16:9, 9:16, 1:1, 2:3, 3:2).
* **🔄 Image-to-Image:** Transform and enhance existing images using AI with text prompts.
* **⚙️ Professional Control Suite:**
    * **Concurrent Prompts:** Process multiple prompts simultaneously to save time.
    * **Smart Delays:** Set custom intervals between prompts to manage rate limits effectively.
    * **Auto-Upscale & Download:** Automatically trigger upscaling and save the final results to your computer.
    * **Auto Change File Name:** Automatically rename downloaded files to keep them organized.
    * **Save to Folder:** Specify a custom subfolder for downloaded files per project.
* **🎭 Auto-add Character Images:** Automatically match and attach images to prompts based on character names in filenames.
* **📊 Real-time Queue Management:** Monitor your generation progress with a visual status bar and active prompt list in the Side Panel.
* **📂 Organized File Management:** Automatically sorts downloads into project-specific folders to keep your workspace clean.
* **🔧 Quick Fix:** One-click tool to recover from video or image generation errors.
* **💳 Plan Management:** Sign in to check your plan and track daily prompt usage.
* **🌐 Multi-language Support:** Available in English, Vietnamese, Chinese, Korean, Spanish, and Japanese.

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

3. **Configure Batch Settings**
   - In the **Control** tab, you can set:
     - **Concurrent Prompts:** How many prompts to run at the same time.
     - **Prompt Delay:** Wait time between each prompt submission.
     - **Save to Folder:** Subfolder name for downloaded files.
     - **Auto Change File Name:** Toggle automatic file renaming.

4. **Select a Mode**
   - Choose from the available generation modes: **Text to Video**, **Frame to Video**, **Ingredients to Video**, **Text to Image**, or **Image to Image**.

---

### 1. Text-to-Video Mode

1. Select **Text to Video** mode.
2. Enter prompts into the input box (separate each prompt with a **blank line**).
3. Alternatively, click the **Upload** icon to import a list of prompts from a `.txt` file.
4. Click **Run** to start the batch.

**Example Prompt:**
```
A futuristic cyberpunk city with neon lights reflecting in the rain.
The camera glides through the narrow alleys.

A peaceful Japanese garden with cherry blossoms falling into a pond.
A slow zoom into the koi fish swimming below.
```

---

### 2. Frame-to-Video Mode

1. Select **Frame to Video** mode.
2. Click to upload or drag & drop source images.
3. Enter prompts (separate with blank lines). Each image will be processed with each prompt.
4. In **Settings**, configure **Image Processing Option**:
   - *Use Start frame only* — one image per prompt.
   - *Use Start frame and End frame* — two images per prompt.
5. Click **Run**.

---

### 3. Ingredients to Video Mode

1. Select **Ingredients to Video** mode.
2. Upload the component or character images you want to animate.
3. Enter prompts (separate with blank lines).
4. Optionally enable **Auto-add character images** to automatically attach images whose filenames match character names mentioned in your prompts.
5. In **Settings**, set **Max Input Images per Prompt** (1–10) to control how many images are used per prompt.
6. Click **Run**.

---

### 4. Text-to-Image Mode

1. Select **Text to Image** mode.
2. Enter detailed descriptions for your images.
3. Configure the desired **Aspect Ratio** and **Image Model** in the Settings tab.
4. Click **Run**.

---

### 5. Image-to-Image Mode

1. Select **Image to Image** mode.
2. Upload the source images you want to transform.
3. Enter prompts (separate with blank lines).
4. Optionally enable **Auto-add character images** to automatically attach images based on filename matching.
5. In **Settings**, set **Max Input Images per Prompt** (1–10).
6. Click **Run**.

---

## ⚙️ Settings Configuration

Access the **Setting** tab to customize your experience:

| Setting | Description |
| :--- | :--- |
| **Default Mode** | Set which mode opens by default. |
| **Default Aspect Ratio** | Choose from 16:9, 9:16, 1:1, 2:3, or 3:2. |
| **Outputs per Prompt (Video)** | Set how many videos (1–4) to generate per prompt. |
| **Outputs per Prompt (Image)** | Set how many images (1–50) to generate per prompt. |
| **Concurrent Prompts** | Number of prompts to process simultaneously (1–6). |
| **Random Delay** | Random wait time before handling the next prompt. |
| **Video Model** | Select the generation model (e.g., Grok 3.1 Fast/Quality, Grok 2). |
| **Image Model** | Select the AI model for text-to-image generation. |
| **Default Video Option** | Default duration: 6s, 10s (Super Grok), 6s extend, or 10s extend (Super Grok). |
| **Default Image Mode Option** | Default input mode for image prompts: New Image or Edit Image. |
| **Image Processing Option** | For Frame-to-Video: start frame only, or start + end frame. |
| **Max Input Images per Prompt** | For Ingredients to Video / Image to Image: 1–10 images. |
| **Max Retries on Failure** | How many times to retry on failure (1–20). |
| **Auto Download Quality (Video)** | No Download, 480p, 480p (Upscale), or 720p (Super Grok). |
| **Auto Download Quality (Image)** | No Download or 1k. |
| **Language** | Switch between English, Tiếng Việt, 中文, 한국어, Español, 日本語. |

---

## 💡 Tips & Best Practices

1. **Wait Times:** If you encounter rate limits, increase the **Random Delay** in Settings.
2. **Concurrent Runs:** Start with 1 concurrent prompt and increase slowly to see what your account supports.
3. **Prompting:** Be specific! Detailed prompts lead to better AI generations. Separate multiple prompts with a clear blank line.
4. **File Organization:** Use the **Save to Folder** field to keep project downloads in named subfolders.
5. **Character Images:** Name your image files after characters (e.g., `hero.png`, `villain.jpg`) and enable **Auto-add character images** to have them matched automatically.
6. **Video Duration:** Use *6s extend* or *10s extend* options to chain prompts into a single long video. The last prompt always uses a non-extend duration.
7. **Quick Fix:** If a generation gets stuck or errors, use the **Fix Error** button in the Control tab.

---

## 🔧 Troubleshooting

| Issue | Solution |
| :--- | :--- |
| **Extension not active** | Ensure you are on [grok.com/imagine](https://grok.com/imagine). Refresh the page if needed. |
| **Generation Errors** | Grok might be busy. The extension will automatically retry based on your **Max Retries** setting. Use **Fix Error** to manually recover. |
| **Downloads not working** | Ensure "Ask where to save each file before downloading" is **OFF** in Chrome Settings. |
| **Login Required** | Make sure you are logged into your Grok.com account. |
| **Not enough images** | In Frame-to-Video mode, ensure you have uploaded enough images for the number of prompts. |

---

## 🔒 Privacy & Data

* **Local Processing:** All automation logic runs locally in your browser.
* **No Data Collection:** We do not store or collect your prompts, images, or account data.
* **Secure Storage:** Settings are saved only in your browser's local storage and synced across tabs.

---

## 📞 Support

- **Author:** Trường Nguyễn
- **Website:** [kylenguyen.me](https://kylenguyen.me)
- **Discord:** Join our community for support and updates.
- **Feedback:** Use the "Report a bug" link in the extension.

---

## 📦 Version

Current version: **2.0.4**

---

## 📜 License

Copyright © 2026 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary. Unauthorized copying or distribution is prohibited.

---

**Made with ❤️ by Trường Nguyễn**
