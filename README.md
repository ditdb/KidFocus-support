# KidFocus Support

[中文](https://github.com/ditdb/KidFocus-support/blob/main/README-zh.md) · [Privacy Policy](https://github.com/ditdb/KidFocus-support/blob/main/PRIVACY.md)

KidFocus lets parents pick the apps their child needs for online class and set the class hours. During those hours every other app is blocked on the iPad, and everything returns when class ends. It uses Apple's Screen Time frameworks, has no account, and never connects to the internet.

## Contact

Questions, bug reports or feedback: <ditdb.team@gmail.com>

Please include your iPad model, iPadOS version and the KidFocus version (Settings → About). If a rule isn't working, also attach the text from **Settings → Diagnostics → Export Diagnostics**. It contains no app names and no personal information.

## Getting started

1. Open KidFocus and allow Screen Time access.
2. Set a 6-digit parent passcode. Don't share it with your child.
3. Tap **+** to create a rule: name it, choose the apps, set start and end times and the days to repeat.
4. Turn **Enabled** on. When the time comes, other apps are blocked automatically, and they come back when it ends.

For stronger protection, we recommend:

- Using a child Apple ID in Family Sharing on your child's iPad, and choosing **Child account** when authorizing.
- Setting a Screen Time passcode in the system Settings app.

## Frequently asked questions

### What is the difference between "Allow only selected apps" and "Block only selected apps"?
- **Allow only selected apps** (default): during the window only the apps you chose can be used; everything else is blocked. This suits online class.
- **Block only selected apps**: during the window the apps you chose are blocked; everything else works as usual. This suits limiting games or video.

### My rule isn't taking effect. What should I check?
1. Settings → **Screen Time Authorization** should say Authorized. If authorization was revoked, a red banner appears on the rule list. Tap **Authorize Again**.
2. Make sure the rule is **Enabled** and the current time and weekday fall inside the window.
3. Open Settings → **Diagnostics** and tap **Reconcile Now**. If the page still reports a problem, export the diagnostics and send them to us.

### Why can't I enable a rule?
Two enabled rules can't overlap in time. Turn one off, or change its time or repeat days. You also need Screen Time authorization before any rule can be enabled.

### I forgot the parent passcode.
The passcode can't be recovered or reset. This is deliberate: a reset that needs no proof would also work for a child. To set a new one:

1. In the system Settings app, revoke KidFocus's Screen Time authorization. With a child account, a parent may need to verify.
2. Delete KidFocus and install it again.

Your focus rules are erased too, so you'll need to create them again.

### Why can't I delete KidFocus?
While any rule is enabled, **Extra Protection** prevents deleting the app, so a child can't remove it to escape the block. To uninstall it, turn off "Prevent Deleting KidFocus" in KidFocus Settings, or turn off all rules.

### Why can't I change the date and time?
While any rule is enabled, KidFocus requires the date and time to be set automatically, so the focus window can't be bypassed by changing the clock. You can turn this off in KidFocus Settings (requires the parent passcode).

### Can my child get around KidFocus?
KidFocus can't stop a child who knows the parent passcode or the Screen Time passcode. With a **My own account** authorization, a child can also revoke access in the system Settings app, so we recommend a child account in Family Sharing.

### Does a rule that crosses midnight work?
Yes. A window such as 22:00 to 06:00 belongs to the day it starts on.

### What data does KidFocus collect?
None. See the [Privacy Policy](https://github.com/ditdb/KidFocus-support/blob/main/PRIVACY.md).

## Requirements

- iPad with iPadOS 17 or later  *(confirm the final minimum version before publishing)*
- Screen Time authorization
