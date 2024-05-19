# Ollama Chat App 🐐

Welcome to my Ollama Chat, this is an interface for the Official ollama CLI to make it easier to chat. It includes futures such as:

- Multiple conversations 💬
- Detect which models are available to use 📋
- Auto check if ollama is running ⏰
- Able to change the host where ollama is running at 🖥️
- Persistance 📀
- Light & Dark Theme 🌗

<br />

<img src="./.github/docs/preview-1.png" />

<br />

## How to build on your machine

### Requirements

- [Git](https://git-scm.com/)
- [NodeJS](https://nodejs.org/en) LTS 18
- [pnpm](https://pnpm.io/) 8.8.0+
- [rust](https://www.rust-lang.org/) 1.72.1=

<br />

1.  Clone the repo `git clone git@github.com:ollama-interface/Ollama-Gui.git`
2.  `pnpm i`
3.  `pnpm build:app:silicon` (:silicon or :intell or :universal) depending on your machine
4.  Go to `/src-tauri/target/release/bundle/dmg/*.dmg` and install the program with the .dmg file.

<br />

You as well you need to install [Ollama](https://ollama.ai) and after you installed it, you can run your local server with this command `OLLAMA_HOST=127.0.0.1:11435 ollama serve`.

## Thanks

This is fork of [Twan Luttik](https://github.com/ollama-interface/Ollama-Gui). Thanks for first implementation.
