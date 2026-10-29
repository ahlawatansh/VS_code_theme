# Warp Pastel Dark

A black VS Code theme with soft green, pink and sky blue colors.

## What you get

- Black editor, terminal and side bar
- Soft pastel code colors
- White blinking cursor
- Green dot for a command that works, red dot for a command that fails
- Hack Nerd Font, size 13
- Side bar on the left, terminal at the bottom
- Cmd+K and Cmd+Backspace clear the terminal

## How to install

**Step 1.** Download the file `warp-pastel-dark-1.0.0.vsix`. It goes to your Downloads folder.

**Step 2.** Install the font. Open the Mac Terminal app and run:

```bash
brew install --cask font-hack-nerd-font
```

**Step 3.** In the same Terminal app, run:

```bash
code --install-extension ~/Downloads/warp-pastel-dark-1.0.0.vsix
```

**Step 4.** Quit VS Code with **Cmd+Q** and open it again.

Done. If the colors do not change, press **Cmd+Shift+P**, type **Color Theme**, and pick **Warp Pastel Dark**.

## If something is wrong

- **Font looks wrong:** run Step 2 again, then quit VS Code with Cmd+Q and reopen it.
- **No green dots:** you need zsh or bash in the terminal.
- **Some settings do not change:** your own `settings.json` is stronger than the theme. Remove the same lines from it.

## How to remove

```bash
code --uninstall-extension ansh.warp-pastel-dark
```
