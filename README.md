# o, the little helper to edit filenames in command line parameters

## Usage

You type:
```bash
bash$ o mv really_complicated_filename_you_want_to_change.txt
```

then a prompt opens where you can edit the destination file name:
```bash
o: mv really_complicated_filename_you_want_to_change.txt really_complicated_filename_you_want_to_change.txt▏
```
notice that the destination file name is *editable* so you can arrow around and whatever

```bash
o: mv really_complicated_filename_you_want_to_change.txt really_complicated_filename_you_are_changing▏.txt
```

press enter and the command is executed as it appears

## Requirements

Requires a recent enough version of bash that the builtin `read` command can take the `-i` option.

Mac OS still ships with a really old bash, so that means you need to upgrade bash using homebrew or whatever, and set the `/usr/local/bin/bash` as your shell.
