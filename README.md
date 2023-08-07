# --// Hyprland dotfiles //--

```shell
      _  _       .                                             _  _          
     / |/ |     / \         _       _  _                      / |/ |   
    / // /     /^  \      _| |_    | || |_  _ _ __ _ __      / // /   
   / // /     /  _  \    |_   _|   | __ | || | '_ \ '_/     / // /  
  / // /     /  | | ~\     |_|     |_||_|\_, | .__/_|      / // /    
 |_/|_/     /.-'   '-.\                  |__/|_|          |_/|_/                 

```


### Installation

**minimal Arch install (with grub)**
- for default full hyprland installation with all configs
```shell
pacman -Sy git
git clone https://github.com/jonyxz/Dots
cd ~/Dots/Scripts
./install.sh 
```

- for full or minimal hyprland installation + your favorite packages (ex. `custom_apps.lst`) 
```shell
./install.sh custom_apps.lst # full install custom_hypr.lst + custom_app.lst with configs
```

- each [section](#process) can also be independently executed as,
```shell
./install.sh -i # minimal install hyprland without any configs
./install.sh -d # minimal install hyprland without any configs, but with (--noconfirm) install
./install.sh -r # just restores the config files
./install.sh -s # start and enable system services
./install.sh -drs # same as ./install.sh, but with (--noconfirm) install
```
