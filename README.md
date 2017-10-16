# fortune-cocktails
IBA official cocktail recipes for the `fortune` program.

## Example
```
$ fortune cocktails | cowsay
 ______________________________________ 
/ The "Manhattan"                      \
|                                      |
| - 5 cl rye whiskey                   |
|                                      |
| - 2 cl sweet red vermouth            |
|                                      |
| - dash of angostura bitters          |
|                                      |
| Stirred over ice, strained into a    |
| chilled glass, garnished, and served |
\ up.                                  /
 -------------------------------------- 
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

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

### Downloading the repository
```bash
$ git clone https://github.com/j0hax/fortune-cocktails.git
$ cd fortune-cocktails-master
```

### Generating strings file
If the cocktail recipes do not work out-of-the-box, you may have to regenerate the strings file.
```bash
$ strfile cocktails
```

### Copying to fortune's database
```
# Copy to fortune's databases on Linux
$ sudo cp cocktails cocktails.dat /usr/share/games/fortunes/

# on macOS
$ sudo cp cocktails cocktails.dat /usr/local/share/games/fortunes/
```
