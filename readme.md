# Al's dotfiles, a fork of Paul's dotfiles that's a fork of mathias's.. (this is getting deep now!)

## Installation

### Using Git and the bootstrap script

```bash
git clone https://github.com/TinyExplosions/dotfiles.git && cd dotfiles && ./bootstrap.sh
```

### Git-free install

```bash
cd; curl -#L https://github.com/TinyExplosions/dotfiles/tarball/master | tar -xzv --strip-components 1 --exclude={README.md,bootstrap.sh}
```

To update later on, just run that command again.

### Sensible OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

## upstream

Suggestions/improvements
[welcome back upstream](https://github.com/mathiasbynens/dotfiles/issues)!
