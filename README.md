# GitHub Menu Bar App

<p align="center">
   <a href="https://github.com/fork-my-spoons/github-activity.spoon/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/fork-my-spoons/github-activity.spoon">
  </a>
  <a href="https://github.com/fork-my-spoons/github-activity.spoon/releases">
    <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/fork-my-spoons/github-activity.spoon/total">
  </a>
</p>

Shows 10 latest events for your github profile, similar to the event feed on github's landing page:

<p align="center">
  <img src="https://github.com/fork-my-spoons/github-activity.spoon/raw/master/screenshots/screenshot.png"/>
<p>

# Installation

 - download and install [Hammerspoon](https://github.com/Hammerspoon/hammerspoon/releases/latest)
 - download and install [github-activity.spoon](https://github.com/fork-my-spoons/github-activity.spoon/releases/download/v1.0/github-activity.spoon.zip)
 - open ~/.hammerspoon/init.lua and add following snippet:

```lua
-- GitHub
hs.loadSpoon('github-activity')
spoon['github-activity']:setup({
    username = 'streetturtle'
})
spoon['github-activity']:start()
```

This app uses icons, to properly display them, install a [feather-font](https://github.com/AT-UI/feather-font) by [downloading](https://github.com/AT-UI/feather-font/raw/master/src/fonts/feather.ttf) this .ttf font and installing it.
