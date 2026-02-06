# Auto-Clicker for macOS

A simple tool that automatically clicks your mouse for you. Perfect for repetitive clicking tasks!

## What You Need

- **Mac computer** (with macOS)
- **Terminal** (comes with your Mac)
- **Internet connection** (to download PowerShell)

## Installation (One-Time Setup)

### Step 1: Open Terminal
1. Press `Command + Space` to open Spotlight
2. Type "Terminal" and press Enter

### Step 2: Navigate to the Installer
1. In Terminal, type or copy this command:
```
cd /path/to/where/you/saved/99NIGHTS/macOS
```
2. Replace `/path/to/where/you/saved/` with the actual location of your folder

### Step 3: Run the Installer
1. Type this command:
```
bash install.sh
```
2. Press Enter
3. The installer will:
   - Check if Homebrew is installed (a package manager for Mac)
   - Install Homebrew if needed
   - Install PowerShell automatically
   - Set up the auto-clicker tool

### Step 4: Wait for Completion
- You'll see green text saying "Installation Complete!"
- This usually takes 2-5 minutes

## How to Use the Auto-Clicker

### After Installation, Run It Anytime:
1. Open Terminal (Command + Space, then type "Terminal")
2. Type:
```
auto-clicker
```
3. Press Enter

### When the Tool Starts:
1. **Answer Question 1:** "How many clicks?"
   - Type a number (like `100`) for that many clicks
   - Just press Enter for infinite clicks (won't stop until you stop it)

2. **Answer Question 2:** "Interval between clicks in seconds?"
   - Type how fast you want it to click: `0.1` is very fast, `1` is one click per second
   - Press Enter to use the default (0.1 seconds)

3. **Answer Question 3:** "Delay before starting?"
   - This is how many seconds to wait before it starts clicking
   - Press Enter to use the default (3 seconds)
   - **MOVE YOUR MOUSE where you want it to click during this countdown!**

4. **Watch It Click!**
   - You'll see "Click #1", "Click #2", etc. in Terminal
   - The mouse will automatically click at that spot

### To Stop It:
- Press `Control + C` on your keyboard to stop it anytime

## Example Usage

**Scenario:** You want 50 clicks, one click per second, starting in 5 seconds

```
How many clicks? (Press Enter for infinite)
50

Interval between clicks in seconds (default: 0.1)
1

Delay before starting in seconds (default: 3)
5

Starting in 5...
Starting in 4...
Starting in 3...
Starting in 2...
Starting in 1...

Clicking started!
Click #1 of 50
Click #2 of 50
...
```

## Common Questions

**Q: Will it click outside the application?**
A: Yes! It will click wherever your mouse cursor is positioned.

**Q: Can I use my computer while it's clicking?**
A: Yes, but be careful—it will click even if you move the mouse.

**Q: How do I uninstall it?**
A: The auto-clicker is installed in your home folder (hidden folder named `.autoclicker`). You can delete it, or just leave it there and ignore it.

**Q: It's not working!**
A: Make sure:
1. PowerShell was installed successfully
2. You're in the right folder when running the installer
3. Terminal output shows "Installation Complete!" in green
4. Try opening a new Terminal window before running `auto-clicker`

## Need Help?

If something isn't working:
1. Try running the installer again
2. Make sure you see "Installation Complete!" message
3. Open a new Terminal window and try running `auto-clicker` again
