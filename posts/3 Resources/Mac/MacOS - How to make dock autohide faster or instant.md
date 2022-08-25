
# MacOS - How to make dock autohide faster or instant

To make the Dock **instantly leap back** into view when it’s needed, rather than slide, open a Terminal window and type the following:

```
defaults write com.apple.dock autohide-time-modifier -int 0;killall Dock
```

---

I find this useful, but if you’d like the animation for the dock to reappear to last for a split-second, try the following:

```
defaults write com.apple.dock autohide-time-modifier -float 0.15;killall Dock
```

To explain, changing "0.15" with any number can let you tailor things as it represents the time in seconds taken for the dock to reappear fully.

---

To revert back to the default sliding effect, open a Terminal window and type the following:

```
defaults delete com.apple.dock autohide-time-modifier;killall Dock
```