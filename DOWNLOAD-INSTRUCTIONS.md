# How to Get the Course Files

You have two options to download the course materials. Choose whichever is easier for you.

---

## Option 1: Download ZIP File (Easiest)

**Best for:** Beginners or anyone who wants the simplest approach

### Steps:

1. **Download the ZIP file**
   - [Download claude-code-course.zip](#) _(add your download link here)_
   - The file will download to your Downloads folder

2. **Extract the ZIP file**
   - **Windows:** Right-click → "Extract All" → Choose a location (like Desktop or Documents)
   - **Mac:** Double-click the ZIP file (it extracts automatically)

3. **Remember where you extracted it**
   - You'll need to open the `workspace` folder in VS Code or Cursor later

4. **You're ready!**
   - Continue to the [Getting Started](#getting-started) section below

---

## Option 2: Clone from GitHub (For Git Users)

**Best for:** Developers or anyone comfortable with Git

### Steps:

1. **Open Terminal**
   - **Mac:** Press `Cmd + Space`, type "Terminal", press Enter
   - **Windows:** Press `Win + R`, type "cmd", press Enter

2. **Navigate to where you want the course**
   ```bash
   cd ~/Desktop
   # or wherever you want to save the course
   ```

3. **Clone the repository**
   ```bash
   git clone https://github.com/cazo-ai/claude-code-business-course.git
   cd claude-code-business-course
   ```

4. **You're ready!**
   - The course files are now in the `claude-code-course` folder

---

## Getting Started

Once you have the course files (via ZIP or Git), follow these steps:

### 1. Install Prerequisites

Before opening the course, make sure you have:
- ✅ **Cursor** (or VS Code) - [Download from cursor.sh](https://cursor.sh)
- ✅ **Node.js** - [Download from nodejs.org](https://nodejs.org) (LTS version)
- ✅ **Claude Code CLI** - Install after Node.js with:
  ```bash
  npm install -g @anthropic-ai/claude-code
  ```

### 2. Open the Workspace

1. **Launch Cursor** (or VS Code)
2. Click **File → Open Folder**
3. Navigate to where you downloaded/cloned the course
4. **Select the `workspace` folder** (not the main folder!)
5. Click "Open"

You should see these folders in the left sidebar:
- `company-context/`
- `inherited-chaos/`
- `.claude/`
- And more...

### 3. Open the Terminal

In Cursor, open the integrated terminal:
- **Mac:** Press `Cmd + \``
- **Windows:** Press `Ctrl + \``
- **Or:** Menu → Terminal → New Terminal

### 4. Launch Claude Code

In the terminal, type:
```bash
claude
```

Press Enter. The first time you run this, it will ask you to authenticate with Anthropic.

### 5. Verify Your Setup

Once Claude Code starts, type:
```
start-module-0
```

This will verify everything is working correctly.

### 6. Begin Learning!

After setup is verified, start Module 1:
```
start-module-1
```

---

## Folder Structure Explained

After downloading, you'll have this structure:

```
📦 claude-code-business-course/          (or whatever you named it)
│
├── 📄 README.md               ← Start here
├── 📄 DOWNLOAD-INSTRUCTIONS.md ← This file
│
├── 📁 workspace/              ← OPEN THIS FOLDER IN CURSOR
│   ├── company-context/       (scenario files)
│   ├── inherited-chaos/       (data to analyze)
│   ├── .claude/               (commands and agents)
│   └── README.md              (workspace guide)
│
├── 📁 lessons/                (reference - read if stuck)
│   ├── module-0-setup-installation.md
│   ├── module-1-getting-started.md
│   └── ...
│
└── 📁 exercises/              (practice problems)
    ├── module-1-exercises.md
    └── ...
```

**Important:** Always open the **workspace/** folder in Cursor, not the main course folder!

---

## Troubleshooting

### "npm: command not found"
→ You need to install Node.js first: [nodejs.org](https://nodejs.org)

### "Claude Code won't start"
→ Make sure you installed it: `npm install -g @anthropic-ai/claude-code`

### "Can't find the workspace folder"
→ Look inside wherever you extracted the ZIP or cloned the repo. The workspace folder is inside there.

### "Permission denied" (Mac/Linux)
→ Try: `sudo npm install -g @anthropic-ai/claude-code`

### "Claude can't see my files"
→ Make sure you opened the **workspace/** folder (not the parent folder) in Cursor

---

## Need Help?

- 📺 Watch the **Module 0 video** for a complete walkthrough
- 📖 Read the **README.md** in the main folder
- 💬 Ask Claude: Once it's running, just ask "What should I do next?"

---

## Ready to Begin?

1. Make sure you've opened the **workspace/** folder in Cursor
2. Open the terminal
3. Type `claude` and press Enter
4. Type `start-module-0` to verify setup
5. Start learning! 🚀
