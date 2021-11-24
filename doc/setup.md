# Setup env for Clojure and ClojureScript

Setup Clojure env and VSCode on Linux.

## Setup env for Clojure

### Setup Linux 

I use `Majaro i3`, an kind of Linux. How to setup i3 and change resources to Chinese resource? Refer to ???

A more popular way is to use Ubuntu 18.04 or higher.

### Setup clojure

- install openjdk (java sdk)
- install clojure
- install leininger
- install clojure

```bash
wget https://raw.githubusercontent.com/technomancy/leiningen/stable/bin/lein
chmod 755 lein
lein repl   # wait for quite a while, till something like `Clojure 1.10.3 ...` is shown
```

### Setup VSCode

In short: vscode + neovim(optional) + Calva

- vscode, using community edition

- Optional, vscode plugin: neovim. If you want to use vi inner VSCode. WARNING: another popular plugin `vscodevim` has key conflicts with clojure. 

NOTE: neovim should be nightly buiuld 0.5.0 or upper. The stablle build is 0.2.x. 

Install neovim (/usr/bin/neovim) on OS, before install neovim plugin on VSCode.

`yay -S neovim`

https://github.com/neovim/neovim/wiki/Installing-Neovim

- vscode plugin: Calva. ???, How to enable it??? ctrl-shift-c, ctrl-shit-j ???
- 



## Setup env for ClojureScript





