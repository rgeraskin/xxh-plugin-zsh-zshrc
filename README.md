Who needs zsh without personal settings and custom plugins set?

With this simple plugin for [xxh-shell-zsh](github.com/xxh/xxh-shell-zsh) your ~/.zshrc will be copied to a remote host and sourced by [xxh-shell-zsh](github.com/xxh/xxh-shell-zsh).

It's not official [xxh](github.com/xxh/xxh) plugin. Moreover, perhaps this plugin violates one of the basic rules: `careful`, because of copying .zshrc to the remote host underhood.

## Install
Install:
```
xxh +I xxh-plugin-zsh-zshrc-zshrc+git+https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc
```
Connect:
``` 
xxh yourhost
```
