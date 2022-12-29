## Table of Contents

<a href="#how-to-pull-down-the-notification-bar">1. How to pull down the notification bar</a>

<a href="#how-to-swipe-drag--drop-or-other-gestures">2. How to swipe, drag & drop or other gestures?</a>

<a href="#chrome-tab-switcher-changes-to-list">3. Chrome tab switcher changes to list</a>

<a href="#google-chrome-ui-changes-when-quick-cursor-is-enabled">4. Google Chrome UI changes when Quick Cursor is enabled</a>

---

# Frequently asked questions and issues

1. ### How to pull down the notification bar?

Move the cursor above the status bar. The default top edge action is "Notifications", which opens the notifications panel.

<details>
  <summary>Pull down notifications bar video</summary>

[Demo video](https://user-images.githubusercontent.com/3103859/210019050-d90388be-192e-4656-abdd-5064aa7fb159.mp4)
</details>

If you have the PRO version, you can change the action to something else. Go to Quick Cursor Settings -> Edge actions.

---

2. ### How to swipe, drag & drop or other gestures?

**PRO users only.** Go to Quick Cursor Settings -> Tap behaviour -> Long tap mode -> **Gesture replication**.

Long tap the tracker and record your gesture. When you release the tracker the gesture will be replayed at the cursor position. 

<details>
  <summary>Gesture replication video demo</summary>
  
[Gesture replication video demo](https://user-images.githubusercontent.com/3103859/210020310-3dd2266a-e1a3-495f-ac59-604ba420a119.mp4)
</details>

Issues:
- [Simulate gestures in real time](https://github.com/micku7zu/QuickCursor/issues/4)
- Gesture replication is smoother on Android 11+ devices. Android 7-10 replication is not that smooth. 

---

3. ### [Chrome tab switcher changes to list](https://github.com/micku7zu/QuickCursor/issues/2)
Go to Google Chrome Settings -> Accessibility -> Disable "**Simplified view for open tabs**". 

More details about this Chrome issue here: https://github.com/micku7zu/QuickCursor/issues/2

---

4. ### [Google Chrome UI changes when Quick Cursor is enabled](https://github.com/micku7zu/QuickCursor/issues/3)

Chrome automatically detects when an accessibility service with touch permission is enabled and changes its UI without the possibility to choose if the user wants that or not.

More details about this Chrome issue here: https://github.com/micku7zu/QuickCursor/issues/3
