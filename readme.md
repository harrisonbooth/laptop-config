# Laptop Config Scripts and Files

## Usage
### Laptop Script
Run `sh ./laptop-setup/mac 2>&1 | tee ./laptop-setup/laptop.log`.

### ZSH Config
Add a `source` to your `.zshrc` file with the path to the `zsh_custom` file.
Optionally add an alias which sources the `zsh_teaching` file.

### VSCode Config
Open VSCode, and use the command palette to `Install 'code' command in PATH`.
Paste the `vs-code-settings.json` code into the VSCode settings JSON.
Run `sh setup.sh` to install extensions and font.
