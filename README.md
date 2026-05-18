# R3BBIT 🐰

> A comprehensive baby care tracking app for Android

Track feedings, sleep, diaper changes, schedules, and soothe your baby with calming sounds - all in one simple, intuitive app designed for one-handed operation. Now with smart scheduling and partner sync!

[![GitHub issues](https://img.shields.io/github/issues/bagramlabs/R3BBIT)](https://github.com/bagramlabs/R3BBIT/issues)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Features

### 📊 Comprehensive Tracking
- **Feed Tracking** - Log bottle (ml/oz) and breastfeeding (left/right/both)
- **Sleep Monitoring** - Track sleep/wake times with automatic duration calculation
- **Diaper Changes** - Record pee, poo, or both
- **Complete History** - View, export, and analyze all logged events
- **Statistics** - Daily averages and trends at a glance

### 📅 Smart Scheduling
- **Wake Window Tracking** - Progressive or constant wake windows
- **Nap Duration Settings** - Customize expected nap lengths
- **Backward Calculation** - Plan from target bedtime
- **Flexible Schedules** - Adapts to your baby's rhythm
- **Feed Schedules** - Set intervals and first feed time

### 🔄 Smart Sync
- **Partner Handoffs** - Intelligently merge data from multiple devices
- **Copy/Paste** - Share logs via clipboard
- **Export/Import CSV** - Full data portability
- **Conflict Resolution** - Automatically handles overlapping time periods

### 🎵 Soothe Feature
Play calming sounds to help comfort your baby with background playback support:
- Brown Noise
- Pink Noise
- White Noise
- Ocean Waves
- Rain
- Heartbeat
- Lullaby
- And more!

**Timer Options:**
- Quick select: 10-100+ minute intervals
- Loop mode for continuous playback
- Extended mode for longer sessions
- Gentle 2-second fade-out
- Change sound/timer while playing

### 🎯 User-Friendly Design
- **One-Handed Operation** - Left and right-handed modes
- **Large Touch Targets** - Easy to use while holding your baby
- **Minimal Taps** - Quick logging with smart defaults
- **Background Service** - Soothe continues even when app is closed
- **Notification Controls** - Stop/restart directly from notification
- **Tablet Support** - Perfect for dedicated baby station

## Installation

### From Google Play
[Download R3BBIT](https://play.google.com/store/apps/details?id=com.bagram.r3bbit)

**Supported Devices:**
- Android phones (portrait mode)
- Tablets (perfect for bedside baby station!)
- Minimum: Android 7.0+

## Usage

### Quick Start

#### Feeding
1. Tap **FEED**
2. Select **BOTTLE** or breastfeeding side (**LEFT**, **RIGHT**, **BOTH**)
3. For bottle: Enter amount and tap **DONE**
4. Quick-select buttons show your last 5 feeding amounts

#### Sleep Tracking
- **Tap START SLEEP** while awake → Logs Sleep
- **Tap STOP SLEEP** while sleeping → Logs Wake (with duration)
- The button label clearly shows current state

#### Diaper Changes
1. Tap **DIAPER**
2. Select **Pee**, **Poo**, or **Both**
3. Change is logged immediately

#### Schedules
1. Tap **SCHEDULE**
2. Choose **SLEEP** or **FEED** tab
3. Configure settings:
   - Wake time
   - Wake windows (Progressive or Constant)
   - Nap duration
4. Record actual times to track against ideal schedule

#### Soothe
1. Tap **SOOTHE**
2. Select a sound
3. Choose timer duration or **LOOP**
4. Tap **START**
5. Control playback from the notification

### Viewing History
1. Tap **LOGS** to view all tracked events
2. Each entry shows timestamp, event type, and details
3. **Tap ✎ to edit** any entry
4. **Long press to delete** entries
5. View daily stats or all-time averages

### Data Management (Toolbox)

Access via **Toolbox** from settings:

- **Copy to Clipboard** - Copy all logs for sharing
- **Paste from Clipboard** - Import logs with Smart Sync
  - **Overwrite** - Replace all data
  - **Smart Sync** - Intelligently merge with existing data
- **Export as CSV** - Save logs to file
- **Import from CSV** - Load logs from file
- **Trends** - View analytics and patterns

### Settings

Access settings via the **SETTINGS** button:

- **Hand Preference** - Toggle LEFT/RIGHT hand mode
- **Measurement Unit** - Switch between ml and oz
- **Restore Purchase** - Restore Pro on new device
- **Clear All Data** - Permanently delete all logs (with confirmation)

## Pro Features

Upgrade to R3BBIT Pro for:
- ✨ **Ad-free experience**
- ⏱️ **Extended features**
- 💚 **Support ongoing development**

Purchase through Settings → **UPGRADE TO PRO**

## Privacy & Data

R3BBIT respects your privacy:
- ✅ All data stored **locally** on your device
- ✅ No user accounts required
- ✅ No internet connection needed for core features
- ✅ Data never transmitted to external servers
- ✅ You control all exports and sharing

**AdMob Integration:**
- The free version displays banner ads via Google AdMob
- AdMob may collect device IDs and app interaction data
- See [Google's Privacy Policy](https://policies.google.com/privacy) for details

View our [Privacy Policy](https://bagramlabs.github.io/R3BBIT)

## Technical Details

### Permissions
- `FOREGROUND_SERVICE` - Required for background sound playback
- `FOREGROUND_SERVICE_MEDIA_PLAYBACK` - Media playback service type
- `POST_NOTIFICATIONS` - For soothe timer notifications
- `INTERNET` - For ads (optional, app works offline)
- `ACCESS_NETWORK_STATE` - For ads

### Data Storage
- Uses Android `SharedPreferences` for local storage
- Logs stored in CSV format for easy export
- All data remains on device unless explicitly exported

## Contributing

We welcome contributions! Here's how you can help:

1. **Report Bugs**
   - Use the [issue tracker](https://github.com/bagramlabs/R3BBIT/issues/new/choose)
   - Include device model and Android version
   - Describe steps to reproduce

2. **Suggest Features**
   - Open a [feature request](https://github.com/bagramlabs/R3BBIT/issues/new/choose)
   - Explain the use case
   - Describe expected behavior

3. **Submit Pull Requests**
   - Fork the repository
   - Create a feature branch
   - Make your changes
   - Submit a PR with clear description

## Roadmap

### Planned Features
- [ ] Widget for home screen quick logging
- [ ] Growth tracking (weight, height)
- [ ] Multiple baby profiles
- [ ] Dark/Light theme toggle
- [ ] More sound options

### In Progress
- [x] Google Play Store release
- [x] Tablet support
- [x] Smart data sync
- [ ] Localization (multiple languages)

## Support

### Getting Help
- 🐛 [Report a bug](https://github.com/bagramlabs/R3BBIT/issues/new/choose)
- 💡 [Request a feature](https://github.com/bagramlabs/R3BBIT/issues/new/choose)
- 📧 Contact: [Open an issue](https://github.com/bagramlabs/R3BBIT/issues)

### Troubleshooting

**Soothe sound won't play?**
- Check device volume settings
- Verify Do Not Disturb isn't blocking media
- Try restarting the app

**Sound stops unexpectedly?**
- Disable battery optimization for R3BBIT
- Check notification permissions are granted
- Ensure battery saver isn't killing background services

**Pro not working after purchase?**
- Wait a few minutes for processing
- Use "RESTORE PURCHASE" in Settings
- Restart the app

**Can't delete log entry?**
- Use **long press** on the entry (not tap)
- Look for delete instructions above the logs table

**Schedule not calculating correctly?**
- Check wake time is set
- Verify wake window settings
- Try switching between Progressive and Constant modes

## Acknowledgments

Built with:
- [Kotlin](https://kotlinlang.org/)
- [Android SDK](https://developer.android.com/)
- [Material Design](https://material.io/)
- [Google Mobile Ads](https://developers.google.com/admob)
- [Google Play Billing](https://developer.android.com/google/play/billing)

## Changelog

### Version 1.0.2 (Current)
- **UX Improvements**
  - Clearer sleep button labels (START SLEEP / STOP SLEEP)
  - Larger, more readable text throughout logs
  - Bigger buttons on home screen for easier tapping
  - Integer statistics (removed decimal points)
  - Delete instructions now visible in logs
- **Schedule Enhancements**
  - Tab-style interface for Sleep/Feed schedules
  - Compact settings layout
  - Added nap duration setting
  - Backward calculation from target bedtime (Constant mode)
- **Interface Refinements**
  - Centered toolbox layout
  - Enhanced visual hierarchy
  - Better tablet support

### Version 1.0.1
- Initial release
- Feed tracking (bottle and breastfeeding)
- Sleep monitoring with duration calculation
- Diaper change logging
- Soothe feature with 9 sound options
- CSV export functionality
- Left/right hand modes
- Pro upgrade option

---

**Made with ❤️ for parents everywhere**

**Developer:** [Bagram Labs](https://github.com/bagramlabs)
