# R3BBIT 🐰

> A comprehensive baby care tracking app for Android

Track feedings, sleep, diaper changes, and soothe your baby with calming sounds - all in one simple, intuitive app designed for one-handed operation.

[![GitHub issues](https://img.shields.io/github/issues/bagramlabs/R3BBIT)](https://github.com/bagramlabs/R3BBIT/issues)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Features

### 📊 Comprehensive Tracking
- **Feed Tracking** - Log bottle (ml/oz) and breastfeeding (left/right/both)
- **Sleep Monitoring** - Track sleep/wake times with automatic duration calculation
- **Diaper Changes** - Record pee, poo, or both
- **Complete History** - View, export, and analyze all logged events

### 🎵 Soothe Feature
Play calming sounds to help comfort your baby with background playback support:
- Brown Noise
- Pink Noise

**Timer Options:**
- Quick select: 5, 10, 15, 20, 30, 45, 60, 90, 120 minutes
- Loop mode for continuous playback
- Pro: Custom timers up to 999 minutes
- Gentle 2-second fade-out

### 🎯 User-Friendly Design
- **One-Handed Operation** - Left and right-handed modes
- **Large Touch Targets** - Easy to use while holding your baby
- **Minimal Taps** - Quick logging with smart defaults
- **Background Service** - Soothe continues even when app is closed
- **Notification Controls** - Stop/restart directly from notification

## Installation

### From Google Play
https://play.google.com/store/apps/details?id=com.bagram.r3bbit

## Usage

### Quick Start

#### Feeding
1. Tap **FEED**
2. Select **BOTTLE** or breastfeeding side (**LEFT**, **RIGHT**, **BOTH**)
3. For bottle: Enter amount and tap **DONE**
4. Quick-select buttons show your last 5 feeding amounts

#### Sleep Tracking
- **Single tap** while awake → Logs Sleep
- **Single tap** while sleeping → Logs Wake (with duration)
- **Long press** while sleeping → Logs Wake and immediately starts new Sleep

The SLEEP button changes color to indicate current state.

#### Diaper Changes
1. Tap **DIAPER**
2. Select **Pee**, **Poo**, or **Both**
3. Change is logged immediately

#### Soothe
1. Tap **SOOTHE**
2. Select a sound (9 options available)
3. Choose timer duration or **LOOP**
4. Tap **START**
5. Control playback from the notification:
   - **STOP** - Fades out and stops
   - **RESTART** - Resets timer to original duration

### Viewing History
1. Tap **LOGS** to view all tracked events
2. Each entry shows timestamp, event type, and details
3. **Export options:**
   - EMAIL - Send via email
   - COPY - Copy to clipboard
   - SHARE - Use Android share menu
4. **Delete:** Long press any entry to remove it

### Settings

Access settings via the **SETTINGS** button:

- **Hand Preference** - Toggle LEFT/RIGHT hand mode
- **Measurement Unit** - Switch between ml and oz
- **Soothe Limit** - 120m (free) or 999m (Pro)
- **Restore Purchase** - Restore Pro on new device
- **Wipe All Data** - Permanently delete all logs (with confirmation)

## Pro Features

Upgrade to R3BBIT Pro for:
- ✨ **Ad-free experience**
- ⏱️ **Extended soothe timer** (up to 999 minutes)
- 💚 **Support ongoing development**

Purchase through Settings → **UPGRADE TO PRO**

## Privacy & Data

R3BBIT respects your privacy:
- ✅ All data stored **locally** on your device
- ✅ No user accounts required
- ✅ No internet connection needed for core features
- ✅ Data never transmitted to external servers
- ✅ You control all exports and sharing

View our [Privacy Policy](https://bagramlabs.github.io/R3BBIT)

## Technical Details

### Permissions
- `FOREGROUND_SERVICE` - Required for background sound playback
- `POST_NOTIFICATIONS` - For soothe timer notifications

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
- [ ] Daily/weekly summary statistics
- [ ] Growth tracking (weight, height)
- [ ] Multiple baby profiles
- [ ] Data backup/sync options

### In Progress
- [x] Google Play Store release
- [ ] Localization (multiple languages)

## Support

### Getting Help
- 📖 Check the [User Guide](docs/USER_GUIDE.md)
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

## Acknowledgments

Built with:
- [Kotlin](https://kotlinlang.org/)
- [Android SDK](https://developer.android.com/)
- [Material Design](https://material.io/)
- [Google Mobile Ads](https://developers.google.com/admob)
- [Google Play Billing](https://developer.android.com/google/play/billing)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Changelog

### Version 1.0.6 (Current)
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

If you find R3BBIT helpful, please ⭐ star this repository!
