# R3BBIT User Guide

Complete guide to using R3BBIT baby care tracker.

## Table of Contents
- [Getting Started](#getting-started)
- [Feed Tracking](#feed-tracking)
- [Sleep Tracking](#sleep-tracking)
- [Diaper Tracking](#diaper-tracking)
- [Soothe Feature](#soothe-feature)
- [Logs and History](#logs-and-history)
- [Settings](#settings)
- [Pro Features](#pro-features)
- [Tips and Best Practices](#tips-and-best-practices)
- [Troubleshooting](#troubleshooting)

---

## Getting Started

### First Launch
When you first open R3BBIT, you'll see the main menu with six colorful buttons:
- **FEED** - Track feedings
- **SLEEP** - Monitor sleep/wake
- **DIAPER** - Log changes
- **SOOTHE** - Play calming sounds
- **LOGS** - View history
- **SETTINGS** - Customize app

### Navigation
- Tap any button to access that feature
- Use **BACK** button to return to main menu
- Tap **DONE** or **SAVE** to confirm entries

### Interface Design
R3BBIT uses large, easy-to-tap buttons designed for one-handed operation. The color-coded interface makes it easy to find what you need quickly, even in the middle of the night.

---

## Feed Tracking

### Bottle Feeding

**How to log a bottle feeding:**

1. Tap **FEED** on main menu
2. Select **BOTTLE**
3. Enter amount using the number pad
4. Tap **DONE**

**Quick Tips:**
- Your last 5 feeding amounts appear as quick-select buttons
- Default unit is ml (change to oz in Settings)
- Tap any quick-select button for instant logging

**Example:**
```
Feed → Bottle → Enter "120" → Done
Logged: "Apr 29 14:30, Feed, 120ml"
```

### Breastfeeding

**How to log breastfeeding:**

1. Tap **FEED**
2. Select **LEFT**, **RIGHT**, or **BOTH**
3. Entry logs immediately (no additional confirmation needed)

**When to use each option:**
- **LEFT** - Nursed from left breast only
- **RIGHT** - Nursed from right breast only  
- **BOTH** - Nursed from both breasts in one session

**Example:**
```
Feed → Left
Logged: "Apr 29 15:45, Feed, Left"
```

### Understanding Your Data
Review feeding patterns in the Logs to identify:
- Typical feeding amounts
- Time between feedings
- Preferred feeding times
- Daily feeding frequency

---

## Sleep Tracking

### How Sleep Tracking Works

R3BBIT uses an intelligent tap system to make sleep logging effortless:

| Current State | Action | Result |
|--------------|---------|---------|
| Awake | Single tap | Logs "Sleep" event |
| Sleeping | Single tap | Logs "Wake" event with duration |
| Sleeping | Long press | Logs "Wake" with duration + starts new "Sleep" |

### Visual Indicator
The **SLEEP** button changes appearance based on state:
- Normal color = Baby is awake
- Highlighted/different color = Baby is sleeping

### Duration Calculation
When logging a Wake event, R3BBIT automatically calculates how long the baby slept:

**Example Timeline:**
```
10:00 AM - Tap SLEEP        → "Apr 29 10:00, Sleep"
11:30 AM - Tap SLEEP (wake) → "Apr 29 11:30, Wake, 90m"
```

The app tracks time between the last Sleep event and the current Wake to calculate duration.

### Quick Transition (Long Press)
For naps where baby wakes briefly then goes back to sleep:

**Instead of:**
1. Tap to Wake
2. Return to menu
3. Tap Sleep again

**Use:**
1. Long press SLEEP button
2. Logs Wake with duration AND starts new Sleep immediately

### Best Practices
- Log sleep immediately when putting baby down
- Check button color to verify current state
- Use long press for brief wake-ups during naps
- Review sleep patterns weekly to establish routines

---

## Diaper Tracking

### How to Log Diaper Changes

1. Tap **DIAPER** on main menu
2. Select the type:
   - **Pee** - Wet diaper only
   - **Poo** - Soiled diaper only
   - **Both** - Both wet and soiled
3. Entry logs immediately

### Why Track Diapers?
Monitoring diaper changes helps you:
- Ensure adequate hydration (wet diapers)
- Track digestion patterns (bowel movements)
- Identify potential health issues early
- Share accurate information with pediatrician

### Typical Patterns
- **Newborns:** 6-8 wet diapers per day
- **Bowel movements:** Vary widely by age and diet
- Track your baby's normal pattern to identify changes

**Example Log:**
```
Apr 29 08:15, Diaper, Pee
Apr 29 10:30, Diaper, Both
Apr 29 12:45, Diaper, Poo
```

---

## Soothe Feature

### Overview
Soothe plays calming sounds to help comfort your baby. The audio continues playing even when:
- You close the app
- You use other apps
- Your screen is locked

### Available Sounds

R3BBIT includes 3 scientifically-backed calming sounds:

#### Noise Types
- **White Noise** - Classic static sound, masks environmental noise
- **Brown Noise** - Deeper, richer tone, like distant thunder or waterfall
- **Pink Noise** - Balanced frequency, softer than white noise

### How to Use Soothe

**Step-by-step:**

1. Tap **SOOTHE** on main menu
2. Select your preferred sound from the list
3. Choose timer duration:
   - Quick select: 5, 10, 15, 20, 30, 45, 60, 90, 120 minutes
   - **LOOP** - Continuous playback until manually stopped
   - **Pro:** Custom timers up to 999 minutes
4. Tap **START**
5. Sound begins playing immediately

### Background Playback

Once Soothe is active:
- A notification appears showing time remaining
- You can close R3BBIT and sound continues
- Use other apps normally
- Lock your screen to save battery

### Notification Controls

The persistent notification shows:
- **Time remaining** (or "Loop mode")
- **STOP button** - Gradually fades out over 2 seconds
- **RESTART button** - Resets timer to original duration

**Example:**
```
Notification: "Soothe Active"
              "15:30 remaining"
              [STOP] [RESTART]
```

### Fade-Out Feature
When you stop Soothe or the timer expires, sound gradually fades out over 2 seconds. This prevents sudden silence from startling your baby awake.

### Timer Options Explained

**Short Timers (5-30 min):**
- Good for settling before sleep
- Calming during diaper changes
- Soothing during feeding

**Medium Timers (45-90 min):**
- Nap time support
- Extended calming periods
- Background during playtime

**Long Timers (120 min / 2 hours):**
- Full nap coverage
- Nighttime sleep support
- Extended soothing sessions

**Loop Mode:**
- All-night use
- Unpredictable nap lengths
- When you want continuous sound

**Pro Extended (999 min / 16+ hours):**
- Overnight without restart
- All-day background sound
- Extended sleep training

### Sound Selection Tips

**Most Effective Sounds:**
1. White, brown, and pink noise tend to work for most babies
2. Heartbeat can be particularly soothing for newborns
3. Ocean and rain offer rhythmic variation

**Experiment to Find What Works:**
- Try different sounds on different days
- Some babies prefer different sounds for naps vs. nighttime
- Volume matters - keep it moderate (about as loud as a shower)

**Safety Note:**
Keep volume at a reasonable level. Sound should be audible but not overwhelming. The American Academy of Pediatrics recommends keeping white noise at or below 50 decibels.

---

## Logs and History

### Viewing Your Logs

**Access logs:**
1. Tap **LOGS** on main menu
2. Scroll through complete history
3. Most recent entries appear first

**What you'll see:**
Each entry displays:
- Date and time (e.g., "Apr 29 14:30")
- Event type (Feed, Sleep, Wake, Diaper)
- Details (amount, duration, type)

**Example log view:**
```
Apr 29 16:45, Wake, 90m
Apr 29 15:15, Sleep
Apr 29 14:30, Feed, 120ml
Apr 29 12:15, Diaper, Both
Apr 29 10:00, Feed, Left
```

### Exporting Logs

R3BBIT provides three export options:

#### 1. EMAIL
- Opens your email app
- Logs attached as CSV file
- Add recipient and send

#### 2. COPY
- Copies all logs to clipboard
- Paste into any app (notes, spreadsheet, document)
- Useful for quick sharing

#### 3. SHARE
- Uses Android's share menu
- Send to any compatible app
- Options include: messaging, cloud storage, documents

**CSV Format:**
Exported data uses standard CSV format:
```csv
Date Time, Event Type, Details
Apr 29 14:30, Feed, 120ml
Apr 29 15:15, Sleep, 
Apr 29 16:45, Wake, 90m
```

This format opens easily in:
- Google Sheets
- Microsoft Excel
- Apple Numbers
- Any spreadsheet application

### Deleting Individual Entries

**To remove a mistake or incorrect entry:**

1. In the Logs screen, find the entry
2. **Long press** on the entry
3. Confirm deletion in the dialog
4. Entry is permanently removed

**Note:** This action cannot be undone. Export logs regularly as backup.

### Using Logs Effectively

**For Daily Tracking:**
- Quick glance to see last feeding time
- Check sleep duration patterns
- Monitor diaper change frequency

**For Doctor Visits:**
- Export week of logs before appointments
- Share feeding amounts and frequency
- Provide sleep pattern information
- Show diaper change regularity

**For Pattern Recognition:**
- Identify optimal feeding times
- Establish sleep schedules
- Recognize digestion patterns
- Track developmental changes

---

## Settings

Access settings via the **SETTINGS** button on main menu.

### Hand Preference

**Options:** RIGHT (default) or LEFT

**What it does:**
Adjusts button layouts for easier one-handed operation.

**When to use:**
- Set to **LEFT** if you typically hold baby in your right arm
- Set to **RIGHT** if you typically hold baby in your left arm
- Switch anytime based on your current need

**How to change:**
1. Tap **SETTINGS**
2. Tap **HAND: RIGHT** or **HAND: LEFT** button
3. Changes immediately

### Measurement Unit

**Options:** ml (milliliters) or oz (ounces)

**What it affects:**
- Bottle feeding input
- Bottle feeding display in logs
- Quick-select buttons

**Default:** ml

**How to change:**
1. Tap **SETTINGS**
2. Tap **UNIT: ml** or **UNIT: oz** button
3. All values update immediately

**Conversion:** 1 oz ≈ 30 ml

### Soothe Limit

**Free Version:** Maximum 120 minutes (2 hours)
**Pro Version:** Maximum 999 minutes (16+ hours)

**What it controls:**
Maximum timer length available in Soothe feature.

**Display:**
- Free: "SOOTHE LIMIT: 120m"
- Pro: "SOOTHE LIMIT: 999m"

### Wipe All Data

**⚠️ WARNING: This action is permanent and cannot be undone!**

**What it does:**
- Deletes all logged events (feeding, sleep, diaper)
- Resets all preferences to defaults
- Clears Pro status (if testing mode was used)

**How to use:**
1. Tap **SETTINGS**
2. Find "WIPE ALL DATA" section
3. Toggle the switch to ON
4. Confirm in the dialog
5. All data is permanently deleted

**When to use:**
- Starting fresh with a new baby
- Clearing test data
- Resetting app completely
- Before giving device to someone else

**Recommendation:** Export your logs before wiping if you want to keep any records.

### Additional Settings

#### Restore Purchase
If you purchased Pro and it's not showing (new device, reinstall, etc.):

1. Tap **SETTINGS**
2. Tap **RESTORE PURCHASE**
3. Wait for verification
4. Pro features activate if purchase found

#### Report Bug / Request Feature
Opens GitHub issues page where you can:
- Report problems or bugs
- Suggest new features
- View existing issues
- Track development progress

#### Privacy Policy
Opens the complete privacy policy at:
https://bagramlabs.github.io/R3BBIT

### Version Information
At the bottom of Settings screen, you'll see:
```
R3BBIT 1.0.0
```

**Hidden Feature:** Tap the version number 5 times quickly to unlock Pro features for testing purposes.

---

## Pro Features

### What's Included

Upgrade to **R3BBIT Pro** for:

✨ **Ad-Free Experience**
- No interruptions while caring for your baby
- Cleaner interface
- Faster app performance

⏱️ **Extended Soothe Timer**
- Free version: 120 minutes maximum
- Pro version: 999 minutes (16+ hours)
- Perfect for all-night use

💚 **Support Development**
- Help fund new features
- Support ongoing updates
- Keep R3BBIT improving

### How to Purchase

1. Tap **SETTINGS** on main menu
2. Tap **UPGRADE TO PRO**
3. Review purchase details
4. Complete purchase through Google Play
5. Pro features activate immediately

**Purchase Details:**
- One-time payment (not a subscription)
- Works on all your Android devices with same Google account
- Permanent unlock (no recurring fees)

### After Purchase

Your Settings will now show:
```
PRO: ACTIVE ✓
```

And:
```
SOOTHE LIMIT: 999m
```

Ads will be removed throughout the app.

### Restore Pro on New Device

If you purchased Pro and installed R3BBIT on a new device:

1. Ensure you're signed in with the same Google account
2. Open **SETTINGS**
3. Tap **RESTORE PURCHASE**
4. Wait for verification (may take a few minutes)
5. Pro features activate

---

## Tips and Best Practices

### Feeding Tips

**For Consistent Tracking:**
- Log feedings immediately after completion
- Use quick-select buttons for common amounts
- Keep device nearby during feeding times
- Set reminders for scheduled feedings

**Pattern Recognition:**
- Export weekly logs to spreadsheet
- Calculate average feeding amounts
- Identify peak feeding times
- Track feeding duration trends

**Sharing with Caregivers:**
- Export daily log before others take over
- Share feeding amounts and times
- Note any changes in routine

### Sleep Tracking Tips

**Accurate Logging:**
- Mark sleep the moment baby goes down
- Don't wait to see if they "really" fall asleep
- Use long press for brief wake-ups
- Check button color to verify state

**Routine Building:**
- Track sleep for 2 weeks to identify patterns
- Look for natural sleep windows
- Schedule activities around sleep times
- Adjust bedtime based on data

**Nap Tracking:**
- Log all naps, even brief ones
- Track location of naps (crib, carrier, car, etc.) in notes
- Identify optimal nap times

### Soothe Best Practices

**Sound Selection:**
- Try each sound for at least 3-4 sessions
- Keep a note of which works best when
- Some babies prefer different sounds for different situations
- Consistency helps - stick with what works

**Volume Guidelines:**
- Start at lower volume and increase if needed
- Should be about as loud as a shower running
- Never louder than your normal speaking voice
- Can be quieter for sleeping, louder for active time

**Timer Strategy:**
- Use short timers (15-30min) for settling
- Medium timers (60-90min) for naps
- Loop or long timers for nighttime
- RESTART button is handy for extending successful sessions

**Battery Conservation:**
- Lower screen brightness when not needed
- Use airplane mode if you don't need other apps
- Close other apps running in background
- Consider battery saver mode for overnight use

### General Best Practices

**Daily Habits:**
- Log events consistently, not just when convenient
- Review yesterday's log each morning
- Export weekly logs for record keeping
- Check patterns monthly for developmental changes

**Data Management:**
- Export logs monthly for backup
- Email logs to yourself for safekeeping
- Delete test entries to keep data clean
- Use descriptive notes when relevant

**Device Tips:**
- Keep device charged and nearby
- Enable notifications for Soothe alerts
- Disable battery optimization for R3BBIT
- Set up quick access (home screen shortcut)

**Sharing with Healthcare Providers:**
- Export 1-2 weeks of logs before appointments
- Open in spreadsheet for easier viewing
- Highlight any concerns or patterns
- Bring device to show real-time data

---

## Troubleshooting

### Soothe Issues

#### Sound Won't Play

**Possible Causes & Solutions:**

1. **Device Volume**
   - Check media volume (not just ringer)
   - Press volume up button
   - Ensure phone isn't muted

2. **Do Not Disturb Mode**
   - May block media playback
   - Check DND settings
   - Allow media exceptions

3. **Audio Focus**
   - Close other media apps
   - Restart R3BBIT
   - Restart device if needed

4. **Sound File Issue**
   - Try a different sound
   - If only one sound fails, report bug
   - Reinstall app if all sounds fail

#### Sound Stops Unexpectedly

**Common Causes:**

1. **Battery Optimization**
   - Android may kill background services
   - **Solution:**
     - Go to Settings → Apps → R3BBIT
     - Battery → Don't optimize
     - Allow background activity

2. **Battery Saver Mode**
   - Kills services to save power
   - **Solution:**
     - Disable battery saver
     - Or add R3BBIT to exceptions

3. **RAM Management**
   - Some devices aggressively close apps
   - **Solution:**
     - Lock R3BBIT in recent apps
     - Increase background app limit (Developer options)
     - Close other apps before starting Soothe

4. **Notification Blocked**
   - Service requires active notification
   - **Solution:**
     - Enable notifications for R3BBIT
     - Don't swipe away Soothe notification

#### Timer Not Counting Down

**Possible Issues:**

1. **Loop Mode Selected**
   - Notification will show "Loop mode" not time
   - This is normal behavior

2. **Display Not Updating**
   - Timer may be running but not refreshing
   - Try stopping and restarting

3. **Service Crashed**
   - Restart app
   - Report bug if it persists

### Data Issues

#### Missing Log Entries

**Troubleshooting Steps:**

1. **Verify Entry Was Saved**
   - Check for confirmation when logging
   - Look for brief success message
   - If unsure, log again

2. **Check Complete Log**
   - Scroll through entire history
   - Entry might be earlier than expected
   - Use export to search in spreadsheet

3. **Data Was Wiped**
   - Check if "Wipe All Data" was triggered
   - Accidental toggle in Settings
   - Check if someone else has access

4. **App Reinstalled**
   - Data is lost on uninstall
   - Must export before uninstalling
   - Can't recover after reinstall

**Prevention:**
- Export logs weekly
- Email to yourself as backup
- Don't uninstall without exporting

#### Wrong Time on Entries

**Causes:**

1. **Device Time Incorrect**
   - Check device date/time settings
   - Enable automatic time zone
   - Sync with network time

2. **Time Zone Changed**
   - Traveling across time zones
   - Entries log in current device time
   - Can't edit historical entries

3. **Manual Entry Needed**
   - R3BBIT always uses current time
   - Can't log past events with different time
   - Export and edit CSV if needed

### Pro Purchase Issues

#### Pro Not Working After Purchase

**Steps to Resolve:**

1. **Wait for Processing**
   - Can take 5-10 minutes
   - Check back later
   - Restart app after waiting

2. **Use Restore Purchase**
   - Settings → RESTORE PURCHASE
   - Wait for confirmation
   - May need internet connection

3. **Verify Purchase in Google Play**
   - Open Play Store
   - Menu → Payments & subscriptions
   - Check if R3BBIT Pro appears
   - Request refund if charged but not working

4. **Check Google Account**
   - Ensure same account on device
   - May need to sign out and back in
   - Restore purchase after re-signing in

5. **Contact Support**
   - If above steps fail
   - Open GitHub issue with:
     - Purchase receipt screenshot
     - Device model
     - Android version
     - Steps you've tried

#### Purchase Failed or Cancelled

**Common Reasons:**

1. **Payment Method Issue**
   - Update payment info in Google Play
   - Try different payment method
   - Check card expiration

2. **Network Connection**
   - Ensure stable internet
   - Try on WiFi instead of mobile data
   - Retry purchase

3. **Google Play Issue**
   - Update Google Play Store
   - Clear Play Store cache
   - Restart device

### App Performance Issues

#### App Crashes

**Immediate Actions:**

1. Force stop app
2. Clear app cache (Settings → Apps → R3BBIT → Clear cache)
3. Restart device
4. Try again

**If Persists:**
- Note when crash occurs (specific action/screen)
- Export logs first (if possible)
- Report bug on GitHub with:
  - Device model
  - Android version
  - Steps to reproduce
  - What you were doing when it crashed

#### App Slow or Laggy

**Optimization Steps:**

1. **Clear Old Data**
   - Export old logs
   - Wipe all data
   - Start fresh (if acceptable)

2. **Free Up Storage**
   - Check device storage
   - Delete unused apps
   - Clear system cache

3. **Restart Device**
   - Often fixes temporary issues
   - Clears RAM
   - Refreshes system

4. **Update App**
   - Check for updates on GitHub
   - New versions may have performance improvements

### Getting Additional Help

If your issue isn't covered here:

1. **Check Existing Issues**
   - Visit: https://github.com/bagramlabs/R3BBIT/issues
   - Search for similar problems
   - Solutions may already be posted

2. **Report New Issue**
   - Click "New Issue"
   - Choose bug report or feature request
   - Provide detailed information:
     - Device model
     - Android version
     - R3BBIT version (from Settings)
     - Steps to reproduce
     - Screenshots if helpful

3. **Be Specific**
   - "Doesn't work" isn't helpful
   - "Soothe stops after 30 seconds on Galaxy S21" is better
   - Include what you expected vs. what happened

4. **Response Time**
   - Issues are reviewed regularly
   - May take a few days for response
   - Community members may help too

---

## Appendix

### Data Privacy

**What R3BBIT Does:**
- Stores all data locally on your device
- Uses Android SharedPreferences
- Data never leaves your device unless you export it

**What R3BBIT Doesn't Do:**
- No cloud storage
- No user accounts
- No automatic uploads
- No tracking or analytics on your data

**Ads (Free Version):**
- Non-personalized ads shown
- Ad provider may collect minimal device info
- No personal baby data shared with advertisers
- Ads removed completely with Pro

**Your Control:**
- Export data anytime
- Delete data anytime  
- Uninstall removes all data permanently
- You own your data

### Technical Specifications

**System Requirements:**
- Android 6.0 (Marshmallow) or higher
- ~20 MB storage space
- Internet connection only needed for:
  - Initial download
  - Pro purchase
  - Ads (free version)

**Permissions Required:**
- `FOREGROUND_SERVICE` - Background sound playback
- `POST_NOTIFICATIONS` - Soothe timer alerts

**Permissions NOT Required:**
- No location access
- No contacts access
- No camera access
- No microphone access
- No file system access (beyond app data)

**Battery Usage:**
- Minimal when logging only
- Moderate during Soothe playback
- Efficient foreground service implementation
- Timer auto-stops to prevent battery drain

**Storage:**
- Log data grows slowly (~1KB per 100 entries)
- Sound files embedded in app
- No cache buildup
- Easy to export and clear old data

---

**Thank you for using R3BBIT!** 

We hope this app makes tracking your baby's care easier and less stressful. If you find it helpful, please star the repository on GitHub and share with other parents!

**Support & Updates:** https://github.com/bagramlabs/R3BBIT

**Privacy Policy:** https://bagramlabs.github.io/R3BBIT

---

*Made with ❤️ for parents everywhere*
