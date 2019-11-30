# my-ohmyzsh-rc

This is my .zshrc file. It uses the fantastic `Oh My Zsh`, which will need to be downloaded from [here](https://ohmyz.sh/) or use the following command  
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Using zsh-autosuggestions
My zshrc also leverages the autosuggestions plugins from here: https://github.com/zsh-users/zsh-autosuggestions  
After installing oh-my-zsh, run the following command to clone zsh-autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

## TMUX-CONFIG
To use tmux-config that supercharges your tmux environment:
```
$ git clone https://github.com/samoshkin/tmux-config.git
$ ./tmux-config/install.sh
```
