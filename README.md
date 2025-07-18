# Go terminal/console support

Well while history and other bug fixes have been merged, there is a new bug fix pending, so this fork is back

Please see https://pkg.go.dev/fortio.org/terminal for a wrapper of x/term that does provide History configuration, saving, conditional addition etc..

[![Go Reference](https://pkg.go.dev/badge/fortio.org/term.svg)](https://pkg.go.dev/fortio.org/term)

This repository provides Go terminal and console support packages.
It's a fork of the [golang.org/x/term](https://pkg.go.dev/golang.org/x/term) pending approval of improvements upstream.

## Download/Install

The easiest way to use is to run `go get -u fortio.org/term`.

Rather than use this lowlevel library, use [fortio.org/terminal](https://github.com/fortio/terminal#terminal) which wraps this one into a higher level and simpler more powerful API.
