Installation
Prerequisites:
•	tmux >= "v2.4"
•	OSX, Linux (tested on Ubuntu 14 and CentOS7), FreeBSD (tested on 11.1)
On OSX you can install latest 2.6 version with brew install tmux. On Linux it's better to install from source, because official repositories usually contain outdated version. For example, CentOS7 - v1.8 from base repo, Ubuntu 14 - v1.8 from trusty/main. For how to install from source, see this gist or just google it.
To install tmux-config:
$ git clone https://github.com/samoshkin/tmux-config.git
$ ./tmux-config/install.sh
install.sh script does following:
•	copies files to ~/.tmux directory
•	symlink tmux config file at ~/.tmux.conf, existing ~/.tmux.conf will be backed up
•	Tmux Plugin Manager will be installed at default location ~/.tmux/plugins/tpm, unless already presemt
•	required tmux plugins will be installed
Finally, you can jump into a new tmux session:
$ tmux new
