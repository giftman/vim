#vim
#===
#sync with linux vim

Install Step:

unzip to /opt/vim  

export VIM=/opt/vim

cp -l $VIM/.vimrc ~/

cd $VIM

git pull



#Some Bundle skill
vim
:BundleInstall
:BundleSearch "taglist"
:BundleClean
