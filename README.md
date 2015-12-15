dotstrap-coreutils
==================
<!-- [![Build Status](https://travis-ci.org/mkwmms/ansible-dotstrap-coreutils.svg)](https://travis-ci.org/mkwmms/dotstrap-coreutils) -->

Install & configure GNU coreutils on OS X

Requirements
------------

[homebrew] and the latest XCode tools.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: servers
      roles:
         - { role: mkwmms.coreutils }
```

License
-------

GPLv3

Author Information
------------------

[@mkwmms]


[@mkwmms]: https://github.com/mkwmms
[dotstrap]: https://github.com/mkwmms/dotstrap
[homebrew]: https://github.com/Homebrew/homebrew
[files]: files/
[default variables]: defaults/main.yml
[variables]: vars/main.yml
[zsh]: http://zsh.sourceforge.net
[fish]: http://fishshell.com/
