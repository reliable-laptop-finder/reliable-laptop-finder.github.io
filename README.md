# Reliable Laptop Finder

A static single-page tool that generates a research prompt for AI assistants — based on real Reddit reviews and user reports, not spec sheets.

**[reliable-laptop-finder.github.io](https://reliable-laptop-finder.github.io/)**

---

## What it does

You pick a laptop model (or several to compare), optionally set your country and preferred response language, and get a ready-to-use prompt. Paste it into ChatGPT, Gemini, Claude, or Perplexity to get a structured report covering:

- Overheating and CPU/GPU throttling under sustained load
- Fan noise levels and cooling effectiveness
- Battery degradation and real-world battery life
- Build quality — hinges, lid flex, keyboard, trackpad
- Display issues — backlight bleed, PWM flickering, color accuracy
- Wi-Fi / Bluetooth instability and port problems
- Webcam quality and hardware privacy shutter
- RAM and SSD — soldered or replaceable
- Linux compatibility and known driver issues
- Repairability and iFixit score
- Driver and BIOS stability
- Regional availability and warranty differences

The prompt instructs the AI to rely only on real user reports and public discussions — no fabricated facts or unsourced assumptions.

---

## How to use

1. Open [reliable-laptop-finder.github.io](https://reliable-laptop-finder.github.io/)
2. Select a laptop model or enter one manually
3. Optionally select your country and response language
4. Copy the generated prompt
5. Paste it into your AI assistant of choice

---

## Tech stack

Pure HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step. One file.

---

## Related

- [clean-phone-finder.github.io](https://clean-phone-finder.github.io/) — the same tool for smartphones