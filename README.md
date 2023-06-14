# fluttervm

- [Instalation (Linux Debian-based)](#ambiente-linux-debian-based)

# Setup

## Linux Environment (Debian-based)

Download/Installation

To install execute:

```bash
$ git clone https://github.com/rafeira/fluttervm.git $HOME/.fluttervm
```
Add fluttervm commands and flutter and dart cammand to your PATH environment variable:

```bash
$ export PATH="$PATH:$HOME/.fluttervm/bin"
$ export PATH="$PATH:$HOME/.fluttervm/fvm/bin"
```
**Note:** If you want these commands always available add them to ~/.zshrc or ~/.bashrc files.
# Usage

To install a version (only stable) execute:

```bash
$ flutter-install-version 3.10.4
```

To set this version run:

```bash
$ fluttervm 3.10.4
```
