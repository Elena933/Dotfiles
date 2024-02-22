# Gitline for Windows

Gitline provides Git status information in your Command Prompt or PowerShell prompt on Windows.

## Instructions for Use

1. **Download**: Download `gitline.sh` from the Gitline repository.

2. **Installation**: Place `gitline.sh` in your preferred location. For example, you can place it in your user directory (`C:\Users\YourUsername\`).

3. **Configuration**: Modify your `.bashrc` or `.bash_profile` file to include the following lines:

   ```bash
   source /c/Users/YourUsername/gitline.sh
   
   build_ps1() {
       local git_line=$(generate_gitline)
       export PS1="\[\e[1;36m\]\u@\h \[\e[1;31m\]\w${git_line}\[\e[1;36m\]\$\[\e[0m\] "
   }
   
   export PROMPT_COMMAND="build_ps1"# Gitline for Windows

Gitline provides Git status information in your Command Prompt or PowerShell prompt on Windows.

## Instructions for Use

1. **Download**: Download `gitline.sh` from the Gitline repository.

2. **Installation**: Place `gitline.sh` in your preferred location. For example, you can place it in your user directory (`C:\Users\YourUsername\`).

3. **Configuration**: Modify your `.bashrc` or `.bash_profile` file to include the following lines:

   ```bash
   source /c/Users/YourUsername/gitline.sh
   
   build_ps1() {
       local git_line=$(generate_gitline)
       export PS1="\[\e[1;36m\]\u@\h \[\e[1;31m\]\w${git_line}\[\e[1;36m\]\$\[\e[0m\] "
   }
   
   export PROMPT_COMMAND="build_ps1"

