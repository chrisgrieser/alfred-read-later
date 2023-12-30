# Read-Later for Alfred
![Download count](https://img.shields.io/github/downloads/chrisgrieser/alfred-read-later/total?label=Total%20Downloads&style=plastic)
![version number](https://img.shields.io/github/v/release/chrisgrieser/alfred-read-later?label=Latest%20Release&style=plastic)

Simple standalone read-later-app for Alfred. Saves the items in plaintext on
your device.

- [ ] Showcase image to be inserted here.

## Usage
- Use the keyword `rl` to add the current tab of the frontmost browser to your
  read-later-list.
- Any item in your reading list also shows up when using the keyword `rl`.
  Press <kbd>⏎</kbd> to open the item in your browser and remove it from your
  read-later-list.

## Items are saved locally
- The items are saved in a local markdown file on your disk. You can set
  the location in the [workflow configuration](https://www.alfredapp.com/help/workflows/user-configuration/).
- The items formatted in the [markdown task syntax](https://simpledev.io/lesson/task-list-md-1/).
	+ Unread items as open tasks: `- [ ] [title](url)`
	+ Read items as completed tasks: `- [x] [title](url)`
- This has several advantages:
	+ No dependency on any read-later service.
	+ The reading list is available offline.
	+ Since Markdown is a widely supported format, you can access your items in many
	other apps as well, such as [Obsidian](https://obsidian.md/).
	+ Easy backup: Just copypaste the file.
	+ Easy sync: Just save the file in a Cloud Drive like iCloud.

> [!TIP]
> You can also access the list on mobile with any note-app that supports
> markdown tasks, when you save it in a Cloud Drive.

## Installation
[➡️ Download the latest release.](./releases/latest)

When admitted to the Alfred Gallery, the workflow auto-updates via Alfred's
workflow-update mechanism.

<!-- vale Google.FirstPerson = NO -->
## Credits
__About Me__  
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

__Profiles__  
- [reddit](https://www.reddit.com/user/pseudometapseudo)
- [Discord](https://discordapp.com/users/462774483044794368/)
- [Academic Website](https://chris-grieser.de/)
- [Twitter](https://twitter.com/pseudo_meta)
- [Mastodon](https://pkm.social/@pseudometa)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'>
	<img
	height='36'
	style='border:0px;height:36px;'
	src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
	border='0'
	alt='Buy Me a Coffee at ko-fi.com'
/></a>
