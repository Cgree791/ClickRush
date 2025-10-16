# 🚀 ClickRush

**ClickRush** is an all-in-one automation tool for Windows built in Python. It combines a high-speed autoclicker, text typer, and action recorder/player into a single, lightweight application. ClickRush is designed for precision, speed, and flexibility — perfect for automating repetitive tasks efficiently.

🔗 **Download ClickRush v4:** [ClickRush v4 Release](https://github.com/Cgree791/ClickRush/releases/tag/clickrushv4)

---

## 🔧 Features

### 🖱️ Autoclicker
- **Custom CPS (Clicks Per Second):** 1–10,000 CPS.
- **Mouse Button Selection:** Left or Right click.
- **Click Type:** Single or double click.
- **Batch Mode:** Click a batch of clicks, then wait a custom delay before the next batch.
- **Infinite or Loop Limit:** Choose how many clicks to perform.

### ⌨️ Typer
- **Text Automation:** Type custom text automatically.
- **Speed Control:** Set typing speed in WPM (Words Per Minute), or type instantly (infinity mode).
- **Auto Send:** Press Enter automatically after typing (optional).
- **Loop Typing:** Repeat typing a set number of times or infinitely.

### 🎥 Action Recorder & Playback
- **Record Keyboard & Mouse:** Capture clicks, key presses, and key releases.
- **Playback Recorded Actions:** Play back your recorded actions with accurate timing.
- **Loop Playback:** Repeat recordings a custom number of times or infinitely.
- **Auto Send During Playback:** Optional pressing of Enter after typing actions.

### ⚡ Hotkeys
Customize hotkeys for each function:

| Action                  | Default Hotkey |
|-------------------------|----------------|
| Start/Stop Clicker      | `/`            |
| Start/Stop Typer        | `\`            |
| Start/Stop Recording    | `-`            |
| Play Recording          | `+`            |
| Clicker + Typer Combo   | `` ` ``        |

### 🖥️ User Interface
- **Tkinter-based GUI:** Clean, minimal, and responsive.
- **Panels:** Separate controls for clicking, typing, recording, and settings.
- **Visual Feedback:** Buttons change color to indicate running state.

### ⚙️ Settings
- Customize hotkeys for all actions.
- Configure loops and infinite toggles for clicker, typer, and recordings.
- Set typing delays between actions.
- Enable/disable auto send after typing.

---

## 🎯 How to Use

### 1. Autoclicker
1. Enter the desired **CPS** in the “Click Speed” box.
2. Choose **Mouse Button** and **Click Type**.
3. Set **Batch Delay** (optional).
4. Click **Start** to begin clicking or press your configured hotkey.
5. Click **Stop** or press the hotkey again to halt clicking.

### 2. Typer
1. Enter the text you want to type in the **Text to Type** box.
2. Set your **Typing Speed** using the slider.
3. Enable **Auto Send** if you want Enter to be pressed automatically.
4. Click **Start** or press the hotkey.
5. Click **Stop** or press the hotkey to stop typing.

### 3. Recording & Playback
1. Press the **Record** button or hotkey to start recording your actions.
2. Perform your keyboard/mouse actions.
3. Press **Record** again to stop.
4. Press **Play** or the hotkey to replay recorded actions.
5. Loops and auto-send can be configured in the settings.

### 4. Clicker + Typer Combo
- Press the **Clicker + Typer** hotkey to run both simultaneously.
- Press again to stop both actions.

### 5. Settings
- Open the **Settings** window to configure:
  - Hotkeys
  - Loops and infinite toggles
  - Typing delays
  - Auto Send

---

## ⚠️ Tips & Warnings
- High CPS (>100) may cause system lag or freezing depending on your computer.
- Hotkeys do not support certain special keys (Shift, Enter, Tab, Escape, Backspace) for starting actions.
- Always test recording/playback on a safe environment before using in critical applications.

---

## 🛠️ Requirements
- **Windows OS**
- **Python 3.9+**
- **Libraries:** `tkinter`, `pynput`, `pyautogui`

Install dependencies:

```bash
pip install pynput pyautogui
