# VEX Completion

*This project aims at gathering/developing completion scripts for command
line interface of VEX development softwares.*

## Dependencies

- zsh

## Manual Installation

### ZSH

Clone the repository

``` sh
$ git clone https://github.com/9623X/vex-completions
```

Include the directory in your `$fpath`, for example by adding in `~/.zshrc`:

``` sh
fpath=(path/to/vex-completion/zsh $fpath)
```

You may have to force rebuild `zcompdump`:

``` sh
$ rm -f ~/.zcompdump; compinit
```

## Contributing

Contributions are welcome, see [CONTRIBUTING](./CONTRIBUTING.md)

## Todo

- PROS:
  - [x] zsh completion script
  - [ ] bash completion script
  - [ ] fish completion script
- Robot Mesh:
  - [ ] zsh completion script
  - [ ] bash completion script
  - [ ] fish completion script
