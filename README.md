# zsh-systemd-extension

This extension is for `oh-my-zsh`'s included systemd plugin.



## Install (oh-my-zsh)

1. clone the repository into your `.oh-my-zsh` custom plugins directory

```bash
git clone https://github.com/UncleClapton/zsh-systemd-extension.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-systemd-extension
```

2. Add the plugin to your `~/.zshrc`

```bash
plugins=(... zsh-systemd-extension)
```

## Aliases

| Alias                  | Command                            | Description                                    |
|:-----------------------|:-----------------------------------|:-----------------------------------------------|
| `sc-reload-daemon`     | `sudo systemctl daemon-reload`     | Reloads systemd daemon (for unit file changes) |

(More soon?)
