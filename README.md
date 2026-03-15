<div align="center">
  <img src="logo.png" width="120" alt="Codictate" />

  # Codictate

  **Local, private voice dictation for macOS - press a shortcut, speak, done.**
</div>

Codictate puts your words wherever your cursor is - no copy-pasting, no switching windows, no cloud. It runs entirely on your machine using local AI models, so nothing you say ever leaves your device.

---

## Why I built this

I was a happy user of tools like Wispr Flow and SuperWhisper. They're great - until they aren't free anymore.

What bothered me wasn't just the price. It was the principle: these tools send your voice to a server somewhere, process it, and send text back. That means someone else's infrastructure is listening. And the moment the pricing changes, you're stuck.

So I decided to build my own. But I also gave myself a challenge: learn a completely new technology stack in the process, and do it **without using AI** to write a single line of code - at least not until the app was working well enough that I could dictate into it and have my words appear on screen.

The idea was simple and a little absurd: I'd only unlock AI assistance once I'd built the very thing that would let me use it. It forced me to actually understand what I was building, read the docs properly, and think through the problems myself.

Codictate is the result - fully local, fast, and free.

---

## Support

Codictate is free. If it saves you money on other tools, consider buying me a coffee - it helps me keep working on it.

[☕ ko-fi.com/emillykke](https://ko-fi.com/emillykke)

---

## Download

Go to [Releases](https://github.com/EmilLykke/codictate-releases/releases) and download the latest `.dmg`.

| Channel | Description |
|---------|-------------|
| **Stable** | Recommended for most users |
| **Canary** | Latest features, updated more frequently |

---

## Installation

First time installing? See the **[step-by-step installation guide](INSTALL.md)** with screenshots for every step.

The short version:
1. Download the `.dmg` from [Releases](https://github.com/EmilLykke/codictate-releases/releases)
2. Drag **Codictate** to your Applications folder
3. Run `xattr -cr /Applications/Codictate.app` in Terminal if macOS blocks it
4. Grant the required permissions when prompted (Input Monitoring, Accessibility, Microphone)

---

## Requirements

- macOS 13 or later
- Apple Silicon (M1 or later)
- No internet connection required after install

---


## Privacy

- No account, no login
- No data collection
- No analytics
- Everything runs locally on your device
