# Goli

[![codecov](https://codecov.io/gh/arthurvdiniz/goli/branch/main/graph/badge.svg?token=ZnjqVDgZk6)](https://codecov.io/gh/arthurvdiniz/goli)
[![Go Report Card](https://goreportcard.com/badge/github.com/arthurvdiniz/goli)](https://goreportcard.com/report/github.com/arthurvdiniz/goli)
![Build](https://github.com/arthurvdiniz/goli/actions/workflows/build.yml/badge.svg)


Goli is a CLI Tool for running Go commands with colorized output.

> Note: Goli is still a WIP. It has very basic commands and limitations. Feel free to contribute with the project.

## Installing

Using Goli is very easy. First, use `go get` to install the latest version of the library. This command will install the `goli` executable along with the library and its dependencies:

```shell
go get github.com/arthurvdiniz/goli
```

## Commands

Under the hood `goli` is going to use the `go` binary installed in your system.

### Test

For running test command just use `goli` instead of `go`.

```shell
goli test ./... -v
```

After running the command you'll get an example of output:

![Text output command example](/assets/images/test-command.png "Text output command example")
