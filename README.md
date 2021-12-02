# MyVIM Configuration File



```
- my_vimrc 					# my vim config file on Windows, you can copy it to ~/.vimrc
- vimrc_ubuntu				# my vim config file on Ubuntu, you can copy it to ~/.vimrc
- plug.vim					# the vim plugins manager, Vim-plug, copy it into ~/.vim/autoload/
```



## Install dependency

- install nodejs, yarn (coc.vim need!, if you don't install nodejs)

```
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -				# to install nodejs, the version: 14x
sudo apt-get install -y nodejs
sudo apt install yarn														# to install yarn

# change to the directory, ~/.vim/plugged/coc.nvim
yarn install

```

- install coc-pyright coc-python

```
:CocInstall coc-python coc-pyright
```

