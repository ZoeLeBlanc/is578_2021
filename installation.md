## Setting Up Your Computer for Coding

In the following sections, we'll go through how to get your computer set up so that you are ready for the course. Follow the instructions for your computer type (Windows = any computer running windows, Mac = any apple computer) Most of the instructions involve clicking on links to follow instructions and pasting text into your computer. If you get stuck or have any problems, please Slack me or email me.

### Windows

* Go to [Windows 10 Installation Guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10) and follow these instructions.


#### Setup Python

* Windows Subsystem Linux (WSL) comes with Python3, but need to install pip.
  
* Open WSL and type:

```sh
sudo apt-get install -y python3-pip
```

* Then you need to install Debian development tools, openSSL, and Python extension headers. Type the following:

```sh
sudo apt-get install build-essential libssl-dev libffi-dev python3-dev
```

* Then update pip:
  
```sh
pip3 install --upgrade pip
```

#### Text Editor

* Finally, install Visual Studio Code for your computer (Select the Download for Mac or download for windows)[Find VS Code here](https://code.visualstudio.com/)

#### More Info

* Feel free to check out this WSL setup for links to more options
[https://github.com/lloydstubber/my-wsl-setup](https://github.com/lloydstubber/my-wsl-setup)

----

### Mac

* Go to [Homebrew](https://brew.sh/)
* Open up Terminal, it should like this:
![Terminal](https://blog.macsales.com/wp-content/uploads/2016/12/DefaultTerminal1280.jpg)

* You can find Terminal in your applications folder. Paste this line into the terminal and press enter:
  
```sh
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

* Once that's complete install Xcode Command Line Tools, by typing into the terminal:

```sh
xcode-select --install
```

#### Setup Python

* Instructions for installing [Python 3](https://docs.python-guide.org/starting/install3/osx/)
  
* Open up your terminal and type this command, then press enter:
  
```sh
brew install python
```

* Then update pip with this command:
  
```sh
pip3 install --upgrade pip
```

#### Text Editor

* Finally, install Visual Studio Code for your computer (Select the Download for Mac or download for windows)[Find VS Code here](https://code.visualstudio.com/)

### Shell (optional, but pretty)

* Install [ZShell (zsh)](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH)
* Install [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)
* Install [iTerm2](https://iterm2.com/)

**CONGRATS YOU'VE SETUP YOUR COMPUTER ????**

## First Steps: Exploring the Command Line 

Let's skim through [https://melaniewalsh.github.io/Intro-Cultural-Analytics/01-Command-Line/01-The-Command-Line.html](https://melaniewalsh.github.io/Intro-Cultural-Analytics/01-Command-Line/01-The-Command-Line.html) and [commandline cheatsheet](commandline_cheatsheet.md).