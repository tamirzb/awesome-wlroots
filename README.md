# Awesome wlroots

A list of tools and compositors around [wlroots](https://github.com/swaywm/wlroots). 

wlroots is a compositor library and defines a large and diverse ecosystem around [wlr-protocols](https://github.com/swaywm/wlr-protocols). 

This list is dedicated to cool stuff/useful tools for wlroots desktops. For general cool stuff and applications on Wayland check out [awesome-wayland](https://github.com/natpen/awesome-wayland). 

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

  - [Brightness Control](#brightness-control)
  - [Clipboard Managers](#clipboard-managers)
  - [Compositors](#compositors)
  - [Configurations](#configurations)
  - [Display Configuration](#display-configuration)
  - [Docks](#docks)
  - [Keyboards](#keyboards)
  - [Launchers](#launchers)
  - [Miscellaneous](#miscellaneous)
  - [Notifications](#notifications)
  - [Remote control](#remote-control)
  - [Screen Locking](#screen-locking)
  - [Screencasting](#screencasting)
  - [Tools](#tools)
  - [Wallpaper](#wallpaper)
  - [License](#license)

## Brightness Control

No Wayland-specific requirements, so you can use your xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl), [brillo](https://gitlab.com/cameronnemo/brillo), [light](https://github.com/haikarainen/light), or just directly manipulate `/sys/class/backlight`.

wlroots supports gamma setting through `wlr-gamma-control-unstable-v1`. 

* [gammastep](https://gitlab.com/chinstrap/gammastep) - Tints the display orange to reduce stress on the eyes (Redshift fork with wlroots compatibility patch)
* [wluma](https://github.com/maximbaz/wluma) - Automatically adjusts screen brightness based on the screen contents and amount of ambient light
* [wl-gammactl](https://github.com/mischw/wl-gammactl) - Control brightness, contrast and gamma
* [wlr-brightness](https://github.com/mherzberg/wlr-brightness) - A dbus-controllable overlay to darken your screen
* [Wlsunset](https://sr.ht/~kennylevinsen/wlsunset/) - Day/night gamma adjustments for Wayland compositors supporting wlr-gamma-control-unstable-v1.

## Clipboard Managers

* [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command-line copy/paste utilities for Wayland
* [clipman](https://github.com/yory8/clipman) - A simple clipboard manager for Wayland

## Compositors

* [Cagebreak](https://github.com/project-repo/cagebreak) - A Wayland tiling compositor inspired by Ratpoison
* [Cardboard](https://gitlab.com/cardboardwm/cardboard) - A scrollable tiling Wayland compositor
* [dwl](https://github.com/djpohly/dwl) - dwm for Wayland
* [epd-wm](https://github.com/dj311/epd-wm) - Wayland window manager that outputs to IT8951 E-Paper displays. 
* [hikari](https://hikari.acmelabs.space/) - A hybrid stacking/tiling Wayland compositor
* [Hopalong](https://github.com/iridescent-desktop/hopalong) - Simple Wayland compositor with a featureset comparable to XFWM
* [Hyprland](https://github.com/hyprwm/Hyprland) - A dynamic tiling Wayland compositor that doesn't sacrifice on its looks
* [kiwmi](https://github.com/buffet/kiwmi) -  A fully programmable Wayland Compositor 
* [labwc](https://github.com/johanmalm/labwc) - A stacking Wayland compositor with look and feel of openbox
* [laikawm](https://github.com/ianmartinez/laikawm) - A stacking Wayland compositor with look and feel of openbox
* [phoc](https://source.puri.sm/Librem5/phoc) - Wayland compositor for mobile phones like the Librem 5 (designed to work with [phosh](https://source.puri.sm/Librem5/phosh))
* [river](https://github.com/ifreund/river) - A dynamic tiling Wayland compositor
* [Sway](https://github.com/swaywm/sway) - i3-compatible Wayland compositor
* [tinybox](https://github.com/icedman/tinybox) - tries to emulate the blackbox, fluxbox, openbox family of wm
* [Waybox](https://github.com/wizbright/waybox) - An openbox clone on Wayland
* [Wayfire](https://github.com/WayfireWM/wayfire) - 3D Wayland compositor
* [wio](https://git.sr.ht/~sircmpwn/wio) - Wayland compositor similar to plan9's rio

## Configurations

* [sway-gnome](https://github.com/Drakulix/sway-gnome) - Allows you to use Sway with GNOME 3 Session infrastructure


## Display Configuration

* [Kanshi](https://github.com/emersion/kanshi) - Dynamic display configuration
* [qkdisplays](https://github.com/tamirzb/qkdisplays) -  A helper tool for quickly configuring a multi-monitor setup, built with tiled window managers in mind
* [Wallutils](https://github.com/xyproto/wallutils) - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers
* [wdisplays](https://github.com/cyclopsian/wdisplays) - GUI display configurator for wlroots compositors
* [wlay](https://github.com/atx/wlay) - Graphical output management for Wayland
* [wlr-randr](https://github.com/emersion/wlr-randr) - An xrandr clone for wlroots compositors

## Docks

[Cairo Dock (wayland_egl)](https://github.com/dkondor/cairo-dock-core/tree/wayland_egl) - Early port of the feature rich Cairo. Core features work.  
wf-dock (part of [wf-shell](https://github.com/WayfireWM/wf-shell)) - Very simple dock for application switching (no launching)




## Keyboards

* [squeekboard](https://source.puri.sm/Librem5/squeekboard) - The Librem5 keyboard
* [wf-osk](https://github.com/WayfireWM/wf-osk) - A very, very basic on-screen keyboard using gtkmm, virtual-keyboard-v1 and layer-shell protocols
* [wvkbd](https://github.com/jjsullivan5196/wvkbd) - A "suckless" on screen keyboard

## Launchers

* [bemenu](https://github.com/Cloudef/bemenu) - Dynamic menu library and client program inspired by dmenu
* [dmenu-wayland](https://github.com/nyyManni/dmenu-wayland) - dmenu-wl is an efficient dynamic menu for wayland (wlroots)
* [fuzzel](https://codeberg.org/dnkl/fuzzel) - Wayland-native application launcher, similar to rofi’s drun mode
* [Kickoff](https://github.com/j0ru/kickoff) -  Simple and uncomplicated program launcher heavily inspired by rofi
* [LavaLauncher](https://git.sr.ht/~leon_plickat/lavalauncher) - A simple launcher panel for Wayland desktops
* [Mauncher](https://github.com/mortie/mauncher) - A GTK-based alternative to dmenu for Wayland which supports display scaling
* [nwg-launchers](https://github.com/nwg-piotr/nwg-launchers) - A GTK-based application grid launcher, button bar and dmenu for Wayland
* [sirula](https://github.com/DorianRudolph/sirula) - Simple app launcher for Wayland written in Rust
* [wldash](https://github.com/kennylevinsen/wldash) - Wayland dashboard and launcher written in Rust
* [Wofi](https://hg.sr.ht/~scoopta/wofi) - A launcher/menu program for wlroots based Wayland compositors such as sway
* [yofi](https://github.com/l4l/yofi) - Minimalistic menu

## Miscellaneous

* [wl-color-picker](https://github.com/jgmdev/wl-color-picker) - Script providing a working color picker using grim and slurp
* [wob](https://github.com/francma/wob/) - Light-weight overlay volume/backlight/progress/anything bar

## Notifications

* [Mako](https://github.com/emersion/mako) - A lightweight Wayland notification daemon

## Remote control

* [waynergy](https://github.com/r-c-f/waynergy) - An implementation of a synergy client for wlroots compositors ("not ready for primetime")
* [wayvnc](https://github.com/any1/wayvnc) - A VNC server for wlroots based compositors

## Screen Locking

* [shaderlock](https://github.com/Xenopathic/shaderlock) - Screen locker with GPU shaders
* [swayidle](https://github.com/swaywm/swayidle) - Idle management daemon for Wayland
* [swaylock](https://github.com/swaywm/swaylock) - Screen locker for Wayland
* [swaylock-effects](https://github.com/mortie/swaylock-effects) - A fork of swaylock with effects such as a blurred screenshot as background or a clock on the lockscreen
* [waylock](https://github.com/ifreund/waylock) - A simple screenlocker for Wayland compositors

## Screencasting

* [ssr-wlroots](https://github.com/foxcpp/ssr-wlroots) - A version of SimpleScreenRecorder with support for `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`). Doesn't support recording area selection and has issues with multiple screens. 
* [wf-recorder](https://github.com/ammen99/wf-recorder) - A utility program for screen recording of `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`)
* [wlrobs](https://hg.sr.ht/~scoopta/wlrobs) - An obs-studio plugin that allows you to screen capture on wlroots based wayland compositors
* [wshowkeys](https://git.sr.ht/~sircmpwn/wshowkeys) - Displays keys being pressed on a Wayland session
* [xdg-desktop-portal-wlr](https://github.com/emersion/xdg-desktop-portal-wlr) - Share your screen through Pipewire

## Screenshots

* [Grim](https://github.com/emersion/grim) - Grab images from a Wayland compositor
* [Slurp](https://github.com/emersion/slurp) - Select a region in a Wayland compositor
* [Swappy](https://github.com/jtheoof/swappy) - A Wayland-native snapshot editing tool, inspired by Snappy on macOS
* [Taiga](https://hg.sr.ht/~scoopta/taiga) - Animated screenshot program


## Session Management

* [wlogout](https://github.com/ArtsyMacaw/wlogout) - A Wayland-based logout menu

## Status Bars

* [i3status-rust](https://github.com/greshake/i3status-rust) - Very resource-friendly and feature-rich replacement for i3status, written in pure Rust
* [rootbar](https://hg.sr.ht/~scoopta/rootbar) - Root Bar is a bar for wlroots based Wayland compositors such as sway
* [Wapanel](https://github.com/Firstbober/wapanel) - Simple panel for Wayland with decent XFCE-like applets
* [waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors
* wf-panel (part of [wf-shell](https://github.com/WayfireWM/wf-shell)) - Panel with support for application launchers
* [YaGoStatus](https://github.com/denysvitali/yagostatus) - Yet Another i3status replacement
* [yambar](https://gitlab.com/dnkl/yambar) - Modular status panel for X11 and Wayland, inspired by polybar

## Tools

* [wtype](https://github.com/atx/wtype) - A Wayland tool that allows you to simulate keyboard input like [xdotool](https://github.com/jordansissel/xdotool)
* [ydotool](https://github.com/ReimuNotMoe/ydotool) - A generic Linux command-line automation tool for Wayland

## Wallpaper

* [Azote](https://github.com/nwg-piotr/azote) - Picture browser and background setter frontend to swaybg 
* [oguri](https://github.com/vilhalmer/oguri) - A very nice animated wallpaper daemon for Wayland compositors
* [mpvpaper](https://github.com/GhostNaN/mpvpaper) - A video wallpaper program for wlroots based wayland compositors
* [swaybg](https://github.com/swaywm/swaybg) - A wallpaper utility for Wayland compositors
* [wbg](https://codeberg.org/dnkl/wbg) - Super simple wallpaper application for Wayland compositors implementing the layer-shell protocol
* wf-background (part of [wf-shell](https://github.com/WayfireWM/wf-shell)) - Simple wallpaper program supporting switching of images

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
