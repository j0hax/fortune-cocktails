# fortune-cocktails
IBA official cocktail recipes for the fortune program

## Installation
This is an extension to the [fortune](http://linux.die.net/man/6/fortune) program. You must install it in order to use these cocktail recipes.

```bash
# Debian/Ubuntu
$ sudo apt install fortune

# Arch Linux
$ sudo pacman -S fortune-mod

# Mac
$ brew install fortune
```

Run `git clone https://github.com/j0hax/fortune-cocktails.git` to download the repository, then copy the fortune files to the directory used by `fortune`:

On Arch/Debian/Ubuntu: `sudo cp fortune-cocktails-master/cocktails* /usr/share/games/fortunes/`

On macOS: `sudo cp fortune-cocktails-master/cocktails* /usr/local/share/games/fortunes/`
