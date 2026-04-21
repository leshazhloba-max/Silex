# 🪨 Silex

Silex is a sleek and powerful file organizer and system cleaner for Windows.  
It combines an intelligent file sorter with a safe temporary file cleaner, wrapped in a modern, animated dark interface.

---

## ✨ Features

### 📁 Silentum – File Organizer
- **Sort by Category**: Automatically moves files into folders like Images, Documents, Archives, Videos, Music, Code, and Others.
- **Selective Deletion**: Choose exactly which files or folders to delete – safely using the Recycle Bin.
- **Drag & Drop**: Just drag any folder into the window to get started.
- **Live Progress**: Watch the operation with a smooth animated progress bar.

### 🧹 Silera – System Cleaner
- **Temporary Files**: Cleans Windows Temp and User Temp folders.
- **Browser Cache**: Removes cache from Chrome, Edge, and Firefox.
- **Granular Selection**: Pick only the locations you want to clean – nothing is deleted without your approval.
- **Safe by Design**: All deletions go through the Recycle Bin (requires `send2trash`).

### 🔐 User Accounts
- **Local Authentication**: Create a personal account with a password (stored securely with SHA-256 + salt).
- **Persistent Sessions**: Stay logged in until you explicitly log out.
- **Reset Account**: Easily log out and clear your session from the main menu.

### 🎨 Interface
- **Frameless Design**: Custom title bar with minimize/close buttons.
- **Animations**: Smooth fade-ins, button hover effects, and window transitions.
- **Dark Purple Theme**: A consistent, eye-friendly color palette inspired by modern UI trends.

---

## 📥 Installation

### Download the executable
Go to the [Releases](https://github.com/leshazhloba-max/silex/releases) page and download the latest `Silex.exe`.  
No installation required – just run the file.

### Run from source
```bash
git clone https://github.com/leshazhloba-max/silex.git
cd silex
python silex.py
