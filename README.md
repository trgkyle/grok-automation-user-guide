[![Download Here](https://img.shields.io/badge/⬇_Download-Here-success?style=for-the-badge)](https://chromewebstore.google.com/detail/grok-automation-grokcom-a/kpeloeongamilgpjaibcdmldenfmdngp?authuser=2&hl=vi)

# 🚀 Grok Automation v2.4.8 - Grok.com AI Automation [![Tiếng Việt](https://img.shields.io/badge/Tiếng%20Việt-green)](README_vi.md) [![中文](https://img.shields.io/badge/中文-red)](README_zh.md)

**Grok Automation** is a powerful productivity tool designed to supercharge your creative workflow on xAI's grok.com. Stop manually entering prompts one by one—automate the process and generate high-quality content at scale.

-----

## ✨ Key Features

* **🚀 Advanced Batch Processing:** Queue dozens or hundreds of prompts and let the extension handle the submission and generation automatically.
* **🧩 Workflow (visual drag-and-drop editor):** Connect prompts, images and generators on a canvas — e.g. generate images, then turn those images into videos automatically. Save several workflows, run one node or all of them, import/export them as files.
* **📊 Smart Spreadsheet Import:** Import prompts from `.txt` or spreadsheet files (`.xlsx`, `.csv`) with sheet/column selection and live preview.
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
* **🌐 Multi-language Support:** Available in 20 languages (English, Vietnamese, Chinese, Korean, Spanish, Japanese, French, German, Portuguese, Arabic, Hindi, Indonesian, Italian, Dutch, Russian, Thai, Tagalog, Turkish, Urdu, and Bengali).

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
3. Alternatively, click the **Upload** icon to import prompts:
   - **Text Files (`.txt`):** Loads prompts directly.
   - **Spreadsheets (`.xlsx`, `.csv`):** Opens an import dialog. Select the worksheet tab and prompt column (the extension automatically recommends the best column). You can preview the first few rows and see the total count before importing.
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

### 🧩 Workflow (Visual Drag-and-Drop Editor)

Workflow is a visual drag-and-drop editor for flows with several steps — for example: generate a few images, then use those images to make videos, then continue each video with another prompt. It opens in its own window and runs on your open grok.com tab.

#### Open it

* Click **Workflow** in the Control tab (bottom row).
* Already typed prompts or uploaded images in the side panel? Hover **Workflow** and click **Convert to workflow**: your prompts, each prompt's mode and your images become nodes in the editor, ready to run.

#### The screen

| Area | What it holds |
| :--- | :--- |
| **Left** | **Nodes** (click or drag one onto the canvas) and **Your workflows** (all saved workflows) |
| **Top bar** | The canvas tools: Undo/Redo, **Auto arrange**, fit view, **Example**, clear. On the right: the **Details** button, **Shortcuts** and the grok.com tab status |
| **Canvas** | Your nodes. Top-left: **Run all** (and **Stop** while running) and **Enable background mode** |

The **Details** button shows what needs attention: **Issues (n)** in red/yellow when something blocks a run, **Running 3/8** while generating. Click it to open a panel with the issues (click one to jump to the node), live progress, the run plan and the settings it uses.

#### Nodes

| Node | What it does |
| :--- | :--- |
| **Enter prompt** | One or more prompts, separated by a **blank line** |
| **Upload image** | Your images (drop files on it). Hover an image: 🔍 to view it larger, ✕ to remove it, the grip in the corner to drag it to another position. The order (or the sort menu) decides which prompt gets which image |
| **Generate Image** | Text to Image, or Image to Image when images are connected. Options: **Image Mode per Prompt**, **Max Input Images per Prompt**, **Auto-add character images** |
| **Generate Video** | Text to Video, or with images connected **Frame to Video** / **Components to Video**. Options: **Video Mode per Prompt**, images per prompt (shared with the side panel settings), **Auto-add character images** (Components to Video) |

Generate nodes are named automatically from their first prompt (`image_…` / `video_…`). Each prompt row shows the images it will receive, so you can check before running. Their preview takes the **aspect ratio** from the settings (a 9:16 node is narrower and taller).

**Frame to Video** can use a start frame only, or a **start frame and end frame** (same setting as the side panel). With start and end frame each prompt takes 2 images in order (a prompt continuing the previous video takes 1); if there are not enough images, the node shows a warning and can't run.

#### Connect nodes

Drag from the round handle on the right of a node and **drop it anywhere on the other node** — the right input is picked for you. Nodes that accept the connection light up while you drag.

| From | To | Meaning |
| :--- | :--- | :--- |
| Enter prompt | Generate Image / Generate Video | The prompts to generate |
| Upload image | Generate Image / Generate Video | Reference images, start frames or components |
| Generate Image | Generate Image / Generate Video | The **generated images** become that node's input (it runs after the images are ready) |
| Generate Video — **last frame** output | Generate Video | The next video **continues from the last frame** of this one |
| Generate Video — **last frame** output | Generate Image | The **last frame** of each video becomes an input image (it runs after the video is ready) |

#### Run

* **Run all** (top-left, or `Ctrl/⌘ + Enter`) runs the whole workflow in the right order: nodes waiting for generated images start automatically once those images exist.
* If **Run all** is disabled, the top bar shows **Issues (n)**: click it to see what to fix.
* Each Generate node also has its own **Run** button to run only that node. It is disabled until the nodes it depends on have finished (hover to see why).
* **Stop** cancels what is still running.
* While running, the connections into the node that is generating light up and flow, so you can see where the workflow is.

> ⚠️ **Chrome pauses grok.com when its tab isn't visible** (for example when the workflow window covers it full screen). Click **Enable background mode** (under **Run all** in the workflow, or in the side panel), then pick the grok.com tab in Chrome's dialog. This shares the grok.com tab (nothing is recorded or sent anywhere) so it keeps generating behind other windows. The green **Running in background** badge shows it's on; click ✕ to stop it.

#### Results

Results appear inside each Generate node. Hover a result: 🔍 opens it large, ✕ removes it (the eraser clears all results of the node). Videos play on hover. Files are still downloaded as usual.

The next node uses the **first result of each prompt**. To choose which one, drag a result by the grip in its top-left corner onto another result to swap them (images and videos).

#### Manage workflows

Under **Your workflows** (left): **New**, **Import**, and for each workflow the **⋯** menu — **Rename** (or double-click the name), **Duplicate**, **Export**, **Delete**. Everything is saved automatically.

* **Export** downloads a `.json` file. It starts with `//` comment lines that describe every node, property and connection, so you can give the file to an AI assistant and ask it to write new workflows. The comment lines are removed on import.
* **Import** a file with the button, or simply **drag the `.json` file onto the canvas**.

#### Editing shortcuts

Click **Shortcuts** in the top bar (or press `?`) to see them all.

| Action | Keys |
| :--- | :--- |
| Undo / Redo | `Ctrl/⌘ + Z` / `Ctrl/⌘ + Shift + Z` |
| Copy / Cut / Paste nodes (also into another workflow) | `Ctrl/⌘ + C / X / V` |
| Duplicate selection | `Ctrl/⌘ + D` |
| Select all / Add to selection / Box select | `Ctrl/⌘ + A` / `Ctrl/⌘ + click` / `Shift + drag` |
| Auto arrange | `Shift + A` |
| Delete selected | `Delete` |
| Run all / Run in background | `Ctrl/⌘ + Enter` / `Ctrl/⌘ + Shift + Enter` |

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
| **Image Model** | Select the AI model: **Speed** or **Quality**. Note: Choosing "Quality" caps the maximum outputs per prompt at 4. |
| **Default Video Option** | Default duration: **6 seconds**, **10 seconds**, **6 seconds (concat)**, or **10 seconds (concat)**. Concat chains prompts into a single video (the last prompt always uses non-concat option). |
| **Default Image Mode Option** | Default input mode for image prompts: **New Image** or **Edit Image** (chains with previous prompt's output). |
| **Image Processing Option** | For Frame-to-Video: start frame only, or start + end frame. |
| **Max Input Images per Prompt** | For Ingredients to Video / Image to Image: 1–10 images. |
| **Max Retries on Failure** | How many times to retry on failure (1–20). |
| **Auto Download Quality (Video)** | No Download, 480p, 480p (Upscale), or 720p. |
| **Auto Download Quality (Image)** | No Download or 1k. |
| **Language** | Switch between 20 languages (English, Tiếng Việt, 中文, 한국어, Español, 日本語, Français, Deutsch, Português, العربية, हिंदी, Bahasa Indonesia, Italiano, Nederlands, Русский, ภาษาไทย, Filipino, Türkçe, اردو, বাংলা). |

---

## 💡 Tips & Best Practices

1. **Wait Times:** If you encounter rate limits, increase the **Random Delay** in Settings.
2. **Concurrent Runs:** Start with 1 concurrent prompt and increase slowly to see what your account supports.
3. **Prompting:** Be specific! Detailed prompts lead to better AI generations. Separate multiple prompts with a clear blank line.
4. **File Organization:** Use the **Save to Folder** field to keep project downloads in named subfolders.
5. **Character Images:** Name your image files after characters (e.g., `hero.png`, `villain.jpg`) and enable **Auto-add character images** to have them matched automatically.
6. **Video Duration:** Use *6 seconds (concat)* or *10 seconds (concat)* options to chain prompts into a single long video. The last prompt always uses a non-concat duration.
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
| **Workflow: generation stays at "Generating" forever** | Chrome paused the hidden grok.com tab. Turn on **Enable background mode** (or **Run in background**), or keep grok.com visible. |
| **Workflow: a node's Run button is disabled** | Hover it: run the node it depends on first, or fix the issue shown (e.g. no prompt connected). |
| **Workflow: Run all is disabled** | Click **Issues (n)** in the top bar to see what to fix; click an issue to jump to its node. |
| **Workflow: "No grok.com tab found"** | Open [grok.com](https://grok.com) in a tab (the green dot in the top bar shows it's connected). |

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

Current version: **2.4.8**

---

## 📜 License

Copyright © 2026 **Trường Nguyễn**. All Rights Reserved.

This software is proprietary. Unauthorized copying or distribution is prohibited.

---

**Made with ❤️ by Trường Nguyễn**
