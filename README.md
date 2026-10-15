<div align="center">

# Awesome Raspberry Pi Handheld Apps 🍓📱

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Platform: Raspberry Pi OS](https://img.shields.io/badge/Platform-Raspberry%20Pi%20OS-red.svg)](https://www.raspberrypi.com/software/)
[![Target: Compact Handhelds](https://img.shields.io/badge/Target-PocketTerm35-blue.svg)](https://github.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

*A carefully curated list of applications for Raspberry Pi OS, perfectly suited for compact handhelds like the **PocketTerm35** (featuring small touchscreens, low resolution, and limited resources) thanks to minimalist Text User Interfaces (TUIs), touch-optimization, or ultra-low footprint.*

</div>

---

## Table of Contents

- [System & Monitoring](#system--monitoring)
- [File Managers & Text Editors](#file-managers--text-editors)
- [Gaming & Emulation](#gaming--emulation)
- [Media & Audio](#media--audio)
- [Productivity & Organization](#productivity--organization)
- [Web & Communication](#web--communication)
- [Development & Utilities](#development--utilities)
- [Contributing](#contributing)

---

## System & Monitoring

Applications designed to track CPU usage, RAM, temperature, and general system health on low-power displays.

1. **[btop](https://github.com/aristocratos/btop)** – A modern, gorgeous resource monitor in the terminal with mouse/touch support and fluid graphs for CPU, RAM, and temperature.
2. **[htop](https://hisham.hm/htop/)** – The classic process management tool; easy to operate on small screens thanks to its clear list layout.
3. **[Glances](https://nicolargo.github.io/glances/)** – Comprehensive system monitoring with a web-UI option and a compact summary view.
4. **[RPi-Monitor](https://github.com/XavierBerger/RPi-Monitor)** – Web-based monitoring specifically tailored for Raspberry Pi metrics, accessible via lightweight browsers.
5. **[Fastfetch](https://github.com/fastfetch-cli/fastfetch)** – A feature-rich, high-performance alternative to neofetch for displaying clean system info summaries instantly.
6. **[s-tui](https://github.com/amanusk/s-tui)** – Stress terminal UI for monitoring CPU temperature, frequency, and power consumption graphically.
7. **[vnStat](https://humdi.net/vnstat/)** – A lightweight network traffic monitor that keeps logs with minimal resource consumption.
8. **[PowerTOP](https://github.com/fenrus75/powertop)** – Diagnostic tool by Intel to measure, monitor, and optimize power management.

---

## File Managers & Text Editors

Efficient tools for file organization, quick navigation, and editing code or notes directly on restricted display sizes.

1. **[Midnight Commander (mc)](https://midnight-commander.org/)** – The legendary dual-pane text-mode file manager – perfectly operable via touch or directional pads.
2. **[nnn](https://github.com/jarun/nnn)** – An extremely fast and lightweight terminal file manager ideal for tiny screens.
3. **[Micro](https://zyedidia.github.io/micro/)** – A modern terminal editor that supports true mouse clicking/touch cursor placement and standard shortcuts (`Ctrl+C`, `Ctrl+V`).
4. **[ncdu](https://dev.yorhel.nl/ncdu)** – NCurses Disk Usage analyzer – graphically shows in the terminal where your SD card storage is being consumed.
5. **[Ranger](https://github.com/ranger/ranger)** – A visual file manager with VI keybindings and file previews.
6. **[lf](https://github.com/gokberk/lf)** – A terminal file manager written in Go, inspired by ranger with fast startup times.
7. **[Neovim](https://neovim.io/)** – A hyperextensible Vim-based text editor, highly customizable for handheld control schemes.
8. **[GNU Nano](https://www.nano-editor.org/)** – A simple, user-friendly CLI text editor well-suited for fast edits on the fly.

---

## Gaming & Emulation

Turn your handheld into a retro gaming powerhouse with engines and frontends designed for low overhead.

1. **[RetroArch / EmulationStation](https://www.retroarch.com/)** – The ultimate frontend ecosystem for retro gaming (NES, GameBoy, SNES, Arcade) on the Raspberry Pi.
2. **[ScummVM](https://www.scummv.org/)** – Perfect for classic point-and-click adventures, uniquely brilliant to control via touchscreen on a handheld.
3. **[Chocolate Doom](https://www.chocolate-doom.org/)** – A conservative port of Doom, running ultra-smoothly and easily mapped to physical handheld buttons.
4. **[Commander Genius](https://clonekeenplus.sourceforge.io/)** – A modern port for the Commander Keen game trilogy, cleanly scaled for small displays.
5. **[C-Dogs SDL](https://cxhextix.github.io/cdogs-sdl/)** – A classic overhead run-and-gun arcade game port with smooth performance.
6. **[OpenBOR](https://www.chronocrash.com/)** – Open-source engine for arcade beat 'em up games, great for custom content packs.
7. **[Aleph One](https://source.ambrosiasw.com/marathon/)** – Open-source engine for Bungie's classic Marathon sci-fi shooter trilogy.
8. **[Noiz2sa](http://www.asahi-net.or.jp/~cs8k-cyu/windows/n2_e.html)** – A lightweight, fast-paced abstract bullet-hell arcade shooter for Linux.

---

## Media & Audio

Keep your pocket device entertained with audio players, visualizers, and lightweight media handlers.

1. **[ncmpcpp](https://rybczak.net/ncmpcpp/)** – A feature-rich, highly customizable MPD (Music Player Daemon) client with a clean TUI.
2. **[mpv](https://mpv.io/)** – A minimalist, hardware-accelerated video and audio player entirely controllable via keyboard shortcuts or touch commands.
3. **[CAVA](https://github.com/karlstav/cava)** – Console-based Audio Visualizer for Alsa – looks stunning as a visual gimmick on a small handheld display.
4. **[Audacious](https://audacious-media-player.org/)** – A lightweight audio player featuring classic skins that remains clean and legible on smaller layouts.
5. **[CMUS](https://cmus.github.io/)** – A small, fast console music player with vim-like keybindings and low memory overhead.
6. **[MOC (Music On Console)](https://moc.daper.net/)** – A console audio player designed to be powerful, easy to use, and independent of desktop environments.
7. **[Termusic](https://github.com/tramhao/termusic)** – A terminal music player written in Rust with rich playlist and backend management.
8. **[F3D](https://f3d.app/)** – A fast, minimalist 3D viewer supporting various formats directly from lightweight environments.

---

## Productivity & Organization

Manage schedules, notes, and tasks efficiently without needing heavy office suites.

1. **[Calcurse](https://calcurse.org/)** – A text-based calendar and todo manager, perfect for a quick overview on the go.
2. **[Taskwarrior](https://taskwarrior.org/)** – Command-line task management system, extremely memory efficient.
3. **[Zim Desktop Wiki](https://zim-wiki.org/)** – A graphical desktop notepad with a scalable GTK interface that remains usable on compact touchscreens.
4. **[jrnl](https://jrnl.sh/)** – A simple command-line journal application for quick notes and thoughts.
5. **[Todo.txt CLI](http://todotxt.org/)** – Minimalist todo-list manager driven by straightforward shell scripts.
6. **[Khal](https://lostpackets.de/khal/)** – A CLI-based calendar application supporting CalDAV synchronization.
7. **[Topyd](https://github.com/scafee/topyd)** – A terminal-based todo.txt manager with an intuitive curses interface.

---

## Web & Communication

Browse the web, check documentation, or chat via matrix protocols with minimal hardware requirements.

1. **[NetSurf](https://www.netsurf-browser.org/)** – An extremely light, native web browser for Raspberry Pi that quickly renders web pages even without heavy JavaScript engines.
2. **[Links](http://links.twibright.com/)** – Capable of rendering graphical web pages inside text terminals while consuming minimal RAM.
3. **[Matrix-Commander](https://github.com/8ca8/matrix-commander)** – A lightweight CLI tool to send and receive messages over the Matrix protocol.
4. **[w3m](https://w3m.sourceforge.net/)** – A text-based web browser with excellent table rendering and inline image support in compatible terminals.
5. **[Elinks](http://elinks.cz/)** – A full-featured text-mode web browser supporting tabs, scripting, and tables.
6. **[WeeChat](https://weechat.org/)** – A fast, lightweight, and heavily extensible chat client designed for the terminal.
7. **[Gomuks](https://github.com/tulir/gomuks)** – A terminal-based Matrix client written in Go with a responsive chat interface.

---

## Development & Utilities

Handy command-line helpers, revision control tools, and environment multiplexers for mobile hackers.

1. **[gitui](https://github.com/extrawurst/gitui)** – A super-fast TUI client for Git supporting smooth keyboard and touch interactions.
2. **[Thonny](https://thonny.org/)** – The standard Python IDE for Raspberry Pi; features a dedicated "Simple Mode" that configures nicely on compact screens.
3. **[tmux](https://github.com/tmux/tmux)** – A terminal multiplexer to manage multiple console sessions in tabs and splits on a small display.
4. **[Lazygit](https://github.com/jesseduffield/lazygit)** – A simple terminal UI for git commands with intuitive panel navigation.
5. **[GNU Screen](https://www.gnu.org/software/screen)** – A classic terminal multiplexer for session persistence.
6. **[fzf](https://github.com/junegunn/fzf)** – A general-purpose command-line fuzzy finder for lightning-fast file and history navigation.
7. **[Broot](https://dystroy.org/broot)** – A new way to see and navigate directory trees with deep search capabilities.

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue if you know of any other fantastic TUI or touch-friendly apps optimized for low-res handhelds like the PocketTerm35.

---

<div align="center">
  <p>Maintained with ❤️ for the Raspberry Pi and Handheld community.</p>
</div>
