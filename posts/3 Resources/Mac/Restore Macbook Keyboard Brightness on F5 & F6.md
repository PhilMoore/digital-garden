
# How to Restore Macbook Keyboard Brightness on F5 & F6

Create a new plist file in `~/Library/LaunchAgents` named `com.local.KeyRemapping.plist` and add the code below. Save the file and reboot. F5 and F6 will now work as keyboard brightness up/down keys (after you log in for the first time after rebooting).

```
<?xml version="1.0" encoding="UTF-8"?><!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd"><plist version="1.0"><dict> <key>Label</key> <string>com.local.KeyRemapping</string> <key>ProgramArguments</key> <array> <string>/usr/bin/hidutil</string> <string>property</string> <string>--set</string> <string>{"UserKeyMapping":[ { "HIDKeyboardModifierMappingSrc": 0xC000000CF, "HIDKeyboardModifierMappingDst": 0xFF00000009 }, { "HIDKeyboardModifierMappingSrc": 0x10000009B, "HIDKeyboardModifierMappingDst": 0xFF00000008 } ]}</string> </array> <key>RunAtLoad</key> <true/></dict></plist>
```

To open ~/Library/LaunchAgents go to finder and Shift+CMD+G and paste "~/Library/LaunchAgents"