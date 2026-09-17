## How to use this repository
Although it is not required, in order to get the most out of this repository, it is advisable to install [Obsidian](https://obsidian.md/).

# I'd rather use just markdown
That's fine, just try and keep things tidy by:
- Using the subfolder `meetings` for meeting notes
- Using the subfolder `other` for additional materials
- Using common sense as often as possible 😅

# I want to use Obsidian
The repository already contains a `.obsidian/` folder with the configuration.
You'll only need to say yes when prompted if you trust the vault's author.

## Details
The list below shows what features we use, and why:
### Use markdown links
**TL;DR**: this configuration is shipped with `.obsidian/app.json`, so you don't have to worry about it.

In order to be friendly to non-Obsidian users, we'll use markdown links instead of Obsidian's default Wikilinks. That is:

- 🚫 ~~`[[note title]]`~~ 
- ✅ `[title](note.md)` 

### Community plugins
We make use of two community plugins:
- `Tasks`: to collect tasks along the whole vault.
- `Dataview`: to collect notes along the whole vault.

Those plugins can be installed and enabled from `Settings/Community plugins`. These plugins enable to summarize tasks and meetings in the home note.

### Easily create new meeting notes
- Go to `Settings/Core plugins` and enable `Unique note creator`
	- Configure it with the following parameters:
		- New file location: `meetings/`
		- Template file location: `templates/Meeting`
		- Unique prefix format: `YYYY-MM-DD HHmmss`
	- A new button `Create unique note` will appear in the left side
	- This will create a boilerplate meeting note for you

> **Why not use daily notes instead?** 
> Because unique notes allow you to create multiple notes per day.
