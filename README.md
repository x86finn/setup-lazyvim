<h1 align="center">💤 Setup Lazyvim | Nerd Font 🤓 | 🪟 Window 11</h1>
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c6ef55cf-65bb-41c7-85e1-3f38ac285aad" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d2d1e959-62a9-4336-8f71-e56de61430a3" />


this is gonna be simple guide to setup your lazyvim . this is the beginner guide that you can't find anywhere else "maybe" let get into it

first of all run this commands into your linux terminal
```
mv ~/.config/nvim{,.bak}
mv ~/.local/share/nvim{,.bak}
mv ~/.local/state/nvim{,.bak}
mv ~/.cache/nvim{,.bak} 
```
╰┈➤ this gonna make a backup for your current neovim file
- then write this command

```
git clone https://github.com/LazyVim/starter ~/.config/nvim
```
╰┈➤ to clone it
```
rm -rf ~/.config/nvim/.git
```
╰┈➤ to delete the .git

- then start the nvim

now you've got the new default lazyvim 
<br/>
Now let's install theme into it for me i like solarized theme 
```
cd ~/.config/nvim/lua/plugins/
```
then type
```
touch solarized.lua
```
now let's edit some file on here by using `nano` or `vim` or `nvim` and then the `<filename>`
```
vim solarized.lua 
```
after that put this <a href="https://github.com/maxmx03/solarized.nvim">solarized.lua</a> into the file
```
return {
  { "maxmx03/solarized.nvim},
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "solarized",
    },
  },
}
```
then save it using ```:wq```
open the nvim again and the lazyvim gonna automatically install the theme and run it .
