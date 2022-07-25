# AOA-Twenty-Twenty-Twenty 👀

This is a small MacOS utility that will display a notification every twenty
minutes to remind users to look for 20 seconds at an object at least 20 feet
away. It is based on a [recommendation by the American Optometric
Association](https://www.aoa.org/AOA/Images/Patients/Eye%20Conditions/20-20-20-rule.pdf).

Your eyes are important, take good care!

## Requirements

This utility can only run on MacOS. It was tested on MacOS Monterey.

## Installation

```sh
git clone XXX
cd aoa-ttt
./aoa-ttt-install
```

To uninstall:

```sh
./aoa-ttt-uninstall
```
or manually remove the crontab entry with `crontab -e`.
