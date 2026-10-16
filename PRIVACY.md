# InvurseChat privacy policy

_Last updated October 16, 2026._

InvurseChat is made by Invurse Studio. It runs AI models on your own Mac, and
it's built so that your conversations stay with you.

## What we collect

Nothing. InvurseChat has no accounts, analytics, crash reporting, advertising
or tracking. Invurse Studio doesn't receive your chats, files, prompts or
usage information, and has no servers that could.

## Where your data lives

- **Chats and settings** are saved as files on your Mac. If you use the
  Windows app, those chats are also saved on that PC.
- **Files you attach** are read on your Mac. Documents are indexed on your
  Mac so you can ask about them later.
- **The model** runs on your Mac. Your messages are not sent to any AI
  service. On Macs with Apple Intelligence, small jobs (writing the briefing,
  Summarize and Rewrite) use Apple's on-device model, which also
  runs on your Mac. You can turn that off in Settings → Advanced.
- **Scheduled tasks** you set up run on your Mac. What they did is kept in an
  activity log on your Mac, and their results are saved as chats like any other.
  Changes a task wants to make wait for your approval, unless you chose "Don't
  ask again" for that kind of change.
- **Calendar and Reminders** are off until you turn them on in Settings →
  Services and allow access in macOS. The assistant reads them on your Mac,
  only from the calendars and lists you choose. It asks you before it adds,
  changes or completes anything, unless you chose "Don't ask again" for that
  kind of change, and always asks before deleting. InvurseChat doesn't copy them
  anywhere. Event details the assistant reads become part of that chat, which
  is saved like any other chat, including on a paired device that asked.
- **Voice.** When you ask Quick Ask by voice, or turn on the "Hey Invurse" wake
  word, your speech is turned into text on your Mac with Apple's on-device
  speech recognition. Audio isn't saved or sent anywhere. The wake word is off
  until you turn it on.
- **Memory** holds facts you ask the assistant to remember. It asks before
  saving one. They're stored on your Mac, added to your chats' instructions,
  and you can see, edit or delete them in Settings → Memory, or turn memory off.
- **Contacts and files.** Contacts are off until you turn them on in Settings →
  Memory. When you ask about your own life or work, the assistant can search
  them and your files on your Mac: Documents, Desktop, Downloads and iCloud Drive
  until you change that list, through Spotlight. It only reads them and doesn't
  copy them anywhere; what it finds becomes part of that chat.
- **Messages** are sent only when you ask the assistant to message someone. It
  shows you the message and asks first, unless you chose "Don't ask again" for
  messages. They go from your own Messages account, like any message you send.

You can delete chats in the app. Uninstalling the app and removing
`~/Library/Application Support/InvurseChat` removes everything it stored.

## When the app goes online

InvurseChat connects to the internet only for these things:

| When | Service | What it receives |
| --- | --- | --- |
| The Mac app checks for updates (about once a day, if you allow it, or when you choose Check for Updates) | GitHub, where releases are published | A normal download request, which names the app and its version |
| You download or search for a model | Hugging Face | The name of the model or search |
| You attach your first document or the assistant first uses memory (a small search model is downloaded once) | Chroma's model files, on Amazon S3 | A normal download request |
| A request needs the web (for example, you ask about current events) | DuckDuckGo, with Bing as a fallback | The search words |
| A request needs the web, and you turned on a search provider in Settings → Services (Brave Search, Tavily, Exa, Kagi, or your own SearXNG) | That provider, tried in the order you set | The search words and the key you entered for it |
| The model opens a web page it found | That website | A normal page request |
| You ask about the weather, or your daily briefing includes it | Open-Meteo, with wttr.in as a fallback | The place you asked about. If you don't name a place, wttr.in estimates it from your internet address. |

Search providers in Settings → Services are off until you turn one on. Their
keys are stored in your Mac's Keychain.

These services have their own privacy policies. The app never sends your chat
history to them, only what the request needs.

## Your other devices and other apps

- Other devices can reach your Mac only after you turn on **Allow network
  access** and pair them with a one-time code. You can unpair a device at any
  time. On your local network, traffic between your devices is not encrypted.
- The OpenAI-compatible API is off until you turn it on. Apps on your Mac can
  use it; other devices need an API key that you create and can revoke.

## Children

InvurseChat isn't directed at children under 13, and it doesn't knowingly
collect anyone's information.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions: [hello@invursestudio.com](mailto:hello@invursestudio.com)
