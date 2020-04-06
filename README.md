# Useful shell commands

Note: Some of these programs are not built-in, and some are platform-dependent

## Package Management
`pacman -Syu` - update all packages on Arch

`brew bundle` - install from a Brewfile

`brew bundle dump` - generate a Brewfile

`. venv/bin/activate.fish` - activate a python venv on fish

## Window Management

### Tmux
`tmux new -s <name>` - create new named tmux session

`tmux a -t <name>` - attach to named session

`tmux ls` - list all tmux sessions

## Networking
`ufw allow 5000/tcp` - allow connections on a given port

`lsof -i :5000` - find which process is running on a given port

## System Configuration
`uname` - get name of operating system (macOS is Darwin)

`neofetch` - display basic system info and splash screen

## Image Processing 
`convert -size 32x32 xc:white white.png` - create a blank image file from command line

## Misc.
`tldr <command>` - simplified man page with examples

`pbcopy/pbpaste` - interact with clipboard from terminal
