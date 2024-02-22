Installation
To install tmux-config:
$ git clone https://github.com/samoshkin/tmux-config.git
$ ./tmux-config/install.sh
install.sh script does following:
•	copies files to ~/.tmux directory
•	symlink tmux config file at ~/.tmux.conf, existing ~/.tmux.conf will be backed up
•	Tmux Plugin Manager will be installed at default location ~/.tmux/plugins/tpm, unless already presemt
•	required tmux plugins will be installed
Finally, jump into a new tmux session:
$ tmux new
