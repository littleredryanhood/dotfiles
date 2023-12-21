# dotfiles

collection of dot files

##Deploy to linux

install starship, add to .bashrc
#I should probably create a bashrc and add it to this repo, but for now just add the below line.
`echo "eval "$(starship init bash)" >> ~/.bashrc`

clone this repo to ~/git/dotfiles
Make sure ~/.config exists, if not make it
`mkdir ~/.config`

create a symlink for starship.toml
`ln - s ~/git/dotfiles/starship/starship.toml ~/.config/starship.toml`
