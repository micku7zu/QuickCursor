# FAQ (Frequently asked questions)

Q: **How to pull down the notification bar?**

A: In the free version, move the cursor above the status bar.
In the pro version, move the cursor above the status bar in the left part. If you want to pull down the quick settings, move the cursor above the status bar in the right part.
This edge actions are configurable in the PRO version. You can check them in Settings -> Edge actions.

---

Q: **How to drag &amp; drop, swipe or other complex gestures?**

A: Go to Settings -> Tap behaviour -> Tap mode and choose "Advanced".
When you long tap the tracker, it will act as a gesture recorder and all your movements will be recorded until you release the tracker. The gesture will replayed on the screen at the cursor position, exactly like you moved the tracker. The gesture replay is smooth in Android 11 and it is a little laggy on older versions (7, 8, 9, 10).


Q: **I like the app and I want to help you. How can I help?**

A: Join the telegram group [https://t.me/quickcursor](https://t.me/quickcursor) to help me test the builds before releasing them to public.
Don\'t forget to share the app with your friends!

---

# Troubleshooting
Bug: **The app stops working after some time**

Solution: Some manufacturers (Xiaomi, Huawei, and others) are killing the background apps even when the user doesn\'t want that, so the user must do some tricks to disable that.
Each manufacturer has his own settings, you can check more details about this here: [https://dontkillmyapp.com](https://dontkillmyapp.com)

---

Bug: **Tap / Click stopped working or never worked at all**

Possible solutions:
* restart the Quick Cursor accessibility service
* force stop the app from the phone settings and start the accessibility service again
* restart the device (this worked on many devices)
* some other accessibility services are blocking the Quick Cursor accessibility service and the app doesn\'t work. This can be fixed only by manual uninstalling other accessibility services.

Unfortunately, in some rare cases on some devices, the accessibility service can\'t tap or click on behalf of user because of unknown reasons.
If you are in this situation, there is no fix for the moment, but please send me your device model and Android version to gather more data why this happens. You can contact me from within "About" section.

---

Bug: **"Open settings" from Quick actions doesn\'t work on MIUI**

Solution: Enable \"Display pop-up while in background\" permission for Quick Cursor from MIUI settings.

---

Bug: **"The trigger does not work on OnePlus device with Oxygen OS gesture navigation**

Solution: Try to swipe vertically on the trigger area, from bottom to top when you try to get the cursor. This is a known reported bug in Oxygen OS implementation: [https://forums.oneplus.com/threads/system-gesture-implementation-issue.1246522/](https://forums.oneplus.com/threads/system-gesture-implementation-issue.1246522/). I can't fix this because they implemented wrong the gesture navigation. We must wait for them to fix it.
