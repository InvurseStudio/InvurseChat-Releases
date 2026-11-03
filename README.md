<p align="center">
  <img src="assets/VireoIcon.svg" alt="Vireo icon" width="140" height="140">
</p>

<h1 align="center">Vireo</h1>

<p align="center"><em>Formerly InvurseChat</em></p>

<p align="center">
  <strong>Private AI that runs on your Mac.</strong><br>
  Open models like Gemma and Qwen, running on your own hardware.<br>
  Chat from your Mac or your Windows PC. Your conversations never leave home.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/github/v/release/InvurseStudio/Vireo-Releases?label=latest&color=5B4FD6&style=flat-square" alt="Latest release"></a>
  <img src="https://img.shields.io/badge/macOS-14%2B-17171C?logo=apple&logoColor=white&style=flat-square" alt="macOS 14 or later">
  <img src="https://img.shields.io/badge/Apple%20Silicon-M1%20or%20later-17171C?logo=apple&logoColor=white&style=flat-square" alt="Apple Silicon">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-17171C?logo=windows&logoColor=white&style=flat-square" alt="Windows 10 or 11">
  <img src="https://img.shields.io/badge/made%20in-Canada%20%F0%9F%8D%81-C9C1FF?style=flat-square" alt="Made in Canada">
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download%20for%20Mac-5B4FD6?logo=apple&logoColor=white&style=for-the-badge" alt="Download for Mac"></a>
  &nbsp;
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/Download%20for%20Windows-17171C?logo=windows&logoColor=white&style=for-the-badge" alt="Download for Windows"></a>
</p>

<p align="center">
  <img src="assets/screenshot-mac.png" alt="Vireo on macOS: a chat with a model running on the Mac, showing the steps it took" width="820">
</p>

---

## Why Vireo

<table>
<tr>
<td width="50%" valign="top">

### 🔒 Private by design
The model runs on your Mac and your chats are saved there. No account, no
cloud, no analytics. Nothing to sign up for.

</td>
<td width="50%" valign="top">

### ⚡ Fast on Apple Silicon
Built on MLX, with llama.cpp for GGUF models. First-run setup picks a model
that fits your Mac's memory.

</td>
</tr>
<tr>
<td valign="top">

### 🔎 Any model you like
Search Hugging Face from the app and see at a glance whether a model fits.
Or add the models you already have, including an LM Studio library.

</td>
<td valign="top">

### 📎 Works with your files
Drop in PDFs, Word documents, spreadsheets, text and images, and ask about
them. It can search the web when a question needs current information.

</td>
</tr>
<tr>
<td valign="top">

### ✅ You stay in control
Deleting or moving files, running commands and exporting documents all wait
for your approval. You see each step as it works.

</td>
<td valign="top">

### 💻 Your Mac, from your PC
Pair a Windows PC with a one-time code and chat with your Mac's model from
there. Other apps can use it too, through an OpenAI-compatible API.

</td>
</tr>
<tr>
<td valign="top">

### 🗓️ Keeps track of your day
Ask what's on today, find a free hour, or add events and reminders. Get a
morning briefing, have it run tasks on a schedule, and tell it what to remember.

</td>
<td valign="top">

### ✨ Quick Ask, from any app
A small panel over whatever you're doing. Type, or hold a shortcut and talk.
Speech is recognised on your Mac.

</td>
</tr>
</table>

## Coming in 0.8

The screenshot above is from the next update, the first under the Vireo name:

