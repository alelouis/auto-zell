# auto-zell
Automatic Zellij command run in Neovim.  

This plug-in allows you to set a given command to be executed in a [Zellij Run](https://zellij.dev/documentation/zellij-run) pane.

## Setup
Add this line to your `init.lua`:
```lua
{ 'alelouis/auto-zell', opt = {} }
```

## How-to

- Use `:AutoZellSet` in order to input the command to be automatically run.
- Use `:AutoZellRun` to automatically create a new Run pane.

## Example

Suppose I want to run a Python script in a new Run Zellij pane, I can type:  
`:AutoZellSet` and then input `python3 main.py`.  
Then, each time I want to run (map to a keymap for faster operations, or make an autocmd on save.):
`:AutoZellRun`

https://github.com/alelouis/auto-zell/assets/6841652/b1f1ab57-fa05-4c8b-96e9-46aacf2cbf08

