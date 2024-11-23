# oh-my-posh-baiza
Custom zsh themes to be used with oh-my-posh

If you are using a Mac go into, or create a .zshrc file in your home directory ~/

In the .zshrc file initialize oh-my-posh and apply the theme to terminal of choice. 

In the example below I am applying to all terminal emulators except the apple terminal.

```
if [ "$TERM_PROGRAM" != "Apple_Terminal" ]; then
eval "$(oh-my-posh init zsh --config LOCAL FILE PATH TO YOUR THEME HERE)"
fi
```

