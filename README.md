# Battery

[![Travis CI](https://img.shields.io/travis/jessfraz/battery.svg?style=for-the-badge)](https://travis-ci.org/jessfraz/battery)
[![GoDoc](https://img.shields.io/badge/godoc-reference-5272B4.svg?style=for-the-badge)](https://godoc.org/github.com/jessfraz/battery)

Battery status getter written in Go.

 * [Installation](README.md#installation)
      * [Binaries](README.md#binaries)
      * [Via Go](README.md#via-go)
 * [Usage](README.md#usage)

## Installation

#### Binaries

For installation instructions from binaries please visit the [Releases Page](https://github.com/jessfraz/battery/releases).

#### Via Go

```console
$ go get github.com/jessfraz/battery
```

## Usage

```console
$ battery -h
battery -  Linux battery status checker.

Usage: battery <command>

Flags:

  -d      enable debug logging (default: false)
  --name  name of your battery (default: BAT0)

Commands:

  version  Show the version information.
```
