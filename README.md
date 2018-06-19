# Keyboard Usage Analyzer
A tool for tracking and helping you analyze/optimize your hand movements across a
keyboard.

## Note to Others
**Please, for the love of God, don't use this software for malicious purposes!** This 
tool is only intended for scientific purposes. For others using this software: please download the
source from this repository. I am pretty good about signing my commits, so you'll know that it is
me. If my commit isn't signed, chances are that it's still me. To be safe, just revert the history
until you find a signed commit and download the source then.

## Usage - keylogger.c
Build the code and deploy it to `/usr/local/sbin/`. Then drop the Launchd script to
 `/System/Library/LaunchDaemons` to fire up this keylogger on startup. By default, the keystrokes
 would be logged in `/var/log/keystroke.log`. You may need root privilege when writing to
 `/var/log/`.

Remember to check *Enable access for assitive devices* in the *Universal Access* preferences panel.
