# Installs

## Productivity

* [Chrome](https://www.google.com/chrome/browser/desktop/)
* [Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [Dropbox](https://www.dropbox.com/install)
* [Sublime Text](https://www.sublimetext.com/)
* [Spotify](https://www.spotify.com/us/download/mac/)

## Configuration

* [Karabiner](https://pqrs.org/osx/karabiner/) - keyboard remapping 
* [BetterTouchTool](https://www.boastr.net/downloads/) - window snapping
* [Seil](https://pqrs.org/osx/karabiner/seil.html.en) - caps locks override
* [Flux](https://justgetflux.com/) - dim at night

## Development

* [Python](https://www.python.org/downloads/)
* [SourceTree](https://www.sourcetreeapp.com/)
* [Webstorm](https://www.jetbrains.com/webstorm/download/download-thanks.html?platform=mac)
* [Postman](https://www.getpostman.com/docs/introduction)

## Mac App Store

* Xcode

## Brew

* [Homebrew](http://brew.sh/)

```
brew tap caskroom/cask
brew install java
brew install android-sdk autojump cask git node wget
```

# System Preferences

## Mission Control

* [ ] Automatically rearrange spaces

## Keyboard

* [x] Use all F1, F2, etc. keys as standard function keys

## Trackpad

Point & Click
* [ ] Look up & data detectors
* [x] Secondary click - click or tap with 2 fingers
* [x] Tap to click - tap with one finger

Scroll & Zoom
* [ ] Scroll direction: natural
* [x] Zoom in or out - pinch with 2 fingers
* [x] Smart zoom - double-tap with 2 fingers
* [x] Rotate - rotate with 2 fingers

More Gestures
* [x] Swipe between pages - swipe with 3 fingers
* [x] Swipe between full-screen apps - swipe left or right with 4 fingers
* [ ] Notification Center
* [x] Mission Control - swipe up with 4 fingers
* [x] App Expose - swipe down with 4 fingers
* [x] Launchpad - pinch with thumb and 3 fingers
* [x] Show Desktop - spread thumb and 3 fingers

## Accessibility

* [ ] Shake mouse pointer to locate

## Users & Groups

* Disable Guest user

# Configuration

## Seil

* Remap caps lock to key code `80` (F19), which is used by Karabiner

## Webstorm Plugins

* Markdown
* gitignore

# Keepass & Wine

[https://www.davidbaumgold.com/tutorials/wine-mac/](https://www.davidbaumgold.com/tutorials/wine-mac/)

Download Keepass: [http://keepass.info/download.html](http://keepass.info/download.html)

```
brew cask install java xquartz
brew install wine
wine path/to/setup.exe
wine ~/.wine/drive_c/Program\ Files/path/to/program.exe
```

# Development Setup

## Git

```
git config --global user.email "your@email.com"
git config --global user.name "Your Name"
```

## npm

```
npm install -g forever grunt-cli istanbul karma
```
