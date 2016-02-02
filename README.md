ansible-coreutils
=================
[![Build Status](https://travis-ci.org/mwilliammyers/ansible-coreutils.svg)](https://travis-ci.org/mwilliammyers/ansible-coreutils)

Install & configure [GNU] [coreutils] on [OS X].

See also: [mwilliammyers.gnu-tools](https://github.com/mwilliammyers/ansible-gnu-tools)

Installation
------------

```
ansible-galaxy install mwilliammyers.coreutils
```

Requirements
------------

[homebrew] and the latest Xcode tools.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: all
      roles:
         - role: mwilliammyers.coreutils
```

Notes
-----

__Warning__: This role modifies your default shell configuration file, eg.
`~/.bash_profile`, `~/.zshrc` or `~/.config/fish/config.fish`.

License
-------

GPLv3

Author Information
------------------

[@mwilliammyers]


[@mwilliammyers]: https://github.com/mwilliammyers
[GNU]: http://www.gnu.org/
[OS X]: http://www.apple.com/osx/
[Xcode]: https://developer.apple.com/xcode/
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[coreutils]: http://www.gnu.org/software/coreutils/
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mwilliammyers/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[neovim]: https://github.com/neovim/neovim
[pip]: https://github.com/pypa/pip
[pure]: https://github.com/sindresorhus/pure
[speedcola]: https://github.com/mwilliammyers/speedcola
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
