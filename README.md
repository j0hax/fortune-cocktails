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
### Copying Files

```bash
# Download the repository
git clone https://github.com/j0hax/fortune-cocktails.git

# Copy to fortune's databases on Linux
sudo cp fortune-cocktails-master/cocktails* /usr/share/games/fortunes/

# or to Mac
sudo cp fortune-cocktails-master/cocktails* /usr/local/share/games/fortunes/
```
