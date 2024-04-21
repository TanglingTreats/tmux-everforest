# Everforest Tmux Theme
Came across the wonderful [Everforest](https://github.com/sainnhe/everforest) theme used in a neovim config and was tempted to use it everywhere but there wasn't a tmux equivalent that I could find and incorporate easily.
So here it is.

The main versions of theme are configured with hex codes. This is still an ongoing process so further versions and xterm256 color support will come eventually.

## Attribution
The configuration and scripts that made this possible is inspired from [tmux-gruvbox](https://github.com/egel/tmux-gruvbox).

## Look and Feel
### Dark Medium
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/b4568b0e-a580-4b4e-8a43-27b9a9d33b16" width="1000px"/>
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/be36b013-093d-4146-b8c4-8f04db39463d" width="1000px"/>

### Light Medium
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/a0af2dc0-6c3d-441b-9a7c-04108c08dc5f" width="1000px"/>
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/a5798450-5516-4e26-a351-bacaae8542a8" width="1000px"/>

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

```
## TODO
- [ ] Port over other versions of Everforest
  - Light
    - [ ] Soft
    - [x] Medium
    - [ ] Hard
  - Dark
    - [ ] Soft
    - [x] Medium
    - [ ] Hard
- [ ] xterm256-specific colors of every version for compatibility
