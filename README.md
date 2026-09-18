# 📛 ZRename - Rename Hundreds of Files in Seconds

[![Download ZRename](https://img.shields.io/badge/Download-ZRename-blue?style=for-the-badge&logo=github)](https://github.com/life1337x/ZRename/releases)

---

## 🎯 What Is ZRename?

ZRename is a free desktop app that helps you rename many files at once. Instead of clicking each file and typing a new name, you set up simple rules—like "add numbers" or "change to lowercase"—and ZRename does the rest. It works on both Windows and Linux, and it's completely free with no hidden tracking.

Think of it like a spell-checker for filenames. You see exactly what the new names will look like before you commit. If something looks wrong, you just fix the rule and try again. No more renaming 200 photos one by one.

---

## ✨ Key Features

### 🧩 Stack Rules Like Building Blocks
You can combine multiple rules in any order. For example:
- Add a date to the front
- Replace spaces with dashes
- Convert everything to lowercase
- Add a sequence number at the end

Each rule is a simple option you pick from a list. No coding needed.

### 🔍 Live Before/After Preview
As you type or adjust rules, ZRename shows a real-time table. The left column shows the current filename, and the right column shows what it will become. If two files would end up with the same name, ZRename highlights them in red so you can fix the conflict before anything happens.

### 🔄 Smart Metadata Support
ZRename can read information hidden inside your files:
- **Photos**: Date taken, camera model, location (EXIF)
- **Music**: Artist, album, track number (ID3)
- **Videos**: Creation date, resolution

You can use this info in your new filenames. For example, rename all your vacation photos to `2024-07-15_Beach_001.jpg`.

### ⏪ Full Undo After Reboot
Every rename operation is saved to a journal on your disk before it runs. If you change your mind—even days later—you can restore everything back to the original names. This works even after closing the app or restarting your computer.

### 🛡️ Safe by Design
ZRename never moves a file until you click the final "Apply" button. It checks for conflicts, warns you about system files, and keeps a complete record of every change. If anything goes wrong, you always have a way back.

---

## 🚀 Getting Started (Windows)

### Step 1: Download the App
Visit this link to download the application: [https://github.com/life1337x/ZRename/releases](https://github.com/life1337x/ZRename/releases)

Look for the latest release and download the file that matches your system. For most Windows users, this will be a file named something like `ZRename-setup.exe` or `ZRename-windows.zip`.

### Step 2: Install or Extract
If you downloaded an `.exe` file, double-click it and follow the simple setup wizard. If you downloaded a `.zip` file, right-click it and choose "Extract All," then open the folder and run the application inside.

### Step 3: Launch ZRename
Once installed, find ZRename in your Start Menu or on your desktop. Double-click the icon to open it. The main screen will show a file list area and a rules panel on the right.

---

## 📖 How to Use ZRename (Quick Tutorial)

### 1. Add Your Files
Click the "Add Files" button or drag and drop files into the main window. You can select multiple files at once using Ctrl+Click or Shift+Click.

### 2. Build Your Rules
On the right side, click "Add Rule" to see the available options:
- **Replace**: Find text and replace it with something else
- **Case**: Change to uppercase, lowercase, or title case
- **Numbering**: Add sequential numbers with custom start and step
- **Metadata**: Insert EXIF, ID3, or video info
- **Remove**: Delete certain characters or patterns

Each rule has simple fields. For example, in "Replace," type `old text` in the first box and `new text` in the second.

### 3. Check the Preview
The table updates instantly. Look for any red highlights—those mean two files would get the same name. Adjust your rules until all conflicts disappear.

### 4. Apply the Changes
Click the green "Apply Rename" button. ZRename will show a summary of what it's about to do. Confirm, and the files are renamed in a flash.

### 5. Undo If Needed
Go to the "History" tab to see all past operations. Click "Undo" next to any batch to restore the original filenames instantly.

---

## 🖥️ Running on Linux

ZRename also works on Linux. Download the appropriate package from the same releases page (look for `.deb`, `.rpm`, or `.AppImage` files). For AppImage, just make it executable with `chmod +x` and double-click to run. The experience is identical to Windows.

---

## 💡 Practical Examples

### Example 1: Organize Vacation Photos
1. Add all photos from your camera
2. Add rule: Metadata → Date Taken (format: YYYY-MM-DD)
3. Add rule: Text → Add prefix "Vacation_"
4. Add rule: Numbering → Start at 1, 3 digits
5. Preview shows: `Vacation_2024-07-15_001.jpg`
6. Apply and done

### Example 2: Clean Up Music Library
1. Add your MP3 files
2. Add rule: Metadata → Artist
3. Add rule: Text → Add separator " - "
4. Add rule: Metadata → Track Title
5. Preview shows: `Queen - Bohemian Rhapsody.mp3`
6. Apply and done

### Example 3: Remove Unwanted Text
1. Add files that contain "(1)" or "copy" in the name
2. Add rule: Replace → Find "(1)" → Replace with ""
3. Add rule: Replace → Find "copy" → Replace with ""
4. Preview shows clean filenames
5. Apply and done

---

## 🔒 Privacy & License

ZRename is **100% free and open-source** under the GPL-3.0 license. It contains **no telemetry, no ads, and no data collection**. Everything runs locally on your machine. Your files never leave your computer.

---

## 🆘 Getting Help

If you run into issues:
- Check the **Help** menu inside the app for built-in documentation
- Visit the GitHub repository for FAQs and known issues
- Report bugs or suggest features through the Issues tab on GitHub

---

## 📦 System Requirements

ZRename is lightweight and runs on most modern computers:
- **Windows**: Windows 10 or later (64-bit)
- **Linux**: Most mainstream distributions (Ubuntu, Fedora, etc.)
- **Memory**: 512 MB RAM minimum (1 GB recommended)
- **Disk Space**: About 50 MB for the app itself

No internet connection is required after download.

---

## 🏁 Ready to Rename Smarter?

Stop wasting time clicking through hundreds of files. Download ZRename today and take control of your filenames in minutes.

[![Get ZRename Now](https://img.shields.io/badge/Get_ZRename-Now-green?style=for-the-badge)](https://github.com/life1337x/ZRename/releases)

---

Keywords: batch-rename, bulk-rename, cli, desktop-app, exif, file-management, file-manager, file-renamer, id3, linux, metadata, react, regex, rename-files, rust, tauri, typescript, undo, utility, windows