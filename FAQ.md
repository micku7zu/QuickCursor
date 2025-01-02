# Frequently asked questions and issues

## Table of Contents

<a href="#1-how-to-pull-down-the-notification-bar">1. How to pull down the notification bar</a>

<a href="#2-how-to-swipe-drag--drop-or-other-gestures">2. How to swipe, drag & drop or other gestures?</a>

<a href="#3-the-application-stops-after-some-time">3. The application stops after some time</a>

<a href="#4-the-click-doesnt-work-on-samsung">4. The click doesn't work on Samsung</a>

<a href="#5-triggers-dont-work-with-oneplus-oppo-realme-gesture-navigation">5. Triggers don't work with OnePlus (Oppo, Realme) gesture navigation</a>

<a href="#6-chrome-tab-switcher-changes-to-list">6. Chrome tab switcher changes to list</a>

<a href="#7-google-chrome-ui-changes-when-quick-cursor-is-enabled">7. Google Chrome UI changes when Quick Cursor is enabled</a>

<a href="#8-open-settings-from-quick-actions-doesnt-work-on-miui">8. "Open settings" from Quick actions doesn't work on MIUI</a>

<a href="#9-change-volume-action-doesnt-work-on-oneplusopporealme">9. Change volume action doesn't work on OnePlus/Oppo/Realme</a>

<a href="#10-the-click-doesnt-work-on-pixel-android-15">10. The click doesn't work on Pixel Android 15</a>

<a href="#11-how-can-i-help">11. How can I help?</a>
<br />

## 1. How to pull down the notification bar?

Move the cursor above the status bar. The default top edge action is "Notifications", which opens the notifications panel.

<details>
  <summary>Pull down notifications bar video</summary>

[Demo video](https://user-images.githubusercontent.com/3103859/210019050-d90388be-192e-4656-abdd-5064aa7fb159.mp4)
</details>

If you have the PRO version, you can change the action to something else. Go to Quick Cursor Settings -> Edge actions.

<br/><br/>

## 2. How to swipe, drag & drop or other gestures?

**PRO users only.** 

Go to Quick Cursor Settings -> Tap behaviour -> Long tap action -> **Start gesture recorder**.

Long tap the tracker and record your gesture. When you release the tracker the gesture will be replayed at the cursor position. 

<details>
  <summary>Gesture replication video demo</summary>

[Gesture replication video demo](https://user-images.githubusercontent.com/3103859/215866130-27d91513-f70f-4728-80a2-78a4c059b2b3.mp4)
</details>

Issues:
- [Gestures are not replicated in real time](https://github.com/micku7zu/QuickCursor/issues/4)
- Gesture replication is smoother on Android 11+ devices. Android 7-10 replication is not that smooth. 

<hr />

**There are also some prerecorded** gestures available that can be dispatched instantly.

Go to Quick Cursor Settings -> Tap behaviour -> Long tap action -> **Open tracker actions once**

Long tap the tracker and select the gesture you want (swipe left, right, top, bottom).
<details>
  <summary>Tracker actions swipes video demo</summary>

[Tracker actions swipes](https://user-images.githubusercontent.com/3103859/215867497-3ab2c5d8-c8ee-47cb-9d8b-c99fe6a6b08b.mp4)
</details>

<br/><br/>

## 3. The application stops after some time

Some manufacturers (Xiaomi, Huawei, Samsung and others) are stopping background apps (like Quick Cursor) even when the user doesn't want this.

The solution is to **lock the app in memory** and **disable all battery optimization for Quick Cursor**. The app doesn't crash in the background, it is stopped by your device!

More details about this issue [here](https://github.com/micku7zu/QuickCursor/issues/5).

<br/><br/>

## 4. The click doesn't work on Samsung

Disable Samsung "**One-Handed mode**" and uninstall Samsung "**One Hand Operation +**" app. Restart the device.

More details about this issue [here](https://github.com/micku7zu/QuickCursor/issues/6).

<br/><br/>

## 5. Triggers don't work with OnePlus (Oppo, Realme) gesture navigation

This is an Oxygen OS (Color OS, Realme UI) bug raised in their forums but they don't fix it.

A workaround is to swipe vertically on the screen margin (bottom to top). [Demo video](https://user-images.githubusercontent.com/3103859/210069142-98d8f4c5-7521-4850-b438-9037460e1ccd.mp4)

More details and possible workarounds about this issue [here](https://github.com/micku7zu/QuickCursor/issues/7).

<br/><br/>

## 6. Chrome tab switcher changes to list
Go to Google Chrome Settings -> Accessibility -> Disable "**Simplified view for open tabs**". 

More details about this Chrome issue [here](https://github.com/micku7zu/QuickCursor/issues/2).

<br/><br/>

## 7. Google Chrome UI changes when Quick Cursor is enabled

Chrome automatically detects when an accessibility service with touch permission is enabled and changes its UI without the possibility to choose if the user wants that or not.

More details about this Chrome issue [here](https://github.com/micku7zu/QuickCursor/issues/3).

<br/><br/>

## 8. "Open settings" from Quick actions doesn't work on MIUI

Enable "Display pop-up while in background" permission for Quick Cursor from MIUI settings. [Screenshot](https://user-images.githubusercontent.com/3103859/210067987-5951f2e6-9d34-4a57-b03d-4a5544560a8e.png)

<br/><br/>

## 9. Change volume action doesn't work on OnePlus/Oppo/Realme

The "Change volume" action doesn't work outside of Quick Cursor app on OnePlus/Oppo/Realme device.
This issue happens only on Oxygen OS, Color OS and Realme UI (all 3 are based on the same system).

[This is currently being investigated](https://github.com/micku7zu/QuickCursor/issues/12). I don't have more details on it yet.

<br/><br/>

## 10. The click doesn't work on Pixel Android 15

This is an OS bug [confirmed by Google](https://issuetracker.google.com/issues/384188031) and they are working on a fix. This bug affects other apps as well. It is not Quick Cursor specific.

Workaround:

1. Assign a "Multi tap" action with 2 simultaneous taps as an Edge action, Tracker action, or Tracker long tap action
2. When the click stops working, trigger that action once
3. The click should start working again

More details here: https://github.com/micku7zu/QuickCursor/issues/29

<br/><br/>

## 11. How can I help?

- Join the [Telegram group t.me/quickcursor](https://t.me/quickcursor) to help me test the beta builds before releasing them to public.
- Help with translations on https://quickcursor.app/translate. If you need help, contact me on [Telegram](https://t.me/quickcursor) or [Email](mailto:quickcursor@protonmail.com)
- Send feedback: bugs, issues, improvement ideas or anything else you think could help me make the app better
