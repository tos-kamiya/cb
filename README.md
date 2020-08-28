cb
==

`cb`, a command-line clipboard, inspired by `psub` command of `fish` shell.

## Install

Copy `cb` to a directory on PATH, such as `~/bin/`.

## Usage

To copy (send output of a command line to the clipboard),

```sh
some-command-line | cb
```

To paste (Extract the clipboard content),

```sh
cb
```

### Usage sample

Open a new terminal and change directory to the same directory of the currrent terminal.

Type in a current terminal:

```sh
pwd | cb
```

Then open a new terminal and type in it:

```sh
cd $(cb)
```
