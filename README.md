# container-compose oh-my-zsh plugin

This plugin provides completion and aliases for [container-compose](https://github.com/apple/container-compose), Apple's native container orchestration tool that works with Docker Compose files.

## Installation

Clone this repository into your oh-my-zsh custom plugins directory:

```sh
git clone https://github.com/alc0der/container-compose-oh-my-zsh-plugin \
  ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/container-compose
```

Then add `container-compose` to the plugins array in your `~/.zshrc`:

```sh
plugins=(... container-compose)
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
