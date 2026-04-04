# homebrew-phpswitcher

A simple Homebrew tap for installing `phpswitcher`, a tool that manages and switches between multiple PHP versions.

## Installation

1. Tap the repository:

   ```bash
   brew tap rawdreeg/phpswitcher
   ```

2. Install the formula:

   ```bash
   brew install phpswitcher
   ```

## Usage

Once installed, `phpswitcher` is available from your PATH.

To switch PHP versions, use:

```bash
phpswitcher use <version>
```

Verify the installed version:

```bash
phpswitcher version
```

## Shell integration

To enable automatic version switching, source the appropriate initialization script in your shell profile.

Bash (`~/.bashrc`) or Zsh (`~/.zshrc`):

```bash
source "$(brew --prefix phpswitcher)/share/phpswitcher/phpswitcher-init.sh"
```

Fish (`~/.config/fish/config.fish`):

```fish
source "$(brew --prefix phpswitcher)/share/phpswitcher/phpswitcher-init.fish"
```

## Formula details

- Formula: `Formula/phpswitcher.rb`
- Homepage: https://github.com/rawdreeg/phpswitcher
- License: MIT

## Contributing

Contributions are welcome. Please open issues or pull requests on the upstream repository.

