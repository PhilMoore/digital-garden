
# Mac Tip - Change Screenshot File Format to JPG from PNG

## JPG

```
defaults write com.apple.screencapture type jpg;killall SystemUIServer
```

## PNG

```
defaults write com.apple.screencapture type png;killall SystemUIServer
```