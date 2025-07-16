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

