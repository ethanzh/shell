# Useful shell commands 

Note: Some of these programs are not built-in, and some are platform-dependent

## Package Management
`pacman -Syu` - update all packages on Arch

`brew bundle` - install from a Brewfile

`brew bundle dump` - generate a Brewfile

`. venv/bin/activate.fish` - activate a python venv on fish

## Networking
`ufw allow 5000/tcp` - allow connections on a given port

`lsof -i :5000` - find which process is running on a given port

## System Configuration
`uname` - get name of operating system (macOS is Darwin)

`neofetch` - display basic system info and splash screen
