# MacSetup
Set up a personal note repository for mac setup

## Setup Fish Shell
- Install fish shell with brew
```
brew install fish
```
- Install oh-my-fish
```
curl -L https://get.oh-my.fish | fish
```
- Change fish shell as default
 - Open `/etc/shell` in your text editor and add `/usr/local/bin/fish` at the end.
 - Change shell
   ```
   chsh -s /usr/local/bin/fish
   ```
