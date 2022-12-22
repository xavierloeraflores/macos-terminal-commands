# macos-terminal-commands
A list of all my favorite terminal commands



Make the dock appear and hide instantly:

`defaults write com.apple.Dock autohide-delay -float 0.0001; killall Dock`

Under this action:

`defaults delete com.apple.Dock autohide-delay; killall Dock`

Change dock animation speed:

`defaults write com.apple.dock autohide-time-modifier -float 0.25;
killall Dock`


