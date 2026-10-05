# Awesome-Text-Editor

# Top Text Editor Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Code Editing, Modal Workflows & Extensible Editing Environments*  
**Last updated: October 2026**

This repository tracks notable **commercial text editors** and **open-source projects** that provide powerful editing environments — from lightweight notepad replacements to fully extensible code editors and terminal-based modal editors.

**Examples** include Windows Notepad, Notepad++, Sublime Text, Visual Studio Code, UltraEdit, BBEdit, Atom, TextMate, Vim, and GNU Emacs (the category leaders).

**Open-source emphasis**: Text editing is one of the strongest open-source domains. **VS Code**, **Vim**, **Neovim**, **Emacs**, and **Kate** collectively power millions of developers worldwide, with **Zed** and **Lapce** emerging as Rust-based performance-focused alternatives. **Micro** and **Helix** bring modern UX to terminal editing. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Sublime Text](https://www.sublimetext.com/)**  
  Legendary proprietary editor known for speed, multiple cursors, and the Command Palette. **One-time purchase** ($99) with free evaluation. **The editor that inspired VS Code's UX** — still beloved for its performance and minimalism .

- **[UltraEdit](https://www.ultraedit.com/)**  
  Powerhouse commercial editor with hex editing, large file handling, macros, scripting, and FTP/SFTP support. **Subscription-based**. Popular in enterprise and data processing workflows .

- **[BBEdit](https://www.barebones.com/products/bbedit/)**  
  macOS-only professional text editor since 1992. **Free mode available** with paid Pro features. **The standard for macOS developers** wanting native performance and deep text processing .

- **[TextMate](https://macromates.com/)**  
  macOS editor that pioneered snippets, bundles, and the concept of scoped editing. **Open-sourced in 2012** but development has slowed. **Historically influential** — inspired Sublime Text and VS Code grammars .

## Open-Source GitHub Projects

- **[Visual Studio Code](https://github.com/microsoft/vscode)**  
  **The most widely used code editor in the world**, MIT licensed with 160,000+ GitHub stars . Built with Electron and TypeScript. **Extensions ecosystem with 50,000+ plugins**, integrated terminal, Git, debugging, and IntelliSense . **VS Code OSS** is the open-source core; Microsoft's branded builds add telemetry and proprietary marketplace access. **Note**: The marketplace and some Microsoft-specific extensions are proprietary . **The de facto standard for modern development** — free and cross-platform.

- **[Vim](https://github.com/vim/vim)**  
  **The legendary modal text editor**, charityware licensed with 38,000+ GitHub stars . Terminal-based with incredibly efficient keyboard-driven editing. **Available on virtually every Unix-like system** — often pre-installed . Highly configurable via vimrc and thousands of plugins. **Steep learning curve but unmatched editing speed** once mastered .

- **[Neovim](https://github.com/neovim/neovim)**  
  **Modern refactor of Vim** with Lua scripting, built-in LSP, treesitter, and async plugin architecture . Apache-2.0 licensed with 85,000+ GitHub stars . **The preferred choice for new Vim users** — better defaults, active development, and a thriving plugin ecosystem (lazy.nvim, telescope, nvim-cmp) . **Turns Vim into a full IDE** without Electron overhead.

- **[GNU Emacs](https://github.com/emacs-mirror/emacs)**  
  **The extensible, customizable, self-documenting editor**, GPL licensed with 4,500+ GitHub stars (mirror) . **More than an editor — a Lisp environment** that happens to edit text. Org-mode, Magit, Dired, and thousands of packages make it a complete workflow platform . **The most extensible editor ever created** — but requires investment to configure .

- **[Zed](https://github.com/zed-industries/zed)**  
  **High-performance, multiplayer code editor** written in Rust, GPL-3.0 licensed with 60,000+ GitHub stars . Built by the creators of Atom and Tree-sitter. **GPU-accelerated rendering**, built-in collaboration, and AI integration . **The fastest modern editor** — native performance without Electron . Available on macOS and Linux; Windows in development.

- **[Lapce](https://github.com/lapce/lapce)**  
  **Lightning-fast and powerful code editor written in Rust**, Apache-2.0 licensed with 35,000+ GitHub stars . **Built-in LSP, remote development, Vim mode, and WASI plugin system** . Custom GPU-accelerated renderer using Floem UI toolkit . **The most feature-complete Rust editor** after Zed — smaller community but rapid development .

- **[Kate](https://github.com/KDE/kate)**  
  **KDE's advanced text editor**, LGPL-2.0 licensed . **Multi-document interface, session management, LSP support, and extensive plugin ecosystem** . **The best GUI editor for KDE Plasma** — integrates with Dolphin and Konsole. Available on Linux, Windows, and macOS .

- **[Micro](https://github.com/zyedidia/micro)**  
  **Modern and intuitive terminal-based text editor**, MIT licensed with 25,000+ GitHub stars . **Feels like Nano but works like a GUI editor** — familiar keybindings (Ctrl+S, Ctrl+Q), mouse support, and syntax highlighting . Single binary with no dependencies . **The best choice for users wanting terminal editing without Vim's learning curve** .

- **[Helix](https://github.com/helix-editor/helix)**  
  **Post-modern modal text editor**, MPL-2.0 licensed with 35,000+ GitHub stars . **Built-in LSP, treesitter, and multiple selections** by default . **Kakoune-inspired selection-first workflow** — different from Vim but logical . **The most promising Vim alternative** for users wanting modal editing with modern defaults .

- **[Lite XL](https://github.com/lite-xl/lite-xl)**  
  **Lightweight, fast, and simple code editor**, MIT licensed with 5,000+ GitHub stars . Written in C and Lua with **minimal resource usage** . **The spiritual successor to Atom** — extensible via Lua plugins without Electron overhead .

- **[CudaText](https://github.com/Alexey-T/CudaText)**  
  **Cross-platform text editor** with syntax highlighting for 300+ languages, code folding, and extensive plugin support . **Free and open-source** with a large feature set comparable to Notepad++ .

- **[Geany](https://github.com/geany/geany)**  
  **Lightweight IDE** using GTK+ with syntax highlighting, code completion, and plugin support . **The classic Linux text editor/IDE hybrid** — fast, stable, and minimal dependencies .

### Additional Strong Open-Source Options

- **Notepad++** — Windows-only open-source editor (GPL) with syntax highlighting, macros, and plugin ecosystem. **The standard Windows notepad replacement** .
- **Gedit** — GNOME's text editor with plugin support, now largely replaced by GNOME Text Editor .
- **GNOME Text Editor** — Modern GNOME editor with session restore, search, and clean interface .
- **Kakoune** — Modal editor with multiple selections and orthogonal design, inspiring Helix .
- **amp** — Terminal-based modal editor written in Rust .
- **Xi Editor** — Experimental editor with rope data structure and modern architecture (development slowed).

**Frameworks for building custom text editing solutions**: Choose based on workflow. **VS Code** for the largest extension ecosystem and general-purpose development . **Neovim** for terminal-based modal editing with modern Lua configuration and LSP . **Emacs** for maximum extensibility and workflow integration via Lisp . **Zed** or **Lapce** for Rust-native performance without Electron . **Micro** for terminal editing with familiar keybindings . **Helix** for modern modal editing with selection-first workflow . **Kate** for KDE-native GUI editing . Note that true commercial editors like Sublime Text and BBEdit offer polished experiences with one-time purchase, but open-source alternatives match or exceed their capabilities for most workflows .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Text editors handle source code, configuration files, and potentially sensitive data. Self-hosted or local editors generally keep data on-device, but cloud-synced settings or AI features may transmit data externally. **Review privacy settings before use**.
- **VS Code's marketplace and some Microsoft extensions are proprietary** — the OSS core is MIT licensed, but the full experience includes closed components . **VSCodium** provides a fully open-source build.
- **Modal editors (Vim, Neovim, Helix, Kakoune) require learning investment** — the productivity gains are real but not immediate .
- The open-source ecosystem provides strong editing, extension, and performance foundations across terminal and GUI environments, but **proprietary polish, vendor support, and integrated AI features** remain primarily commercial offerings.

---

**Made for developers, writers, system administrators, and anyone who lives in a text editor.**  
Let's make text editing more open, transparent, and powerful.
