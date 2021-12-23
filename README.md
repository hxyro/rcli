# rcli
Browse and download images from reddit.

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

## Usege

