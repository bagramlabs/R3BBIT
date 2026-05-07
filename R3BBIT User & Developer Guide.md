# R3BBIT User Guide

Complete guide to using R3BBIT baby care tracker.

## Table of Contents
- [Getting Started](#getting-started)
- [Feed Tracking](#feed-tracking)
- [Sleep Tracking](#sleep-tracking)
- [Diaper Tracking](#diaper-tracking)
- [Schedule Module](#schedule-module)
- [Soothe Feature](#soothe-feature)
- [Logs and History](#logs-and-history)
- [Toolbox](#toolbox)
- [Settings](#settings)
- [Pro Features](#pro-features)
- [Tips and Best Practices](#tips-and-best-practices)
- [Troubleshooting](#troubleshooting)

---

## Getting Started

### First Launch
When you first open R3BBIT, you'll see the main menu with six beautifully designed buttons in a premium neumorphic style:
- **🍼 FEED** (Blue gradient) - Track feedings
- **🚼 DIAPER** (Orange gradient) - Log changes
- **🌙 SLEEP** (Purple gradient) - Monitor sleep/wake
- **☁️ SOOTHE** - Play calming sounds
- **📅 SCHEDULE** - Plan feeding and sleep routines
- **📝 LOGS** - View history and trends

### Visual Design
R3BBIT features a modern neumorphic design with:
- **Embossed buttons** that feel tactile and responsive
- **Color-coded categories** for quick recognition
- **Large touch targets** designed for one-handed use
- **Smooth animations** that provide visual feedback

### Color Coding System
Enable color coding in Settings to make the main tracking buttons stand out:
- **Blue gradient** - Feed (bottle icon 🍼)
- **Orange gradient** - Diaper (changing station icon 🚼)
- **Purple gradient** - Sleep (moon icon 🌙)
- **Gray** - Utility functions (Soothe, Schedule, Logs)

### Navigation
- Tap any button to access that feature
- Use **BACK** button to return to main menu
- Tap **DONE** or **SAVE** to confirm entries
- Look for the ✎ pencil icon to edit data

### Visual Confirmation
After logging Feed, Diaper, or Sleep events, a confirmation popup appears at the top of the screen for 1.5 seconds showing what you just logged.

---

## Feed Tracking

### Bottle Feeding

**How to log a bottle feeding:**

1. Tap **🍼 FEED** on main menu
2. Select **BOTTLE**
3. Enter amount using the number pad
4. Tap **DONE**
5. A confirmation popup appears briefly

**Quick Tips:**
- Your last 5 feeding amounts appear as quick-select buttons
- Default unit is ml (change to oz in Settings)
- Tap any quick-select button for instant logging
- Visual confirmation shows at top of screen

**Example:**
```
Feed → Bottle → Enter "120" → Done
Popup shows: "Feed logged: 120ml"
Logged: "Apr 29 14:30, Feed, 120ml"
```

### Breastfeeding

**How to log breastfeeding:**

1. Tap **🍼 FEED**
2. Select **LEFT**, **RIGHT**, or **BOTH**
3. Entry logs immediately with confirmation popup

**When to use each option:**
- **LEFT** - Nursed from left breast only
- **RIGHT** - Nursed from right breast only  
- **BOTH** - Nursed from both breasts in one session

**Example:**
```
Feed → Left
Popup shows: "Feed logged: Left"
Logged: "Apr 29 15:45, Feed, Left"
```

### Understanding Your Data
Review feeding patterns in the Logs to identify:
- Typical feeding amounts
- Time between feedings
- Preferred feeding times
- Daily feeding frequency
- Trend charts showing feeding over time

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
The **🌙 SLEEP** button changes appearance based on state:
- Normal purple gradient = Baby is awake
- Highlighted/pressed appearance = Baby is sleeping

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
- Check button appearance to verify current state
- Use long press for brief wake-ups during naps
- Review sleep patterns in Schedule module
- Check trend charts weekly to establish routines

---

## Diaper Tracking

### How to Log Diaper Changes

1. Tap **🚼 DIAPER** on main menu
2. Select the type:
   - **Pee** - Wet diaper only
   - **Poo** - Soiled diaper only
   - **Both** - Both wet and soiled
3. Entry logs immediately with confirmation popup

**Example:**
```
Diaper → Both
Popup shows: "Diaper logged: Both"
Logged: "Apr 29 10:30, Diaper, Both"
```

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

## Schedule Module

**NEW FEATURE** - Plan and track your baby's daily routine!

### Overview
The Schedule module helps you establish consistent feeding and sleep routines by setting target times based on wake windows and feeding intervals.

### Accessing Schedule
Tap **📅 SCHEDULE** on the main menu to see two tabs:
- **Sleep** - Wake windows and nap planning
- **Feed** - Feeding interval planning

### Sleep Tab

**What it shows:**
- Current time
- Last wake time (from your logs)
- Wake window duration (how long baby has been awake)
- Recommended nap times based on your schedule

**Sleep Schedule Settings:**

1. **Wake Time** - When baby typically wakes up (e.g., 7:00 AM)
2. **Wake Window** - How long baby stays awake between naps (e.g., 90 minutes)
3. **Number of Naps** - How many naps per day (1-5)

**Example Sleep Schedule:**
```
Wake Time: 7:00 AM
Wake Window: 90 minutes
Naps: 3

Suggested Schedule:
Nap 1: 8:30 AM (90 min after wake)
Nap 2: 11:30 AM (90 min + typical nap length)
Nap 3: 2:30 PM
```

**Editing Schedule:**
- Tap the ✎ pencil icon next to any time to edit
- "ACTUAL START" and "ACTUAL END" columns let you record what really happened
- Compare planned vs. actual to refine your routine

**Tips:**
- Start with your baby's natural wake windows
- Adjust based on actual sleep patterns from Logs
- Wake windows typically increase with age
- Use trend charts to find optimal nap timing

### Feed Tab

**What it shows:**
- Time of last feeding (from your logs)
- Time until next feeding
- Recommended feeding times throughout the day

**Feed Schedule Settings:**

1. **1st Feed** - Time of first feeding (e.g., 7:30 AM)
2. **Interval** - Time between feedings (e.g., 3 hours)

**Example Feed Schedule:**
```
1st Feed: 7:30 AM
Interval: 3 hours

Suggested Schedule:
Feed 1: 7:30 AM
Feed 2: 10:30 AM
Feed 3: 1:30 PM
Feed 4: 4:30 PM
Feed 5: 7:30 PM
```

**Editing Schedule:**
- Tap ✎ to edit base wake window or feed interval
- Enter new values in minutes
- Schedule recalculates automatically

**Tips:**
- Newborns typically feed every 2-3 hours
- Intervals often lengthen as baby grows
- Night feedings may be on-demand rather than scheduled
- Use Logs to see your actual feeding pattern

### Using Schedule Effectively

**Getting Started:**
1. Track normally for 1-2 weeks using Feed, Sleep, and Diaper buttons
2. Review Logs to identify natural patterns
3. Set up Schedule based on those patterns
4. Use Schedule to maintain consistency

**Daily Use:**
- Check Schedule to know when next nap/feeding is due
- Log actual times in "ACTUAL START/END" columns
- Compare planned vs. actual to adjust routine
- Use as a guide, not a strict rulebook

**Flexibility:**
- Babies don't always follow schedules perfectly
- Use Schedule as a framework, not a requirement
- Adjust settings as baby's needs change
- Some days will be off-schedule - that's normal!

---

## Soothe Feature

### Overview
Soothe plays calming sounds to help comfort your baby. The audio continues playing even when:
- You close the app
- You use other apps
- Your screen is locked

### Available Sounds

R3BBIT includes scientifically-backed calming sounds accessible via an easy-to-use dropdown menu:

#### Noise Types
- **White Noise** - Classic static sound, masks environmental noise
- **Brown Noise** - Deeper, richer tone, like distant thunder or waterfall
- **Pink Noise** - Balanced frequency, softer than white noise

### How to Use Soothe

**Step-by-step:**

1. Tap **☁️ SOOTHE** on main menu
2. Under "SELECT SOUND", tap the dropdown menu (arrow on the right)
3. Choose your preferred sound from the list
4. Use the timer picker to select duration:
   - **Loop** - Continuous playback until manually stopped
   - **10m, 20m, 30m...** up to maximum (120m free, 999m Pro)
5. Tap **START**
6. Sound begins playing immediately

### Dropdown Interface
The sound selector features:
- Clear "SELECT SOUND" label above the dropdown
- Sound name displayed prominently
- Dropdown arrow aligned to the right for easy recognition
- Tap anywhere on the button to open the menu

### Background Playback

Once Soothe is active:
- A notification appears showing time remaining
- You can close R3BBIT and sound continues
- Use other apps normally
- Lock your screen to save battery

### Notification Controls

The persistent notification shows:
- **Time remaining** (or "INFINITE" for loop mode)
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

**Short Timers (10-30 min):**
- Good for settling before sleep
- Calming during diaper changes
- Soothing during feeding

**Medium Timers (40-90 min):**
- Nap time support
- Extended calming periods
- Background during playtime

**Long Timers (100-120 min / free, up to 999 min / Pro):**
- Full nap coverage
- Nighttime sleep support
- Extended soothing sessions

**Loop Mode:**
- All-night use
- Unpredictable nap lengths
- When you want continuous sound

### Sound Selection Tips

**Most Effective Sounds:**
1. White, brown, and pink noise tend to work for most babies
2. Try different sounds on different days
3. Some babies prefer different sounds for naps vs. nighttime
4. Volume matters - keep it moderate (about as loud as a shower)

**Safety Note:**
Keep volume at a reasonable level. Sound should be audible but not overwhelming. The American Academy of Pediatrics recommends keeping white noise at or below 50 decibels.

---

## Logs and History

### Viewing Your Logs

**Access logs:**
1. Tap **📝 LOGS** on main menu
2. See overview statistics (TODAY or ALL-TIME)
3. Scroll through complete history below
4. Most recent entries appear first

### Logs Overview

At the top of the Logs screen, you'll see statistics cards that you can tap to switch between views:

**TODAY view shows:**
- Total volume fed today
- Number of feedings
- Number of diaper changes
- Total sleep time in minutes

**ALL-TIME view shows:**
- Total volume fed (all time)
- Total number of feedings
- Total diaper changes
- Total sleep time

**Tap the card to switch** between TODAY and ALL-TIME views.

### Log Table

Below the overview, you'll see a detailed table with columns:

**DATE | TIME | TYPE | DATA**

- **DATE** - Shows date with ✎ pencil icon (editable)
- **TIME** - Shows time with ✎ pencil icon (editable)
- **TYPE** - Event type in gray (Feed, Sleep, Wake, Diaper) - not editable
- **DATA** - Details with special formatting:
  - **Feed entries**: Amount with ✎ pencil icon (editable) - e.g., "120ml ✎"
  - **Diaper entries**: Type with ✎ pencil icon (editable) - e.g., "Both ✎"
  - **Sleep entries**: Empty (no data, no pencil)
  - **Wake entries**: Duration in gray (calculated, not editable) - e.g., "90m"

**What you'll see:**
```
DATE        TIME     TYPE      DATA
May 06 ✎   16:45 ✎   Wake      90m
May 06 ✎   15:15 ✎   Sleep     
May 06 ✎   14:30 ✎   Feed      120ml ✎
May 06 ✎   12:15 ✎   Diaper    Both ✎
May 06 ✎   10:00 ✎   Feed      Left ✎
```

### Editing Log Entries

**To edit an entry:**
1. Tap the ✎ pencil icon next to the field you want to edit
2. For **Date**: A date picker appears - select new date
3. For **Time**: A time picker appears - select new time
4. For **Data** (Feed amount): Enter new amount
5. For **Data** (Diaper type): Select Pee, Poo, or Both
6. Changes save automatically

**Note:** Wake duration is calculated automatically and cannot be edited directly. To change wake duration, edit the Sleep or Wake times.

### Deleting Individual Entries

**To remove an entry:**
1. **Long press** anywhere on the row
2. Confirm deletion in the dialog
3. Entry is permanently removed

**Note:** This action cannot be undone. The logs refresh immediately after deletion.

### Trend Charts (Shareable!)

**NEW FEATURE** - Trend charts are now shareable!

In the Logs screen, you'll see visual charts showing:
- Feeding trends over the last 7 days
- Sleep patterns
- Diaper change frequency

**To share a chart:**
1. **Tap anywhere on the chart** you want to share
2. Android's share sheet opens
3. Choose where to send it:
   - Text message
   - Email
   - Social media
   - Cloud storage (Google Drive, Dropbox, etc.)
   - Any app that accepts images

**Chart image includes:**
- Chart title
- Date range ("Last 7 Days" or specific dates)
- Your data visualization
- "R3BBIT" watermark at bottom

**Use cases for sharing:**
- Send weekly progress to your partner
- Share with pediatrician before appointments
- Post milestones to family chat
- Keep in cloud storage for records
- Email to yourself for backup

### Using Logs Effectively

**For Daily Tracking:**
- Quick glance at TODAY card for current totals
- Check last feeding/sleep time
- Monitor diaper change frequency
- Tap ALL-TIME to see cumulative stats

**For Doctor Visits:**
- Share trend charts directly from the app
- Export CSV for detailed records
- Show feeding amounts and frequency
- Provide sleep pattern information
- Share diaper change regularity

**For Pattern Recognition:**
- Review charts weekly
- Compare TODAY vs ALL-TIME averages
- Identify optimal feeding times
- Establish sleep schedules
- Track developmental changes

---

## Toolbox

**Access via Settings → Toolbox section**

### Export as CSV

**How to export:**
1. Tap **EXPORT AS CSV** in Settings
2. Choose export method:
   - **Email** - Opens email with CSV attached
   - **Share** - Uses Android share sheet for any app
   - **Copy** - Copies data to clipboard

**CSV Format:**
```csv
Date Time, Event Type, Details
May 06 14:30, Feed, 120ml
May 06 15:15, Sleep, 
May 06 16:45, Wake, 90m
```

Opens easily in:
- Google Sheets
- Microsoft Excel
- Apple Numbers
- Any spreadsheet application

### Import CSV

**How to import:**
1. Tap **IMPORT CSV** in Settings
2. Android file picker opens
3. Navigate to your CSV file
4. Select the file
5. Data imports and merges with existing logs

**Important:**
- CSV must follow the same format as exported files
- Imported data merges with existing data (doesn't replace)
- Duplicate entries may be created if importing same data twice

### Copy to Clipboard

**Quick data transfer:**
1. Tap **COPY TO CLIPBOARD** in Toolbox
2. All log data copies as plain text
3. Paste into any app (notes, messages, documents)

**Use cases:**
- Quick share via text message
- Paste into notes app
- Add to documents
- Temporary backup

---

## Settings

Access settings via the main menu (tap settings icon or button).

### Visual Preferences

#### Color Coding
**Toggle:** COLOR CODING: ON/OFF

**What it does:**
- **ON** - Main tracking buttons show colored gradients:
  - Feed = Blue gradient
  - Diaper = Orange gradient  
  - Sleep = Purple gradient
- **OFF** - All buttons use standard gray appearance

**When to use:**
- Turn ON for easier visual recognition
- Turn OFF for a more subtle, monochrome look
- Personal preference - try both!

#### Haptic Feedback
**Toggle:** HAPTICS: ON/OFF

**What it does:**
- **ON** - Phone vibrates briefly when tapping buttons
- **OFF** - Silent button presses

**When to use:**
- Turn ON for tactile confirmation
- Turn OFF to avoid disturbing sleeping baby
- Turn OFF to save battery

### Functional Preferences

#### Hand Preference
**Options:** RIGHT (default) or LEFT

**What it does:**
Adjusts button layouts for easier one-handed operation.

**When to use:**
- Set to **LEFT** if you typically hold baby in your right arm
- Set to **RIGHT** if you typically hold baby in your left arm
- Switch anytime based on your current need

#### Measurement Unit
**Options:** ml (milliliters) or oz (ounces)

**What it affects:**
- Bottle feeding input
- Bottle feeding display in logs
- Quick-select buttons
- Trend chart labels

**Default:** ml

**Conversion:** 1 oz ≈ 30 ml

### Soothe Settings

#### Extended Timer (Pro Feature)
**Free Version:** Maximum 120 minutes (2 hours)
**Pro Version:** Maximum 1000 minutes (16+ hours)

**Display:**
- Free: "SOOTHE EXT: OFF" (120m max)
- Pro: "SOOTHE EXT: ON" (1000m max)

### Privacy & Support

#### Crash Reports
**Toggle:** CRASH REPORTS: ON/OFF
**Default:** OFF

**What it does:**
- **ON** - Saves crash logs locally if app crashes
- **OFF** - No crash data saved

**When enabled:**
- Logs saved only on your device
- Never sent automatically
- You choose whether to include in bug reports
- Can be deleted anytime

**Privacy:**
- Crash logs contain technical info only
- NO personal data or baby tracking information
- See Privacy Policy for details

#### Report Bug / Request Feature
Opens GitHub issues where you can:
- Report problems
- Suggest new features
- View development progress
- See existing issues

#### Privacy Policy
Opens complete privacy policy at:
https://bagramlabs.github.io/R3BBIT/privacy_policy.html

### Data Management

#### Wipe All Data

**⚠️ WARNING: This action is permanent and cannot be undone!**

**What it deletes:**
- All logged events (feeding, sleep, diaper)
- All schedule settings
- All preferences
- Pro status (if applicable)

**How to use:**
1. Find "WIPE ALL DATA" section in Settings
2. Toggle the switch to ON
3. Confirm in the dialog
4. All data is permanently deleted

**Recommendation:** Export your logs before wiping if you want to keep any records.

### Pro Version

#### Upgrade to Pro
**If not Pro:** Button shows "UPGRADE TO PRO"
**If Pro:** Button shows "PRO: ACTIVE ✓"

**Tap to:**
- Purchase Pro (if not owned)
- See Pro features
- Complete purchase via Google Play

#### Restore Purchase
If you purchased Pro and it's not showing:
1. Tap **RESTORE PURCHASE**
2. Wait for verification
3. Pro features activate if purchase found

**When to use:**
- New device
- Reinstalled app
- Signed in with different account (must use original purchase account)

### App Information

#### Version Number
At bottom of Settings screen:
```
R3BBIT 1.0.0
```

Shows current app version.

---

## Pro Features

### What's Included

Upgrade to **R3BBIT Pro** for:

✨ **Ad-Free Experience**
- No banner ads on any screen
- Cleaner interface
- Faster app performance
- Better focus on your baby

⏱️ **Extended Soothe Timer**
- Free version: 120 minutes maximum
- Pro version: 1000 minutes (16+ hours)
- Perfect for all-night use
- Extended nap support

💚 **Support Development**
- Help fund new features
- Support ongoing updates
- Keep R3BBIT improving
- Independent development

### How to Purchase

1. Tap **Settings** on main menu
2. Scroll to PRO VERSION section
3. Tap **UPGRADE TO PRO**
4. Review purchase details
5. Complete purchase through Google Play
6. Pro features activate immediately

**Purchase Details:**
- One-time payment (not a subscription)
- Works on all your Android devices with same Google account
- Permanent unlock (no recurring fees)
- Secure payment through Google Play

### After Purchase

Your Settings will now show:
```
PRO: ACTIVE ✓
SOOTHE EXT: ON (1000m max)
```

All ads are removed throughout the app.

### Restore Pro on New Device

If you purchased Pro and installed R3BBIT on a new device:

1. Ensure you're signed in with the same Google account used for purchase
2. Open **Settings**
3. Tap **RESTORE PURCHASE**
4. Wait for verification (may take a few minutes)
5. Pro features activate

**Troubleshooting:**
- Must use same Google account as original purchase
- Requires internet connection
- May take 5-10 minutes to process
- Contact support if issues persist

---

## Tips and Best Practices

### Feeding Tips

**For Consistent Tracking:**
- Log feedings immediately after completion
- Use quick-select buttons for common amounts
- Keep device nearby during feeding times
- Check Schedule module for next feeding time
- Share trend charts with partner/caregivers

**Pattern Recognition:**
- Review trend charts weekly
- Use Schedule module to plan feeding times
- Compare TODAY vs ALL-TIME in Logs overview
- Export CSV monthly for long-term records

**Sharing with Caregivers:**
- Share feeding trend chart before others take over
- Export daily log as CSV
- Show Schedule for planned feeding times
- Note any changes in routine

### Sleep Tracking Tips

**Accurate Logging:**
- Mark sleep the moment baby goes down
- Don't wait to see if they "really" fall asleep
- Use long press for brief wake-ups
- Check button appearance to verify state
- Wake duration appears in Logs automatically (calculated, in gray)

**Routine Building:**
- Use Schedule module to plan naps
- Set wake windows based on baby's actual patterns
- Review sleep trend charts weekly
- Adjust schedule settings as baby grows
- Track actual vs. planned times

**Nap Tracking:**
- Log all naps, even brief ones
- Use Schedule to predict optimal nap times
- Compare actual to suggested times
- Adjust wake windows based on real data

### Schedule Module Tips

**Getting Started:**
- Track for 1-2 weeks before setting schedule
- Review Logs to find natural patterns
- Start with baby's actual wake windows
- Use trend charts to optimize timing

**Daily Use:**
- Check Schedule in morning to plan day
- Log actual times in schedule table
- Compare planned vs. actual times
- Adjust settings weekly as baby changes

**Flexibility:**
- Schedules are guides, not rules
- Some days will be off-schedule
- Adjust for growth spurts, illness, travel
- Trust your baby's cues over strict timing

### Soothe Best Practices

**Sound Selection:**
- Use dropdown menu to try different sounds
- Try each sound for 3-4 sessions
- Some babies prefer different sounds for different times
- Consistency helps once you find what works

**Volume Guidelines:**
- Start at lower volume and increase if needed
- Should be about as loud as a shower running
- Never louder than normal speaking voice
- Can be quieter for sleeping, louder for active time

**Timer Strategy:**
- Short timers (10-30min) for settling
- Medium timers (40-90min) for naps
- Long timers (100-120min free, up to 1000min Pro) for nighttime
- Use Loop mode for unpredictable sleep lengths
- RESTART button extends successful sessions

**Battery Conservation:**
- Lower screen brightness when not needed
- Use airplane mode if you don't need other apps
- Close other apps running in background
- Consider battery saver mode for overnight (but add R3BBIT to exceptions)

### General Best Practices

**Daily Habits:**
- Log events consistently for accurate trends
- Check Logs overview (TODAY) each morning
- Review Schedule to plan the day
- Use trend charts to spot patterns
- Export logs monthly for backup

**Data Management:**
- Export CSV monthly for safekeeping
- Share charts with partner weekly
- Delete test entries to keep data clean
- Email exports to yourself as backup

**Device Tips:**
- Keep device charged and nearby
- Enable notifications for Soothe alerts
- Disable battery optimization for R3BBIT
- Set up quick access (home screen shortcut)
- Turn on haptics for tactile feedback

**Sharing with Healthcare Providers:**
- Export 1-2 weeks before appointments
- Share trend charts directly
- Open CSV in spreadsheet for detailed view
- Highlight any concerns or patterns
- Bring device to show real-time data

**Using Color Coding:**
- Enable in Settings for visual recognition
- Blue = Feed, Orange = Diaper, Purple = Sleep
- Helps identify buttons quickly
- Especially useful at night
- Disable for minimalist appearance

---

## Troubleshooting

### Soothe Issues

#### Sound Won't Play

**Possible Causes & Solutions:**

1. **Device Volume**
   - Check media volume (not just ringer)
   - Press volume up button while sound should be playing
   - Ensure phone isn't in silent mode

2. **Do Not Disturb Mode**
   - May block media playback
   - Check DND settings
   - Allow media exceptions for R3BBIT

3. **Audio Focus**
   - Close other media apps (Spotify, YouTube, etc.)
   - Restart R3BBIT
   - Restart device if problem persists

4. **Sound File Issue**
   - Try selecting a different sound from dropdown
   - If only one sound fails, report bug
   - If all sounds fail, reinstall app

#### Sound Stops Unexpectedly

**Common Causes:**

1. **Battery Optimization**
   - Android may kill background services
   - **Solution:**
     - Settings → Apps → R3BBIT
     - Battery → Don't optimize
     - Allow background activity

2. **Battery Saver Mode**
   - Kills services to save power
   - **Solution:**
     - Disable battery saver while using Soothe
     - Or add R3BBIT to battery saver exceptions

3. **RAM Management**
   - Some devices aggressively close background apps
   - **Solution:**
     - Lock R3BBIT in recent apps menu
     - Close other apps before starting Soothe
     - Increase background app limit (Developer options)

4. **Notification Blocked**
   - Soothe service requires active notification
   - **Solution:**
     - Enable notifications for R3BBIT in system settings
     - Don't swipe away Soothe notification
     - Check notification permissions

#### Timer Not Counting Down

**Possible Issues:**

1. **Loop Mode Selected**
   - Notification shows "INFINITE" not time
   - This is normal behavior for Loop mode
   - Select a specific time if you want countdown

2. **Display Not Updating**
   - Timer may be running but notification not refreshing
   - Try stopping and restarting
   - Check if sound is still playing

3. **Service Crashed**
   - Sound stops, notification disappears
   - Restart app and try again
   - Enable crash reports and report bug if it persists

### Schedule Issues

#### Schedule Times Don't Match Real Life

**Solutions:**
1. Review Logs to see actual patterns
2. Adjust wake windows in Schedule settings
3. Tap ✎ pencil icons to edit times
4. Use actual start/end columns to track reality vs. plan
5. Schedules are flexible - adjust weekly

#### Can't Edit Schedule Fields

**Check:**
- Look for ✎ pencil icon next to field
- Fields without pencil are calculated (not editable)
- Tap the pencil icon directly, not the time
- Make sure you're in edit mode

### Logs Issues

#### Missing Log Entries

**Troubleshooting Steps:**

1. **Verify Entry Was Saved**
   - Look for confirmation popup after logging
   - If no popup appeared, entry may not have saved
   - Try logging again

2. **Check Complete Log**
   - Scroll through entire history
   - Entry might be earlier than expected
   - Check both TODAY and ALL-TIME views

3. **Data Was Wiped**
   - Check if "Wipe All Data" was accidentally toggled
   - Check if someone else has access to device
   - Data cannot be recovered after wipe

4. **App Reinstalled**
   - Data is lost on uninstall
   - Must export before uninstalling
   - Cannot recover after reinstall

**Prevention:**
- Export logs monthly
- Email CSV to yourself as backup
- Don't uninstall without exporting first

#### Can't Edit Log Entry

**Check:**
- Look for ✎ pencil icon
- Sleep/Wake DATA fields don't have pencil (calculated)
- TYPE column doesn't have pencil (not editable)
- Date, Time, and data for Feed/Diaper ARE editable
- Wake duration is calculated - edit Sleep/Wake times instead

#### Charts Not Sharing

**Troubleshooting:**
1. Make sure you have data to chart (need at least 2 days)
2. Tap directly on the chart image
3. Wait for share sheet to appear
4. Try tapping chart again if it doesn't open
5. Restart app if problem persists

#### Wrong Time on Entries

**Causes:**

1. **Device Time Incorrect**
   - Check device date/time settings
   - Enable automatic time zone
   - Sync with network time

2. **Time Zone Changed**
   - Traveling across time zones
   - Entries log in current device time
   - Historical entries don't update

### Pro Purchase Issues

#### Pro Not Working After Purchase

**Steps to Resolve:**

1. **Wait for Processing**
   - Can take 5-10 minutes
   - Check back later
   - Restart app after waiting

2. **Use Restore Purchase**
   - Settings → PRO VERSION → RESTORE PURCHASE
   - Wait for confirmation
   - Requires internet connection

3. **Verify Purchase in Google Play**
   - Open Play Store app
   - Menu → Payments & subscriptions → Purchases
   - Check if R3BBIT Pro appears
   - Request refund if charged but not working

4. **Check Google Account**
   - Must be same account used for purchase
   - Sign out and back in if needed
   - Restore purchase after re-signing in

5. **Contact Support**
   - If above steps fail
   - Open GitHub issue with:
     - Purchase receipt screenshot
     - Device model and Android version
     - Steps you've tried

#### Purchase Failed or Cancelled

**Common Reasons:**

1. **Payment Method Issue**
   - Update payment info in Google Play
   - Try different payment method
   - Check card expiration date

2. **Network Connection**
   - Ensure stable internet
   - Try on WiFi instead of mobile data
   - Retry purchase

3. **Google Play Issue**
   - Update Google Play Store app
   - Clear Play Store cache
   - Restart device and try again

### App Performance Issues

#### App Crashes

**Immediate Actions:**

1. Force stop app (Settings → Apps → R3BBIT → Force Stop)
2. Clear app cache (Don't clear data or you'll lose logs!)
3. Restart device
4. Try again

**If Crashes Persist:**
- Enable crash reports in Settings
- Note when crash occurs (specific action/screen)
- Export logs first if possible
- Report bug on GitHub with:
  - Device model
  - Android version
  - Steps to reproduce
  - What you were doing when it crashed
  - Include crash logs if available

#### App Slow or Laggy

**Optimization Steps:**

1. **Check Log Size**
   - Very large log history can slow app
   - Consider exporting old logs and wiping data
   - Start fresh if acceptable

2. **Free Up Device Storage**
   - Check device storage space
   - Delete unused apps
   - Clear system cache

3. **Restart Device**
   - Often fixes temporary issues
   - Clears RAM
   - Refreshes system

4. **Update App**
   - Check GitHub for new releases
   - New versions may have performance improvements
   - Install latest version

#### Visual Issues

**Button Colors Not Showing:**
- Check Settings → COLOR CODING is ON
- Restart app
- Report bug if persists

**Charts Not Appearing:**
- Need at least 2 days of data for trends
- Scroll down in Logs to see charts
- Export and reimport data if issue persists

### Getting Additional Help

If your issue isn't covered here:

1. **Check Existing Issues**
   - Visit: https://github.com/bagramlabs/R3BBIT/issues
   - Search for similar problems
   - Solutions may already be posted
   - Comment if you have same issue

2. **Report New Issue**
   - Click "New Issue"
   - Choose bug report or feature request
   - Provide detailed information:
     - Device model (e.g., "Samsung Galaxy S22")
     - Android version (e.g., "Android 13")
     - R3BBIT version (from Settings)
     - Steps to reproduce
     - Screenshots if helpful
     - Crash logs if enabled

3. **Be Specific**
   - "Doesn't work" isn't helpful
   - "Soothe stops after 30 seconds on Pixel 7" is better
   - Include what you expected vs. what happened
   - Mention recent changes (updated Android, new device, etc.)

4. **Response Time**
   - Issues are reviewed regularly
   - May take a few days for response
   - Community members may help too
   - Check back for updates

---

## Appendix

### Data Privacy

**What R3BBIT Does:**
- Stores all tracking data locally on your device
- Uses Android SharedPreferences for settings
- Data never leaves device unless you export/share it
- No cloud storage, no user accounts

**What R3BBIT Doesn't Do:**
- No automatic uploads
- No tracking or analytics on your baby's data
- No selling of data
- No third-party access to logs

**Ads (Free Version):**
- Banner ads shown via Google AdMob
- AdMob may collect device advertising ID and basic device info
- NO personal baby data shared with advertisers
- Ads completely removed with Pro

**Charts Sharing:**
- Charts saved temporarily in app cache when shared
- You control where charts are sent via share sheet
- Charts include only data you choose to share
- Temporary files cleaned up automatically by Android

**Your Control:**
- View all data anytime in Logs
- Export data anytime as CSV
- Share charts selectively
- Delete individual entries or all data
- Uninstall removes all data permanently
- You own your data

**Full Privacy Policy:**
https://bagramlabs.github.io/R3BBIT/privacy_policy.html

### Technical Specifications

**System Requirements:**
- Android 7.0 (Nougat) or higher
- ~20 MB storage space
- Internet connection only needed for:
  - Pro purchase
  - Ads (free version)
  - Bug reports

**Permissions Required:**
- `FOREGROUND_SERVICE` - Background sound playback for Soothe
- `POST_NOTIFICATIONS` - Soothe timer alerts

**Permissions NOT Required:**
- No location access
- No contacts access
- No camera access
- No microphone access
- No broad file system access

**Battery Usage:**
- Minimal when logging only
- Moderate during Soothe playback (media player)
- Efficient foreground service implementation
- Timer auto-stops to prevent battery drain
- Haptics use minimal power

**Storage:**
- Log data grows slowly (~1KB per 100 entries)
- Sound files embedded in app (~2MB total)
- Chart cache cleaned automatically
- Easy to export and clear old data

**Performance:**
- Optimized for one-handed use
- Neumorphic design with smooth animations
- Fast button response times
- Efficient data structures
- Minimal memory footprint

---

**Thank you for using R3BBIT!** 

We hope this app makes tracking your baby's care easier and less stressful. If you find it helpful, please share with other parents!

**Support & Updates:** https://github.com/bagramlabs/R3BBIT

**Privacy Policy:** https://bagramlabs.github.io/R3BBIT/privacy_policy.html

---

*Made with ❤️ for parents everywhere*
