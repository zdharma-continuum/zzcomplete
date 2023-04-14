# ZZ Complete [![Gitter][gitter-image]][gitter-link]

Complete options from manual pages – press Ctrl-F to start the completer.

## Motivation

The completion of options has drawbacks:

1. The user has to remember a part of the option he wants to complete.
1. OR forced to read through all the options (listed after TAB).

With ZZ Complete, the user can:

1. Search in the manual for arbitrary text related to the option.
1. Then select the option located nearby the found text.
1. The user can also read about the possible values of the options and select them.

## Asciicast

You can resize the video like a standard web page, i.e., with `Ctrl`/`Cmd` + `plus` and `Ctrl`/`Cmd` + `minus`.

[![asciicast](https://asciinema.org/a/293365.svg)](https://asciinema.org/a/293365)

## Instalation

### Dependencies

The plugin also needs [ZUI](https://github.com/zdharma-continuum/ZUI) plugin and a Zsh built with the `zsh/curses`
module.

### Manual

Clone the Repository.

```zsh
git clone https://github.com/zdharma-continuum/zzcomplete ~/path/to/zzcomplete
```

Next, add the following to your `zshrc` file.

```zsh
source ~/path/to/zzcomplete/zzcomplete.plugin.zsh
```

### Zplugin

Add the following to your `zshrc` file.

```zsh
zplugin light zdharma-continuum/zzcomplete
```

### Antigen

Add the following to your `zshrc` file.

```zsh
antigen bundle zdharma-continuum/zzcomplete
```

### Zgen

Add the following to your `.zshrc` file in the same place you're doing your other `zgen load` calls in.

```zsh
zgen load zdharma-continuum/zzcomplete
```

### Oh-My-Zsh

Clone the Repository.

```zsh
git clone https://github.com/zdharma-continuum/zzcomplete.git \
  ~ZSH_CUSTOM/plugins/zzcomplete
```

And add `zzcomplete` to your plugin list.

[gitter-image]: https://badges.gitter.im/zdharma-continuum/community.svg
[gitter-link]: https://gitter.im/zdharma-continuum/community
