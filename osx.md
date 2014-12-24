# OS X Defaults


#### Disable shadow for screenshot

	defaults write com.apple.screencapture disable-shadow -bool true


#### Change location of screenshots

	defaults write com.apple.screencapture location ${HOME}/Documents/_incoming/screenshots
	
Restart SystemUIServier:

	killall SystemUIServer


### Disable natural scrolling

    
     defaults write NSGlobalDomain com.apple.swipescrolldirection -bool false
