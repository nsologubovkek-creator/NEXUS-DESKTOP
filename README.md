# 🖥️ NEXUS — Daily Assistant Desktop

A Python overlay app that sticks to the right edge of your screen.

---

## 📦 INSTALLATION (Windows)

### Step 1 — Install Python
1. Go to **https://www.python.org/downloads/**
2. Download Python 3.11 or newer
3. ⚠️ **IMPORTANT**: Check "Add Python to PATH" during installation

### Step 2 — Launch NEXUS
Double-click **`LANCER_NEXUS.bat`**

That's it! NEXUS will launch and automatically add itself to Windows startup.

---

## 🚀 AUTO-START

On first launch, NEXUS automatically registers itself in the Windows registry to start with your computer.

To disable auto-start:
- Press `Win + R` → type `regedit`
- Navigate to: `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run`
- Delete the `NexusApp` key

---

## 🎯 FEATURES

| Icon | Feature |
|------|---------|
| 🕐 | **Clock** — Analog + digital real-time clock |
| 🌤 | **Weather** — Temperature, humidity, wind (via your location) |
| ✅ | **Tasks** — With priorities and progress bar |
| 🍅 | **Pomodoro** — 25min timer with animated ring |
| 🔢 | **Calculator** — Full featured, keyboard supported |
| 📝 | **Notes** — Auto-saved locally |
| 🔥 | **Habits** — 7-day weekly tracker |
| 💬 | **Quotes** — Daily motivation |

---

## 📁 DATA

All your data is saved in:
```
C:\Users\[YourName]\.nexus_data.json
```

---

## 🔧 USAGE

- **Click an icon** → opens the corresponding panel
- **Click the same icon again** → closes the panel
- **Mouse leaves the panel** → panel closes automatically
- **✕ at the bottom** → closes the app
- The overlay always stays on top of other windows

---

## 💻 COMPATIBILITY

- Windows 10/11 ✅
- macOS ✅ (auto-start via LaunchAgent)
- Linux ✅ (auto-start via .desktop autostart)

---

*NEXUS v3.0 — Python 3.8+ with tkinter*

IF NEED ANY HELP TEXT ME ON TIKTOK @kute_00!!!!!!!!!!!!!