- A new look, in the colours of [invursestudio.com](https://invursestudio.com).
- Each step shows as a checklist while it works, then folds away when the answer is done.
- Small actions like adding a reminder are approved right in the reply.
- **Undo this run** puts back the files a reply changed, and deleted files go to the Trash.
- Chats name themselves and are grouped by day.

## Download

Grab the latest version from the **[Releases page](../../releases/latest)**.

Releases up to 0.7.7 and the Windows client still use the name InvurseChat. Your
chats and settings carry over.

| | Mac | Windows |
| --- | --- | --- |
| **File** | `Vireo-<version>-arm64.dmg` | `InvurseChat-Setup-<version>-x64.exe` (installer), or `InvurseChat-Portable-<version>-x64.exe` to run without installing |
| **Role** | Runs the model and keeps your chats | Chat client for your Mac |
| **Needs** | Apple Silicon (M1 or later), macOS 14 or later | Windows 10 or 11 (x64), and Vireo on a Mac on the same network |

### How much memory do I need?

| Model | Minimum | Recommended | Download |
| --- | --- | --- | --- |
| Gemma 4 E2B | 8 GB | 12 GB | ~2 GB |
| Gemma 4 E4B | 12 GB | 16 GB | ~4.5 GB |
| Gemma 4 26B | 24 GB | 32 GB | ~28 GB |

Not sure? The app looks at your Mac and recommends one the first time you
open it.

## Getting started

<details open>
<summary><strong>On your Mac</strong></summary>

1. Open the DMG and drag **Vireo** to **Applications**.
2. Open Vireo. Setup recommends a model for your Mac and downloads it.
3. Start chatting. Attach files with **+** or by dragging them in.

</details>

<details>
<summary><strong>On your Windows PC</strong></summary>

1. Run `InvurseChat-Setup-<version>-x64.exe`.
   The installer isn't code-signed yet, so Windows SmartScreen may say
   "Windows protected your PC". Choose **More info**, then **Run anyway**.
2. On your Mac, open Vireo **Settings**, turn on **Allow network
   access**, and choose **Pair a Device…**.
3. Enter the code shown on your Mac in the Windows app.

</details>

## Updates

The Mac app checks for new versions and installs them for you (you can turn
this off in Settings, or choose **Vireo › Check for Updates…** at any
time). Every update is signed, and checked before it's installed.
The Windows app doesn't update itself yet: download the new installer from
the [Releases page](../../releases/latest).

## FAQ

<details>
<summary><strong>Does it work offline?</strong></summary>

Yes. Once a model is downloaded, chatting works with no internet connection.
Only web searches, weather, model downloads and update checks need to go
online.

</details>

<details>
<summary><strong>Does it work on an Intel Mac?</strong></summary>

No. Running models locally needs Apple Silicon (M1 or later).

</details>

<details>
<summary><strong>Can I use it away from home on my PC?</strong></summary>

The Windows app connects to your Mac over your local network, so both need to
be on the same network, and your Mac needs to be on.

</details>

<details>
<summary><strong>Can I use my own models?</strong></summary>

Yes. Search Hugging Face for any MLX or GGUF model from the app, or add a
folder of models you already have.

</details>

<details>
<summary><strong>What about iPhone and iPad?</strong></summary>

Companion apps are on the way in a future update.

</details>

## About

Vireo is my first major app. I started it to learn how local AI really
works: running models on a Mac, streaming replies, tools, and connecting other
devices. Along the way it grew into the app I wanted to use every day.

It's made by one person at Invurse Studio in Canada, and it's still early. It's
also signed and notarized by Apple, updates itself safely, and never collects
your data. If something's rough or you have an idea,
[let me know](#feedback). Feedback is how it gets better.

I used Claude, Anthropic's AI, along the way to find bugs, review code, and
implement fixes and polish.

## Privacy

Vireo collects nothing: no accounts, analytics or tracking. Read the
full [privacy policy](PRIVACY.md).

## Feedback

Found a bug or have an idea? [Open an issue](../../issues/new) on GitHub, or
email [hello@invursestudio.com](mailto:hello@invursestudio.com) if you don't
have a GitHub account.

---

<p align="center">
  <img src="assets/VireoIcon.svg" alt="" width="28" height="28"><br>
  Developed in Canada 🍁 by <strong>Invurse Studio</strong>
</p>
