Install Chocolaty from https://chocolatey.org/install or you can install it from nodeJs module by clicking this prompt while installing nodeJs image=>choco-prompt-nodejs.jpg

after Installing Choco

Now Time to install Neovim

choco install neovim

then Press [Y] to Completely Install NeoVim

Image=>neovim_install_terminal.png

I have Already Installed So its Showing already Installed.

Once Installed.

Press Win+r and Type `%appdata%` or go to `C:\Users\[Your-desktop-user]\AppData\Local\`

If nvim folder is present in the Local Folder then create a init.vim file using command touch init.vim
If nvim folder doesn't exists then create a new folder named nvim and then create a init.vim file and start editing.


Now Here It Gets TrickyL:
    If you want to get plugins in your neovim we have install a library to install plugins to our config file.
    Now go to this repo for installing plugin library : https://github.com/junegunn/vim-plug

    Open Power Shell in adminstrative mode and copy this block and paste then hit enter

    After Then Install git beacuse Vim-plug require git to run

    and then Install Nerd Font

    and copy the init file

    and then open with nvim and type :PlugInstall and then enjoy the Customized NeoVim



    In My System I don't Have Nerd Fonts Still It Looks Good 


