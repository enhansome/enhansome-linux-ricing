# Awesome linux ricing with stars

<br/>
<div align='center'>
  <img src='media/awesome_tux.png'>
  <h1>Awesome Linux Ricing</h1>
  <h4>Carefully curated list of awesome Linux customization resources</h4>
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome Badage"></a>
</div>
<br/>
<p align="center">
	<a href="CONTRIBUTING.md">Contribution</a>&nbsp;&nbsp;•&nbsp;
	<a href="code_of_conduct.md">Code of Conduct</a>&nbsp;&nbsp;•&nbsp;
	<a href="LICENSE">License</a>
</p>
<br/>

## Description

This very **AWESOME** list is made to help anyone interested in extensively customizing their Linux desktop, or what we call 'ricing'. It's a very good place to start your adventure, helping you discover what you can use, or what **ELSE** you can use to over-customize your rice. The goal is to have some of the very popular themes and tools, as well as some lesser-known ones, to help you find that perfect fit. It's your go-to list when you need to waste your time ricing, instead of tending to your responsibilities.

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Window Manager](#window-manager)
  * [Stacking](#stacking)
  * [Tiling](#tiling)
  * [Dynamic](#dynamic)
* [Color Scheme](#color-scheme)
  * [Utilities](#utilities)
* [Wallpapers](#wallpapers)
  * [Utilities](#utilities-1)
* [Font](#font)
  * [Sans Fonts](#sans-fonts)
  * [Monospace Fonts](#monospace-fonts)
  * [Nerd Fonts](#nerd-fonts)
* [Bar](#bar)
* [Cursor](#cursor)
  * [Utilities](#utilities-2)
* [Icons](#icons)
* [Application Launcher](#application-launcher)
* [Notifications Daemon](#notifications-daemon)
* [Widgets](#widgets)
* [Logout Menu](#logout-menu)
* [Screen Lock](#screen-lock)
* [Terminal](#terminal)
  * [Emulator](#emulator)
  * [Shell](#shell)
  * [Prompt](#prompt)
  * [Multiplexer](#multiplexer)
  * [Tools](#tools)
    * [File Manager](#file-manager)
    * [Editor](#editor)
    * [Image Printing](#image-printing)
    * [Music Players](#music-players)
    * [System Monitoring](#system-monitoring)
    * [Mail Client](#mail-client)
    * [Screenshot](#screenshot)
    * [Recording](#recording)
    * [Directory Listing](#directory-listing)
    * [Misc](#misc)
  * [Fancies](#fancies)
    * [Fetch](#fetch)
    * [Terminal Visuals](#terminal-visuals)
    * [Clock](#clock)
    * [Audio Visualizer](#audio-visualizer)
    * [Matrix](#matrix)
    * [Character Play](#character-play)
    * [Pokemon-Themed](#pokemon-themed)
    * [Text and Fonts](#text-and-fonts)
* [GUI Apps](#gui-apps)
  * [Web Browser](#web-browser)
  * [File Manager](#file-manager-1)
  * [Image Viewer](#image-viewer)
  * [Music Player](#music-player)
  * [Video Streamer](#video-streamer)
  * [Document Reader](#document-reader)
  * [Text Editor](#text-editor)
  * [Archive Manager](#archive-manager)
  * [Email](#email)
  * [Calculator](#calculator)
  * [Notes](#notes)
  * [Workstation - Content Creation](#workstation---content-creation)
    * [Image Editing](#image-editing)
    * [Video Editing](#video-editing)
    * [Music Production](#music-production)
    * [3D](#3d)
    * [Office](#office)
    * [Screen Recording / Live Streaming](#screen-recording--live-streaming)
  * [Gaming](#gaming)
* [GUI Apps Ricing](#gui-apps-ricing)
  * [Firefox](#firefox)
    * [Theme](#theme)
    * [Startpage](#startpage)
  * [Spotify](#spotify)
  * [Discord](#discord)
  * [VSCode](#vscode)
* [Display Manager](#display-manager)
* [GRUB](#grub)
* [Installation and Configuration](#installation-and-configuration)
* [Contribution](#contribution)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

***

## Window Manager

<details>
  <summary><b>Window Manager (WM) vs Desktop Environment (DE)</b></summary>
  <p>A <b>WM</b> is a software that manages the windows on your screen. It controls the placement and appearance of windows, and provides basic functionality like window resizing and moving.</p>
  <p>A <b>DE</b> is a collection of software that provides a complete desktop experience. It includes the <b>window manager</b>, along with a file manager, a bar/panel, and other apps, tools and utilities.</p>
  <p><b>DEs</b> usually provide a more integrated and user-friendly experience, while <b>WMs</b> are more lightweight and customizable, requiring you to manually configure and install additional software to get the same functionality as a <b>DE</b>, but with more control over the look and feel of your desktop.</p>
</details>
<br/>
<details>
  <summary><b>Stacking vs Tiling vs Dynamic WMs</b></summary>
  <ul>
    <li><b>Stacking WMs</b> are traditional window managers that place windows on top of each other (like MS Windows). They allow you to move and resize windows freely, but they can be cluttered and hard to manage with many windows open.</li>
    <li><b>Tiling WMs</b> automatically arrange windows in a non-overlapping layout. They are efficient and help you make the most of your screen space, but they can be less flexible than stacking WMs.</li>
    <li><b>Dynamic WMs</b> combine the best of both worlds. They allow you to switch between tiling and stacking layouts, giving you the flexibility to choose the best layout for your workflow.</li>
  </ul>
</details>
<br/>
<details>
  <summary><b>X11 vs Wayland</b></summary>
  <p><b>X11</b> is the traditional display server protocol used in Linux. It is mature and stable, but it has some limitations in terms of security and performance.</p>
  <p><b>Wayland</b> is a newer display server protocol that aims to address the limitations of <b>X11</b>. It is more secure and efficient, allowing for better performance, smoother animations, touch gestures, etc. However, it is still under development, and usually Nvidia GPUs have issues with it.</p>
  <p>All applications with a GUI (as well as WMs) are run under a display server and are usually developed for a specific display server protocol, meaning you can't run a <b>Wayland</b> app on <b>X11</b>, or vice versa. However, it is possible to use a compatibility layer like XWayland to run <b>X11</b> apps on <b>Wayland</b>.</p>
</details>
<br/>

### Stacking

* [GNOME](https://gitlab.gnome.org/GNOME)<sup>X11 + Wayland</sup> - Modern desktop environment that aims to be simple and easy to use.
* [KDE](https://kde.org/)<sup>X11 + Wayland</sup> - Feature-rich and versatile desktop environment.
* [XFCE](https://www.xfce.org/)<sup>X11</sup> - Lightweight desktop environment. It aims to be fast and low on system resources, while still being visually appealing and user-friendly.
* [Openbox](http://openbox.org/)<sup>X11</sup> - Highly configurable next generation window manager with extensive standards support.

### Tiling

* [sway](https://github.com/swaywm/sway) ⭐ 17,251 | 🐛 1,378 | 🌐 C | 📅 2026-07-31<sup>Wayland</sup> - Tiling Wayland compositor and a drop-in replacement for the i3 window manager for X11.
* [i3](https://github.com/i3/i3) ⭐ 10,545 | 🐛 375 | 🌐 C | 📅 2026-07-28<sup>X11</sup> - Tiling window manager for X11.
* [bspwm](https://github.com/baskerville/bspwm) ⭐ 8,305 | 🐛 348 | 🌐 C | 📅 2026-06-19<sup>X11</sup> - Tiling window manager that represents windows as the leaves of a full binary tree.
* [leftwm](https://github.com/leftwm/leftwm) ⭐ 3,045 | 🐛 114 | 🌐 Rust | 📅 2026-07-21<sup>X11</sup> - Tiling window manager written in Rust for advanced.
* [herbstluftwm](https://github.com/herbstluftwm/herbstluftwm) ⭐ 1,163 | 🐛 130 | 🌐 C++ | 📅 2026-07-02<sup>X11</sup> - Manual tiling window manager for X.

### Dynamic

* [Ηyprland](https://github.com/hyprwm/Hyprland) ⭐ 37,950 | 🐛 187 | 🌐 C++ | 📅 2026-08-19<sup>Wayland</sup> - Highly customizable dynamic tiling Wayland compositor that doesn't sacrifice on its looks.
* [niri](https://github.com/YaLTeR/niri) ⭐ 27,007 | 🐛 479 | 🌐 Rust | 📅 2026-08-19<sup>Wayland</sup> - Scrollable-tiling Wayland compositor, heavily inspired by PaperWM.
* [awesome](https://github.com/awesomeWM/awesome) ⭐ 6,944 | 🐛 572 | 🌐 Lua | 📅 2026-07-26<sup>X11</sup> - Highly configurable, next generation framework window manager for X.
* [QTile](https://github.com/qtile/qtile) ⭐ 5,288 | 🐛 198 | 🌐 Python | 📅 2026-08-19<sup>X11 + Wayland</sup> - Full-featured, hackable tiling window manager.
* [river](https://github.com/riverwm/river) ⭐ 4,248 | 🐛 67 | 🌐 Zig | 📅 2026-08-16<sup>Wayland</sup> - Dynamic tiling Wayland compositor with flexible runtime configuration.
* [XMonad](https://github.com/xmonad/xmonad) ⭐ 3,582 | 🐛 61 | 🌐 Haskell | 📅 2026-06-28<sup>X11</sup> - Small but functional ICCCM-compliant tiling window manager.
* [MangoWC](https://github.com/DreamMaoMao/mangowc) ⭐ 3,484 | 🐛 214 | 🌐 C | 📅 2026-08-18<sup>Wayland</sup> - Modern, lightweight, high-performance Wayland compositor built on dwl.
* [ragnar](https://github.com/cococry/ragnar) ⭐ 1,245 | 🐛 19 | 🌐 C | 📅 2026-07-31<sup>X11</sup> - Minimal, flexible & user-friendly X tiling window manager.
* [dwm](https://dwm.suckless.org/)<sup>X11</sup> - Dynamic window manager for X. It manages windows in tiled, monocle and floating layouts.

## Color Scheme

<details>
  <summary><b>What are color schemes</b></summary>
  Color schemes in ricing are a set of carefully selected colors used to create a theme. You can pick and use a specific theme you like to customize the colors of all your configurable apps (i.e WM, bar, terminal, browser, etc...), in order to achieve a consistent look and feel across your desktop.
</details>
<br/>

* [Dracula](https://github.com/dracula/dracula-theme) ⭐ 23,562 | 🐛 3 | 📅 2026-08-13 - Dark spooky theme.
* [Catppuccin](https://github.com/catppuccin/catppuccin) ⭐ 19,660 | 🐛 117 | 🌐 TypeScript | 📅 2026-07-25 - Soothing pastel theme for the high-spirited.
* [Gruvbox](https://github.com/morhetz/gruvbox) ⭐ 15,690 | 🐛 159 | 🌐 Vim Script | 📅 2026-06-08 - Retro groove color scheme.
* [Nord](https://github.com/nordtheme/nord) ⭐ 6,865 | 🐛 84 | 🌐 SCSS | 📅 2023-10-18 - Arctic, north-bluish color palette.
* [Kanagawa](https://github.com/rebelot/kanagawa.nvim) ⭐ 6,344 | 🐛 90 | 🌐 Lua | 📅 2026-05-10 - Dark color scheme inspired by the famous painting.
* [Everforest](https://github.com/sainnhe/everforest) ⭐ 4,173 | 🐛 6 | 🌐 Vim Script | 📅 2026-06-08 - Comfortable and pleasant green forest color scheme.
* [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme#other-ports) ⭐ 2,406 | 🐛 16 | 📅 2025-02-05 - Clean, dark theme that celebrates the lights of Tokyo at night.
* [Sweet](https://github.com/EliverLara/Sweet) ⭐ 1,701 | 🐛 79 | 🌐 CSS | 📅 2026-08-13 - Colorful candy theme.
* [Rosé Pine](https://github.com/rose-pine/rose-pine-theme) ⭐ 1,606 | 🐛 5 | 📅 2026-07-05 - All natural pine, faux fur and a bit of soho vibes for the classy minimalist.
* [Everblush](https://github.com/Everblush/everblush) ⭐ 161 | 🐛 0 | 📅 2025-05-10 - Dark, vibrant and beautiful Colorscheme.
* [BlackLotus](https://github.com/PoisonIsBestType/BlackLotus) ⭐ 80 | 🐛 0 | 🌐 Lua | 📅 2023-10-19 - Dark, dim, blue, purple... beautiful.
* [Whale](https://github.com/anufrievroman/whale) ⭐ 72 | 🐛 0 | 🌐 CSS | 📅 2025-10-02 - Dark theme inspired by Ark and Nord.
* [opulo](https://github.com/kewmine/opulo) ⭐ 49 | 🐛 0 | 🌐 Shell | 📅 2023-10-24 - Colorscheme for absolute nerds.
* [Shades of purple](https://github.com/EliverLara/Shades-of-purple-gtk) ⭐ 28 | 🐛 4 | 🌐 CSS | 📅 2026-03-20 - Sweet purple theme.
* [camellia](https://github.com/camellia-theme/camellia) ⭐ 25 | 🐛 1 | 📅 2025-02-05 - Dark yet vibrant color scheme.

### Utilities

* [pywall](https://github.com/dylanaraps/pywal) ⚠️ Archived - Generate and change color-schemes according to your wallpaper.
* [wpgtk](https://github.com/deviantfero/wpgtk) ⭐ 2,197 | 🐛 22 | 🌐 Python | 📅 2026-08-03 - Colorscheme, wallpaper and template manager.
* [Gtheme](https://github.com/daavidrgz/gtheme) ⭐ 24 | 🐛 3 | 🌐 Rust | 📅 2026-08-17 - Command-line theme manager. Apply consistent themes across your terminal, editor, status bar, wallpaper, and WM with one command. 350+ themes, Rust.
* [Paletty](https://paletty.dev) - Terminal color scheme generator and theme gallery. Generate from scratch, extract from image, or browse community themes. Exports to Ghostty, Alacritty, Kitty, WezTerm, iTerm2, and more.

## Wallpapers

Some great GitHub repos with wallpaper collections by:

* [dharmx](https://github.com/dharmx/walls) ⭐ 8,534 | 🐛 5 | 📅 2024-03-06
* [D3Ext](https://github.com/D3Ext/aesthetic-wallpapers) ⭐ 3,438 | 🐛 10 | 📅 2025-06-17
* [linuxdotexe](https://github.com/linuxdotexe/nordic-wallpapers) ⭐ 1,846 | 🐛 2 | 🌐 Python | 📅 2025-12-31<sup>Nord</sup>
* [AngelJumbo](https://github.com/AngelJumbo/gruvbox-wallpapers) ⭐ 1,200 | 🐛 0 | 🌐 Shell | 📅 2026-07-20<sup>Gruvbox</sup>
* [zhichaoh](https://github.com/zhichaoh/catppuccin-wallpapers) ⭐ 887 | 🐛 0 | 📅 2024-04-17<sup>Catppuccin</sup>
* [FrenzyExists](https://github.com/FrenzyExists/wallpapers) ⭐ 773 | 🐛 0 | 🌐 Shell | 📅 2022-12-02
* [Apeiros-46B](https://github.com/Apeiros-46B/everforest-walls) ⚠️ Archived<sup>Everforest</sup>
* [Axenide](https://github.com/Axenide/Wallpapers) ⭐ 162 | 🐛 0 | 📅 2025-12-09
* [er2de2](https://github.com/er2de2/catppuccin_walls) ⭐ 97 | 🐛 2 | 📅 2026-04-12<sup>Catppuccin</sup>
* [gboncoffee](https://github.com/gboncoffee/wallpapers) ⭐ 96 | 🐛 0 | 📅 2026-01-09
* [zDyanTB](https://github.com/zDyanTB/aesthetic-wallpapers) ⭐ 96 | 🐛 0 | 📅 2024-08-23
* [vctrblck](https://github.com/vctrblck/gruvbox-wallpapers) ⭐ 35 | 🐛 0 | 📅 2022-01-22<sup>Gruvbox</sup>
* [jorgeloopzz](https://codeberg.org/jorgeloopzz/Wallpapers)

### Utilities

* [mpvpaper](https://github.com/GhostNaN/mpvpaper) ⭐ 1,571 | 🐛 16 | 🌐 C | 📅 2026-07-25<sup>Wayland</sup> - Video wallpaper program for wlroots based wayland compositors.
* [hyprpaper](https://github.com/hyprwm/hyprpaper) ⭐ 1,345 | 🐛 50 | 🌐 C++ | 📅 2026-08-13<sup>Wayland</sup> - Fast Wayland wallpaper utility with IPC controls.
* [swaybg](https://github.com/swaywm/swaybg) ⭐ 811 | 🐛 14 | 🌐 C | 📅 2026-05-25<sup>Wayland</sup> - Wallpaper tool for Wayland compositors
* [awww](https://codeberg.org/LGFae/awww)<sup>Wayland</sup> - Efficient animated wallpaper daemon for wayland, controlled at runtime.

## Font

<details>
  <summary><b>Sans vs Serif vs Mono</b></summary>
  <ul>
    <li><b>Serif</b> fonts have decorative lines or strokes at the ends of the letters. They are often used for body text in printed materials.</li>
    <li><b>Sans-serif</b> fonts are modern and clean, without the decorative flourishes of serif fonts. They are often used for headings and titles.</li>
    <li><b>Monospace</b> fonts have equal spacing between characters, making them ideal for coding, editors and terminals.</li>
  </ul>
    <p><b>Sans</b> and <b>Mono</b> are the ones usually used for ricing, as they are more readable and modern.</p>
</details>
<br/>

<details>
  <summary><b>What are ligatures</b></summary>
  <p><b>Ligatures</b> are special characters that combine two or more letters into a single glyph. They are used to improve the appearance and readability of text, especially in code and terminal applications.</p>
  <p>Example:</p>
  <img src="media/ligatures.svg" height=240>
</details>
<br/>

### Sans Fonts

* [Google Sans](https://font.download/font/google-sans)<sup>ligatures</sup> - Google's custom and versatile sans-serif font.
* [Open Sans](https://fonts.google.com/specimen/Open+Sans) - The peace and love issue.
* [Roboto](https://fonts.google.com/specimen/Roboto) - The Android font.
* [Ubuntu](https://fonts.google.com/specimen/Ubuntu) - The Ubuntu font.
* [DejaVu](https://github.com/dejavu-fonts/dejavu-fonts) ⭐ 935 | 🐛 67 | 🌐 Perl | 📅 2024-05-15 - Font family based on Bitstream Vera.

### Monospace Fonts

* [FiraCode](https://github.com/tonsky/FiraCode) ⭐ 81,933 | 🐛 428 | 🌐 Clojure | 📅 2026-07-28<sup>ligatures</sup> - Monospaced font with programming ligatures.
* [Cascadia Code](https://github.com/microsoft/cascadia-code) ⭐ 27,855 | 🐛 161 | 🌐 Python | 📅 2025-03-06<sup>ligatures</sup> - Fun font designed to enchance the modern look and feel of the \*\*\* Terminal.
* [Iosevka](https://github.com/be5invis/Iosevka) ⭐ 22,636 | 🐛 104 | 🌐 JavaScript | 📅 2026-08-18<sup>ligatures</sup> - Versatile typeface for code, from code.
* [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono) ⭐ 12,977 | 🐛 204 | 🌐 Shell | 📅 2025-01-31<sup>ligatures</sup> - Τypeface made for developers.
* [monoid](https://github.com/larsenwork/monoid) ⭐ 7,958 | 🐛 77 | 🌐 Python | 📅 2020-10-26<sup>ligatures</sup> - Customisable coding font with alternates, ligatures and contextual positioning.
* [Hasklig](https://github.com/i-tu/Hasklig) ⭐ 5,717 | 🐛 44 | 🌐 Python | 📅 2022-02-19<sup>ligatures</sup> - Code font with monospaced ligatures.
* [Victor Mono](https://github.com/rubjo/victor-mono) ⭐ 3,789 | 🐛 7 | 🌐 Vue | 📅 2026-07-18<sup>ligatures</sup> - Free programming font with cursive italics and ligatures.
* [DejaVuCode](https://github.com/SSNikolaevich/DejaVuSansCode) ⭐ 482 | 🐛 10 | 🌐 Perl | 📅 2019-05-06<sup>ligatures</sup> - Monospaced font with programming ligatures based on DejaVu Sans Mono.
* [Gohufont](https://github.com/hchargois/gohufont) ⭐ 396 | 🐛 7 | 🌐 Python | 📅 2017-06-26 - Monospace bitmap font.
* [Operator-caska](https://github.com/Anant-mishra1729/Operator-caska-Font)<sup>ligatures</sup> - Font with ligature and cursive support, combination of both CaskaydiaCove Nerd Font and Operator Mono.

### Nerd Fonts

<details>
  <summary><b>What are the Nerd Fonts</b></summary>
    <p><b>Nerd Fonts</b> are patched fonts that contain additional glyphs, icons, and ligatures. These fonts are designed to be used in terminals and code editors, providing a more visually appealing and functional experience. <b>Nerd Fonts</b> are compatible with most of the font families.</p>
</details>
<br/>

* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) ⭐ 64,302 | 🐛 18 | 🌐 CSS | 📅 2026-08-10 - Collection of nerd fonts.
* [font-patcher](https://github.com/ryanoasis/nerd-fonts?tab=readme-ov-file#font-patcher) ⭐ 64,302 | 🐛 18 | 🌐 CSS | 📅 2026-08-10 - Patch your own fonts.
* [getnf](https://github.com/getnf/getnf) ⭐ 1,256 | 🐛 1 | 🌐 Shell | 📅 2026-06-19 - Helpful tool to install Nerd Fonts.

> \[!TIP]
> In order to make use of glyphs, you should at least have one nerd font installed on your system. Setting your default font as a nerd font is usually not required, as it may show glyphs smaller than they are supposed to be. However, you may need to include a nerd font family along with your default font, when configuring fonts for an application, in order to display the glyphs properly.

## Bar

<details>
  <summary><b>What is a bar</b></summary>
  <p>A <b>bar</b> is a graphical element usually used to display a variety of information, like the time, date, battery, volume, etc, like the "Task Bar" in Windows and the "Menu Bar" in MacOS. It is usually placed at the top or bottom of the screen, and can be customized in any style.</p>
</details>
<br/>

* [Polybar](https://github.com/polybar/polybar) ⭐ 15,334 | 🐛 232 | 🌐 C++ | 📅 2025-09-24<sup>X11</sup> - Fast and easy-to-use status bar.
* [Eww](https://github.com/elkowar/eww) ⭐ 12,616 | 🐛 378 | 🌐 Rust | 📅 2026-07-17<sup>X11 + Wayland</sup> - ElKowars wacky widgets.
* [Waybar](https://github.com/Alexays/Waybar) ⭐ 11,819 | 🐛 712 | 🌐 C++ | 📅 2026-08-14<sup>Wayland</sup> - Highly customizable Wayland bar.
* [ags](https://github.com/Aylur/ags) ⭐ 3,077 | 🐛 30 | 🌐 TypeScript | 📅 2026-04-08<sup>X11 + Wayland</sup> - Very customizable and extensible shell.
* [lemonbar](https://github.com/LemonBoy/bar) ⭐ 1,689 | 🐛 22 | 🌐 C | 📅 2024-09-02<sup>X11</sup> - Featherweight, lemon-scented, bar based on xcb.
* [fabric](https://github.com/Fabric-Development/fabric/) ⭐ 1,355 | 🐛 11 | 🌐 Python | 📅 2026-08-19<sup>X11 + Wayland</sup> - Next-gen framework for building desktop widgets using Python.
* [gBar](https://github.com/scorpion-26/gBar) ⭐ 538 | 🐛 38 | 🌐 C++ | 📅 2024-12-17<sup>Wayland</sup> - Blazingly fast status bar written with GTK.
* [Quickshell](https://quickshell.org/)<sup>X11 + Wayland</sup> - Toolkit for building status bars, widgets, lockscreens, and other desktop components using QtQuick.

> \[!NOTE]
> Some of these tools can also be used to create widgets and other UI elements, not just bars.

## Cursor

* [Bibata](https://github.com/ful1e5/Bibata_Cursor) ⭐ 3,935 | 🐛 18 | 🌐 Shell | 📅 2024-06-18 - Open source, compact, and material designed cursor set.
* [Apple](https://github.com/ful1e5/apple_cursor) ⭐ 2,009 | 🐛 20 | 🌐 Shell | 📅 2024-09-28 - Cursor inspired by Apple's macOS.
* [Qogir](https://github.com/vinceliuice/Qogir-icon-theme) ⭐ 931 | 🐛 48 | 🌐 Shell | 📅 2025-11-04 - Cursor inspired by Qogir icon theme.
* [BreezeX](https://github.com/ful1e5/BreezeX_Cursor) ⭐ 470 | 🐛 12 | 🌐 Shell | 📅 2024-07-27 - Extended KDE cursor.
* [Vimix](https://github.com/vinceliuice/Vimix-cursors) ⭐ 450 | 🐛 6 | 🌐 Shell | 📅 2022-08-13 - Cursor inspired by Material Design.
* [Fuchsia](https://github.com/ful1e5/fuchsia-cursor) ⭐ 110 | 🐛 3 | 🌐 Shell | 📅 2024-08-14 - Cursor inspired by Google's FuchsiaOS.

### Utilities

* [hyprcursor](https://github.com/hyprwm/hyprcursor) ⭐ 567 | 🐛 10 | 🌐 C++ | 📅 2026-08-11 - The hyprland cursor format, library and utilities.

## Icons

* [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) ⭐ 8,023 | 🐛 578 | 🌐 Shell | 📅 2026-08-01 - Pixel perfect icon theme.
* [Tela](https://github.com/vinceliuice/Tela-icon-theme) ⭐ 1,859 | 🐛 104 | 🌐 Shell | 📅 2026-08-10 - Flat colorful Design icon theme.
* [Flat Remix](https://github.com/daniruiz/Flat-Remix) ⭐ 1,759 | 🐛 6 | 🌐 Makefile | 📅 2025-11-19 - Icon theme inspired by material design.
* [Candy](https://github.com/EliverLara/candy-icons) ⭐ 1,313 | 🐛 147 | 📅 2026-03-06 - Sweet gradient icons.
* [Colloid](https://github.com/vinceliuice/Colloid-icon-theme) ⭐ 1,136 | 🐛 55 | 🌐 Shell | 📅 2026-08-17 - Icon theme with a colorful and playful design.
* [Qogir](https://github.com/vinceliuice/Qogir-icon-theme) ⭐ 931 | 🐛 48 | 🌐 Shell | 📅 2025-11-04 - Colorful design icon theme.
* [suru-plus](https://github.com/gusbemacbe/suru-plus) ⭐ 391 | 🐛 16 | 🌐 Shell | 📅 2026-05-25 - Cyberpunk, elegant, futuristic and Papirus-like third-party icons theme.
* [BeautyLine](https://github.com/gvolpe/BeautyLine) ⭐ 18 | 🐛 1 | 📅 2022-01-16 - Outlined icons designed to have unified look and comprehensive coverage.

## Application Launcher

<details>
  <summary><b>What is an application launcher</b></summary>
  <p>An <b>application launcher</b> is a tool that provides you a graphical interface to quickly search for and launch applications on your system. It provides a convenient way to access your favorite apps without having to navigate through menus or desktop icons. Application launchers can also be used to search for files, folders, and other resources on your system. Most of these app launchers are very customizable.</p>
</details>
<br/>

* [Rofi](https://github.com/davatorium/rofi) ⭐ 16,333 | 🐛 117 | 🌐 C | 📅 2026-08-09<sup>X11 + <a href="https://github.com/lbonn/rofi">Wayland</a></sup> - Window switcher, application launcher and dmenu replacement.
  * [custom confs](https://github.com/adi1090x/rofi) ⭐ 8,753 | 🐛 67 | 🌐 Shell | 📅 2026-05-31 - Huge collection of Rofi based custom Applets, Launchers & Powermenus by adi1090x
  * [rofi-wifi-menu](https://github.com/zbaylin/rofi-wifi-menu) ⭐ 490 | 🐛 14 | 🌐 Shell | 📅 2023-09-23 - Bash script using nmcli and rofi to make a wifi menu.
* [vicinae](https://github.com/vicinaehq/vicinae) ⭐ 8,951 | 🐛 191 | 🌐 C++ | 📅 2026-08-17 - Focused launcher for your desktop — native, fast, extensible.
* [Ulauncher](https://github.com/Ulauncher/Ulauncher/) ⭐ 4,503 | 🐛 130 | 🌐 Python | 📅 2026-08-10<sup>X11 + Wayland</sup> - Feature rich application Launcher.
* [tofi](https://github.com/philj56/tofi) ⭐ 1,396 | 🐛 117 | 🌐 C | 📅 2024-12-30<sup>Wayland</sup> - Tiny dynamic menu for Wayland.
* [Anyrun](https://github.com/Kirottu/anyrun) ⭐ 1,291 | 🐛 73 | 🌐 Rust | 📅 2026-08-14<sup>Wayland</sup> - Wayland native, highly customizable runner.
* [Gauntlet](https://github.com/project-gauntlet/gauntlet) ⭐ 819 | 🐛 19 | 🌐 Rust | 📅 2025-10-02<sup>X11</sup> - Raycast-inspired open-source application launcher with React-based plugins.
* [wofi](https://gitlab.com/dgirault/wofi)<sup>Wayland</sup> - Launcher/menu program for wlroots based wayland compositors.
* [fuzzel](https://codeberg.org/dnkl/fuzzel)<sup>Wayland</sup> - Application launcher for wlroots based Wayland compositors, similar to rofi's drun mode.

## Notifications Daemon

<details>
  <summary><b>What is a notification daemon</b></summary>
  <p>A <b>notification daemon</b> is a software component that provides a way for applications to display notifications to the user. It manages the display of notifications on the screen, including their appearance, duration, and behavior.</p>
</details>
<br/>

* [Dunst](https://github.com/dunst-project/dunst) ⭐ 5,567 | 🐛 123 | 🌐 C | 📅 2026-08-11<sup>X11 + Wayland</sup> - Lightweight and customizable notification daemon.
* [mako](https://github.com/emersion/mako) ⭐ 3,227 | 🐛 135 | 🌐 C | 📅 2026-06-30<sup>Wayland</sup> - Lightweight Wayland notification daemon.
* [SwayNC](https://github.com/ErikReider/SwayNotificationCenter) ⭐ 2,559 | 🐛 110 | 🌐 Vala | 📅 2026-06-25<sup>Wayland</sup> - Simple notification daemon with a GTK gui for notifications and the control center.

## Widgets

* [conky](https://github.com/brndnmtthws/conky) ⭐ 8,470 | 🐛 86 | 🌐 C++ | 📅 2026-08-07 - Light-weight system monitor.
* [Kando](https://github.com/kando-menu/kando) ⭐ 6,197 | 🐛 63 | 🌐 TypeScript | 📅 2026-08-18 - The Cross-Platform Pie Menu.
* [GLava](https://github.com/jarcode-foss/glava) ⭐ 1,272 | 🐛 99 | 🌐 C | 📅 2024-01-19 -OpenGL audio spectrum visualizer.
* [wallpaper-cava](https://github.com/rs-pro0/wallpaper-cava) ⭐ 49 | 🐛 4 | 🌐 Rust | 📅 2026-06-15 - Display cava on top of your wallpaper.

## Logout Menu

* [rofi](https://github.com/davatorium/rofi) ⭐ 16,333 | 🐛 117 | 🌐 C | 📅 2026-08-09<sup>X11 + <a href="https://github.com/lbonn/rofi">Wayland</a></sup> - Window switcher, application launcher and dmenu replacement. Can be used to create logout menu.
* [wlogout](https://github.com/ArtsyMacaw/wlogout) ⭐ 1,046 | 🐛 45 | 🌐 C | 📅 2024-07-04<sup>Wayland</sup> - Wayland based logout menu

## Screen Lock

* [hyprlock](https://github.com/hyprwm/hyprlock) ⭐ 1,636 | 🐛 188 | 🌐 C++ | 📅 2026-08-11<sup>Wayland</sup> - Hyprland's GPU-accelerated screen locking utility
* [swaylock](https://github.com/swaywm/swaylock) ⭐ 1,214 | 🐛 101 | 🌐 C | 📅 2026-07-09<sup>Wayland</sup> - Screen locker for Wayland.
  * [swaylock-effects](https://github.com/mortie/swaylock-effects) ⭐ 861 | 🐛 61 | 🌐 C | 📅 2023-11-28 - Swaylock, with fancy effects
* [i3lock](https://github.com/i3/i3lock) ⭐ 995 | 🐛 16 | 🌐 C | 📅 2025-10-31<sup>X11</sup> - Improved screen locker.

## Terminal

<details>
  <summary><b>Terminal Emulator vs Shell</b></summary>
  <p>A <b>Terminal Emulator</b> is software that emulates a physical terminal. It provides a graphical or text interface that allows you to interact with a shell. It provides output and input, but it doesn't interpret commands.</p>
<p>A <b>Shell</b> is a command-line interpreter. It acts as a bridge between the user and the operating system. It reads, interprets, and executes the commands you type.</p>
</details>
<br/>

### Emulator

* [alacritty](https://github.com/alacritty/alacritty) ⭐ 65,426 | 🐛 341 | 🌐 Rust | 📅 2026-08-17 - Cross-platform, OpenGL terminal emulator.
* [ghostty](https://github.com/ghostty-org/ghostty) ⭐ 59,863 | 🐛 253 | 🌐 Zig | 📅 2026-08-19 - Fast, feature-rich, and cross-platform terminal emulator
* [kitty](https://github.com/kovidgoyal/kitty) ⭐ 34,473 | 🐛 11 | 🌐 Python | 📅 2026-08-18 - Cross-platform, fast, feature-rich, GPU based terminal.
* [wezterm](https://github.com/wez/wezterm) ⭐ 28,443 | 🐛 1,815 | 🌐 Rust | 📅 2026-08-18 - GPU-accelerated cross-platform terminal emulator and multiplexer.
* [st](https://github.com/siduck/st) ⭐ 750 | 🐛 5 | 🌐 C | 📅 2026-07-19 - Snazzy terminal (suckless + beautiful)
* [foot](https://codeberg.org/dnkl/foot) - Fast, lightweight and minimalistic Wayland terminal emulator.

### Shell

* [nushell](https://github.com/nushell/nushell) ⭐ 40,295 | 🐛 1,430 | 🌐 Rust | 📅 2026-08-19 - New type of shell.
* [fish](https://github.com/fish-shell/fish-shell) ⭐ 34,034 | 🐛 571 | 🌐 Rust | 📅 2026-08-17 - User-friendly shell with autosuggestions and syntax highlighting.
  * [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) ⭐ 11,374 | 🐛 0 | 🌐 Shell | 📅 2026-05-19 - The Fish Shell Framework.
* [bash](https://www.gnu.org/software/bash/) - Default shell for most distros.
  * [ble.sh](https://github.com/akinomyoga/ble.sh) ⭐ 4,629 | 🐛 82 | 🌐 Shell | 📅 2026-08-18 - Line editor written in pure Bash with syntax highlighting, auto suggestions, vim modes, etc. for Bash.
* [zsh](https://zsh.sourceforge.io/) - Powerful shell with scripting capabilities.
  * [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) ⭐ 189,264 | 🐛 599 | 🌐 Shell | 📅 2026-08-17 - Delightful, open source, community-driven framework for managing your Zsh configuration.
  * [prezto](https://github.com/sorin-ionescu/prezto) ⭐ 14,566 | 🐛 197 | 🌐 Shell | 📅 2026-04-24 - Popular configuration framework for Zsh.
  * [Antigen](https://github.com/zsh-users/antigen) ⭐ 8,350 | 🐛 98 | 🌐 Shell | 📅 2026-07-15 - Popular plugin manager for Zsh.
  * [zinit](https://github.com/zdharma-continuum/zinit) ⭐ 4,804 | 🐛 112 | 🌐 Shell | 📅 2026-08-18 - Flexible and fast ZSH plugin manager.
  * [zimfw](https://github.com/zimfw/zimfw) ⭐ 4,668 | 🐛 25 | 🌐 Shell | 📅 2026-08-17 - Modular, customizable, and blazing fast Zsh framework.
  * [zgen](https://github.com/tarjoilija/zgen) ⭐ 1,528 | 🐛 41 | 🌐 Shell | 📅 2021-07-21 - Lightweight and simple plugin manager for ZSH.
  * [zap](https://github.com/zap-zsh/zap) ⭐ 1,170 | 🐛 13 | 🌐 Shell | 📅 2026-03-01 - Minimal zsh plugin manager.

### Prompt

<details>
  <summary><b>What is the prompt</b></summary>
  <p>A<b>prompt</b> is the text or symbol displayed by the shell that indicates it is ready to receive a command from the user. It usually appears before the command you type and can show information like your username, current directory, or computer name.</p>
</details>
<br/>

* [Starship](https://github.com/starship/starship) ⭐ 59,480 | 🐛 1,032 | 🌐 Rust | 📅 2026-08-17 - Minimal, blazing-fast, and infinitely customizable prompt.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) ⭐ 54,937 | 🐛 150 | 🌐 Shell | 📅 2026-08-15<sup>zsh</sup> - Theme for zsh emphasizing speed, flexibility and out-of-the-box experience.
* [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh) ⭐ 23,309 | 🐛 15 | 🌐 Go | 📅 2026-08-18 - The most customisable and low-latency cross platform/shell prompt renderer.
* [Pure](https://github.com/sindresorhus/pure) ⭐ 14,396 | 🐛 0 | 🌐 Shell | 📅 2026-07-16<sup>zsh</sup> - Pretty, minimal and fast ZSH prompt.
* [trueline](https://github.com/petobens/trueline) ⭐ 397 | 🐛 12 | 🌐 Shell | 📅 2024-05-31<sup>bash</sup> - Fast and extensible bash powerline prompt with true color and fancy icon support.
* [roundy](https://github.com/nullxception/roundy) ⚠️ Archived<sup>zsh</sup> - Fast, cute, and-of-course, roundy prompt-theme for Zsh.

### Multiplexer

<details>
  <summary><b>What is a multiplexer</b></summary>
  <p>A <b>terminal multiplexer</b> enables a number of terminals to be created, accessed, and controlled from a single screen. It lets you switch between different sessions, detach and reattach them, and manage them efficiently. Multiplexers are useful for running long-running processes, managing multiple tasks, and working on remote servers.</p>
</details>
<br/>

* [tmux](https://github.com/tmux/tmux) ⭐ 48,718 | 🐛 28 | 🌐 C | 📅 2026-08-19 - Terminal multiplexer with a focus on simplicity and productivity.
  * [tmux-plugins](https://github.com/orgs/tmux-plugins/repositories) - Collection of useful tmux plugins.
* [zellij](https://github.com/zellij-org/zellij) ⭐ 34,995 | 🐛 1,858 | 🌐 Rust | 📅 2026-08-18 - Terminal workspace with batteries included.
* [byobu](https://www.byobu.org/home) - Text-based window manager and terminal multiplexer.
* [GNU Screen](https://www.gnu.org/software/screen/) - Full-screen window manager that multiplexes a physical terminal between several processes.

### Tools

#### File Manager

* [yazi](https://github.com/sxyazi/yazi) ⭐ 41,485 | 🐛 66 | 🌐 Rust | 📅 2026-08-19 - Blazing fast terminal file manager written in Rust.
* [superfile](https://github.com/yorukot/superfile) ⭐ 22,636 | 🐛 258 | 🌐 Go | 📅 2026-08-15 - Pretty fancy and modern terminal file manager.
* [nnn](https://github.com/jarun/nnn) ⭐ 21,817 | 🐛 4 | 🌐 C | 📅 2026-08-17 - Tiny, small and incredibly fast file manager for the terminal.
* [ranger](https://github.com/ranger/ranger) ⭐ 17,355 | 🐛 897 | 🌐 Python | 📅 2026-08-15 - VIM-inspired file manager for the console.
  * [devicons](https://github.com/alexanderjeurissen/ranger_devicons) ⭐ 1,004 | 🐛 0 | 🌐 Python | 📅 2025-06-05 - File glyphs / icon support to Ranger.

#### Editor

* [neovim](https://github.com/neovim/neovim) ⭐ 101,862 | 🐛 1,866 | 🌐 Vim Script | 📅 2026-08-19 - Vim-fork focused on extensibility and usability.
* [Helix](https://github.com/helix-editor/helix) ⭐ 45,878 | 🐛 1,614 | 🌐 Rust | 📅 2026-08-18 - Post-modern text editor.
* [vim](https://github.com/vim/vim) ⭐ 40,771 | 🐛 1,628 | 🌐 Vim Script | 📅 2026-08-18 - Highly configurable text editor built to enable efficient text editing.
* [micro](https://github.com/zyedidia/micro) ⭐ 29,383 | 🐛 1,033 | 🌐 Go | 📅 2026-08-19 - Modern and intuitive terminal-based text editor.
* [kakoune](https://github.com/mawww/kakoune) ⭐ 11,030 | 🐛 913 | 🌐 C++ | 📅 2026-08-19 - Modal editor with multiple selections and orthogonal design.
* [nano](https://github.com/madnight/nano) ⭐ 185 | 🐛 3 | 🌐 C | 📅 2026-08-17 - Simple and easy-to-use text editor.

#### Image Printing

* [timg](https://github.com/hzeller/timg) ⭐ 2,729 | 🐛 36 | 🌐 C++ | 📅 2026-08-05 - User-friendly terminal image viewer that uses graphic capabilities of terminals.
* [catimg](https://github.com/posva/catimg) ⭐ 1,573 | 🐛 12 | 🌐 C | 📅 2026-04-07 - Insanely fast image printing in your terminal.
* [imcat](https://github.com/stolk/imcat) ⭐ 346 | 🐛 12 | 🌐 C | 📅 2025-05-25 - Show any image in a terminal window.

#### Music Players

* [spotify-tui](https://github.com/Rigellute/spotify-tui) ⭐ 19,307 | 🐛 306 | 🌐 Rust | 📅 2024-04-04<sup>Spotify</sup> - Spotify for the terminal written in Rust.
* [spotify\_player](https://github.com/aome510/spotify-player) ⭐ 7,091 | 🐛 163 | 🌐 Rust | 📅 2026-07-20<sup>Spotify</sup> - Spotify player in the terminal with full feature parity.
* [cmus](https://github.com/cmus/cmus) ⭐ 6,219 | 🐛 217 | 🌐 C | 📅 2026-08-12 - Small, fast and powerful console music player.
* [ncmpcpp](https://github.com/ncmpcpp/ncmpcpp) ⭐ 2,473 | 🐛 226 | 🌐 C++ | 📅 2026-06-25 - [MPD](https://github.com/MusicPlayerDaemon/MPD) ⭐ 2,745 | 🐛 166 | 🌐 C++ | 📅 2026-08-19 - Featureful ncurses based MPD client.

#### System Monitoring

* [btop](https://github.com/aristocratos/btop) ⭐ 34,087 | 🐛 529 | 🌐 C++ | 📅 2026-08-08 - Resource monitor that shows usage and stats for processor, memory, disks, network and processes.
* [Glances](https://github.com/nicolargo/glances) ⭐ 33,377 | 🐛 108 | 🌐 Python | 📅 2026-08-18 - Glances an Eye on your system.
* [htop](https://github.com/htop-dev/htop) ⭐ 8,263 | 🐛 349 | 🌐 C | 📅 2026-08-16 - Interactive process viewer.
* [s-tui](https://github.com/amanusk/s-tui) ⭐ 5,066 | 🐛 38 | 🌐 Python | 📅 2026-08-19 - Terminal-based CPU stress and monitoring utility.

#### Mail Client

* [mutt](https://gitlab.com/muttmua/mutt) - Text-based mail client renowned for its powerful features.

#### Screenshot

* [scrot](https://github.com/resurrecting-open-source-projects/scrot) ⭐ 596 | 🐛 17 | 🌐 C | 📅 2026-03-14 - Command line screen capture utility.

#### Recording

* [wf-recorder](https://github.com/ammen99/wf-recorder) ⭐ 1,303 | 🐛 55 | 🌐 C++ | 📅 2026-04-12<sup>Wayland</sup> - Utility program for screen recording.

#### Directory Listing

* [eza](https://github.com/eza-community/eza) ⭐ 22,969 | 🐛 429 | 🌐 Rust | 📅 2026-08-06 - Modern alternative to `ls`.
* [lsd](https://github.com/Peltoche/lsd) ⭐ 16,180 | 🐛 206 | 🌐 Rust | 📅 2026-08-17 - The next gen `ls` command.
* [Color LS](https://github.com/athityakumar/colorls) ⭐ 5,136 | 🐛 87 | 🌐 Ruby | 📅 2026-07-27 - Ruby gem that beautifies the terminal's `ls` command with color and font-awesome icons.
* [logo-ls](https://github.com/Yash-Handa/logo-ls) ⭐ 1,185 | 🐛 37 | 🌐 Go | 📅 2023-05-10 - Modern `ls` command with vscode like file icons and `git` integrations.

#### Misc

* [nvm](https://github.com/nvm-sh/nvm) ⭐ 94,654 | 🐛 394 | 🌐 Shell | 📅 2026-08-18 - POSIX-compliant bash script to manage multiple active node.js versions.
* [carbon-now-cli](https://github.com/mixn/carbon-now-cli) ⭐ 6,030 | 🐛 8 | 🌐 TypeScript | 📅 2025-11-14 - Beautiful images of your code — from right inside your terminal.
* [xdg-ninja](https://github.com/b3nj5m1n/xdg-ninja) ⭐ 3,354 | 🐛 67 | 🌐 Haskell | 📅 2026-05-10 - Shell script which checks your $HOME for unwanted files and directories.
* [evillimiter](https://github.com/bitbrute/evillimiter) ⭐ 2,004 | 🐛 29 | 🌐 Python | 📅 2026-03-24 - Tool that monitors, analyzes and limits the bandwidth of devices on the local network without administrative access.
* [arch-update](https://github.com/Antiz96/arch-update) ⭐ 429 | 🐛 0 | 🌐 Shell | 📅 2026-08-17 - Update applier for Arch Linux that assists you with important pre/post update tasks.
* [ncdu](https://code.blicky.net/yorhel/ncdu) - Disk usage analyzer with an ncurses interface.
* more:
  * [awesome-shell](https://github.com/alebcay/awesome-shell) ⭐ 37,461 | 🐛 183 | 📅 2025-08-28
  * [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps) ⭐ 20,187 | 🐛 1 | 🌐 Shell | 📅 2026-08-18

### Fancies

#### Fetch

* [fastfetch](https://github.com/fastfetch-cli/fastfetch) ⭐ 24,275 | 🐛 76 | 🌐 C | 📅 2026-08-19 - Feature-rich and performance oriented, `neofetch` like system information tool.
* [neofetch](https://github.com/dylanaraps/neofetch) ⚠️ Archived - Command-line system information tool written in bash.
  * [neofetch-themes](https://github.com/Chick2D/neofetch-themes) ⭐ 1,734 | 🐛 8 | 🌐 Shell | 📅 2025-12-25 - Collection of themes for `neofetch`.
* [pfetch](https://github.com/dylanaraps/pfetch) ⚠️ Archived - Pretty system information tool written in POSIX sh.
* [hyfetch](https://github.com/hykilpikonna/hyfetch) ⭐ 2,088 | 🐛 9 | 🌐 Shell | 📅 2026-08-09 - `neofetch` with LGBTQ+ pride flags.
* [macchina](https://github.com/Macchina-CLI/macchina/) ⭐ 1,964 | 🐛 11 | 🌐 Rust | 📅 2025-03-08 - System information frontend with an emphasis on performance.
* [uwufetch](https://github.com/ad-oliviero/uwufetch) ⭐ 815 | 🐛 10 | 🌐 C | 📅 2026-04-14 - Meme system info tool for Linux, based on nyan/uwu trend on r/linuxmasterrace.
* [fetch](https://github.com/areofyl/fetch) ⭐ 666 | 🐛 3 | 🌐 C | 📅 2026-08-18 - A `neofetch` alternative with a 3D animated distro logo
* [nerdfetch](https://github.com/ThatOneCalculator/NerdFetch) ⭐ 653 | 🐛 0 | 🌐 Shell | 📅 2026-07-16 - POSIX \*nix fetch script using Nerdfonts.
* [nitch](https://github.com/ssleert/nitch) ⭐ 649 | 🐛 32 | 🌐 Nim | 📅 2024-06-22 - Incredibly fast system fetch written in nim.
* [freshfetch](https://github.com/K4rakara/freshfetch) ⭐ 507 | 🐛 19 | 🌐 Rust | 📅 2024-06-05 - A fresh take on neofetch.
* [rxfetch](https://github.com/Mangeshrex/rxfetch) ⭐ 498 | 🐛 3 | 🌐 Shell | 📅 2025-07-25 - Custom system info fetching tool.
* [catnap](https://github.com/iinsertNameHere/catnap) ⭐ 292 | 🐛 2 | 🌐 Nim | 📅 2026-07-01 - Highly customizable systemfetch written in nim.
* [bunnyfetch](https://github.com/Rosettea/bunnyfetch) ⭐ 191 | 🐛 1 | 🌐 Go | 📅 2025-01-14 - Tiny system info fetch utility.
* [ufetch](https://gitlab.com/jschx/ufetch) - Tiny system info for Unix-like operating systems.

#### Terminal Visuals

* [SL](https://github.com/mtoyoda/sl) ⭐ 3,328 | 🐛 37 | 🌐 C | 📅 2024-06-11 - SL(1): Cure your bad habit of mistyping.
* [pipes.sh](https://github.com/pipeseroni/pipes.sh) ⭐ 3,013 | 🐛 14 | 🌐 Shell | 📅 2024-08-12 - Animated pipes terminal screensaver.
* [Nyancat](https://github.com/klange/nyancat) ⭐ 1,583 | 🐛 17 | 🌐 C | 📅 2024-04-19 - Nyancat in your terminal, rendered through ANSI escape sequences.
* [arttime](https://github.com/poetaman/arttime) ⭐ 1,376 | 🐛 6 | 🌐 Shell | 📅 2026-08-18 - text art with functionality of clock / timer / pattern-based time manager.
* [Asciiquarium](https://github.com/cmatsuoka/asciiquarium) ⭐ 1,252 | 🐛 19 | 🌐 Perl | 📅 2023-08-25 - Enjoy the mysteries of the sea from the safety of your own terminal!
* [ascii-rain](https://github.com/nkleemann/ascii-rain) ⭐ 152 | 🐛 2 | 🌐 C | 📅 2025-07-11 - Ncurses rain effect.
* [cbonsai](https://gitlab.com/jallbrit/cbonsai) - Grow bonsai trees in your terminal.
* [Shell Color Scripts](https://gitlab.com/dwt1/shell-color-scripts) - Collection of terminal color scripts.
* [sortty](https://github.com/dormant-chicken/sortty) - Sorting algorithms in the terminal.

#### Clock

* [tty-clock](https://github.com/xorg62/tty-clock) ⭐ 1,138 | 🐛 34 | 🌐 C | 📅 2024-07-31 - Clock using lib ncurses.
* [Peaclock](https://github.com/octobanana/peaclock) ⭐ 795 | 🐛 25 | 🌐 C++ | 📅 2024-03-15 - Responsive and customizable clock for the terminal.
* [tenki](https://github.com/ckaznable/tenki) ⭐ 167 | 🐛 0 | 🌐 Rust | 📅 2026-07-23 - tty-clock with weather effect

#### Audio Visualizer

* [CAVA](https://github.com/karlstav/cava) ⭐ 6,354 | 🐛 17 | 🌐 C | 📅 2026-08-18 - Cross-platform Audio Visualizer.
* [Musializer](https://github.com/tsoding/musializer) ⭐ 1,459 | 🐛 34 | 🌐 C | 📅 2026-06-27 - Music Visualizer.
* [ReCidia](https://github.com/GhostNaN/recidia-audio-visualizer) ⭐ 42 | 🐛 1 | 🌐 C++ | 📅 2026-07-19 - Highly customizable real time audio visualizer on Linux.
* [ReVidia](https://github.com/GhostNaN/ReVidia-Audio-Visualizer) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2020-09-28 - Highly customizable real time audio visualizer.

#### Matrix

* [CMatrix](https://github.com/abishekvashok/cmatrix) ⭐ 5,207 | 🐛 84 | 🌐 C | 📅 2024-08-21 - Terminal based "The Matrix" like implementation.
* [unimatrix](https://github.com/will8211/unimatrix) ⭐ 1,941 | 🐛 27 | 🌐 Python | 📅 2026-05-20 - Python script to simulate the display from "The Matrix" in terminal.
* [neo](https://github.com/st3w/neo) ⭐ 948 | 🐛 16 | 🌐 C++ | 📅 2024-04-02 - Simulates the digital rain from "The Matrix".

#### Character Play

* [ponysay](https://github.com/erkin/ponysay) ⭐ 1,318 | 🐛 79 | 🌐 Pony | 📅 2024-08-14 - Pony rewrite of cowsay.
* [cowsay](https://github.com/piuccio/cowsay) ⭐ 1,310 | 🐛 16 | 🌐 JavaScript | 📅 2024-09-24 - Configurable talking cow.
* [boxes](https://github.com/ascii-boxes/boxes/) ⭐ 682 | 🐛 0 | 🌐 C | 📅 2026-08-11 - Command line ASCII boxes unlimited!
* [lovesay](https://github.com/dotzenith/lovesay.rs) ⭐ 19 | 🐛 0 | 🌐 Rust | 📅 2026-06-20 - Cowsay, but full of love.
* [fortune](http://bxr.su/OpenBSD/games/fortune/) - Random poignant, inspirational, silly or snide phrases.

#### Pokemon-Themed

* [pokeget-rs](https://github.com/talwat/pokeget-rs) ⭐ 293 | 🐛 5 | 🌐 Rust | 📅 2026-07-13 - Bash script you can use to display **AWESOME** sprites of pokemon in your terminal.
* [krabby](https://github.com/yannjor/krabby) ⭐ 235 | 🐛 5 | 🌐 Rust | 📅 2025-03-30 - Print pokemon sprites in your terminal.
* [Poketex](https://github.com/ckaznable/poketex) ⭐ 214 | 🐛 0 | 🌐 Rust | 📅 2026-05-05 - Simple Pokedex based on TUI.
* [pokeshell](https://github.com/acxz/pokeshell) ⭐ 207 | 🐛 11 | 🌐 Shell | 📅 2024-11-24 - Featureful shell program to show pokemon sprites in the terminal.
* [pokemon-colorscripts](https://gitlab.com/phoneybadger/pokemon-colorscripts) - CLI utility to print out images of pokemon to terminal.

#### Text and Fonts

* [lolcat](https://github.com/busyloop/lolcat) ⭐ 6,565 | 🐛 33 | 🌐 Ruby | 📅 2024-03-05 - Rainbows and unicorns!
* [FIGlet](https://github.com/cmatsuoka/figlet) ⭐ 1,641 | 🐛 16 | 🌐 C | 📅 2023-09-13 - Claudio's FIGlet tree.
* [toilet](https://github.com/cacalabs/toilet) ⭐ 308 | 🐛 7 | 🌐 C | 📅 2024-05-24 - The Other Implementation of figLET.
* [lolcrab](https://github.com/mazznoer/lolcrab) ⭐ 169 | 🐛 4 | 🌐 Rust | 📅 2025-12-22 - Like lolcat but with noise and more colorful.

## GUI Apps

### Web Browser

* [chromium](https://github.com/chromium/chromium) ⭐ 24,560 | 🐛 28 | 📅 2026-08-19 - Open-source browser project that aims to build a safer, faster, and more stable way for all users to experience the web.
* [Floorp](https://github.com/Floorp-Projects/Floorp/) ⭐ 8,333 | 🐛 97 | 🌐 TypeScript | 📅 2026-08-19<sup>Firefox</sup> - Browser built for keeping the Open, Private and Sustainable Web alive.
* [thorium](https://github.com/Alex313031/Thorium) ⭐ 7,444 | 🐛 135 | 🌐 C++ | 📅 2026-08-18<sup>Chromium</sup> - Chromium fork for linux named after radioactive element No. 90.
* [Firefox](https://www.mozilla.org/firefox) - Free and Open Source web browser focused on privacy, security and customization.
* [Brave](https://brave.com/)<sup>Chromium</sup> - privacy-focused browser, which automatically blocks most advertisements and website trackers in its default settings.
* [Tor](https://www.torproject.org/)<sup>Firefox</sup> - Web browser capable of accessing the Tor network.

### File Manager

* [Nemo](https://github.com/linuxmint/nemo) ⭐ 1,549 | 🐛 323 | 🌐 C | 📅 2026-08-15 - Default file browser for Cinnamon.
* [PCmanFM](https://github.com/lxde/pcmanfm) ⭐ 249 | 🐛 34 | 🌐 C | 📅 2026-02-03 - Extremely fast and lightweight file manager.
* [Nautilus](https://gitlab.gnome.org/GNOME/nautilus) - Default file browser for GNOME.
* [Dolphin](https://invent.kde.org/system/dolphin) - Default file browser for KDE.
* [thunar](https://gitlab.xfce.org/xfce/thunar) - Default file browser for Xfce.

### Image Viewer

* [qimgv](https://github.com/easymodo/qimgv) ⭐ 3,107 | 🐛 307 | 🌐 C++ | 📅 2026-01-19 - Image viewer. Fast, easy to use. Optional video support.
* [feh](https://github.com/derf/feh) ⭐ 1,905 | 🐛 257 | 🌐 C | 📅 2026-07-22 - Fast and light image viewer.
* [imv](https://git.sr.ht/~exec64/imv) - Simple image viewer for tiling window managers.
* [Eye of GNOME](https://gitlab.gnome.org/GNOME/eog) - Default image viewer for GNOME.

### Music Player

* [feishin](https://github.com/jeffvli/feishin) ⭐ 9,546 | 🐛 230 | 🌐 TypeScript | 📅 2026-08-19 - Modern self-hosted music player.
* [DeaDBeeF](https://github.com/DeaDBeeF-Player/deadbeef) ⭐ 1,958 | 🐛 377 | 🌐 C | 📅 2026-08-12 - Multiple-platform music player.
* [G4Music](https://github.com/neithern/g4music) ⭐ 435 | 🐛 67 | 🌐 Vala | 📅 2026-06-27 - Light weight music player written in GTK4, with a fluent adaptive user interface.
* [lyssa](https://github.com/cococry/lyssa) ⭐ 209 | 🐛 9 | 🌐 C++ | 📅 2024-06-01 - Aestethic, minimal, suckless music player.
* [Amberol](https://gitlab.gnome.org/World/amberol) - Music player with no delusions of grandeur.
* [Sunamu](https://github.com/NyaomiDEV/Sunamu) - Fancy music controller whose only purpose is to look as fancy as possible on secondary displays.

### Video Streamer

* [mpv](https://github.com/mpv-player/mpv) ⭐ 36,589 | 🐛 1,133 | 🌐 C | 📅 2026-08-17 - Command line video player.
* [VLC](https://github.com/videolan/vlc) ⭐ 19,375 | 🐛 2 | 🌐 C | 📅 2026-08-19 - Open source media player and multimedia engine, focused on playing everything, and running everywhere.

### Document Reader

* [zathura](https://github.com/pwmt/zathura) ⭐ 3,250 | 🐛 181 | 🌐 C | 📅 2026-08-17 - Highly customizable and functional document viewer.
* [Bookworm](https://github.com/babluboy/bookworm) ⭐ 1,385 | 🐛 145 | 🌐 Vala | 📅 2026-08-13 - Simple ebook reader for Elementary OS.

### Text Editor

* [vscodium](https://github.com/VSCodium/vscodium) ⭐ 32,885 | 🐛 139 | 🌐 Shell | 📅 2026-08-12 - Binary releases of VS Code without MS branding/telemetry/licensing.
* [geany](https://github.com/geany/geany) ⭐ 3,696 | 🐛 1,269 | 🌐 C | 📅 2026-08-03 - Lightweight and fast IDE.
* [kate](https://github.com/KDE/kate) ⭐ 1,097 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - Modern text editor built on the KDE Frameworks and Qt.
* [gedit](https://gitlab.gnome.org/GNOME/gedit) - Default text editor for GNOME.

### Archive Manager

* [File Roller](https://gitlab.gnome.org/GNOME/file-roller) - Archive manager for GNOME.

### Email

* [Thunderbird](https://github.com/mozilla/releases-comm-central) ⭐ 194 | 🐛 82 | 🌐 JavaScript | 📅 2026-08-19 - Powerful and customizable open source email client with lots of users.

### Calculator

* [GNOME Calculator](https://gitlab.gnome.org/GNOME/gnome-calculator) - Default calculator for GNOME.

### Notes

* [AppFlowy](https://github.com/AppFlowy-IO/AppFlowy) ⭐ 75,718 | 🐛 998 | 🌐 Dart | 📅 2026-08-11 - AI collaborative workspace where you achieve more without losing control of your data.
* [qnote](https://github.com/Omibranch/qnote) ⚠️ Archived - Minimal frameless notepad with Markdown preview, real PDF export via Typst, OCR via Tesseract, and automatic version history. Built with Tauri 2. Available on AUR.
* [Obsidian](https://obsidian.md/) - Personal knowledge base and note-taking software application that operates on Markdown files.

### Workstation - Content Creation

#### Image Editing

* [GIMP](https://gitlab.gnome.org/GNOME/gimp) - GNU Image Manipulation Program.
* [krita](https://github.com/KDE/krita) ⭐ 10,235 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - Digital painting and illustration application.
* [Inkscape](https://gitlab.com/inkscape/inkscape) - Professional vector graphics editor.

#### Video Editing

* [Olive](https://github.com/olive-editor/olive) ⭐ 9,115 | 🐛 158 | 🌐 C++ | 📅 2024-12-05 - Free non-linear video editor.
* [Kdenlive](https://github.com/KDE/kdenlive) ⭐ 5,483 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - Free and open source video editor, based on MLT Framework and KDE Frameworks.
* [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) - Professional video editing software.

#### Music Production

* [MuseScore](https://github.com/musescore/MuseScore) ⭐ 14,994 | 🐛 4,112 | 🌐 C++ | 📅 2026-08-19 - Open source and free music notation software.
* [lmms](https://github.com/lmms/lmms) ⭐ 10,262 | 🐛 1,447 | 🌐 C++ | 📅 2026-08-17 - Cross-platform music production software.
* [Blue](https://github.com/kunstmusik/blue) ⭐ 152 | 🐛 295 | 🌐 Java | 📅 2026-07-04 - Integrated Music Environment.
* [Ardour](https://ardour.org/) - Hard disk recorder and digital audio workstation application.
* [reaper](https://www.reaper.fm/) - Digital audio workstation, MIDI sequencer and video editing software application.
* [Bitwig](https://www.bitwig.com/) - Digital audio workstation (DAW) and music production software.

#### 3D

* [FreeCAD](https://github.com/FreeCAD/FreeCAD) ⭐ 32,939 | 🐛 4,085 | 🌐 C++ | 📅 2026-08-19 - Open-source parametric 3D CAD modeler.
* [blender](https://github.com/blender/blender) ⭐ 19,771 | 🐛 0 | 🌐 C++ | 📅 2026-08-19 - Popular free and open-source 3D computer graphics software toolset.
* [MeshLab](https://github.com/cnr-isti-vclab/meshlab) ⭐ 5,797 | 🐛 197 | 🌐 C++ | 📅 2026-08-12 - Open source mesh processing system.
* [wings](https://github.com/dgud/wings) ⭐ 663 | 🐛 22 | 🌐 Erlang | 📅 2026-07-07 - Advanced sub-division 3D modeler.

#### Office

* [LibreOffice](https://www.libreoffice.org/) - Free and open-source office productivity software suite.
* [OnlyOffice](https://www.onlyoffice.com/) - Free software office suite and ecosystem of collaborative applications.
* [OpenOffice](https://www.openoffice.org/) - Free and open-source office suite.

#### Screen Recording / Live Streaming

* [OBS Studio](https://github.com/obsproject/obs-studio) ⭐ 75,194 | 🐛 1,179 | 🌐 C | 📅 2026-08-15 - Open Broadcaster Software.
* [ssr](https://github.com/MaartenBaert/ssr) ⭐ 2,881 | 🐛 525 | 🌐 C++ | 📅 2026-08-14 - SimpleScreenRecorder, screen recorder for Linux.
* [kazam](https://github.com/henrywoo/kazam) ⭐ 390 | 🐛 31 | 🌐 Python | 📅 2026-07-29 - Linux Screen Recorder, Broadcaster, Capture and OCR with AI in mind.

### Gaming

* [Heroic](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher) ⭐ 12,039 | 🐛 880 | 🌐 TypeScript | 📅 2026-08-18 - Games launcher for GOG, Amazon and Epic Games.
* [Lutris](https://github.com/lutris/lutris) ⭐ 10,151 | 🐛 291 | 🌐 Python | 📅 2026-08-17 - Game Launcher that helps you manage, install and play games from all eras and from most gaming systems.
* [Rare](https://github.com/RareDevs/Rare) ⭐ 923 | 🐛 42 | 🌐 Python | 📅 2026-08-17 - Open source alternative for Epic Games Launcher.
* [Cartridges](https://github.com/kra-mo/cartridges) ⭐ 828 | 🐛 29 | 🌐 Python | 📅 2026-08-07 - Easy-to-use, elegant game launcher.
* [Steam](https://store.steampowered.com/about/) - Digital distribution platform and games launcher that allows games to run through Proton.

> \[!TIP]
> Check out [r/linux\_gaming](https://www.reddit.com/r/linux_gaming/) for guides and information.

## GUI Apps Ricing

### Firefox

#### Theme

* [ShyFox](https://github.com/Naezr/ShyFox) ⭐ 2,132 | 🐛 71 | 🌐 CSS | 📅 2025-01-21 - Very shy little theme that hides the entire browser interface in the window border.
* [SimpleFox](https://github.com/migueravila/SimpleFox) ⚠️ Archived - Userstyle theme for Firefox minimalist and Keyboard centered.
* [Mod-Blur](https://github.com/datguypiko/Firefox-Mod-Blur) ⭐ 1,726 | 🐛 5 | 🌐 CSS | 📅 2026-07-24 - For dark theme lovers / More compact / Modular / Blur.
* [Cascade](https://github.com/andreasgrafen/cascade) ⭐ 1,603 | 🐛 21 | 🌐 CSS | 📅 2026-05-23 - Responsive One-Line CSS Theme for Firefox.
* [FlyingFox](https://github.com/akshat46/FlyingFox) ⚠️ Archived - Opinionated set of configurations for firefox.
* [Sweet](https://github.com/EliverLara/firefox-sweet-theme) ⭐ 813 | 🐛 41 | 🌐 CSS | 📅 2025-03-02 - Dark and modern theme for firefox with vibrant colors.
* [Nord](https://github.com/EliverLara/firefox-nordic-theme) ⭐ 407 | 🐛 28 | 🌐 CSS | 📅 2025-03-02 - Dark theme for firefox theme created using the awesome Nord color palette.
* [AnimatedFox](https://github.com/RemyIsCool/AnimatedFox) ⚠️ Archived - Minimal Firefox theme with a hidden popup URL bar and satisfying animations
* [Onebar](https://codeberg.org/Freeplay/Firefox-Onebar) - Single bar for Firefox's UI.

#### Startpage

* [nightTab](https://github.com/zombieFox/nightTab) ⭐ 2,047 | 🐛 109 | 🌐 JavaScript | 📅 2024-10-19 - Neutral new tab page accented with a chosen colour.
* [Excalith](https://github.com/excalith/excalith-start-page) ⭐ 747 | 🐛 5 | 🌐 JavaScript | 📅 2025-04-05 - Terminal-inspired, clean, feature-rich and customizable browser start page.
* [Starter Tab](https://github.com/allister-grange/startertab) ⭐ 412 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-17 - Custom new tab page, keeping all the best info handy.
* [dawn](https://github.com/b-coimbra/dawn) ⭐ 411 | 🐛 2 | 🌐 JavaScript | 📅 2024-05-25 - Minimal modern startpage.
* [yags](https://github.com/PrettyCoffee/yet-another-generic-startpage) ⭐ 318 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-14 - Yet Another Generic Startpage.
* [Bento-next](https://github.com/lewisdoesstuff/bento-next) ⭐ 59 | 🐛 0 | 🌐 Vue | 📅 2025-04-11 - Fork of Bento written in Vue 3 with TailwindCSS and Typescript.

### Spotify

* [Spicetify](https://github.com/spicetify/spicetify-cli) ⭐ 24,121 | 🐛 15 | 🌐 JavaScript | 📅 2026-08-19 - Powerful CLI tool to take control of the Spotify client.
  * [spicetify-themes](https://github.com/spicetify/spicetify-themes) ⭐ 6,046 | 🐛 12 | 🌐 CSS | 📅 2026-07-15 - The official Spicetify themes repository.
  * [comfy](https://github.com/NYRI4/Comfy-spicetify) ⭐ 795 | 🐛 27 | 🌐 JavaScript | 📅 2026-01-04 - Stay comfy while listening to music.
  * [fluent](https://github.com/williamckha/spicetify-fluent) ⭐ 313 | 🐛 31 | 🌐 CSS | 📅 2024-05-03 - Spicetify theme inspired by Microsoft's Fluent Design.
  * [catppuccin](https://github.com/catppuccin/spicetify) ⭐ 595 | 🐛 13 | 🌐 CSS | 📅 2025-10-22 - Soothing pastel theme for Spotify.
  * [bloom](https://github.com/nimsandu/spicetify-bloom) ⭐ 682 | 🐛 12 | 🌐 CSS | 📅 2025-05-20 - Powerful theme to calm your eyes while listening to your favorite beats.
  * [nord](https://github.com/Tetrax-10/Nord-Spotify) ⚠️ Archived - Nord themed Spotify.
  * [dribbblish-dynamic](https://github.com/JulienMaille/dribbblish-dynamic-theme) ⭐ 367 | 🐛 0 | 🌐 CSS | 📅 2026-05-26 - Mod of Dribbblish theme for Spicetify.
  * [lucid](https://github.com/sanoojes/spicetify-lucid) ⭐ 486 | 🐛 21 | 🌐 TypeScript | 📅 2026-07-31 - Dynamic, Highly Customizable Spicetify theme inspired by Bloom and Microsoft Fluent Design.

### Discord

* [Vencord](https://github.com/Vendicated/Vencord) ⭐ 13,925 | 🐛 302 | 🌐 TypeScript | 📅 2026-08-19 - Cutest Discord client mod.
* [BetterDiscord](https://github.com/BetterDiscord/BetterDiscord) ⭐ 9,182 | 🐛 48 | 🌐 TypeScript | 📅 2026-08-19 - Client modification for Discord with endless flexibility and addons.
  * [Themes](https://betterdiscord.app/themes) - Collection of themes for BetterDiscord.

### VSCode

* [Material Theme](https://github.com/material-theme/vsc-material-theme) ⭐ 11,311 | 🐛 0 | 📅 2026-06-28 - The most epic theme for VSC.
* [Night Owl](https://github.com/sdras/night-owl-vscode-theme) ⭐ 2,957 | 🐛 48 | 📅 2024-12-31 - Dark theme for contrast for nighttime coding.
* [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme) ⭐ 2,406 | 🐛 16 | 📅 2025-02-05 - Clean, dark Visual Studio Code theme that celebrates the lights of Downtown Tokyo at night.
* [Dracula](https://github.com/dracula/visual-studio-code) ⭐ 877 | 🐛 17 | 🌐 JavaScript | 📅 2026-08-12 - Dracula for VSCode.

## Display Manager

<details>
  <summary><b>What is a Display Manager</b></summary>
  <p>A display manager is a daemon that:</p>
  <ul>
    <li>Runs display servers (e.g. X) where necessary.</li>
    <li>Runs greeters to allow users to pick which user account and session type to use.</li>
    <li>Allows greeters to perform authentication using PAM.</li>
    <li>Runs session processes once authentication is complete.</li>
    <li>Provides remote graphical login options.</li>
  </ul>
  In short, it's your login screen.
</details>
<br/>

* [ly](https://github.com/fairyglade/ly) ⭐ 7,536 | 🐛 0 | 🌐 Zig | 📅 2026-07-31 - Display manager with console UI.
* [sddm](https://github.com/sddm/sddm) ⭐ 2,333 | 🐛 751 | 🌐 C++ | 📅 2026-08-19 - QML based X11 and Wayland display manager.
  * [astronaut](https://github.com/Keyitdev/sddm-astronaut-theme) ⭐ 3,190 | 🐛 16 | 🌐 QML | 📅 2026-07-16 - Modern looking sddm qt6 theme.
  * [Sugar Dark](https://github.com/MarianArlt/sddm-sugar-dark) ⭐ 311 | 🐛 18 | 🌐 QML | 📅 2023-04-26 - The sweetest dark theme around for SDDM.
  * [corners](https://github.com/aczw/sddm-theme-corners) ⭐ 300 | 🐛 9 | 🌐 QML | 📅 2024-03-14 - Customizable SDDM theme that puts stuff on your screen corners.
  * [Tokyo Night](https://github.com/rototrash/tokyo-night-sddm) ⚠️ Archived - Tokyo Night theme for SDDM.
  * [sddm-themes](https://github.com/Rokin05/SDDM-Themes) ⭐ 84 | 🐛 10 | 🌐 QML | 📅 2023-12-26 - Dynamics and highly customizable themes build from scratch for SDDM.
  * [deepin](https://github.com/Match-Yang/sddm-deepin) ⭐ 59 | 🐛 2 | 🌐 QML | 📅 2022-09-18 - Deepin style SDDM theme.
  * [LentenRose](https://github.com/theoisdumb/lentenrose) ⭐ 11 | 🐛 1 | 🌐 QML | 📅 2023-10-30 - Dark theme for SDDM, made with QML.
  * [Sugar Candy](https://framagit.org/MarianArlt/sddm-sugar-candy) - The sweetest login theme available for SDDM. It's so sweet it may cause you diabetes.
* [lightdm](https://github.com/canonical/lightdm) ⭐ 990 | 🐛 231 | 🌐 C | 📅 2026-08-18 - Lightweight, cross-desktop display manager.
  * [Web Greeter](https://github.com/JezerM/web-greeter) ⭐ 269 | 🐛 21 | 🌐 Python | 📅 2026-05-11 - Modern, visually appealing greeter for LightDM.
  * [Shikai](https://github.com/TheWisker/Shikai) ⭐ 137 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19 - Modern lightdm webkit2 theme.
* [gdm](https://gitlab.gnome.org/GNOME/gdm) - GNOME Display Manager.

## GRUB

<details>
  <summary><b>What is GRUB</b></summary>
    <b>GRUB</b> (GRand Unified Bootloader) is a versatile bootloader commonly used in Linux distributions. It's the software that you first see when your computer starts, allowing you to select which operating system or kernel to boot into. <b>GRUB</b> is very customizable and there is plenty of creative themes made by users.
</details>
<br/>

* [Minegrub](https://github.com/Lxtharia/minegrub-theme) ⭐ 4,584 | 🐛 5 | 🌐 Python | 📅 2026-08-11 -  GRUB theme in Minecraft style.
* [grub2-themes](https://github.com/vinceliuice/grub2-themes) ⭐ 4,573 | 🐛 61 | 🌐 Shell | 📅 2026-08-12 - Modern design GRUB theme collection.
* [Matter](https://github.com/mateosss/matter) ⭐ 930 | 🐛 20 | 🌐 Python | 📅 2022-07-25 - Customizable GRUB theme inspired by Material Design.
* [Dark Matter](https://github.com/VandalByte/darkmatter-grub2-theme) ⭐ 407 | 🐛 6 | 🌐 Python | 📅 2026-06-14 - Dark Matter GRUB Theme.
* [Poly dark](https://github.com/shvchk/poly-dark) ⭐ 212 | 🐛 3 | 🌐 Shell | 📅 2023-07-24 -  Poly dark GRUB theme.
* [Tartarus](https://github.com/AllJavi/tartarus-grub) ⭐ 118 | 🐛 2 | 📅 2023-01-02 - Basic grub theme with material gruvbox style.
* [Tokyo Night](https://github.com/mino29/tokyo-night-grub) ⭐ 65 | 🐛 0 | 📅 2023-04-22 - GRUB theme using Tokyo Night color scheme based on Dracula GRUB.
* [Dracula](https://github.com/dracula/grub) ⭐ 25 | 🐛 2 | 📅 2022-10-31 - Dracula GRUB theme.
* [steam-big-picture](https://github.com/arvigeus/steam-big-picture-grub-theme) ⭐ 8 | 🐛 0 | 🌐 HTML | 📅 2024-09-12 - Steam Big Picture inspired GRUB theme.

> \[!TIP]
> To install a theme, follow the instructions provided in the respective theme's  repo.

***

## Installation and Configuration

Quick note for beginners:

* Most of these apps are linked to repositories on GitHub, where you can find installation instructions. However, typically, you can install apps using your package manager way more easily. We usually don't use a "download" button on Linux when installing an app, so it's best to avoid it if you come across one.
* Configuring on Linux is usually done by editing text files. These files should be in `~/.config/` and can follow a specific syntax. To be sure, check the documentation of the app.

## Contribution

Any helpful contribution is welcome, see [CONTRIBUTING](CONTRIBUTING.md).

<!-- ### Thanks -->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
