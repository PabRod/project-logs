# How to use this repository
Although it is not required, in order to get the most out of this repository, it is advisable to install [Obsidian](https://obsidian.md/) and open it as a vault.

> Meh, I'd rather use just markdown
> That's fine. The only price you pay is you won't be able to open `.base` queries nor the task prompts.
## I'll use Obsidian
The repository already contains a `.obsidian/` folder with the basic configuration. It will take care of the details listed below. You'll only need to say yes when prompted if you trust the vault's author.

We use the [Tasks](https://publish.obsidian.md/tasks/) community plug-in to collect the to do's from all notes (see [Tasks manager](notes/Tasks%20manager.md)). It ships with the repository, but Obsidian won't run it until you enable it once: `Settings → Community plugins → Tasks`.

Feel free to add personal configuration such as hotkeys, themes, etc. The `.gitignore` file protects the repository from accidentally uploading personal configuration files.
## Details
The list below shows what features we use, and why:
### Use markdown links
In order to be friendly to non-Obsidian users, we'll use markdown links instead of Obsidian's default Wikilinks. That is:

- 🚫 ~~`[[note title]]`~~ 
- ✅ `[title](relativepath/note.md)`

If you are using Obsidian, you don't have to worry about this. Links will be auto-formatted.
### Create new meeting note
Press `Create unique note`.

> **Why not use daily notes instead?** 
> Because unique notes allow you to create multiple notes per day.
### Track tasks
#### Triage: Obsidian or GitHub?
Tasks in the notes are our inbox. Review them regularly (see [Tasks manager](notes/Tasks%20manager.md)) and decide:

- **Small tasks** stay in Obsidian.
- **Large tasks** (they need code, involve more than one person, or take more than a day) become a GitHub issue in the repository where the work happens. Then, in Obsidian, change the status to `[>]` (_Moved to GitHub_) and link the issue. In the issue, link back to the note for context.

| Status        | Meaning          | Tracked in |
| ------------- | ---------------- | ---------- |
| `[ ]`         | To do            | Obsidian   |
| `[/]`         | In progress      | Obsidian   |
| `[>]`         | Moved to GitHub  | GitHub     |
| `[x]` / `[-]` | Done / cancelled | Obsidian   |

> **Why a separate status for promoted tasks?**
> Once a task is an issue, GitHub is its single source of truth. `[>]` takes the task out of every open-task query, so there is nothing to keep in sync.
