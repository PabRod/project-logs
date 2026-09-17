## How to use this repository
Although it is not required, in order to get the most out of this repository, it is advisable to install [Obsidian](https://obsidian.md/) and open it as a vault.

# Meh, I'd rather use just markdown
That's fine. The only price you pay is you won't be able to open `.base` queries. Please try and keep things tidy by:

- Using the subfolder `meetings` for meeting notes
- Using the subfolder `tasks` for tasks
- Using common sense as often as possible 😅

# I want to use Obsidian
The repository already contains a `.obsidian/` folder with the basic configuration. It will take care of the details listed below. You'll only need to say yes when prompted if you trust the vault's author.

Feel free to add personal configuration such as hotkeys, themes, etc. The `.gitignore` file protects the repo from accidentally uploading personal configuration files.

## Details
The list below shows what features we use, and why:

### Use markdown links
In order to be friendly to non-Obsidian users, we'll use markdown links instead of Obsidian's default Wikilinks. That is:

- 🚫 ~~`[[note title]]`~~ 
- ✅ `[title](note.md)` 

### Add a new task
Press `Insert template` and  choose `Task`.

> **Why not use inline tasks** 
> Because browsing through them requires installing an external plug-in. Additionally, we want tasks with extended information, so they can become the seed of a GitHub issue.

### Create mew meeting note
Press `Create unique note`.

> **Why not use daily notes instead?** 
> Because unique notes allow you to create multiple notes per day.


## Purpose
The purpose of this repository is to create an Obsidian template than can be easily reused as a project log for our projects at the Netherlands eScience Center.

It contains three basic types of files:

- Meetings, containing information about meetings (such as date, attendants, place, ...)
- Tasks, containing information about tasks (such as assignee, priority, due date, ...)
- Notes, containing any general information

## How is this different from a regular Obsidian vault?
The main difference is the [`.gitignore`](,gitignore) file. It allows to share some configuration options (such as the markdown links) without interfering with the user's configuration:

### Community plug-ins
If you install any community plug-in, it will not be propagated to the rest of your team. Would you like that to happen, then check how to do it in the [`.gitignore`](,gitignore) file.
