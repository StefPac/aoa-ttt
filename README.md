# AOA-Twenty-Twenty-Twenty 👀

This is a small MacOS utility that will display a notification every twenty
minutes to remind users to look for 20 seconds at an object at least 20 feet
away. It is based on a [recommendation by the American Optometric
Association](https://www.aoa.org/AOA/Images/Patients/Eye%20Conditions/20-20-20-rule.pdf).

Your eyes are important, take good care!

## Requirements

This utility can only run on MacOS. It was tested on MacOS Monterey and
later.

## Installation

```sh
git clone https://github.com/StefPac/aoa-ttt.git
cd aoa-ttt
./aoa-ttt-install
```

To uninstall:

```sh
./aoa-ttt-uninstall
```

The installer registers a `launchd` agent at
`~/Library/LaunchAgents/com.aoa-ttt.plist` that fires every 20 minutes. To
remove it manually, run `launchctl unload ~/Library/LaunchAgents/com.aoa-ttt.plist`
and delete the file.
