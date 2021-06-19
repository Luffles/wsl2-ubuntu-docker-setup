# wsl2-ubuntu-docker-setup
https://www.endpoint.com/blog/2020/06/18/linux-development-in-windows-10-docker-wsl-2



Windows:
    Docker for Windows
    https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker
    https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl
    https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

Ubuntu 20.04 WSL2
Install WSL2 update

Launch Ubuntu via VS Code
    Term setup
        PS1='[\u@dev\W]\$ '
        export PROMPT_COMMAND="echo -n \[\$(date +%H:%M:%S)\]\ "