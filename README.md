# nordic-vim
slim but usefull vim dotfiles using the nord colorscheme
<a href="https://i.imgur.com/T6IY6Mc.png">
  <img src="https://imgur.com/T6IY6Mcl.png" />
</a>


### Why another .vimrc?

When i created the PaperColor-themes Repo i was a beginner in using Vim. I collected tipps from various resources to create a .vimrc with the best tools and settings for my needs.
After a while i learned that many of the plugins and options i used are not neccessary for my work so i removed more and more stuff to create a clean .vimrc that only inclodes the stuff i realy need.
The second problem was the colorscheme, i realy like it and its well developed but for long coding sessions at night it was to much, didnt fit into my desktop and i began using the nord colorscheme.


### What else is new?

Mainly i stopped working with tmux. Its a great tool but had in my eyes to many little anoying bugs. After most big patches i was focred to rewrite the .tmuxrc cause some features was removed or reworked. At the end i choosed Tilix as Terminal and its splitting features.
I also reworked the theme for the zsh-shell to fit in most terminals, now its not created for a fixed theme, it simply uses the colors 0 to 15 of the terminal. you can find it inside the powerbash-zsh repo.

### How to install

If not already installed you need git on your machine:

    $ sudo apt-get install git
     
Then clone the repo to your homefolder, check the included files and move the .vimrc file and the .vim folder inside the nordic-vim folder to your hove folder.

    $ git clone https://github.com/erikschreier/nordic-vim
    $ cd nordic-vim
    $ mv .vimrc .vim ~/
    cd .. && rm -rf nordic-vim
     
