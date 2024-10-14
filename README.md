## About

This is a list of i3 toolings one might enjoy. They might work for sway.

Inspired by the [discussion](https://github.com/i3/i3/discussions/4509) I
gathered some the tools that I found in the threads and from other sources to
this repository akin to [awesome
lists](https://github.com/sindresorhus/awesome). At this time I violate at least
one of the
[major](https://github.com/sindresorhus/awesome/blob/main/awesome.md#only-awesome-is-awesome)
points in the Awesome Manifesto.

This list is not (fully) vetted and I do not endorse ~any~ most of the tools. I
did not test all of them. Tough I did use some of them — some even on a daily
basis — some are even mine. If I found a tool that did not work, I did not
include it in the list.

If you find a new tool or find that a tool from the list is broken and
unmaintained please open an issue or pull request.

## Information Fetcher
Show/View some parts of i3.

- [i3-match](https://gitlab.com/ferreum/i3-match): match and query i3/sway
  window properties and events
  (written in C)
- [i3expo](https://gitlab.com/d.reis/i3expo): show screenshots of open
  containers
- [i3expo-ng](https://github.com/morrolinux/i3expo-ng): Fork of i3expo
  ![language](https://img.shields.io/github/languages/top/morrolinux/i3expo-ng) ![stars](https://img.shields.io/github/stars/morrolinux/i3expo-ng?style=flat)

### Trees

- [i3get](https://gist.github.com/budRich/892c0153c06a27ea7bc89d8f8dec99d2):
  search for windows in i3 tree, return desired information
  (written in shell script)
- [i3tree](https://github.com/sciurus/i3tree): shows containers as tree
  ![language](https://img.shields.io/github/languages/top/sciurus/i3tree) ![stars](https://img.shields.io/github/stars/sciurus/i3tree?style=flat)
- [py3tree](https://github.com/DavidAntliff/py3tree): Reimplementation of
  sciurus/i3tree
  ![language](https://img.shields.io/github/languages/top/DavidAntliff/py3tree) ![stars](https://img.shields.io/github/stars/DavidAntliff/py3tree?style=flat)
- [i3tree](https://github.com/Ajnasz/i3tree): shows container as text tree or in
  graphwiz format
  ![language](https://img.shields.io/github/languages/top/Ajnasz/i3tree) ![stars](https://img.shields.io/github/stars/Ajnasz/i3tree?style=flat)
- [i3nodes](https://github.com/Syphdias/i3nodes): show tree in concise manor
  ![language](https://img.shields.io/github/languages/top/Syphdias/i3nodes) ![stars](https://img.shields.io/github/stars/Syphdias/i3nodes?style=flat)


## Management/Manipulation

### Layout
Tools that change the behavior of how containers/windows are opened, how the
behave.

- [i3-master-layout](https://github.com/Hippo0o/i3-master-layout):
  master-stack/split/tabbed layout, master always on left
- [i3ipc-dynamic-tiling](https://github.com/chlyz/i3ipc-dynamic-tiling): similar
  tiling to swm and xmonad
- [autotiling](https://github.com/nwg-piotr/autotiling): change split of current
  container depending on ratio of width to height
- [i3-alternating-layout](https://github.com/olemartinorg/i3-alternating-layout):
  Very similar to autotiling, similar behavior based on ratio (not actually
  alternating), limited configuration
- [i3-autolayout](https://github.com/BiagioFesta/i3-autolayout): Similar to
  autotiling and i3-alternateing-layout, can save and restore layouts, limited
  configuration
- [i3nator](https://github.com/pitkley/i3nator): Tmuxinator for i3, manage
  projects and restore them
- [i3-resurrect](https://github.com/JonnyHaystack/i3-resurrect): save and
  restore layouts
- [i3-layout-manager](https://github.com/klaxalk/i3-layout-manager): Save and
  restore layouts
- [i3-balance-workspace](https://github.com/atreyasha/i3-balance-workspace):
  resets split ratio of workspace or focused containers similar to emacs' `M-x
  balance-windows` or vim's `<c-w>=`

### Workspace
Tools that focus, move, or resize a workspace.

-

### Container/Window
Tools that focus, move, or resize a container/window.

-

### Workspace and Container/Window
Tools that focus, move, or resize a workspace or container/window.

- [i3-tools](https://github.com/miseran/i3-tools): 


## i3 Bars

### i3 Bar Status Command
What you put after `status_command` in `bar` block

- [i3status](https://github.com/i3/i3status): Generate status bar (default)
  ![language](https://img.shields.io/github/languages/top/i3/i3status) ![stars](https://img.shields.io/github/stars/i3/i3status?style=flat)
- [i3blocks](https://github.com/vivien/i3blocks): The hacker-friendly
  status_command for Sway and i3
  ![language](https://img.shields.io/github/languages/top/vivien/i3blocks) ![stars](https://img.shields.io/github/stars/vivien/i3blocks?style=flat)
- [j4status](https://github.com/sardemff7/j4status): Status line generator
  ![language](https://img.shields.io/github/languages/top/sardemff7/j4status) ![stars](https://img.shields.io/github/stars/sardemff7/j4status?style=flat)
- [i3-dstatus](https://github.com/altdesktop/i3-dstatus): ultimate DIY
  statusline generator
  ![language](https://img.shields.io/github/languages/top/altdesktop/i3-dstatus) ![stars](https://img.shields.io/github/stars/altdesktop/i3-dstatus?style=flat)
- [i3status-rs](https://github.com/greshake/i3status-rust): Rust replacement for
  i3status
  ![language](https://img.shields.io/github/languages/top/greshake/i3status-rust) ![stars](https://img.shields.io/github/stars/greshake/i3status-rust?style=flat)
- [goi3bar](https://github.com/denbeigh2000/goi3bar): configurable, extensible
  replacement for i3status
  ![language](https://img.shields.io/github/languages/top/denbeigh2000/goi3bar) ![stars](https://img.shields.io/github/stars/denbeigh2000/goi3bar?style=flat)
- [bumblebee-status](https://github.com/tobi-wan-kenobi/bumblebee-status):
  modular, theme-able status line generator
  ![language](https://img.shields.io/github/languages/top/tobi-wan-kenobi/bumblebee-status) ![stars](https://img.shields.io/github/stars/tobi-wan-kenobi/bumblebee-status?style=flat)
- [yagostatus](https://github.com/burik666/yagostatus): i3status replacement
  ![language](https://img.shields.io/github/languages/top/burik666/yagostatus) ![stars](https://img.shields.io/github/stars/burik666/yagostatus?style=flat)
- [i3pyblocks](https://github.com/thiagokokada/i3pyblocks): i3status with
  asyncio
  ![language](https://img.shields.io/github/languages/top/thiagokokada/i3pyblocks) ![stars](https://img.shields.io/github/stars/thiagokokada/i3pyblocks?style=flat)
- [polybar](https://github.com/polybar/polybar): fast and easy-to-use status bar
  ![language](https://img.shields.io/github/languages/top/polybar/polybar) ![stars](https://img.shields.io/github/stars/polybar/polybar?style=flat)

### Alternatives to `i3bar`
- [dzen2](https://github.com/minos-org/dzen2): general purpose messaging,
  notification and menuing program for X11
  ![language](https://img.shields.io/github/languages/top/minos-org/dzen2) ![stars](https://img.shields.io/github/stars/minos-org/dzen2?style=flat)
- [xmobar](https://codeberg.org/xmobar/xmobar): minimalist status bar


## Looks
- [i3-style](https://github.com/altdesktop/i3-style): themes and switcher
  ![language](https://img.shields.io/github/languages/top/altdesktop/i3-style) ![stars](https://img.shields.io/github/stars/altdesktop/i3-style?style=flat)
- [Online Colorscheme Configurator for i3, i3status,
  dmenu](https://thomashunter.name/i3-configurator/): easily preview changes
  in colors
- [scusage](https://github.com/tobi-wan-kenobi/scusage): summarizes shortcut
  usage, very useful to optimize keybinds
- [i3-workspace-brightness](https://github.com/orhun/i3-workspace-brightness):
  set individual brightness levels for each workspace
- [percentual-gaps](https://github.com/applejax124/percentual-gaps): set gaps to
  be percentual instead of fixed pixel values (changes config)

### Showing keybinds

- [i3-keylist](https://github.com/s-n-g/i3-keylist): display key list
  ![language](https://img.shields.io/github/languages/top/s-n-g/i3-keylist) ![stars](https://img.shields.io/github/stars/s-n-g/i3-keylist?style=flat)
- [i3keys](https://github.com/RasmusLindroth/i3keys): list available bindings
  for i3/Sway with graphical or text keyboard
  ![language](https://img.shields.io/github/languages/top/RasmusLindroth/i3keys) ![stars](https://img.shields.io/github/stars/RasmusLindroth/i3keys?style=flat)
- [i3help](https://github.com/glennular/i3help): dialog to view key bindings
  ![language](https://img.shields.io/github/languages/top/glennular/i3help) ![stars](https://img.shields.io/github/stars/glennular/i3help?style=flat)


## Libraries for Building Tools
Libraries using IPC to interact with i3 (sometimes compatible with sway)

- [go-i3](https://github.com/i3/go-i3): Go library (official)
- [i3ips-glib](https://github.com/altdesktop/i3ipc-glib): C interface library
  ![language](https://img.shields.io/github/languages/top/altdesktop/i3ipc-glib) ![stars](https://img.shields.io/github/stars/altdesktop/i3ipc-glib?style=flat)
- [i3ipc-python](https://github.com/altdesktop/i3ipc-python): Python library for
  i3/sway
  ![language](https://img.shields.io/github/languages/top/altdesktop/i3ipc-python) ![stars](https://img.shields.io/github/stars/altdesktop/i3ipc-python?style=flat)
- [node-i3](https://github.com/sidorares/node-i3): node.js library
  ![language](https://img.shields.io/github/languages/top/sidorares/node-i3) ![stars](https://img.shields.io/github/stars/sidorares/node-i3?style=flat)
- [i3ipc-rs](https://github.com/tmerr/i3ipc-rs): Rust library
  ![language](https://img.shields.io/github/languages/top/tmerr/i3ipc-rs) ![stars](https://img.shields.io/github/stars/tmerr/i3ipc-rs?style=flat)


## Launchers and Switchers
Not i3/sway specific but useful

- [dmenu](https://git.suckless.org/dmenu): menu to launch applications and more
- [rofi](https://github.com/davatorium/rofi): window switcher, application
  launcher, dmenu replacement
  ![language](https://img.shields.io/github/languages/top/davatorium/rofi) ![stars](https://img.shields.io/github/stars/davatorium/rofi?style=flat)
- [i3-dmenu-desktop](https://github.com/i3/i3/blob/next/i3-dmenu-desktop): run
  .desktop files with dmenu
- [j4-dmenu-desktop](https://github.com/enkore/j4-dmenu-desktop): aims to be
  faster than i3-dmenu-desktop
  ![language](https://img.shields.io/github/languages/top/enkore/j4-dmenu-desktop) ![stars](https://img.shields.io/github/stars/enkore/j4-dmenu-desktop?style=flat)
- [raiseorlaunch](https://github.com/open-dynaMIX/raiseorlaunch):
  run-or-raise-application launcher
  ![language](https://img.shields.io/github/languages/top/open-dynaMIX/raiseorlaunch) ![stars](https://img.shields.io/github/stars/open-dynaMIX/raiseorlaunch?style=flat)
- [i3menu](https://github.com/giacomos/i3menu): Based on rofi and dmenu
  ![language](https://img.shields.io/github/languages/top/giacomos/i3menu) ![stars](https://img.shields.io/github/stars/giacomos/i3menu?style=flat)
- [i3-individual-workspace-actions](https://github.com/realestninja/i3-individual-workspace-actions):
  Use same keybinding for different actions depending on active workspace
  ![language](https://img.shields.io/github/languages/top/realestninja/i3-individual-workspace-actions) ![stars](https://img.shields.io/github/stars/realestninja/i3-individual-workspace-actions?style=flat)


## Programs to use with i3
Programs that only lightly interact with i3

- [picom](https://github.com/yshui/picom): lightweight X11 compositor to enable
  transparency, shadows, animation, blur, etc
  ![language](https://img.shields.io/github/languages/top/yshui/picom) ![stars](https://img.shields.io/github/stars/yshui/picom?style=flat)
- `xprop`: show attributes of window for example class to write window rules
- [i3-volume](https://github.com/hastinbe/i3-volume): volume control with
  on-screen display notification


## Configuration Examples
Repositories with example configurations. You should not just copy everything
from them. Look at them as a reference and inspiration to make your own
configuration.

- [i3wm-configuration](https://github.com/vincentbernat/i3wm-configuration):
  With accompanying [blog post](https://vincent.bernat.ch/en/blog/2021-i3-window-manager)
- [dotfiles from Fabian Untermoser](https://gitlab.com/FabianUntermoser/dot-files/-/tree/master/i3): i3 dotfiles and scripts
