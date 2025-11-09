# Terminal File Explorer (C++ + Ncurses)

This project is a **console-based File Explorer** built using **C++**, **Ncurses**, and the **C++17 `<filesystem>` library**.  
It allows users to **navigate directories, view file details, create, rename, delete, copy, cut, paste, search, and modify permissions** — all inside the **terminal interface** without relying on a graphical environment.

This makes the project especially useful for **Linux servers, remote SSH systems, and low-resource environments** where GUI file managers are not available.

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| **Directory Navigation** | Move through folders using arrow keys |
| **File Listing with Permissions** | Displays permissions, size, and type |
| **Create Files & Directories** | Quickly generate new files/folders |
| **Rename & Delete** | Modify or remove files and directories |
| **Copy / Cut / Paste** | Works for both files and folders |
| **Change Permissions** | Set UNIX-style permission codes (e.g., 755, 644) |
| **Search Function** | Find files by name recursively |
| **Ncurses UI** | Styled, interactive terminal interface |

---

## 🎮 Controls / Key Bindings

| Key | Action |
|-----|--------|
| ↑ / ↓ | Move Selection Cursor |
| ENTER | Open Directory |
| ← | Go to Parent Directory |
| `n` | Create New File |
| `m` | Create New Directory |
| `r` | Rename Selected Item |
| `d` | Delete Selected Item |
| `c` | Copy Selected Item |
| `x` | Cut Selected Item |
| `v` | Paste Item |
| `p` | Change File Permissions |
| `/` | Search File/Directory |
| `q` | Quit Program |

---

## 🛠️ Build & Run Instructions

### **MSYS2 (Windows)**
Install dependencies:
```bash
pacman -S mingw-w64-x86_64-gcc mingw-w64-x86_64-ncurses
