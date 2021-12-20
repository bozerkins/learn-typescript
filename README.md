# Learn typescript

The repository with code examples for learning typescript (and node.js) programming

# Prerequisites

It is preferable to work in a unix-like evnironment. 

MacOS and Linux distributions are inherently unix-like. Windows 10+ has WSL 2 support, which enables Linux sub-system on your operating system.

> Please note that the tutorial is focused on programming on Windows operating system.

## Tools we will be using throughout the learning

* Visual Studio Code - code editor for programming. Required, works on all platformws <br> https://code.visualstudio.com/
* NodeJS compiler with Node Version Manager - a compiler for NodeJS (which TypeScript is based on). Required, works on all playforms <br> 
https://nodejs.org/en/ <br> 
https://github.com/nvm-sh/nvm#installing-and-updating

## Windows-specific tools

Those tools provide for better learning experience for how applications are run and how they interact with related toolkit (docker, databases, etc).

* WSL 2 - Linux-subsystem for Windows. Optional, Recommended. <br> https://docs.microsoft.com/en-us/windows/wsl/about
* Remote WSL - Visual Studio Code extension to work with WSL. Optional, Recommended. <br> https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl
* Windows Terminal <br> https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701

## Installation steps - Windows

This is currently the preferred way of working on Windows.

### Install WSL 2
This command will enable the required optional components, download the latest Linux kernel, set WSL 2 as your default, and install a Linux distribution for you (Ubuntu by default, see below to change this).<br>
https://docs.microsoft.com/en-us/windows/wsl/install#install

### Install Visual Studio Code. 
https://code.visualstudio.com/

### Install Remote WSL extension. 
https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl

### Create WSL user
Open PowerShell and type ```wsl```. This will log you into the wsl system. Configure your creadentials (create user and password), then continue to the next step.

### Install Node Version Manager inside the WSL.
Go into ```wsl``` terminal and run this code
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
Then run Node.JS installation, which will install current LTS version of Node.JS
```bash
nvm install --lts
```

## Installation steps - Windows (alternative)

Alternatively you can use binary Node.JS installation. 

### Install Visual Studio Code. 
https://code.visualstudio.com/

### Install Node.JS binary
https://nodejs.org/en/


## Installation steps - Mac OS

### Install Visual Studio Code. 
https://code.visualstudio.com/

### Install Node Version Manager and Node.JS
Run this command in the terminal
```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
For MacOS there might be some troubleshouting involved, please refer to this guide<br>
https://github.com/nvm-sh/nvm#installing-and-updating

Then install the LTS version of Node.JS
```bash
nvm install --lts
```

## Installation steps - Ubuntu (Linux)

### Install Visual Studio Code. 
https://code.visualstudio.com/

### Install Node Version Manager and Node.JS
Run this command in the terminal
```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```

Then install the LTS version of Node.JS
```bash
nvm install --lts
```
