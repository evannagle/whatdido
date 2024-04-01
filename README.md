# Whatdido

No more "git commit -m "adsfkjaef"" in a fit of rage. Simply type `dido` to add your changes and write a simple and sane commit message.

**This package is in an exploratory beta state. Please use carefully and at your own risk.**

## Installation

```python
pip install whatdido

alias dido="git add -A && git commit -m "$(whatdido summary)""

```

## Usage

```
whatdido --help

 Usage: whatdido [OPTIONS] COMMAND [ARGS]...

╭─ Options ────────────────────────────────────────────────────────────────╮
│ --install-completion          Install completion for the current shell.  │
│ --show-completion             Show completion for the current shell, to  │
│                               copy it or customize the installation.     │
│ --help                        Show this message and exit.                │
╰──────────────────────────────────────────────────────────────────────────╯
╭─ Commands ───────────────────────────────────────────────────────────────╮
│ commit     Edit the message using the user's preferred editor.           │
│ config                                                                   │
│ diff       Get the terse diff of the staged changes.                     │
│ summary    Summarize the changes in the repository.                      │
╰──────────────────────────────────────────────────────────────────────────╯

```

## Quick commit command

```
alias dido="git add -A && git commit -m "$(whatdido summary)""
```
