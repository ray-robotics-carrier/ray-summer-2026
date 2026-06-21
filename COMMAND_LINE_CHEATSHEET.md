# 💻 Ray's Command Line Cheat Sheet

A quick reference for working in the Shell (the terminal). These commands work in Replit and on almost every coding setup, including the ones used at Google and SpaceX.

> Tip: type the command, then press **Enter** to run it.

---

## 📍 Where am I? What is here?

| Command | What it stands for | What it does |
|---|---|---|
| `pwd` | print working directory | Shows which folder you are in right now |
| `ls` | list | Shows the files and folders around you |

---

## 🚶 Moving around

| Command | What it does |
|---|---|
| `cd foldername` | Go into a folder (change directory) |
| `cd ..` | Go back up one folder |
| `cd` | Jump straight to your home folder |

The two dots (`..`) always mean "the folder above this one."

---

## 🛠️ Making folders and files

| Command | What it does |
|---|---|
| `mkdir foldername` | Make a new folder (make directory) |
| `touch filename` | Make a new empty file |

Example:
```bash
mkdir practice
touch notes.txt
```

---

## 👀 Looking inside a file

| Command | What it does |
|---|---|
| `cat filename` | Prints what is inside a file onto the screen |

Example:
```bash
cat main.py
```

---

## 🧹 Cleaning up and deleting (be careful)

| Command | What it does |
|---|---|
| `clear` | Wipes the screen clean (deletes nothing) |
| `rm filename` | Deletes a file. There is no undo. |
| `rm -r foldername` | Deletes a whole folder and everything inside it |

⚠️ **Warning:** `rm` has no trash can and no "are you sure?" Once it is gone, it is gone. Read the name twice before pressing Enter.

---

## 🐍 Running Python

| Command | What it does |
|---|---|
| `python3 main.py` | Runs your Python program |
| `python3 --version` | Shows your Python version |

---

## ⌨️ Two tricks the pros use constantly

- **Up arrow key:** brings back your last command so you do not retype it.
- **Tab key:** start typing a file or folder name, press Tab, and the computer finishes it for you. (This is called tab completion.)

---

## 🎯 Practice sequence

Run this to use almost everything at once. Think through what each line does as you go.

```bash
mkdir myfolder
cd myfolder
touch hello.txt
ls
pwd
cd ..
rm -r myfolder
```

If you understand every line above, you know the basics. That puts you ahead of a lot of people who have been coding for months.
