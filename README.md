# rcli   ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hxyro/rcli?color=g) ![GitHub top language](https://img.shields.io/github/languages/top/hxyro/rcli?color=g)  ![GitHub contributors](https://img.shields.io/github/contributors/hxyro/rcli?color=g) ![GitHub](https://img.shields.io/github/license/hxyro/rcli?color=g) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/hxyro/rcli?color=g)
---
Browse and download images from reddit.

<p align="center"><img src="https://raw.githubusercontent.com/hxyro/rcli/master/assets/demo.gif" width=990px alt="demo"></p>

---
## Fast Installation
```
curl -sL "https://raw.githubusercontent.com/hxyro/rcli/master/rcli" | sudo tee /usr/local/bin/rcli >/dev/null && sudo chmod 755 /usr/local/bin/rcli
```

---
## Dependencies
* required
    * [`fzf`](https://github.com/junegunn/fzf)
    * [`curl`](https://github.com/curl/curl) 
    * [`jq`](https://github.com/stedolan/jq) (to parse json)
    * [`Überzug`](https://github.com/seebye/ueberzug) (for image preview)
* optional
    * [`dunst`](https://github.com/dunst-project/dunst) (for desktop notifications)
    * [`xclip`](https://github.com/astrand/xclip)

## Install dependencies

* ## `Arch based`
    ```
    sudo pacman -S jq dunst fzf xclip curl ueberzug
    ```
* ## `Debian based`
    ```
    sudo apt install jq curl fzf xclip dunst
    pip install ueberzug
    ```
---

## [Customization](https://github.com/hxyro/rcli/blob/main/config.example)
To see all available color options, open the configuration file 

    $HOME/.config/rcli/config
    
        # sets default color scheme
        # available options: doom-one, gruv-box, nord, dracula, solarized
        COLOR_SCHEME="doom-one"

## [License](https://github.com/hxyro/rcli/blob/main/LICENSE)


The GNU General Public License v3.0 (GPL-3.0)

Copyright (c) 2021-2022 Shubham vyas


