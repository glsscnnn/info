# INFO

Info is a simple script that shows you sys info similar to like pfetch or neofetch. I'd like to belive that this is fairly suckless but there's quite a bit of bloat, you can modify this script reuse it whatever. The only dependencies it has is cowsay which you can remove the cowsay part by just going into the script and removing the line with the comment cowsay over it if you don't want to install cowsay.

# INSTALL

First choose to install cowsay or not, if you choose to install cowsay `sudo pacman -S cowsay` or `sudo apt install cowsay`, after that you can just `pwd` to find the current directory and add that to your path. So like this: `export PATH=[output of pwd]/info:"$PATH" now you can just run info and it'll run fine. You can add this on startup buy just putting `info` at the bottom of your bashrc or zshrc or whatever you use.
