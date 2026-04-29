You're right—that looks like a leftover from a localization pass! I've swapped the Chinese character **核心** for the English **Core** to keep everything consistent for your GitHub documentation.

Here is the corrected, ready-to-paste version:

---

# 🍼 R3-BBIT User & Developer Guide

Welcome to the production documentation for **R3-BBIT**. This guide explains the core modules, settings, and hidden features found in the main application file.

## Core Modules

### 1. Soothe Service (White Noise)
The `SootheService` is a foreground service that handles high-fidelity audio playback.
*   **Loop Mode:** Plays the selected `.raw` audio file indefinitely.
*   **Timer Mode:** Automatically stops playback after a user-defined interval.
*   **Fade Out:** When stopping or when the timer expires, the audio fades out over 2 seconds to prevent startling the baby.
*   **Controls:** Integrated into the Android Notification tray. You can **Stop** or **Restart** the session without opening the app.

### 2. Sleep Tracking & Smart Schedules
R3-BBIT uses a dynamic "Wake Window" (WW) logic to predict the next nap.
*   **Dynamic WW:** If a previous nap was short (<60m), the app automatically shortens the next Wake Window by 12.5% to 25% to prevent overtiredness.
*   **Tracking:** 
    *   **Single Tap:** Toggles current state (Sleep ↔ Wake).
    *   **Double Tap:** Logs a "Standalone Wake" to fix accidental logs.

### 3. Logs & Data Management
Logs are stored in a raw CSV format within `SharedPreferences`.
*   **Metrics:** Tracks total feed volume, diaper counts (Pee/Poo/Both), and total sleep minutes.
*   **Calculations:** Provides "Today" vs "All-Time" statistics.
*   **Editing:** Long-press any log entry to delete it. Tap a specific cell (Time/Date/Data) to edit that specific value.

---

## 🛠 Toolbox (Pro Features)
The Toolbox provides advanced data portability features for power users:

| Feature | Description |
| :--- | :--- |
| **Copy/Paste Sync** | Allows users to sync logs between two devices by copying the raw CSV string to the clipboard. |
| **CSV Export** | Generates a `.csv` file with headers (`date,time,type,data`) for use in Excel or Google Sheets. |
| **CSV Import** | Merges or overwrites existing logs from a local file. |
| **Trends** | Visualizes the last 7 days of data using custom-drawn bar charts for volume, feeds, diapers, and sleep. |

---

## ⚙️ Settings & Configuration

### Application Settings
*   **Hand Orientation:** Swaps the primary and utility grid items on the home screen to accommodate left-handed or right-handed thumb reach.
*   **Unit Toggle:** Switch between `ml` and `oz` globally.
*   **Soothe Limit:** Toggle between a "Safe" 120-minute limit or an "Extended" 999-minute limit.
*   **Data Wipe:** A safety-switched option to clear all local logs and preferences.

### Debug & Testing
*   **Hidden Unlock:** Tapping the version number (`v1.0.0`) 5 times in the Settings menu will force-unlock Pro features (used for internal beta testing only).
*   **Fireworks:** Tapping the screen 4 times in rapid succession triggers a celebratory particle animation.

---

## 🏗 Developer Integration Notes

### Requirements
*   **Permissions:** Requires `POST_NOTIFICATIONS` (Android 13+) and `FOREGROUND_SERVICE_MEDIA_PLAYBACK`.
*   **AdMob:** Currently configured with Test IDs. Replace `ADMOB_BANNER_ID` before final Play Store submission.
*   **Billing:** Uses Google Play Billing Library 5+. Ensure `r3bbit_pro` matches your product ID in the Play Console.

### Data Format
The internal logging system follows this CSV structure:
`MMM dd HH:mm, [Type], [Data]`
*   *Example:* `Apr 28 22:30, Feed, 120 ml`
*   *Example:* `Apr 28 23:15, Sleep, `
