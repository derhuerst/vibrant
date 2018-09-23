![ISC-licensed](https://img.shields.io/github/license/derhuerst/vibrant.svg) [![Slack Room][slack-badge]][slack-link]

# Vibrant

Pretty, minimal and fast prompt, inspired by [Pure](https://github.com/vkovtash/pure)

[![the Vibrant prompt in action](https://asciinema.org/a/80034.png)](https://asciinema.org/a/80034)

## Install

With [fisherman]:

```shell
fisher derhuerst/vibrant
```

## Features

- current path.
- Git
	- untracked files (`*`)
	- dirty files (`±`)
	- staged files (`⇈`)
	- unpushed commits (`↑`)
	- unpulled commits (`↓`)
- prompt character turns red if last command failed
- user and host only shown when root, sudo or in an SSH session

[slack-link]: https://fisherman-wharf.herokuapp.com
[slack-badge]: https://fisherman-wharf.herokuapp.com/badge.svg
[fisherman]: https://github.com/fisherman/fisherman
