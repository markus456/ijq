# ijq

Interactive frontend to the `jq` JSON processor.

## Usage

```
ijq [JSONFILE]
```

## Commands

- `help`

  - Displays the manpage for `jq`.

- `load [FILENAME]`

  - Loads a new JSON file. If the program was started with no file, a file must
    be loaded before any of the commands work.

- `raw`

  - Enable raw input (same as `jq -r`)

- `noraw`

  - Disable raw input

- `color`

  - Enable color output (same as `jq -C`)

- `nocolor`

  - Disable color output (same as `jq -M`)

- `quit`, `exit`, `q`, `Ctrl+D`

  - Exits the program
