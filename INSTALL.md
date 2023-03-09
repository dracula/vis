### [vis](https://github.com/martanne/vis)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/vis.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/vis/archive/master.zip) option and unzip them.

#### Activating theme

1. add the theme to your vis config directory
```bash
mkdir -p ~/.config/vis/themes
cp base16-dracula.lua ~/.config/vis/themes
```
2. either copy `visrc.lua` to `~/.config/vis/`, or add `vis:command('set theme base16-dracula')` inside `vis.events.subscribe(vis.events.INIT, ...` function (global config options) in your `visrc.lua` file.

optionally you can try it out beforehand with `:set theme base16-dracula` (command mode in vis)
