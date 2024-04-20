# Everforest Tmux Theme
Came across the wonderful [Everforest](https://github.com/sainnhe/everforest) theme used in a neovim config and was tempted to use it everywhere but there wasn't a tmux equivalent that I could find.
So here it is.

The configuration and scripts that made this possible is inspired from [tmux-gruvbox](https://github.com/egel/tmux-gruvbox)

## Look and Feel
### Dark Medium
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/b4568b0e-a580-4b4e-8a43-27b9a9d33b16" width="1000px"/>
<img src="https://github.com/TanglingTreats/tmux-everforest/assets/19703014/0b8283a5-eb11-471e-a96a-c5f4a79b853b" width="1000px"/>

## Installation
### Manual
Copy and paste the contents in the configuration file into your own `.tmux.conf` file or
```bash
cat ./tmux-everforest-dark-medium.conf >> ~/.tmux.conf
```

### Tmux Plugin Manager
This would require the [plugin manager](https://github.com/tmux-plugins/tpm) to be installed and configured within `.tmux.conf` 
```bash
set -g @plugin 'TanglingTreats/tmux-everforest' # Adds to the list of plugins
set -g @tmux-everforest 'dark-medium' # Sets the option to select the theme

```
## TODO
- [ ] Port over other versions of the theme
  - Light
    - [ ] Soft
    - [ ] Medium
    - [ ] Hard
  - Dark
    - [ ] Soft
    - [ ] Hard
- [ ] xterm256-specific colors of every version for compatibility
