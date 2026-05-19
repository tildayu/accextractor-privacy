# Privacy Policy for AccExtractor

**Last updated: May 20, 2026**

AccExtractor ("the app") is a personal research tool that records accelerometer data from an Apple Watch and stores it on the user's devices. This privacy policy explains exactly what data the app handles and how.

## What the app collects

While the app is recording, your Apple Watch captures:

- Accelerometer measurements (X, Y, Z axes) at approximately 50 Hz
- Timestamps for each measurement

Recording happens only when **all** of the following are true:

- You have explicitly tapped "Start" in the app
- The Motion & Fitness permission is granted on your Apple Watch
- You are wearing the watch

## Where the data is stored

- **On the Apple Watch:** in the watch's secure on-device motion buffer (Apple's `CMSensorRecorder` API).
- **On your iPhone:** when you tap "Export & Send" on the watch, samples are compressed (gzip CSV) and transferred to the paired iPhone over the encrypted Apple Watch ↔ iPhone link. Files are stored inside the app's sandbox (Documents directory). They are not synced to iCloud and not accessible to other apps.

## What is shared

**Nothing is sent to the developer.** AccExtractor does not operate any servers and does not transmit your data anywhere on its own.

If you tap the share button next to a file, iOS opens its standard share sheet so you can choose where to send the file (email, AirDrop, Files app, etc.). In that case, the file goes wherever you direct it. That choice is yours, not the app's.

## How to delete your data

- **One file:** swipe left on it in the Files list.
- **All files:** tap "Delete all data" at the bottom of the main screen. This permanently removes every CSV stored on the iPhone.
- **Revoke motion access entirely:** iOS Settings → Privacy & Security → Motion & Fitness → AccExtractor.

## Children's privacy

The app is not intended for children under 13 and does not knowingly collect data from anyone in that age range.

## Changes to this policy

We may update this policy from time to time. The "Last updated" date at the top reflects the current version.

## Contact

For questions about this policy or the app: zhangxumou@gmail.com
