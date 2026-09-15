# 👁 Eye Care Reminder for Windows

A lightweight Windows desktop application that reminds you to follow the **20-20-20 eye care rule** while using your computer.

> **20-20-20 Rule:** Every 20 minutes, look at something approximately 20 feet (6 meters) away for at least 20 seconds.

The application runs quietly in the background and displays a small reminder notification near the Windows taskbar.

---
<img width="853" height="403" alt="Eye_care_Control" src="https://github.com/user-attachments/assets/1300bf66-68af-437b-944b-efa83b99d5ac" />
<img width="857" height="527" alt="Eye_care_Notify" src="https://github.com/user-attachments/assets/ccc53310-3085-4585-97c5-db07abe64e81" />
<img width="886" height="485" alt="Eye_care_BG_B_Notify" src="https://github.com/user-attachments/assets/3a91a798-f8ec-4d3e-b7e4-5475c8d8b63e" />




## ✨ Features

- 👁 Eye-care reminders every **20 minutes**
- ⏱ Reminder stays visible for **20 seconds**
- 🖥️ Works silently in the Windows background
- 🔔 Attractive animated notification
- 📍 Notification appears near the bottom-right corner of the screen
- 🎨 Two notification themes available:
  - **White / Light notification**
  - **Black / Dark notification**
- 🛑 Pause reminders whenever you want
- 🔔 Show a reminder immediately for testing
- 🚀 Automatically starts with Windows
- 🔒 Prevents multiple copies from running at the same time
- ❌ Close an individual reminder without stopping the application
- 📴 Completely disable the application and Windows startup from the system tray
- 💻 No Python installation required
- 📦 Portable Windows EXE — no installation wizard required

---

# 📥 Download

Go to the **Releases** section or download the EXE files directly from this repository.

Two versions are available:

### 🤍 EyeCare_BG_W.exe

**White / Light notification**

Choose this version if you prefer a bright, clean notification appearance.

### 🖤 EyeCare.exe

**Black / Dark notification**

Choose this version if you prefer a darker notification appearance.

> **You only need to run ONE version.**  
> Choose either the white or black version according to your preference.

---

# 🚀 How to Start

No installation is required.

### Step 1 — Download

Download one of the following:

```text
EyeCare_BG_W.exe
```

or

```text
EyeCare.exe
```

### Step 2 — Run

Simply **double-click the EXE file**.

The application will start in the background.

You may not see a normal application window. This is intentional.

### Step 3 — Check the Windows System Tray

Look near the Windows clock on the taskbar.

You should see the **Eye Care** icon.

The application is now running.

---

# 🔔 How the Reminder Works

Once running, Eye Care waits for **20 minutes**.

After 20 minutes, a notification appears near the bottom-right corner of your screen.

The reminder says:

> **Follow the 20-20-20 rule**  
> Look at something 20 feet away for 20 seconds.

The notification automatically disappears after approximately **20 seconds**.

You can also close it manually using the **Close** button.

### Important

Closing the notification **does not stop Eye Care**.

The application continues running in the background and will show the next reminder after another 20-minute interval.

---

# 🖱️ System Tray Menu

Right-click the **Eye Care icon** near the Windows clock to open the application menu.

You will see options similar to:

```text
Eye Care Reminder
────────────────────────
☑ Pause Reminders
🔔 Show Reminder Now
────────────────────────
❌ Exit & Disable Startup
```

---

## ⏸ Pause Reminders

Select:

**Pause Reminders**

This temporarily stops the eye-care reminders.

The application remains running in the background.

When you want to start receiving reminders again, right-click the Eye Care tray icon and select:

**Pause Reminders**

again.

The check mark will indicate that reminders are paused.

> Pausing is temporary. It does not permanently disable Windows startup.

---

# 🔔 Show Reminder Now

Select:

**Show Reminder Now**

to immediately display the eye-care notification.

This is useful if you want to:

- Test the notification
- Check which notification theme you are using
- Demonstrate the application
- Test the application after starting Windows

