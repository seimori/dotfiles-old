# dotfiles
Where I keep my current configuration

I've set it up following [smalleycreative's tutorial](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)

To install, clone it and write this in terminal:
````
cd ~/dotfiles
chmod +x makesymlinks.sh
./makesymlinks.sh
````

Alernatively I added a makesymlinks_without.sh install. As the name implies, it is for use when you don't want the script to install zsh on top of changing dotfiles (e.g. if used on another person's machine). 
