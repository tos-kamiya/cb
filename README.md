cb
==

`cb`, a command-line clipboard, inspired by `psub` command of `fish` shell.

## Install

Copy `cb` to a directory on PATH, such as `~/bin/`.

## Usage

To copy the output of a command line to the clipboard,

```sh
a-command-line | cb
```

To paste the contents of the clipboard to another command line,

```sh
cb | another-command-line
```

To show the contents of the clipboard,

```sh
cb
```

### Usage sample

Open a new terminal and change directory to the same directory of the current terminal.

Type in a current terminal:

```sh
pwd | cb
```

Then open a new terminal and type in it:

```sh
cd $(cb)
```
