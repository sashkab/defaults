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

