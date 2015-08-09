# My Macbook Pro OS X config
This is list of my personal laptop set up. It will serve as a reminder/checklist for reinstalls and a place to store my  dotfiles.
Lots of inspiration taken from [Nicolas Hery](https://github.com/nicolashery). Check out his mac dev setup [here](https://github.com/nicolashery/mac-dev-setup).

## OS X System Settings

- Keyboard > Modifier Keys > Caps Lock changed to Control
- Keyboard > Key Repeat > Set to fastest
- Keyboard > Delay Until Repeat > Set to shortest
- Trackpad > Tap to click
- Dock > Automatically show and hide dock
- Dock > Size > About 80% of the way towards small
- Mission Control > Hot Corners > Top left Mission Control, top right Notification Center, bottom left Application Windows, bottom right Start Screen Saver 
- Sharing > Change computer name to whatever you want

STILL NEEDS TO ADD, add major project directories to 'favorites sidebar', screenshots of Finder > Preferences, tags removed, auto open to 'andrew', what is displayed in finder windows, show file extensions, show view options, show path bar, show status bar, auto opening on login, Remove shared and tags
New finder window to open in the home directory, Remove the display and bluetooth icons
Change battery to show percentage symbols

## installing languages and dev tools

XCode command line tools

- `xcode-select --install`

Homebrew

- `$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
- Test with `brew doctor`
- Run `brew update` to get most recent

## iTerm2

- General > uncheck Confirm closing multiple sessions 
- General > uncheck Confirm "Quit iTerm2 (Cmd+Q)" command
- Profiles > Create New > Set as Default
- Profiles > Window > Columns: 125 and Rows: 35.
- Profiles > Window > Transparecy: About 10% transparent
- Profiles > Color > Color Preset > [One Dark Terminal](https://github.com/nathanbuchar/one-dark-terminal) (to match atom). Then increase foreground to brighten it up a bit.
- Keys > Hotkey > Show/Hide iTerm with system-wide hotkey > "Command + ~"
- Profiles > Hotkey Window > Window > Full-height Left of Screen
- Profiles > Text > Meslo for Powerline

## dotfiles

- .bash_prompt
- .bash_profile
- .aliases

## Git

- `brew install git`

When done, to test that it installed fine you can run:

```git --version```

And `which git` should output `/usr/local/bin/git`.

Add the .gitconfig to `~` directory.

```
git config --global user.name "Your Name Here"
git config --global user.email "your_email@youremail.com"
git config --global credential.helper osxkeychain
```

## Atom

- One Dark theme and syntax

## Node.js

- 
