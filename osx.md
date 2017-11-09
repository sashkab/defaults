# OS X Defaults


#### Disable shadow for screenshot

    defaults write com.apple.screencapture disable-shadow -bool true


#### Change location of screenshots

    defaults write com.apple.screencapture location ${HOME}/Documents/_screenshots

Restart SystemUIServier:

    killall SystemUIServer


### Disable natural scrolling

     defaults write NSGlobalDomain com.apple.swipescrolldirection -bool false


### Show volumes on Desktop

#### internal drives 

    defaults write com.apple.finder ShowHardDrivesOnDesktop -bool true

#### removable media

    defaults write com.apple.finder ShowRemovableMediaOnDesktop -bool true


#### external drives

    defaults write com.apple.finder ShowExternalHardDrivesOnDesktop -bool true

#### mounted servers 

    defaults write com.apple.finder ShowMountedServersOnDesktop -bool true

### Expand Save and Print dialogs by default

    defaults write -g NSNavPanelExpandedStateForSaveMode -boolean true
    defaults write -g PMPrintingExpandedStateForPrint -bool TRUE

### Disable File extension change warning dialog

defaults write com.apple.finder FXEnableExtensionChangeWarning -bool false

### Disable .DSStore files on USB drives

```
defaults write com.apple.desktopservices DSDontWriteUSBStores -bool true
```

[source](http://krypted.com/mac-security/disable-dsstore-files-on-usb-drives)

### Disable .DSStore files on Network drives

```
defaults write com.apple.desktopservices DSDontWriteNetworkStores true
```

### Enable Debug menu in App Store

```
defaults write com.apple.appstore ShowDebugMenu -bool true
```

[source](https://www.macstories.net/mac/what-to-do-when-the-mac-app-store-app-just-spins-and-spins/)

### Use plain text as default format in TextEdit

```
defaults write com.apple.TextEdit RichText -int 0
```

[source](http://www.defaults-write.com/plain-text-default-textedit/)
