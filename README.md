# Dear Diary

Dear Diary helps writing diary entries in Markdown files using Helix text editor and Zellij.

![Dear Diary Screenshot](images/ddiary.png)

## Setup

### Prereqs

- text editor. I recommend [Helix](https://helix-editor.com)
- [zellij](https://zellij.dev) - Terminal workspace.

### Steps

- Add the `/bin` director to your path.
- Link the `config/ddiary.kdl` layout to `~/.config/ddiary/ddiary.kdl`
- Make a directory for your diary files: `~/notes/diary/`

## Usage

- `> ddiary` will open a new zellij workspace with an entry for today, yesterday, and last year.
- `> diary` and the other scripts will open those files directly in your editor
