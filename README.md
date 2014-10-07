dotfiles.git
============
Clone and run this on terminal to configure your `bash` and `emacs` 'screen'
development environment as follows:

```sh
cd $HOME
git clone https://github.com/VictorBarrigaJr/dotfiles
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```
