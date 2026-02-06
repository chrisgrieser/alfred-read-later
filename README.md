# Read-Later for Alfred 🔖
![GitHub downloads](https://img.shields.io/github/downloads/chrisgrieser/alfred-read-later/total?label=GitHub%20Downloads&style=plastic&logo=github)
![Alfred Gallery downloads](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2Fchrisgrieser%2F.config%2Frefs%2Fheads%2Fmain%2FAlfred.alfredpreferences%2Falfred-gallery-downloads.yaml&query=read-later&style=plastic&logo=alfred&label=Gallery%20Downloads&color=%235C1F87)
![Latest release](https://img.shields.io/github/v/release/chrisgrieser/alfred-read-later?label=Latest%20Release&style=plastic)

Simple standalone read-later-app for Alfred. Saves the items in plaintext on
your device.

<img alt="showcase" width=70% src="https://github.com/chrisgrieser/alfred-read-later/assets/73286100/b82dbf42-370d-4faa-aaad-b2f4291be331">

## Usage
- Use the keyword `rl` to add the current tab of the front-most browser to your
  read-later-list.
- Any item in your reading list also shows up when using the keyword `rl`.
    - <kbd>⏎</kbd>: Open the item in your browser and mark it as read.
    - <kbd>⌘</kbd><kbd>⏎</kbd>: Mark the item as read.
    - <kbd>⌥</kbd><kbd>⏎</kbd>: Open and keep unread.

> [!NOTE]
> [Unfortunately, Firefox is not and cannot be supported.](https://www.alfredforum.com/topic/16748-how-to-do-x-in-firefox-from-alfred/)

## Item previews
Install [AlfredExtraPane](https://github.com/mr-pennyworth/alfred-extra-pane)
for previews of the items.

## Items are saved locally
- The items are saved in a local Markdown file on your disk. You can set the
  location in the [workflow
  configuration](https://www.alfredapp.com/help/workflows/user-configuration/).
- The items are formatted in the [markdown task syntax](https://simpledev.io/lesson/task-list-md-1/).
    - Unread items as open tasks: `- [ ] [title](url)`
    - Read items as completed tasks: `- [x] [title](url)`
- This has several advantages:
    - No dependency on any read-later service.
    - The reading list is available offline.
    - Since Markdown is a widely supported format, you can access your items in
      many other apps as well, such as [Obsidian](https://obsidian.md/).
      (Interoperability)
    - Easy backup: Just copypaste the file.
    - Easy sync: Just save the file in a cloud drive like iCloud.
    - By saving in a cloud drive, you can also access the reading list on mobile
      with any editor app that supports Markdown tasks.

## Installation
[➡️ Download the latest release.](https://github.com/chrisgrieser/alfred-read-later/releases/latest)

The workflow auto-updates via Alfred's workflow-update mechanism.

## Credits
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

- [Academic Website](https://chris-grieser.de/)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

If you find this project helpful, you can support me via [🩷 GitHub
Sponsors](https://github.com/sponsors/chrisgrieser?frequency=one-time).
