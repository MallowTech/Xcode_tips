---
title: How to show the duration of builds in Xcode
tip-number: 01
tip-username: arasu01
tip-username-profile: https://github.com/arasu01
tip-description: How long xcode take to build the project.


---

Ever wondered how long your builds in Xcode are taking? Here’s a quick way to show the build duration in seconds inside Xcode after each build:


1. In your terminal, type:

```bash
defaults write com.apple.dt.Xcode ShowBuildOperationDuration -bool YES
```

2. Relaunch Xcode.
3. Build your project to see the duration of each build!

![Xcode Build Time](Xcode_build_time.png "Xcode Build Time")
