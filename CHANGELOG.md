# Changelog - ~/.zsh

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/), and this project adheres to [Semantic Versioning](https://semver.org/).

## [1.3.0] - 2021-09-20

### Added

- Add an auto compile process of `ZDOTDIR`

## [1.2.0] - 2021-04-10

### Added

- Let it show the hostname if the shell is executed in a remote host

## [1.1.0] - 2021-02-20

### Added

- Set the environment variable `EDITOR` to `vi` if `EDITOR` is not set and there is a `vi` command

## [1.0.1] - 2021-02-14

### Fixed

- Remove an extra space in the process about `gcloud` command

## [1.0.0] - 2021-02-14

### Added

- Considering use in macOS and Linux, consideration not to break the design concept of the OS distribution
- Considering not to put dynamic files in the repository (Shell state saving for Apple_Terminal is disabled)
- Assuming use of [zinit](https://zdharma.org/zinit/wiki/)
- Assuming use of [Homebrew](https://brew.sh/)
- Assuming use of [syndbg/goenv](https://github.com/syndbg/goenv), [nodenv/nodenv](https://github.com/nodenv/nodenv), [phpenv/phpenv](https://github.com/phpenv/phpenv), [pyenv/pyenv](https://github.com/pyenv/pyenv), [rbenv/rbenv](https://github.com/rbenv/rbenv), [kylef/swiftenv](https://github.com/kylef/swiftenv)
- Dynamically set ZDOTDIR based on the relative relationship between home directory and ZDOTDIR
- Compliant with XDG Base Directory Specification
