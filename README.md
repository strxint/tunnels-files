# ***Tunnels-files v2.0.0***

**-> Built-in TunnelsOS(coming soon) official configuration files, for stuff like: terminal, status bars or shells. <-**


## ***Features***

- Support terminals: alacritty.
- Support shells: zsh.
- Support status bar: polybar.

## ***Authors***

- [@strxint](https://www.github.com/strxint) (archnon@protonmail.com)

## ***Installation***

Clone repo

```bash
  git clone https://github.com/strxint/tunnels-files
```

Get inside the main folder

```bash
  cd tunnels-files
```

Move everything to your personal config path, ex:

```bash
  mv * /path/to/dir
```

Try them, ex:

```bash
  # Try shell config for zsh:

  source /path/to/zshrc # asume zsh installed.

  # Try launching my polybar config(if you use it)

  pkill polybar && polybar -c /path/to/config.ini
```

## ***License***
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/) 
* [GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)


## ***Acknowledgements***

 - [zsh](https://www.zsh.org/)
 - [Bash - GNU Project](https://www.gnu.org/software/bash/)
 - [Polybar](https://polybar.github.io/2023/11/05/Release-3.7.0.html)
