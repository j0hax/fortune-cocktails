# fortune-cocktails
IBA official cocktail recipes for the fortune program

## Installation
First install [fortune package](http://linux.die.net/man/6/fortune). If your computer has already installed it, skip this step.

```bash
# Debian/Ubuntu
$ sudo apt install fortune

# Mac
$ brew install fortune
```

Run `git clone https://github.com/j0hax/fortune-cocktails.git` to download the repository, then copy the fortune files to the directory used by `fortune`:

On Debian/Ubuntu: `sudo cp fortune-cocktails-master/cocktails* /usr/share/games/fortunes/`
On macOS: `sudo cp fortune-cocktails-master/cocktails* /usr/local/share/games/fortunes/`
