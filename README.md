# ***Tunnels-files v2.0.0***

**-> Builtin TunnelsOS official configuration files, stuff like: terminal, status bars or shells. <-**


## ***Features***

- Support terminals: alacritty.
- Support shells: zsh, bash, sh.
- Support status bar: polybar.

## ***Authors***

- [@strxint](https://www.github.com/strxint) (archnon@protonmail.com)


## ***Extra***

- Check the tunnels builtin scripts here: https://github.com/strxint/tunnels-scripts

## ***Installation***

Clone repo

```bash
  git clone https://github.com/strxint/tunnels-files
```

Get inside folder

```bash
  cd tunnels-files
```

Move everything to your personal config path, ex:

```bash
  mv config.ini .* /path/to/your/custom/dir  
```

Try them, ex:

```bash
  # Try shell config for bash, others are: .shrc, .zshrc
  # note: .profile is required for .shrc

  source /path/to/your/.bashrc # asume bash is installed

  # Try launching my polybar config(if you use it)

  pkill polybar && polybar -c /path/to/your/config.ini
```

## ***License***
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/) 
* [GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)


## ***Acknowledgements***

 - [zsh](https://www.zsh.org/)
 - [Bash - GNU Project](https://www.gnu.org/software/bash/)
 - [Polybar](https://polybar.github.io/2023/11/05/Release-3.7.0.html)
