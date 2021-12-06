Hello and Congrats on setting up your computer for development. Setup instructions for Raybeam's preferred tools are below. If you prefer different development tools, feel free to use those instead.

At Raybeam we generally recommend using the following development tools: 

Tools on Mac:
- terminal: iterm2
- package manager: Homebrew
- shell: zsh + OhMyZsh shell configuration for easier usability
- text editor: Visual Studio Code (VS Code)
- virtualization: Docker

Tools on Windows:
- linux compatibility layer: WSL2
- terminal: Windows Terminal Emulator
- package manager: chocolatey
- shell: zsh + OhMyZsh for easier usability
- text editor: Visual Studio Code (VS Code)
- virtualization: Docker

Setup is very different between Mac and windows. Make sure you follow the set up instructions that corresponds with your machine type. Mac now has two processor chip types: legacy intel chips and M1 chips for new MacBook Air's from 2021 and later. You may need to adjust your setup if you have an Mac with an M1 chip.

# Local Envionment Setup for Mac
## iterm2 (terminal) installation
(Download)[https://iterm2.com/index.html], (Documentation)[https://iterm2.com/documentation-one-page.html#documentation-highlights.html]
<br>
1. Review the iterm2 documentation to understand its benefits and features 
2. (Download iterm2)[https://iterm2.com/] from the official website to your local 'downloads' directory (the 'downloads' is the preconfigured defualt download directory on Mac).
3. Drag the iterm2 from your local 'downloads' folder to 'applications'.
4. Open iterm2 from applications.
5. Pin iterm2 to your doc if you'll be using it frequently.

## homebrew (package manager) installation
(Documentation)[https://brew.sh/]
<br>
1. Review the homebrew (Documentation)[https://brew.sh/] to understand how to use it 
2. Copy and paste the following into your terminal and hit **return**:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```
Respond to the command line prompts as they appear. Type 'yes' for the options.

3. Confirm that homebrew installed correctly. In your terminal type the following and hit **return**:
```
brew --version
```
The response should look like this. Later versions are ok too:
```
Homebrew 3.3.4
Homebrew/homebrew-core (git revision 1bd12fbea7b; last commit 2021-11-18)
Homebrew/homebrew-cask (git revision 8fdad7ef8a; last commit 2021-11-19)
```


## zsh (shell) installation + OhMyZsh configuration
### zsh (shell) installation
Most macs come with zsh pre-installed. To check whether zsh is installed on your machine type the following into your terminal and hit **return**:
```
$ zsh --version
```
The response should look like this. Later versions are ok too:
```
zsh 5.8 (x86_64-apple-darwin20.0)
```

If you receive the error 'zsh is not a command' then you need to install zsh. <br>

Use the homebrew package manager to install zsh. To do so, type the following into your terminal and hit **return**
```
brew install zsh
```

Now confirm again whether zsh is installed.

### OhMyZsh shell configuration setup
(download)[https://ohmyz.sh/], [documentation](https://github.com/ohmyzsh/ohmyzsh/wiki)

The OhMyZsh shell configuration will help you work faster in your shell by adding additional features such as copy/paste with keyboard shortcuts, text highlighting, text serching, autocomplete, and more. You can update the zsh configuration for a specific (theme)[https://github.com/ohmyzsh/ohmyzsh/wiki/Themes] by modifying your .zsrch file. 

To install OhMyZsh, copy the following paste it into your terminal and hit **enter**:
```
$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## VS Code (text editor) installation
VS Code is a text editor that offers multiple features such as text hihglighting for python and sql, soure links, search/replace and more. 

(Download)[https://code.visualstudio.com/download], (Documentation)[https://code.visualstudio.com/docs]
<br>
1. Review the VS Code documentation to understand its benefits and features 
2. (Download VS Code)[https://code.visualstudio.com/download] from the official website to your local 'downloads' directory (the 'downloads' is the preconfigured defualt download directory on Mac).
3. Drag the VS Code from your local 'downloads' folder to 'applications'.
4. Open VS Code from applications.
5. Pin VS Code to your doc if you'll be using it frequently.

# Local Environment Setup for Widows - more info to be populated...