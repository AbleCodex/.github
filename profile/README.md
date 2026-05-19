# AbleCodex

**Talk to Claude Code on your computer, from your phone.**

AbleCodex is an Android app that gives you a comfortable chat interface for [Claude Code](https://claude.com/claude-code) running on your laptop. Your phone stays in sync with every Claude Code session you have open on the computer — and with any new one you start — so you can dictate prompts, listen to replies, and switch between projects without sitting at your desk.

> **Status: closed beta — validating interest.** The Android app is built and working; the helper that runs on the computer is currently a Node.js script you launch from a terminal (no installer or system tray yet, only Windows validated end-to-end). Pricing for the eventual public release is being figured out. **Today, AbleCodex is free.** If the niche resonates with you, install it and [start a Discussion](https://github.com/AbleCodex/ablecodex/discussions) — that feedback is what tells us whether to keep going.

---

## What you get

<table>
<tr>
<td width="50%" valign="top">

### A chat shaped for Claude Code

A clean Android UI built for one job: talking to Claude Code. Bubbles, reply cards, streaming text, copy and share — none of the friction of using a terminal on a phone.

</td>
<td width="50%" valign="top" align="center">

<img src="Chat.png" width="260" alt="AbleCodex chat — header, your message, Claude streaming a reply" />

</td>
</tr>
<tr>
<td valign="top">

### Synced to your terminals

Your phone sees every Claude Code session you have open on the computer — the one you launched from a terminal an hour ago, plus any new one you start from the AbleCodex drawer. Switch between them with one tap.

</td>
<td valign="top" align="center">

<img src="Drawer.png" width="260" alt="AbleCodex drawer — chat list with green status dots and the New chat button" />

</td>
</tr>
<tr>
<td valign="top">

### Voice input

Dictate prompts with the microphone — the waveform reacts to your voice as you speak. Android's built-in speech recognizer transcribes what you say; edit the text or send it straight away.

</td>
<td valign="top" align="center">

<img src="Audio-Recording.png" width="260" alt="AbleCodex recording a voice message — moving waveform in place of the composer" />

</td>
</tr>
<tr>
<td valign="top">

### Voice playback

Tap the speaker icon under any reply and Claude reads it back to you. Three speed pills (1x, 1.5x, 2x) work mid-playback. Use the phone's built-in text-to-speech for free, or link your own ElevenLabs account for a high-quality voice — AbleCodex falls back to the system voice if the API is unreachable.

</td>
<td valign="top" align="center">

<img src="Waveform.png" width="260" alt="AbleCodex playing back a reply — wave animation above the composer, speed pills active" />

</td>
</tr>
<tr>
<td valign="top">

### Settings you'll actually use

Pick the font you read best in, choose what fires a notification, reduce motion if animations bother you, export a backup of your configuration. Nothing you have to touch on day one; everything you might want on day thirty.

</td>
<td valign="top" align="center">

<img src="Settings.png" width="260" alt="AbleCodex Settings — Transcription, Language, Typography, Notifications, Accessibility, Data and backup, About" />

</td>
</tr>
<tr>
<td valign="top">

### One UI, two languages

Spanish and English live-switchable from Settings. The whole app re-renders instantly, and Claude follows the same language by default for new replies. More languages on the roadmap.

</td>
<td valign="top" align="center">

<img src="Language-Picker-EN.png" width="260" alt="App language picker showing Spanish and English options" />

</td>
</tr>
</table>

---

## What you don't get

- **No screen mirroring.** AbleCodex is a chat app, not a remote desktop. If you want to see your laptop screen on your phone, pick something else.
- **No vendor lock-in.** Your chats live on your phone and on your computer. There is no AbleCodex cloud server in the middle of your conversation.
- **No surprise bills.** AbleCodex itself is free during the open beta. The Claude usage you'd have anyway from your computer is what costs money — AbleCodex doesn't add to it.

---

## Get started (about ten minutes during the beta)

1. Install [Claude Code](https://docs.claude.com/en/docs/claude-code/quickstart) on your computer. Confirm `claude --version` works in a terminal.
2. Install Node.js 20+ if you don't already have it.
3. Clone this repo, `cd ablecodex/bridge`, run `npm install`, then `node index.js`. Keep that terminal open — it's the helper. See [Installation](https://github.com/AbleCodex/ablecodex/wiki/Installation).
4. Download the APK from the [Releases](https://github.com/AbleCodex/ablecodex/releases) page (or ask in Discussions if no signed build is up yet). Install it on your Android phone.
5. Open AbleCodex on the phone → Start → scan the QR code in the helper terminal → you're paired. See [First-Time Setup](https://github.com/AbleCodex/ablecodex/wiki/First-Time-Setup).
6. Tap a suggestion bubble and you're rolling.

> Today's flow is intentionally rough — installers, system-tray UI, and auto-start are on the [Roadmap](https://github.com/AbleCodex/ablecodex/wiki/Roadmap). If a manual setup blocks you, that itself is useful feedback — say so in Discussions.

Full documentation lives in the [Wiki](https://github.com/AbleCodex/ablecodex/wiki).

---

## Links

- 📘 [Documentation Wiki](https://github.com/AbleCodex/ablecodex/wiki)
- 📦 [Releases](https://github.com/AbleCodex/ablecodex/releases/latest)
- 💬 [Discussions](https://github.com/AbleCodex/ablecodex/discussions)
- 🐛 [Issues](https://github.com/AbleCodex/ablecodex/issues)
- 🗺️ [Roadmap](https://github.com/AbleCodex/ablecodex/wiki/Roadmap)
