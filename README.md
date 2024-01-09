# Spice up your MacOS Terminal

Written By Utsav

### Here are some steps to juice up the boring MacOS terminal using iterm2.

#### Step 1: Install Homebrew
Run: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

#### Step 2: Install iTerm2
Run: `brew install --cask iterm2`


#### Step 3: setup Profile files

set .zprofile for homebrew
Run: `'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/ethancrown/.zprofile`


##### install vscode

##### add vscode (code) executable path to your .zshrc
Run: `echo 'export PATH="/Applications/Visual Studio Code.app/Contents/Resources/app/bin:$PATH"' >> ~/.zshrc`

#### Step 4: Install nvm for nodejs
Run: `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash`

#### Step 5: Install pyenv for python
Run: `brew install pyenv`

##### Initialize pyenv in your shell:
Run:
```bash
echo 'export PATH="$HOME/.pyenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(pyenv init --path)"' >> ~/.zshrc
```

#### Step 6: Install git
Run: `brew install git`

#### Step 7: Install oh-my-zsh
Run: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

#### Step 8: Install fonts
Download & Install: [SourceCodePro+PowerLine+AwesomeRegular](https://github.com/Falkor/dotfiles/blob/master/fonts/SourceCodePro%2BPowerline%2BAwesome%2BRegular.ttf)

#### Step 9: Install theme
Run: `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`

#### 10: Open VSCode from the Terminal
open vscode's command pallet and type in:

`shell command: install code`

Set theme on .zshrc: `ZSH_THEME="powerlevel10k/powerlevel10k"`

#### Step 11: Update iterm2 preferences
Create new profile, make it default, delete default profile

Set colors to newly created itermcolors files

Set font to SourceCode+PowerLine+AwesomeRegular

#### Step 12: Configure Power Level 10K
Re-launch iterm2 and follow prompts

#### Step 13: Enable suggestions
Clone: `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`

Add plugin to .zshrc file: `plugins=(zsh-autosuggestions)`

#### Step 14: Configure Vs Code
Update terminal.integrated.fontFamily setting to 
`'SourceCodePro+PowerLine+AwesomeRegular'`

#### Step 15: Install gitui
GitUI provides you with the comfort of a git GUI but right in your terminal
Download & Install: [gitui](https://github.com/extrawurst/gitui)

