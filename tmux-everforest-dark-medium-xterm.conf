## COLORSCHEME: everforest dark medium
set-option -g status "on"
set -g status-interval 2

set-option -g status-fg 'color181' # fg
set-option -g status-bg 'color236' # bg0

set-option -g mode-style fg='color175',bg='color238' # fg=purple, bg=bg_visual

# default statusbar colors
set-option -g status-style fg='color181',bg='color235',default # fg=fg bg=bg_dim

# ---- Windows ----
# default window title colors
set-window-option -g window-status-style fg='color59',bg='color236' # fg=yellow bg=bg0

# default window with an activity alert
set-window-option -g window-status-activity-style bg=colour237,fg=colour248 # bg=bg1, fg=fg3

# active window title colors
set-window-option -g window-status-current-style fg='color181',bg='color238' # fg=fg bg=bg_green

# ---- Pane ----
# pane borders
set-option -g pane-border-style fg='color237' # fg=bg1
set-option -g pane-active-border-style fg='color109' # fg=blue

# pane number display
set-option -g display-panes-active-colour 'color109' # blue
set-option -g display-panes-colour 'color174' # orange

# ---- Command ----
# message info
set-option -g message-style fg='color174',bg='color235' # fg=statusline3 bg=bg_dim

# writing commands inactive
set-option -g message-command-style fg='colour223',bg='colour239' # bg=fg3, fg=bg1

# ---- Miscellaneous ----
# clock
set-window-option -g clock-mode-colour 'color109' #blue

# bell
set-window-option -g window-status-bell-style fg='color236',bg='color174' # fg=bg, bg=statusline3

# ---- Formatting ----
set-option -g status-left-style none
set -g status-left-length 60
set -g status-left '#[fg=color235,bg=color144,bold] #S #[fg=color144,bg=color238,nobold] #[fg=color144,bg=color238,bold]#(whoami) #[bg=color236] '

set-option -g status-right-style none
set -g status-right-length 150
set -g status-right '#[fg=color238] #[fg=color181,bg=color238] #[fg=color181,bg=color238]%Y-%m-%d | %H:%M #[fg=color235,bg=color108,bold] #h '

set -g window-status-separator '#[fg=color247,bg=color236] '
set -g window-status-format "#[fg=color8,bg=color236] #I | #[fg=color8,bg=color236]#W  "
set -g window-status-current-format "#[fg=color181,bg=color238] #I | #[fg=color181,bg=color238,bold]#W #[fg=color238,bg=color236,nobold] "
