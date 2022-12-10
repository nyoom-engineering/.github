[![Fennel](https://img.shields.io/badge/Made%20with%20Fennel-2C2D72?style=for-the-badge&logo=lua&logoColor=white)](https://fennel-lang.org)
![Discord Server](https://img.shields.io/discord/1050624267592663050?color=738adb&label=Discord&Color=white&style=for-the-badge)

<a href="http://ultravioletbat.deviantart.com/art/Yay-Evil-111710573">
  <img src="https://raw.githubusercontent.com/hlissner/doom-emacs/screenshots/cacochan.png" align="right" />
</a>

> It's a tale as old as time: a stubborn, shell-dwelling, and melodramatic
> vimmer -- tormented by Vimscript and his boundless productivity -- makes a
> formal request to the netherworld for a transfer. They agree. The terms? He
> must lure more unsuspecting souls into a life of eternal bikeshedding. Now he
> runs the place.

Nyoom.nvim was an answer to abstracted and complex codebases that take away end-user extensibility, try to be a one-size-fits-all config, and needlessly lazy load *everything*. It solves this problem by providing a set of well integrated modules similar to doom-emacs. Modules contain curated plugins and configurations that work together to provide a unified look and feel across all of Nyoom. The end goal of nyoom.nvim is to be used as a framework config for users to extend and add upon, leading to a more unique editing experience.

Nyoom can be anything you'd like. Enable all the modules for the vscode-alternative in you, remove some and turn it into the prose editor of your dreams, or disable everything and have a nice set of macros to start your configuration from scratch!

Its all powered by the [oxocarbon](https://github.com/nyoom-engineering/oxocarbon) theme. If you would like to add functionality to Nyoom.nvim or port over the oxocarbon theme to other editors, contributions and feature requests are welcome!

### Quick install

```bash
git clone --depth 1 https://github.com/nyoom-engineering/nyoom.nvim.git ~/.config/nvim 
cd ~/.config/nvim/
bin/nyoom install 
bin/nyoom sync
```

Read <https://github.com/nyoom-engineering/nyoom.nvim> for more
