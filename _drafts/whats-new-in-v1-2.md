---
author_staff_member: marco
title: What's new in v1.2
date: 2019-06-23 16:27:00 +0000
description: "Swift 5 .... and \U0001F41E-fixes"
image: "/images/whats-new-in-1-2-super-mario.gif"
categories:
- release
comments: true

---
Neither big bells and whistles nor new features this time. Just ordinary improvements. It's safe to say we are fully in line with the [Zombieland rule #32: "Enjoy the little things"](https://www.youtube.com/watch?v=Hp2W0Lylzrs) with this update.

### 🌟 Swift 5

The upgrade to Swift 5 is undeniably the biggest change in this release. The programming language from Apple matures and so does Progress. Swift 5 was published in March 2019, so it's time for Progress to catch up. From a user perspective you won't notice any difference for now. Here's what Apple has to say about the benefits of Swift 5:

> Swift 5 makes it dramatically easier to release your apps. Because the Swift runtime is now built into iOS, macOS, tvOS, and watchOS, your app no longer needs to bundle this library for these latest OS releases. Users who download an app built with Swift from the App Store will get a smaller app and a faster download. - [Apple](https://developer.apple.com/swift/)

### 🐞 Delete confirmation when adding a report

Under certain circumstances a delete confirmation dialog was shown while the user was adding a report. Obviously this leads to a lot of confusion. This bug has been fixed.

### 🐞 Number as goal for report with "overall" period

If the user set a custom number as goal for a report with the "overall" period, the user defined number was ignored. Instead Progress wrongly calculated the score of all available reminders and assumed this is the goal the user wants to achieve. This behaviour has been fixed.

**Progress v1.2 - this is it. If you have any question of feedback, drop me a line:** [**support@progress.rocks**](mailto:support@progress.rocks)

_If you use Apple Reminders to organise your to-do lists, Progress for Apple Reminders can help you to achieve what you want. Give it a try and let me know what you think!_

<p>
<a href="https://itunes.apple.com/us/app/progress-for-apple-reminders/id1450818073?mt=8&ign-mpt=uo%3D2" target="_blank" class="appstore">
<img src="/images/App_Store_Badge.svg" alt="Download on the App Store" />
</a>
</p>