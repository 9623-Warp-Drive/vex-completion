# VEX Completion

*This project aims at gathering/developing completion scripts for command
line interface of VEX development softwares.*

## Dependencies

- bash
- zsh

## Manual Installation

Clone the repository

``` sh
$ git clone https://github.com/9623X/vex-completions
```

### ZSH

Include the directory in your `$fpath`, for example by adding in `~/.zshrc`:

``` sh
fpath=(path/to/vex-completion/pros/zsh $fpath)
```

You may have to force rebuild `zcompdump`:

``` sh
$ rm -f ~/.zcompdump; compinit
```

### Bash

Source the bash completion script, for example by adding in `~/.bashrc`:

``` sh
. path/to/vex-completion/pros/bash/prosv5
```

## Contributing

Contributions are welcome, see [CONTRIBUTING](./CONTRIBUTING.md)

## Todo

- PROS:
  - [x] zsh completion script
  - [x] bash completion script
  - [ ] fish completion script
- Robot Mesh:
  - [ ] zsh completion script
  - [ ] bash completion script
  - [ ] fish completion script
