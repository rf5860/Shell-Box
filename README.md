# Shell Box

## Overview

A simple script for printing a given string in a box

## Examples

Input:

```sh
inBox "Hello World"
```

Output:

```text
┌─────────────┐
│ Hello World │
└─────────────┘
```

## Usage

```text
usage: inBox [-h | --help]
             [-V | --version]
             [-C | --no-color]
             [-l | --light]
             [-v | --heavy]
             [-d | --double]
             [--box-color=<ansi-color>]
             [--text-color=<ansi-color>]
            <text>

Miscellaneous:
  -V, --version             display version information and exit
  -h, --help                display this help text and exit

Output control:
  -C, --no-color            disable coloured output
  -l, --light               use light-single box-drawing characters
  -v, --heavy               use heavy-single box-drawing characters
  -d, --double              use double box-drawing characters
  --box-color               ansi color code for the box
  --text-color              ansi color code for the text
```
