# Laptop Config Scripts and Files

## Installation:
Post cloning, move into each submodule folder and run:
```bash
git submodule init

git submodule update
```

## Usage

### ZSH Config
Add a `source` to your `.zshrc` file with the path to the `zsh_custom` file.
Optionally add an alias which sources the `zsh_teaching` file.


### Laptop Script
Run `sh ./laptop/mac 2>&1 | tee ~/laptop.log`.

### VSCode Config
Install VSCode, open it, and use the command palette to `Install 'code' command in PATH`.
Paste the `vs-code-settings.json` code into the VSCode settings JSON.
Run `sh setup.sh` to install extensions and font.
