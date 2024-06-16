# Convenience scripts

These scripts work in conjunction with my dotfiles to make my workflow much
easier.

Simply create a directory called `scripts` in the home directory under `.local`, and
you should be good to go. (The dot files add this directory to the `$PATH`).

## Installation

1. First setup the directory:
`mkdir -p ~/.local/scripts`

2. Then clone this repository to another directory (replace `.custom-repos` with
your own):
` git clone --depth=1 git@github.com:mendydias/scripts.git ~/.custom-repos `

3. Finally, symlink the scripts you need to the directory you set up in the fist
step:
`ln -s /home/<username>/.custom-repos/scripts/<script name>
/home/<username>/.local/scripts/<script name>`

Replace `<username>` with your username,  `<script name>` with one of the script
filenames in this repo.
