# gh-sweep

A simple tool to clean up failed and cancelled GitHub Action runs.

## Dependencies

- [GitHub CLI](https://github.com/cli/cli): Required. Must be installed and authenticated (`gh auth login`).
- [fzf](https://github.com/junegunn/fzf): Optional. Used for the interactive search menu. If missing, the script will offer to install it automatically via Homebrew or direct binary download.

## Installation

1. Create your local bin directory:
   mkdir -p ~/.local/bin

2. Save the `gh-sweep` script into that directory.

3. Make the script executable:
   chmod +x ~/.local/bin/gh-sweep

4. Ensure your shell can find the command. Add this to your .bashrc:
   export PATH="$HOME/.local/bin:$PATH"

## Usage

Start the interactive menu:
$ gh-sweep

Clean a specific repository:
$ gh-sweep repo-name

## License

GPL-3.0
