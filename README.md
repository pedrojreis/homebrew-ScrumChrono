<div align="center">

![ScrumChrono](https://github.com/pedrojreis/ScrumChrono/blob/main/assets/example.gif?raw=true)

# ScrumChrono

   • <a href="#about">About</a> •
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
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

<p align="center">
  <img width="420" height="640" src="https://github.com/pedrojreis/ScrumChrono/blob/main/assets/jira_example.png?raw=true">
</p>

## Installation

```shell
brew install pedrojreis/tap/scrumchrono
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