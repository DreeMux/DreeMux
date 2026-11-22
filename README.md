# DreeMux

Jarvis PowerShell dev. If it compiles, it ships. If it doesn't, it gets a new version number.

I write command-line tools, security self-tests, and experimental terminal interfaces using **Python**, **C++**, **JavaScript**, and **HTML**. Outside of desktop software, I spend time tinkering with console modding and homebrew setups across **PS3**, **PS5**, **Nintendo Switch**, **3DS**, and **2DS**.

### Projects

**[Jarvis-PowerShell](https://github.com)** is my main project: a Windows-PowerShell-style terminal written in pure Python that you can talk to in plain language. It stays read-only by default, finds your games, hunts down corrupted files, updates itself through 9 safety gates with rollback, and fuzzes its own commands with over 1,200 hostile payloads (`jarvis hack yourself`).

**phetarch-ui** is an Electron-based `.exe` UI concept simulating a low-level ROM flash, an interactive coldboot terminal (`boot`) with a Gemini Flash API reader, and a BlackArch-inspired desktop shell with an eDEX-style easter egg. It is concluded as a standalone visual prototype and kept ready to be wired up to an upcoming project currently in development.

### How I build & what I'm exploring

I prefer keeping core tools lightweight, modular, and safe by default—relying on the standard library whenever possible, verifying every change with self-tests, and avoiding unnecessary background writes.

Right now, alongside expanding Jarvis, I am exploring **Domain Shadowing**, **Tor network parameters and routing**, and practical **cryptography**.

### Contact

Found a bug, have an idea, or want to talk code? Open an issue on any repository or write to `DreeMux.dev@gmail.com`. Italian (native), English (conversational).
