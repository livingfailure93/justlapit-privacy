# Privacy Policy for JustLapIt

**Last updated: December 2025**

Living Excellence Games ("we", "our", or "us") operates the JustLapIt mobile application. This Privacy Policy explains how we collect, use, and protect your information.

## Summary

- **Free users**: All data stays on your device. No account required.
- **Premium users**: Optional cloud sync requires a Google account or email signup.
- **Location data**: Only used during distance workouts, never stored on our servers.
- **We don't sell your data. Ever.**

---

## 1. Information We Collect

### 1.1 Information You Provide

**Account Information (Optional)**
- Email address (if you create an account)
- Google account info (if you sign in with Google)
- Account creation is only required for Premium features

**Profile Information (Optional)**
- Weight, height, age, gender (for calorie calculations)
- This data is stored locally on your device
- Premium users can optionally sync this to the cloud

**Workout Data**
- Timer configurations, workout history, custom presets
- Free users: stored locally only
- Premium users: synced to cloud for backup

### 1.2 Information Collected Automatically

**Location Data (Distance Workouts Only)**
- GPS coordinates during active distance-based workouts
- Used to calculate distance traveled and pace
- **Never transmitted to our servers**
- **Never stored after workout ends**
- You can use the app without location permissions

**Device Information**
- We do not collect device identifiers, IP addresses, or analytics data

### 1.3 Payment Information

- Payments are processed entirely by Google Play
- We never see or store your payment details
- We only receive confirmation of subscription status

---

## 2. How We Use Your Information

| Data | Purpose |
|------|---------|
| Email/Account | Authentication, password reset |
| Profile (weight, height, etc.) | Calorie burn calculations |
| Workout history | Display your progress, cloud backup |
| Location (GPS) | Real-time distance and pace tracking |

We do **not** use your data for:
- Advertising or marketing
- Selling to third parties
- User profiling or analytics
- Any purpose other than app functionality

---

## 3. Data Storage & Security

### Local Storage (All Users)
- Settings, preferences, and workout data stored on your device
- Uses Android's secure SharedPreferences and Room database

### Cloud Storage (Premium Users Only)
- Data stored in Google Firebase (Firestore)
- Firebase is SOC 2 and ISO 27001 certified
- Data encrypted in transit and at rest
- Servers located in the United States

### Data Retention
- Local data: Until you uninstall the app or clear data
- Cloud data: Until you delete your account
- We do not keep backups after account deletion

---

## 4. Third-Party Services

We use the following services:

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| Google Firebase Authentication | User account login | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| Google Firebase Firestore | Cloud data storage (Premium) | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| Google Firebase Cloud Messaging | Push notifications for reminders | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| Google Firebase Cloud Functions | Scheduled reminder delivery | [Firebase Privacy](https://firebase.google.com/support/privacy) |
| Google Play Billing | Subscription payments | [Google Privacy](https://policies.google.com/privacy) |

We do **not** use:
- Analytics services (no Google Analytics, Firebase Analytics, etc.)
- Advertising networks
- Social media tracking

---

## 5. Your Rights & Choices

### Access & Export
- View all your data within the app
- Premium users can access cloud data anytime

### Deletion
- **Local data**: Clear app data or uninstall
- **Cloud data**: Delete your account in Settings > Account
- Account deletion is immediate and permanent

### Location Permissions
- You can deny or revoke location permissions anytime
- The app works fully without location (except distance workouts)

### Account
- You can use the app without creating an account
- Accounts are only required for Premium cloud features

---

## 6. Children's Privacy

JustLapIt is not directed at children under 13. We do not knowingly collect information from children under 13. If you believe a child has provided us with personal information, please contact us.

---

## 7. Changes to This Policy

We may update this Privacy Policy occasionally. We will notify you of significant changes by:
- Updating the "Last updated" date
- In-app notification for material changes

---

## 8. Contact Us

Questions, concerns, or requests regarding your data:

**Email**: livingexcellencegames@gmail.com

---

## 9. Fitness Data Disclaimer

All fitness metrics provided by JustLapIt (calories burned, distance traveled, pace, etc.) are **estimates only** and should not be relied upon for medical purposes. See our Terms of Service for the complete health and safety disclaimer.

---

## 10. Push Notifications & Reminders

### How Reminders Work
- Premium users can set workout reminder alarms
- Reminders are delivered via Firebase Cloud Messaging (FCM)
- A unique FCM token identifies your device for notifications

### What We Store
- Your FCM device token (to send notifications to your device)
- Alarm settings (enabled/disabled, time, days of week, timezone)
- This data is stored in Firebase Firestore under your account

### Your Control
- You can disable reminders in Settings > Notifications
- You can revoke notification permissions in Android settings
- Deleting your account removes all notification data

### Smart Reminders
- The app analyzes your workout patterns locally on your device
- Suggestions for optimal workout times are generated on-device
- No workout pattern data is sent to our servers for this feature

---

## 11. User-Selected Sounds

Premium users can select custom sounds from their device for timer notifications (lap completion, workout completion, countdown warnings).

**Important:**
- Custom sounds are selected from your device's storage
- We do not store, transmit, or process your custom sound files
- The sound file remains on your device only
- You are solely responsible for ensuring you have the right to use any sounds you select
- We do not claim ownership of or responsibility for any user-selected sounds

---

## 12. Permissions Explained

| Permission | Why We Need It |
|------------|----------------|
| `POST_NOTIFICATIONS` | Timer alerts when app is in background |
| `VIBRATE` | Haptic feedback during workouts |
| `ACCESS_FINE_LOCATION` | GPS tracking for distance workouts |
| `ACCESS_COARSE_LOCATION` | Required alongside fine location |
| `FOREGROUND_SERVICE` | Keep timer running in background |
| `WAKE_LOCK` | Prevent device sleep during workouts |
| `INTERNET` | Cloud sync (Premium only) |
| `BILLING` | Process subscriptions via Google Play |

---

*Living Excellence Games*
*JustLapIt - Your Personal Workout Timer*
