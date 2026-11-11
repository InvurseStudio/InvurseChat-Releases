# Vireo privacy policy

_Last updated November 11, 2026._

Vireo (formerly InvurseChat) is made by Invurse Studio. It runs AI models on your own Mac, and
it's built so that your conversations stay with you.

## What we collect

Nothing. Vireo has no accounts, analytics, crash reporting, advertising
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
  runs on your Mac. You can turn that off in Settings → Model.
- **Scheduled tasks** you set up run on your Mac. What they did is kept in an
  activity log on your Mac, and their results are saved as chats like any other.
  Changes a task wants to make wait for your approval, unless you chose "Don't
  ask again" for that kind of change.
- **Calendar and Reminders** are off until you turn them on in Settings →
  Connections and allow access in macOS. The assistant reads them on your Mac,
  only from the calendars and lists you choose. It asks you before it adds,
  changes or completes anything, unless you chose "Don't ask again" for that
  kind of change, and always asks before deleting. Vireo doesn't copy them
  anywhere. Event details the assistant reads become part of that chat, which
  is saved like any other chat, including on a paired device that asked.
- **Voice.** When you ask Quick Ask by voice, or turn on the "Hey Vireo" wake
  word, your speech is turned into text on your Mac with Apple's on-device
  speech recognition. Audio isn't saved or sent anywhere. The wake word is off
  until you turn it on.
- **Memory** holds facts you ask the assistant to remember. It asks before
  saving one. With "Notice things worth remembering" on, it can also offer to
  remember a lasting fact you mention about yourself; only your own messages are
  read for this, never documents, web pages or tool results. Facts are stored on
  your Mac, the most relevant are added to your chats' instructions, and you can
  see, edit or delete them in Settings → Memory, or turn memory off.
- **Earlier chats.** So the assistant can find something you discussed before,
  your chats are indexed on your Mac. The index stays there, and a chat you
  delete is dropped from it the next time it's searched.
- **Long chats** that outgrow the model's memory get a running summary of their
  earlier part, written on your Mac and saved with the chat. Deleting the chat
  deletes it.
- **Learned skills.** After a long job, Vireo may offer to save how it did it as
  a skill. The offer waits in Window → Assistant → Approvals and nothing is
  saved until you approve it. Skills are files on your Mac. You can turn this
  off in Settings → Assistant.
- **Contacts and files.** Contacts are off until you turn them on in Settings →
  Memory. When you ask about your own life or work, the assistant can search
  them and your files on your Mac: Documents, Desktop, Downloads and iCloud Drive
  until you change that list, through Spotlight. It only reads them and doesn't
  copy them anywhere; what it finds becomes part of that chat.
- **Watched folders** you add in Settings → Memory are indexed on your Mac so
  the assistant can search them. Their files are only read, never changed or
  copied anywhere; the index stays on your Mac, and removing a folder removes
  its files from the index.
- **Your screen.** When you ask about what's on screen, the assistant reads the
  window you were using (or the whole screen, without Vireo's own windows) with
  Apple's on-device text recognition. It asks first, unless you chose "Don't
  ask again", and needs macOS's Screen Recording permission. The image isn't
  saved or sent anywhere; the text it reads becomes part of that chat. It's
  never done for paired devices or scheduled tasks.
- **Undo copies.** When the assistant changes or replaces a file, it keeps a
  private copy of what was there on your Mac, so **Undo this run** can put it
  back. Copies are deleted after 14 days. Files it deletes go to your Trash.
- **Pages, Numbers and Keynote files** are read by having that app export a
  temporary Word, Excel or PowerPoint copy on your Mac, which is deleted
  straight after. This needs macOS's Automation permission for that app. An app
  Vireo opens for this is closed again; your own open documents aren't saved or
  changed.
- **Shortcuts** run only when you ask the assistant to, and it asks before each
  run. A shortcut can do anything it was built to do, including going online,
  and Vireo can't undo it.
- **Task triggers.** A scheduled task can also start when new files arrive in a
  folder you choose, or when its private link is opened. Anyone who has the
  link and can reach your Mac (from the Mac itself, or from your network when
  Allow network access is on) can start that task and send it text. That text
  is treated like a web page: changes the task wants to make still ask first.
  Changing the task's trigger makes a new link.
- **Messages** are sent only when you ask the assistant to message someone. It
  shows you the message and asks first, unless you chose "Don't ask again" for
  messages. They go from your own Messages account, like any message you send.

You can delete chats in the app. Uninstalling the app and removing
`~/Library/Application Support/InvurseChat` removes everything it stored.

## When the app goes online

Vireo connects to the internet only for these things:

| When | Service | What it receives |
| --- | --- | --- |
| The Mac app checks for updates (about once a day, if you allow it, or when you choose Check for Updates) | GitHub, where releases are published | A normal download request, which names the app and its version |
| You download or search for a model | Hugging Face | The name of the model or search |
| You attach your first document, add a watched folder, or the assistant first uses memory (a small search model is downloaded once) | Hugging Face (Google's EmbeddingGemma, or Qwen3-Embedding when a Qwen 3 model is loaded) | A normal download request |
| A request needs the web (for example, you ask about current events) | DuckDuckGo, with Bing as a fallback | The search words |
| A request needs the web, and you turned on a search provider in Settings → Connections (Brave Search, Tavily, Exa, Kagi, or your own SearXNG) | That provider, tried in the order you set | The search words and the key you entered for it |
| The model opens a web page it found | That website | A normal page request |
| You add an MCP server in Settings → Connections, and the assistant uses one of its tools | The server you set up (servers that run on your Mac don't go online unless they do so themselves) | What the assistant sends to that tool |
| You ask about the weather, or your daily briefing includes it | Open-Meteo, with wttr.in as a fallback | The place you asked about. If you don't name a place, wttr.in estimates it from your internet address. |

Search providers in Settings → Connections are off until you turn one on. Their
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

Vireo isn't directed at children under 13, and it doesn't knowingly
collect anyone's information.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions: [hello@invursestudio.com](mailto:hello@invursestudio.com)
