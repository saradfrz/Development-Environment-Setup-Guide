# Setting up a development environment in WSL

## Install WSL
- In a Powershell window: `wsl --install`
- Install Ubuntu 20.04LTS from Microsoft Store
- Restart Windows
- Wait for Ubuntu to finish installing.
- Setup your username and password
- `sudo apt update`
- `sudo apt upgrade`

## Using WSL in VSCode
 - Open a new VSCode Window
 - CTRL + shift + P
 - WSL: New WSL Window
 - Open Folder: `/home/{user}/`

## Configure SSH
- [Add a New SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account?platform=linux)

## Create virtual env
- Install pip<br>
`sudo apt-get install python3-pip`
- Install virtualenv<br>
`sudo pip3 install virtualenv`
- Create virtualenv<br>
`virtualenv .venv`
