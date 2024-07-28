# // Backup Hyprland dotfiles //

```shell

      _  _     .                  _   _                  _                 _     ____        _              _  _  
     / |/ |   / \         _      | | | |_   _ _ __  _ __| | __ _ _ __   __| |   |  _ \  ___ | |_ ___       / |/ | 
    / // /   /^  \      _| |_    | |_| | | | | '_ \| '__| |/ _` | '_ \ / _` |   | | | |/ _ \| __/ __|     / // /  
   / // /   /  _  \    |_   _|   |  _  | |_| | |_) | |  | | (_| | | | | (_| |   | |_| | (_) | |_\__ \    / // /  
  / // /   /  | | ~\     |_|     |_| |_|\__, | .__/|_|  |_|\__,_|_| |_|\__,_|   |____/ \___/ \__|___/   / // /  
 |_/|_/   /.-'   '-.\                   |___/|_|                                                       |_/|_/
       

```


### Installation

**minimal Arch install (with grub)**
- for default full hyprland installation with all configs
```shell
git clone https://github.com/jonyxz/Dots
cd ~/Dots/Scripts
./install.sh 
```

- for full hyprland installation + favorite packages (`custom_apps.lst`) 
```shell
./install.sh custom_apps.lst # full install custom_hypr.lst + custom_app.lst with configs
```

- each section can also be independently executed as,
```shell
./install.sh -i # minimal install hyprland without any configs
./install.sh -d # minimal install hyprland without any configs, but with (--noconfirm) install
./install.sh -r # just restores the config files
./install.sh -s # start and enable system services
./install.sh -drs # same as ./install.sh, but with (--noconfirm) install
```
