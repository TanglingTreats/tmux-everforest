# Everforest Tmux Plugin
Came across the wonderful [Everforest](https://github.com/sainnhe/everforest) colorschemes used in a neovim config and was tempted to use it everywhere but there wasn't a tmux equivalent that I could find and incorporate easily.
So here it is.

The main versions of theme are configured with hex codes. This is still an ongoing process so further versions and xterm256 color support will come eventually.

## Dependencies
The normal versions of the theme requires unicode support from the fonts used in your choice of terminal emulators. If you aren't able to see the following symbols in the terminal
```
   
```
you can use get [NerdFonts](https://github.com/ryanoasis/nerd-fonts) or [Powerline fonts](https://github.com/powerline/fonts). Alternatively you can use the xterm versions of the theme instead:


## Installation
### Manual
Copy and paste the contents in the configuration file into your own `.tmux.conf` file or
```bash
cat ./tmux-everforest-dark-medium.conf >> ~/.tmux.conf
```
This methods gives you the most granular customization over what has been committed into the repository.

### Tmux Plugin Manager
This would require the [plugin manager](https://github.com/tmux-plugins/tpm) to be installed and configured within `.tmux.conf` .
```bash
set -g @plugin 'TanglingTreats/tmux-everforest' # Adds to the list of plugins
set -g @tmux-everforest 'dark-medium' # Sets the option to select the theme. Also the default.
# Add '-xterm' to the back of the name for xterm256 compatibility
# E.g. 'dark-medium-xterm'

```

## Look and Feel
### Dark Medium
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/b4568b0e-a580-4b4e-8a43-27b9a9d33b16" width="1000px"/>
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/be36b013-093d-4146-b8c4-8f04db39463d" width="1000px"/>

### Light Medium
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/a0af2dc0-6c3d-441b-9a7c-04108c08dc5f" width="1000px"/>
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/a5798450-5516-4e26-a351-bacaae8542a8" width="1000px"/>

## TODO
- Direct Everforest port
  - Light
    - [x] Soft
    - [x] Medium
    - [x] Hard
  - Dark
    - [x] Soft
    - [x] Medium
    - [ ] Hard
- xterm256 version
  - Light
    - [ ] Soft
    - [x] Medium
    - [ ] Hard
  - Dark
    - [ ] Soft
    - [x] Medium
    - [ ] Hard


## Attribution
- [Everforest](https://github.com/sainnhe/everforest) colorschemes from [sainnhe](https://github.com/sainnhe/)
- The configuration and scripts that made this possible is inspired from [tmux-gruvbox](https://github.com/egel/tmux-gruvbox).
