<div align="center">

Image here

# ScrumChrono

   • <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#built-with">Built With</a> •
</div>

---

## About

ScrumChrono is a terminal UI to aid Scrum meetings. The goal of this project is to make easy to track time and provide some extra information.
Feel free to open an issue with any bug you encounter of any suggestion.

## Features

* Config your teams by members, time and font.
* Countdown will change color when 33%, 66% and 100% of time has elapsed.
* Pause
* Atlassian Integration
* Soon: Statistics

## Installation

```shell
brew tap pedrojreis/scrumchrono
brew install scrumchrono
```

Feel free to edit the config (view Usage) to your own needs.

## Usage

```shell
# Current version
ScrumChrono version

# View Config - it will include path and content
ScrumChrono config view

# Run for firstteamname
ScrumChrono -t firstteamname
```

## Built With

* [Go 1.21.7](https://go.dev/dl/) - Framework
  * [Cobra](https://github.com/spf13/cobra) - lib to create cli app
  * [Viper](https://github.com/spf13/viper) - configuration solution
  * [Termui](https://github.com/gizak/termui) - terminal dashboard and widget library
  * [Go-Figure](https://github.com/common-nighthawk/go-figure) - beautiful ASCII
* ❤️
