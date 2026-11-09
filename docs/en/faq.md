# iCadence FAQ

[Back to iCadence](../../README.md) · [简体中文](../zh-CN/faq.md)

## What does iCadence do?

iCadence helps desk workers and students take short breaks. Set a routine, receive a reminder, and complete a walking, camera-assisted, or timed activity before continuing your day.

## Which iPhone and iOS version do I need?

The current App Store release requires **iOS 18.6 or later**. Strong AlarmKit reminders require **iOS 26 or later**, a supported device, Pro, and system authorization. Feature availability depends on your device and permissions. The App Store listing is the reference for current compatibility.

## How can I schedule breaks?

Choose work intervals, selected minutes each hour, or fixed daily times. Set working time windows and repeat days. For interval routines, a completed break starts the next work interval from completion; an unfinished action window ends before the next interval starts. Fixed-time routines follow their configured schedule.

## Why did my reminder not appear?

Check that your routine is enabled, the current day and time fall within its schedule, and no Quiet Period is active. In iPhone Settings, allow iCadence notifications and check Focus and notification delivery settings. If you use AlarmKit, check its separate authorization and iOS compatibility too.

Reminders are scheduled in advance through the system, so the app does not need to stay open to deliver them. Delivery still depends on iOS permissions and settings. Reopen iCadence after changing permissions or your schedule so it can refresh its state. If the problem continues, [contact support](mailto:support@qinfu-cloud.cn).

## How does walking verification work?

Carry your iPhone, enable Motion & Fitness access, and keep the walking activity page open while moving. Motion detection may take several steps to begin updating. Walking verification is separate from the system's background reminder delivery; do not rely on background walking verification.

## Does every activity use the camera?

No. Walking uses motion sensors. Standing, stretching, squats, jumping jacks, and push-ups use camera-assisted pose detection with Pro. Eye breaks, drinking water, and breathing use guided timers. A timer does not verify that you drank water or looked away from the screen. Manual confirmation is recorded separately from sensor-verified completion.

## Are my camera images saved or uploaded?

No. Camera frames used for pose detection are processed on device and are not saved or uploaded. See the [official privacy policy](https://www.qinfu-cloud.cn/health/en/privacy) for the complete policy, including optional iCloud sync.

## What are Quiet Periods?

Quiet Periods temporarily suppress reminders across your routines on the current device. Choose a quick duration, custom start and end times, or a repeating period. For interval routines, the end of a Quiet Period starts a fresh work interval rather than sending a backlog of break reminders. Quiet Period settings are local to the device.

## How do I add a widget?

Add iCadence from the iPhone Home Screen widget gallery, or customize your Lock Screen and choose an iCadence widget. Create and enable a routine in the app first. Widgets show upcoming breaks, action information, or Quiet Period status. This is separate from a Live Activity or Dynamic Island feature.

## Is iCadence free?

Yes, you can create and run one basic routine with ordinary notifications and a non-camera activity. Pro unlocks multiple routines, camera verification, AlarmKit reminders, full history, and iCloud sync. History records are retained when access to the full history view is locked.

Pro is available as an annual auto-renewing subscription or a one-time lifetime purchase. Eligible new subscribers may receive a trial. Prices and eligibility are shown at purchase and vary by storefront. Manage or cancel an annual subscription in your Apple ID subscription settings. [Apple Standard EULA](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/).

## How do I restore Pro on another device?

Use the Apple ID that made the purchase, open the Pro screen, and choose Restore Purchases. A lifetime purchase does not require a recurring subscription. If Pro access is missing after restoring, email support with your app version and a description of the problem; do not post receipts publicly.

## Can I sync with iCloud?

Pro includes optional iCloud sync for supported routines and break history using your private CloudKit database. Enable it in iCadence settings and use the same iCloud account on your devices. Sync depends on iCloud availability and network access; it is not a promise of instant delivery. Raw camera frames and raw motion data are not synced. Quiet Periods remain device-local.

## Where can I get help or suggest a feature?

Email [support@qinfu-cloud.cn](mailto:support@qinfu-cloud.cn) for user support, or [developer@qinfu-cloud.cn](mailto:developer@qinfu-cloud.cn) for developer and business inquiries. Include your iPhone model, iOS and app versions, and steps to reproduce an issue. See [release notes](../../CHANGELOG.md) and the [official support page](https://www.qinfu-cloud.cn/health/en/support).
