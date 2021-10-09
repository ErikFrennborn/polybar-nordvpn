# polybar-nordvpn

Polybar nordvpn module.

Display current vpn status and also for easy connection and disconnect via clicking the module.

## Installation/usage

Requires python3.10 and nordvpn cli so for arch [link](https://aur.archlinux.org/packages/nordvpn-bin/)

1. Pull that repo into ./config/polybar/
2. Configure display setting in nordvpn/main
3. Added the module to polybar configure, for example
4. Surf safe and enjoy

```
[module/nordvpn]
type = custom/script
interval = 10
format = 旅 <label>
exec = python3.10 .config/polybar/nordvpn/main.py
click-left = python3.10 .config/polybar/nordvpn/main.py click
```

## Contibution

If you want contibution it would most welcome, please a pull request to master and I will look at it as soon as I can. Please explain what and why you did and keep consistent code style. Thanks in advance.
