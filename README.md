# wizctl

A TUI tool to control Phillips wiz lights. Communicates over UDP. 360 lines of bash.

## What you can do

1. Easy interactive setup with automatic discovery. Just connect to the same wifi network as the bulb.
2. Apply scenes, colors, temperatures etc interactively in the CLI fzf-style.
3. You can use the preview feature to quickly checkout different colors/scenes live in your lamp.
4. You can save profiles and apply them whenever.
5. Simple config file if you have an exotic networking setup.
6. Easy non-interactive scripting usage.

## Depends on

1. `gum` a TUI tool. Actually I forked and add `fzf --preview` equivalent to it so you have to wait for that or look at my
   fork...
2. My own tool `colorinspector`

## TODO

Prettify outputs and make screenshots and gifs and stuff for here. Add links to the above.
