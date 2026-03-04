# container-compose zsh plugin

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This plugin provides completion and aliases for [container-compose](https://github.com/Mcrich23/Container-Compose), a tool to manage Docker Compose files with Apple's native Container runtime.

## Installation

### [Oh My Zsh](https://ohmyz.sh)

Clone this repository into your custom plugins directory:

```sh
git clone https://github.com/alc0der/container-compose-oh-my-zsh-plugin \
  ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/container-compose
```

Add `container-compose` to the plugins array in your `~/.zshrc`:

```sh
plugins=(... container-compose)
```

### [Zinit](https://github.com/zdharma-continuum/zinit)

Add to your `~/.zshrc`:

```sh
zinit light alc0der/container-compose-oh-my-zsh-plugin
```

### [Antigen](https://github.com/zsh-users/antigen)

Add to your `~/.zshrc`:

```sh
antigen bundle alc0der/container-compose-oh-my-zsh-plugin
```

### Manual

Clone the repository and source the plugin in your `~/.zshrc`:

```sh
git clone https://github.com/alc0der/container-compose-oh-my-zsh-plugin \
  ~/.container-compose-zsh-plugin

# Add to ~/.zshrc
source ~/.container-compose-zsh-plugin/container-compose.plugin.zsh
```

## Aliases

| Alias   | Command                       |
|---------|-------------------------------|
| `cco`   | `container-compose`           |
| `ccup`  | `container-compose up`        |
| `ccupd` | `container-compose up -d`     |
| `ccupb` | `container-compose up -b`     |
| `ccupdb`| `container-compose up -d -b`  |
| `ccdn`  | `container-compose down`      |
| `ccv`   | `container-compose version`   |
