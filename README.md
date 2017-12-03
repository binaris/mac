# So, you got a new Mac?

Here is a bunch of stuff we find useful, especially if you're coming from a non-Mac background.
Yes, some of it costs money (has $ sign in the title). Ask your boss.

## [Alfred](https://www.alfredapp.com/) $

It's much better than the built-in launcher of spotlight search. It's very fast, and is pluggable into many other apps on your Mac.

## [iTerm](https://www.iterm2.com/features.html)

A superiour terminal app. Tons of features, including a storng TMUX integration, infinite history playback (scroll time to see terminal history), handy splitting of windows, panes, tabs, broadcasting input to multiple shells.

## [Moom](https://manytricks.com/moom/) $

It's a windows manager. Lets you do stuff like Maximize window, organize windows to fill screen, move between screens, etc.

Strong keyboard bindinds.

![moom](https://manytricks.com/moom/images/grid.png)

## [Scroll Reverser](https://pilotmoon.com/link/scrollreverser)

If you're using a mouse and used to scrolling in the "natural" direction.

## [Dash](https://kapeli.com/dash)

Offline documentation for all languages, libraries, tools, servers. Good keyboard bindings. Hooks into Vim (and all other lesser editors).

## [Karabiner Elements](https://github.com/tekezo/Karabiner-Elements/blob/master/README.md)

Tweak your keyboard to your heart's content. Switch keys, turn Caps into Esc, modify the key repeat speed and latency - a crazy amount of configuration options. Global Vim mode in your Mac, anyone?

## [Copy 'em Paste](http://www.apprywhere.com/copy-em-paste.html)

Clipboard manager. Saves your copy-pasting history, including images, and has tons of keyboard shortcuts to quickly paste them.

Notice Alfred does this as well, so it's a matter of preference (or if you don't want to install Alfred, but do want a clipboard manager).

## [Monodraw](https://monodraw.helftone.com/) $

ASCII diagram editor. Lets you export to text, obviously, but also keep the vectorized layers in a smart, editable way.

## [Airmail](http://airmailapp.com/) $

A better Email client for Mac (better than the built-in one, at least). Unified inboxes, snoozing, good keyboard bindind.

## [Commander One](https://itunes.apple.com/us/app/commander-one-dual-pane-file-manager/id1035236694?mt=12) $

Like Total Commander for Mac, if you're into that kind of stuff.

## [Spectacle](https://www.spectacleapp.com/)

A small and free application enabling easy keyboard shortcuts for window location on your monitor(s), including fullscreen, right/left/center of screen, move to the next/previous monitor, etc. Quite similar to what you can easily do with the Windows key on Windows...

# Handy Vim Plugins

- `hashivim/vim-terraform` for auto-formatting your Terraform files, and other stuff.
    (e.g. to auto-format upon saving a `.tf` file, add this to your `.vimrc`:

      autocmd bufwritepost *.tf :TerraformFmt

# CLI Tools
* [`ag`](https://github.com/ggreer/the_silver_searcher): Super-fast recursive search in code files.
* [`tree`](http://brewformulas.org/Tree): Recursive directory view.
* [`jq`](https://stedolan.github.io/jq/): Parse, filter, query and prettify JSON output.
* [`fzf`](https://github.com/junegunn/fzf): Fast fuzzy find in filenames (and more).
* [`ranger`](https://github.com/ranger/ranger): Quick file naviagion and preview
* [`saws`](https://github.com/donnemartin/saws) AWS CLI tool with useful autocomplete