You do **not** need to wait 20 minutes to test the reminder.

---

# ❌ How to Completely Disable Eye Care

If you want to completely stop the application and prevent it from starting automatically with Windows:

### Step 1

Right-click the **Eye Care icon** near the Windows clock.

### Step 2

Select:

**Exit & Disable Startup**

The application will:

1. Close immediately.
2. Stop all reminders.
3. Remove itself from Windows Startup.
4. No longer start automatically when Windows starts.

---

# 🔄 How to Enable It Again

If you previously selected:

**Exit & Disable Startup**

and later want to use Eye Care again:

Simply **double-click the EXE file again**.

The application will start and automatically register itself to start with Windows.

You do not need to configure Windows Startup manually.

---

# 🖥️ Windows Startup Behavior

The application is designed to work as a background utility.

### First time you run it:

```text
Double-click EyeCare.exe
        ↓
Application starts
        ↓
Automatically registers with Windows Startup
        ↓
Runs in the background
```

### After restarting Windows:

```text
Windows starts
        ↓
Eye Care starts automatically
        ↓
Runs in the background
        ↓
Reminders every 20 minutes
```

### If you choose "Exit & Disable Startup":

```text
Exit & Disable Startup
        ↓
Application closes
        ↓
Windows Startup registration removed
        ↓
Eye Care will NOT start next time Windows starts
```

---

# 🎨 Which Version Should I Use?

Both versions provide the same functionality.

| Version | Appearance | Recommended For |
|---|---|---|
| `EyeCare_BG_W.exe` | 🤍 White / Light | Bright and clean interface |
| `EyeCare.exe` | 🖤 Black / Dark | Dark-mode preference |

There is **no functional difference** between the two versions.

Choose whichever notification style you prefer.

---

# 🔒 Privacy

Eye Care is designed as a simple local Windows utility.

It does not require an account or login to use the application.

The application is intended to provide local eye-care reminders while you work on your computer.

---

# 💻 System Requirements

- Windows 10 or later
- 64-bit Windows recommended
- No Python installation required
- No additional libraries need to be installed
- Internet connection is not required for normal reminder operation

---

# ⚠️ Windows Security Warning

Because this is a standalone executable and may not have a commercial code-signing certificate, Windows Defender or SmartScreen may occasionally display a warning when running the application.

If you downloaded the file from the official repository and trust the source, review the Windows warning and choose the appropriate option to run the application.

---

# 📌 Recommended Usage

For the best experience:

1. Start Eye Care when you begin working.
2. Leave it running in the background.
3. When the reminder appears, look away from the screen.
4. Focus on something approximately **20 feet away**.
5. Continue looking away for **20 seconds**.
6. Return to your work.
7. Repeat every 20 minutes.

The application is designed to make this habit automatic.

---

# 🩺 The 20-20-20 Rule

The **20-20-20 rule** is a simple reminder technique commonly used to encourage regular breaks from prolonged screen viewing:

**Every 20 minutes → Look 20 feet away → For 20 seconds**

Eye Care simply helps you remember to do it.

---

## 📷 Screenshots

Screenshots of the notification and instructions for disabling the application are included in this repository.

You can add them here if desired:

```text
screenshots/
├── white-notification.png
├── black-notification.png
└── disable-app.png
```

Then display them in GitHub using:

```markdown
![White Notification](screenshots/white-notification.png)

![Black Notification](screenshots/black-notification.png)

![Disable Application](screenshots/disable-app.png)
```

---

## 📦 Available Downloads

```text
EyeCare_BG_W.exe    → White / Light notification
EyeCare.exe         → Black / Dark notification
```

**Download → Double-click → Choose your preferred version → Keep it running in the background.**

---

## ❤️ Stay Healthy While Working

Long periods of uninterrupted screen use can be uncomfortable.

Let Eye Care remind you to look away regularly.

### 👁 20 Minutes
### 👀 20 Feet Away
### ⏱ 20 Seconds

**Take care of your eyes while you work.**
