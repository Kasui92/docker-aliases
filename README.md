![alt text](https://miro.medium.com/max/2404/1*JUOITpaBdlrMP9D__-K5Fw.png)


# Docker-Aliases

The purpose of this project is to simplify the use of [Docker](https://www.docker.com/) commands through the use of shortcuts and aliases and make it more accessible to everyone, even those who are beginners.

Currently there are some of the main **Docker** commands and some shortcuts to interact with **Docker Compose**. The list of commands can be expanded according to the user's needs by adding new shortcuts in the `.docker_aliases` file.

*This library has been designed to be applied to a LINUX environment or to any other environment equipped with BASH (for example WSL for Windows or macOS)*.

## Installation

Open the `~/.bashrc` (Linux or WSL) or `~/.bash_profile` (macOS) file and add the following at the bottom:

````
# Docker Alias definitions.
# You may want to put all your additions into a separate file like
# ~/.docker_aliases, instead of adding them here directly.

if [ -f ~/.docker_aliases ]; then
    . ~/.docker_aliases
fi
````

Save the `.docker-aliases` file in the same directory as the `~/.bashrc` file.

## Usage

Once installed, you can use the commands in bash.


## Reference

This library of aliases was built from different sources that inspired me and led me to create a version more familiar to me. I am infinitely grateful to the people who contributed to the articles and repositories listed below for their work and the inspiration they have been able to transmit to me.

- [Handy Docker Aliases | Hacker Noon](https://hackernoon.com/handy-docker-aliases-4bd85089a3b8)
- [Useful Docker Bash functions and aliases](https://www.kartar.net/2014/03/useful-docker-bash-functions-and-aliases)
- [ akarzim / zsh-docker-aliases ](https://github.com/akarzim/zsh-docker-aliases)
- [ tcnksm / docker-alias ](https://github.com/tcnksm/docker-alias)




