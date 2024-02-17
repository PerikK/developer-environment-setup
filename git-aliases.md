# Bash Aliases for Git

The following is a list of aliases that abbreviate common `git` operations that you may perform from a `bash` shell.

```bash

# Add this text to your .bashrc file and they will be available the next time you open a new shell.

# Feel free to update or add your own aliases

# Using an alias - when you feel like you want to try them
# You type the alias and it will be replaced with the definition
# You can add things after the alias as you normally would
#
# Eg you can use
#   ga my-file
#
# rather than typing
#   git add my-file

# An alias to get you to your 'projects' directory (folder)
# I use 'projects' but you can change this
#   leave the '~/' as that is your home directory
alias p='cd ~/projects'

# VS Code - type: c. <Enter> to start VS Code in your current directory
alias c.='code .'

# Additional directory listing aliases
alias ltr='ls -ltr'
alias l='ls -ltr'

# Git aliases
alias ga='git add'
alias gl='git log'
alias gb='git branch'
alias gp='git pull'
alias gpl='git pull'
alias gco='git checkout'
alias gcl='git clone'
alias gui='gitk'
alias gs='git status'
alias gc='git commit'
alias gd='git diff'
alias gdd='git diff HEAD^ HEAD'
alias gph='git push'

# This lists the git aliases above in case you forget

#Modified to show all created aliases. Shows some more things that it shouldn't
alias gitaliases="alias | grep '^\s*alias ' | sed -e \"s/^alias /  /\""

#Original grep
#alias gitaliases="alias | grep -e \"='git\" | sed -e \"s/^alias /  /\""

#Others that don't work as expected
#alias gitaliases="alias | grep '^alias ' | sed -e \"s/^alias /  /\""
#alias gitaliases="alias | grep '\= \w*git \w*' | sed -e \"s/^alias /  /\""
#alias gitaliases="alias | grep -e \"='alias\" | sed -e \"s/^alias /  /\""



```
