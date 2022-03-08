# scoop-neovim-dev

Forked to handle a possible change in the directory structure inside the windows release zip.

```
> scoop bucket add neovim-dev https://github.com/benallan/scoop-neovim-dev
Checking repo... ok
The neovim-dev bucket was added successfully.

> scoop search neovim
'main' bucket:
    neovim (0.3.8)

'neovim-dev' bucket:
    neovim-dev (nightly)
```

after this has been down, you can use `scoop install neovim-dev` to install the nightly build version of neovim.
