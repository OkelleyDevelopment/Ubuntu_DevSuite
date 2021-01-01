# Debian Development Suite

## Motivation

Manual installs of tools that are commonly used in a development environment becomes cumbersome
and can cause tools to be forgotten between installs. With this bash script automating the process,
all the tools will be installed and ready to go!

## Prerequisites

1. Must have an internet connection to install the tools.
2. Must have cURL installed.

## Program Execution

Run in one command:

```sh
bash <(curl -s https://raw.githubusercontent.com/OkelleyDevelopment/Debian_Dev_Tools/master/dev_suite.sh)
```

Assuming correct permissions

```
./dev_suite.sh
```

If permissions are incorrect, then run:

```
chmod 755
```

and the above command.

## Future Goals

- Add a small yes/no gathering for which tools to install saving space for unwanted software.
- Convert this script for Arch based distros

## Installed Tools

- GIT
- NodeJS
- Pip3
- neofetch
- NeoVim
- xClip
- Discord
- Spotify
- My custom [NeoVim Config](https://github.com/OkelleyDevelopment/Nvim-Config)
