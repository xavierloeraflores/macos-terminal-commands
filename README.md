# macos-terminal-commands
A list of all my favorite terminal commands



Make the dock appear and hide instantly:

`defaults write com.apple.Dock autohide-delay -float 0.0001; killall Dock`

Under this action:

`defaults delete com.apple.Dock autohide-delay; killall Dock`

Change dock animation speed:

`defaults write com.apple.dock autohide-time-modifier -float 0.25;
killall Dock`

Vim for VSCode repeating key:

`defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false`

Install Xcode Packages:

`xcode-select --install`


Pomodoro CLI @ [bashbunni](https://gist.github.com/bashbunni/f6b04fc4703903a71ce9f70c58345106):

1. `brew install caarlos0/tap/timer`
2. `alias work="timer 60m && terminal-notifier -message 'Pomodoro'\
        -title 'Work Timer is up! Take a Break 😊'\
        -appIcon '~/Pictures/pumpkin.png'\
        -sound Crystal"`
3. `alias rest="timer 10m && terminal-notifier -message 'Pomodoro'\
        -title 'Break is over! Get back to work 😬'\
        -appIcon '~/Pictures/pumpkin.png'\
        -sound Crystal" `

