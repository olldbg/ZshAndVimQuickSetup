# ZshAndVimQuickSetup
setting up [oh-my-zsh](https://ohmyz.sh/) and my vim plugin quickly 

## Introduction

oh-my-zsh and vim plugin can improve my shell operation enormously, but official installation need connect to server and download necessary files. Given slow bandwidth outside the GFW，is painfully to reinstall the two plugin on new installed system. In order to support `offline mode`, I have packaged necessary files, these can made me happy when install them next time.

## Installation

1. need install zsh and vim first

   ```shell
   # for debain/ubuntu based system
   sudo apt install zsh vim
   
   # for centos/fedora based system
   sudo yum install zsh vim
   ```

2. switch to zsh

   ```shell
   chsh `whoami` -s /usr/bin/zsh
   ```

3. clone this repository

   ```shell
   git clone https://github.com/olldbg/ZshAndVimQuickSetup.git
   ```

4. run `setup.sh`
   ```shell
   cd ZshAndVimQuickSetup
   chmod +x setup.sh
   ./setup.sh
   ```
   
5. install `YouCompleteMe`

   ```shell
   # follow https://github.com/ycm-core/YouCompleteMe#linux-64-bit compile YouCompleteMe
   ```
   
   



