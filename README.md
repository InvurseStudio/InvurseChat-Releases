<p align="center">
  <img src="assets/VireoIcon.svg" alt="Vireo icon" width="140" height="140">
</p>

<h1 align="center">Vireo</h1>

<p align="center"><em>Formerly InvurseChat</em></p>

<p align="center">
  <strong>The private AI agent that does real work on your Mac.</strong><br>
  Hand it a job, not just a question. It works through your files, plans the steps,<br>
  checks its work and asks before it changes anything.<br>
  Open models like Gemma and Qwen, running on your own hardware. Nothing leaves home.
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
  <a href="../../releases/tag/v0.7.7"><img src="https://img.shields.io/badge/Download%20for%20Windows-17171C?logo=windows&logoColor=white&style=for-the-badge" alt="Download for Windows"></a>
</p>

<p align="center">
  <img src="assets/screenshot-mac.png" alt="Vireo on macOS: a chat with a model running on the Mac, showing the steps it took" width="820">
</p>

---

## An agent, not just a chat window

Vireo started as a private chat app. Now it's an agent: give it a job and it gets
on with it. It reads your files, uses tools on your Mac, works through each step
and comes back with the work done, not just an answer.

- *"Process the November invoices in Finance and log them in the tracker."*
- *"Sort these donation requests against our policy and draft the replies."*
- *"Fill the sponsorship template for Harbour Lane, then make a slide deck from it."*
- *"Check this trip against the travel policy and work out the per diems."*
- *"Every time a new invoice lands in this folder, log it."*

**How a job runs**

1. **It plans.** Longer jobs get a short checklist, and you can see the step it's on.
2. **It uses real tools.** It reads and writes Word, Excel and PowerPoint files,
   reads Pages, Numbers and Keynote, searches your files, earlier chats and the
   web, checks your calendar, runs your Shortcuts, and does sums with an exact
   calculator. MCP servers add more.
3. **It follows your rules.** It reads the policy that applies, flags what doesn't
   fit, and marks things as pending until someone approves them.
4. **It checks its work.** Turn on **Check its work**, and after a job that
   changed files it looks over the result and fixes mistakes before you see it.
5. **You approve, and can undo.** Changes wait for your OK, and **Undo this run**
   puts back any files it changed.
6. **It learns.** After a long job it can offer to save how it did it as a skill,
   and it remembers the people and facts that matter, once you approve.

It can also work on its own: on a schedule, when new files arrive in a folder,
or when a private link is opened. Changes it wants to make still wait for you.

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
Word, Excel, PowerPoint, Pages, Numbers, Keynote, PDFs, text and images. It
reads them, fills templates, updates spreadsheets and builds decks, and keeps
the folders you choose indexed so it can find things by what they say.

</td>
</tr>
<tr>
<td valign="top">

### ✅ You stay in control
Deleting or moving files, running commands and exporting documents all wait
for your approval. You see its plan and each step as it works, it can check
its own work, and **Undo this run** puts back any files it changed.

</td>
<td valign="top">

### 💻 Your Mac, from your PC
Pair a Windows PC with a one-time code and use your Mac's model from there.
Other apps can use it too, through an OpenAI-compatible API.

</td>
</tr>
<tr>
<td valign="top">

### 🗓️ Keeps track of your day
Ask what's on today, find a free hour, or add events and reminders. Get a
morning briefing, and hand off routine jobs to run on a schedule or when new
files arrive.

</td>
<td valign="top">

### ✨ Quick Ask, from any app
A small panel over whatever you're doing. Type, or hold a shortcut and talk.
Speech is recognised on your Mac.

</td>
</tr>
</table>

## Tested on real work

Before 0.9 shipped, three local models worked through a month of made-up office
work in Vireo: 32 tasks covering invoices, donations, events, travel, expenses
and inventory, plus four safety traps. The problems that turned up on Vireo's
side were fixed, and the whole test was run again.

| Model | Fully right (of 32) | Partly right | Wrong | Time |
| --- | --- | --- | --- | --- |
| Gemma 4 31B | 22 → **25** | 9 → 7 | 1 → **0** | 59 → **52** min |
| Muse Glimmer 30B | 16 → **24** | 15 → 8 | 1 → **0** | 86 → **79** min |
| Qwen 3.8 27B | 20 → **27** | 10 → 5 | 2 → **0** | 132 → **118** min |

No model got a task wrong after the fixes, and all three handled the safety
traps correctly both times. Each model ran once before and once after, so small
differences can be down to luck. Read the
[before-and-after report](test-results/Vireo-0.9-Before-After.pdf) (PDF) for
every task in plain language. All test data is fictional.

## Download

Grab the latest version from the **[Releases page](../../releases/latest)**.

Releases up to 0.7.7 and the Windows client still use the name InvurseChat. Your
chats and settings carry over.

Vireo 0.9 is for the Mac only. The current Windows app (0.7.5) is attached to the
[0.7.7 release](../../releases/tag/v0.7.7) and works with Vireo 0.9 on your Mac.
A new native Windows app is coming soon. See the
[0.9 release notes](../../releases/tag/v0.9.0) for everything that's new.

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

For agent jobs on your own files, larger models do noticeably better. The 0.9
tests used Gemma 4 31B, Qwen 3.8 27B and Muse Glimmer 30B, which suit Macs with
48 GB of memory or more. Gemma, Qwen and Muse Glimmer each get settings tuned for
agent work.

## Getting started

<details open>
<summary><strong>On your Mac</strong></summary>

1. Open the DMG and drag **Vireo** to **Applications**.
2. Open Vireo. Setup recommends a model for your Mac and downloads it.
3. Ask a question, or give it a job. Attach files with **+** or by dragging them in.

</details>

<details>
<summary><strong>On your Windows PC</strong></summary>

1. Run `InvurseChat-Setup-<version>-x64.exe`, from the
   [0.7.7 release](../../releases/tag/v0.7.7).
   The installer isn't code-signed yet, so Windows SmartScreen may say
   "Windows protected your PC". Choose **More info**, then **Run anyway**.
2. On your Mac, open Vireo **Settings › Sharing**, turn on **Allow network
   access**, and choose **Pair a Device…**.
3. Enter the code shown on your Mac in the Windows app.

</details>

## Updates

The Mac app checks for new versions and installs them for you (you can turn
this off in Settings, or choose **Vireo › Check for Updates…** at any
time). Every update is signed, and checked before it's installed.
The Windows app doesn't update itself yet: download the new installer from
the [Releases page](../../releases) when there is one.

## FAQ

<details>
<summary><strong>What's the difference between an assistant and an agent?</strong></summary>

An assistant answers. An agent does the work. Ask Vireo about a folder of
invoices and it can read each one, check them against your policy, add up the
totals, log them in your spreadsheet and draft the emails, showing each step as
it goes. It still asks before it changes anything.

</details>

<details>
<summary><strong>Will it change my files without asking?</strong></summary>

No. Writing, moving and deleting files, running commands, changing your calendar
and sending messages all wait for your approval. You can choose "Don't ask
again" for some kinds of change, but deleting files and running commands always
ask, and saving over an existing file always asks. **Undo this run** puts back
any files a job changed, and deleted files go to the Trash.

</details>

<details>
<summary><strong>Does it work offline?</strong></summary>

Yes. Once a model is downloaded, chats and agent jobs work with no internet connection.
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
devices. Along the way it grew into the app I wanted to use every day, and then
into an agent that can take real work off my plate.

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
