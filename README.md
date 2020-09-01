# Mellon (The Elvish word for "Friend." Used by Gandalf to open the gates to the mines of Moria.)

[![go.dev reference](https://img.shields.io/badge/go.dev-reference-007d9c?logo=go&logoColor=white&style=flat-square)](https://pkg.go.dev/github.com/thanos-community/mellon)
[![Latest Release](https://img.shields.io/github/release/thanos-community/mellon.svg?style=flat-square)](https://github.com/thanos-community/mellon/releases/latest)
[![CI](https://github.com/thanos-community/mellon/workflows/go/badge.svg)](https://github.com/thanos-community/mellon/actions?query=workflow%3Ago)
[![Go Report Card](https://goreportcard.com/badge/github.com/thanos-community/mellon)](https://goreportcard.com/report/github.com/thanos-community/mellon)

CLI oriented to help you with maintaining high quality project docs and website with ease.

## Requirements

* Go 1.14+
* Linux or MacOS

## Installing

```shell
go get github.com/thanos-community/mellon && go mod tidy
```

or via [bingo](github.com/bwplotka/bingo) if want to pin it:

```shell
bingo get -u github.com/thanos-community/mellon
```

## Usage

[embedmd]:# (mellon-help.txt $)
```$
usage: mellon [<flags>] <command> [<args> ...]

TBD.

Features:

Flags:
  -h, --help               Show context-sensitive help (also try --help-long and
                           --help-man).
      --version            Show application version.
      --log.level=info     Log filtering level.
      --log.format=logfmt  Log format to use. Possible options: logfmt or json.

Commands:
  help [<command>...]
    Show help.

  tbd
    yolo.


```

## Contributing

Any contributions are welcome! Just use GitHub Issues and Pull Requests as usual.
We follow [Thanos Go coding style](https://thanos.io/contributing/coding-style-guide.md/) guide.

## Initial Author

[@bwplotka](https://bwplotka.dev)
