# Changelog

All notable changes to R3BBIT will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Planned
- Home screen widget for quick logging
- Daily/weekly statistics and summaries
- Growth tracking (weight, height)
- Multiple baby profiles
- Dark mode
- Medication tracking
- Temperature logging

## [1.0.0] - 2024-XX-XX

### Added
- **Feed Tracking**
  - Bottle feeding with amount (ml/oz)
  - Breastfeeding (left/right/both)
  - Quick-select buttons for recent amounts
  - Unit preference (ml or oz)

- **Sleep Tracking**
  - Single tap to log sleep/wake
  - Automatic duration calculation
  - Long press for quick wake-and-sleep transition
  - Visual state indicator on button

- **Diaper Tracking**
  - Pee, Poo, or Both options
  - Quick one-tap logging

- **Soothe Feature**
  - 9 calming sounds:
    - White noise
    - Brown noise
    - Pink noise
    - Rain
    - Ocean
    - Heartbeat
    - Vacuum
    - Hair dryer
    - Fan
  - Timer options: 5, 10, 15, 20, 30, 45, 60, 90, 120 minutes
  - Loop mode for continuous playback
  - Background playback with foreground service
  - Notification controls (Stop/Restart)
  - 2-second fade-out on stop
  - Pro: Extended timer up to 999 minutes

- **Logs & Export**
  - Complete history view
  - CSV export via email/copy/share
  - Individual entry deletion (long press)
  - Formatted timestamp display

- **Settings**
  - Left/right hand mode toggle
  - Measurement unit selection (ml/oz)
  - Wipe all data option
  - Restore Pro purchase
  - Link to bug reports/feature requests
  - Privacy policy link
  - Version display

- **Pro Features**
  - Ad-free experience
  - Extended soothe timer (999 minutes)
  - One-time purchase via Google Play Billing
  - Restore purchase functionality

- **User Interface**
  - Card-based design with large touch targets
  - One-handed operation support
  - Color-coded feature buttons
  - Material Design components
  - Responsive layouts

### Technical Details
- Built with Kotlin
- Minimum SDK: Android 6.0 (API 23)
- Target SDK: Android 14 (API 34)
- Local data storage using SharedPreferences
- Foreground service for reliable audio playback
- Google Mobile Ads integration
- Google Play Billing integration

---

## Version History

### Version Number Scheme
- **Major.Minor.Patch** (e.g., 1.0.0)
- **Major:** Breaking changes or major new features
- **Minor:** New features, backward compatible
- **Patch:** Bug fixes, backward compatible

### Release Types
- **[Unreleased]** - Changes in development
- **[Version]** - Released versions with date

### Change Categories
- **Added** - New features
- **Changed** - Changes to existing functionality
- **Deprecated** - Soon-to-be removed features
- **Removed** - Removed features
- **Fixed** - Bug fixes
- **Security** - Security improvements

---

## How to Read This File

Each version section includes:
1. Version number and release date
2. Changes grouped by category
3. Brief description of each change
4. Issue/PR references where applicable

**Example:**
```
## [1.1.0] - 2024-12-01

### Added
- Widget for home screen quick logging (#45)
- Daily statistics summary view (#52)

### Fixed
- Soothe stops on screen lock (#67)
- Sleep duration calculation edge case (#71)

### Changed
- Improved feed button layout (#58)
```

---

**Note:** This is a living document. Check back regularly for updates on new features and fixes!
