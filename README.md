**Obsolete, use [starship](https://starship.rs) instead.**

---

# Vibrant

Pretty, minimal and fast prompt, inspired by [Pure](https://github.com/vkovtash/pure)

![ISC-licensed](https://img.shields.io/github/license/derhuerst/vibrant.svg)

[![the Vibrant prompt in action](https://asciinema.org/a/80034.png)](https://asciinema.org/a/80034)

## Install

With [fisherman]:

```shell
fisher add derhuerst/vibrant
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

[fisherman]: https://github.com/fisherman/fisherman
