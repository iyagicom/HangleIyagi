# HangleIyagi Norin

**A Korean input method for Linux that never loses the last character — every keystroke becomes a finished syllable right away. Works on Wayland and GNOME.**

[English](README.md) · [한국어](README_ko.md)

## Why HangleIyagi?

- **The last character stays.** Ordinary Korean IMEs hold a "composing" state, so clicking elsewhere or moving focus mid-word can swallow the last syllable. HangleIyagi keeps no composing state — it commits finished syllables immediately.
- **Search sees what you typed.** Because the text is already committed, search boxes and autocomplete react to the very last character.
- **Fewer keystrokes.** Type `ㅏ` and get `아` — no need for the silent initial `ㅇ`. 20–30% fewer keys, and your rhythm never breaks.
- **Your layout.** Dubeolsik, Sebeolsik 390, Sebeolsik Final (391), plus a **custom layout** editor — click a key on the keyboard picture to reassign it.
- **Typed in the wrong mode?** Text typed in English mode is converted to Hangul when you switch.
- **Works in every app.** GTK3, GTK4, Qt5, Qt6 and XIM (terminals, Wine) — Chrome, Tilix and Google Docs included. X11 and Wayland.

## Features

- Dubeolsik · Sebeolsik 390 · Sebeolsik Final (391) · custom layout editor
- Han/Eng toggle — Hangul key, Shift+Space, Ctrl+Shift, or any key you choose
- English-to-Hangul auto conversion; choose the start mode (English / Hangul / last used)
- Auto-commit on focus change, per-key delete
- Word candidates and autocomplete, user dictionary that learns
- Manager window (`hangleiyagi-manager`) for every setting
- D-Bus signal so other apps can show the current input mode

## Download

**[⬇ Latest release](https://github.com/iyagicom/HangleIyagi/releases/latest)**

| Your system | File to pick |
|---|---|
| Ubuntu 24.04 · Debian | `.deb` marked **ubuntu24.04** |
| Ubuntu 26.04 | `.deb` marked **ubuntu26.04** |
| Fedora · openSUSE | `.rpm` |
| Arch · Manjaro | `.pkg.tar.zst` |
| Any other Linux | `.zip` |

```bash
sudo apt install ./hanguliyagi_*_amd64.deb   # Ubuntu / Debian
```

After installing, choose **HangleIyagi** under **Settings → System → Region & Language → Keyboard input method** and log in again.

## License

[License](LICENSE)
