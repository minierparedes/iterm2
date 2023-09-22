# Spice up your MacOS Terminal

Written By Utsav

### Here are some steps to juice up the boring MacOS terminal using iterm2.

#### Step 1: Install Homebrew
Run: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

#### Step 2: Install iTerm2
Run: `brew install --cask iterm2`

#### Step 3: Install git
Run: `brew install git`

#### Step 4: Install oh-my-zsh
Run: `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

#### Step 5: Install fonts
Download & Install: [SourceCodePro+PowerLine+AwesomeRegular](https://github.com/Falkor/dotfiles/blob/master/fonts/SourceCodePro%2BPowerline%2BAwesome%2BRegular.ttf)

#### Step 6: Install theme
Run: `git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k`

#### 7: Open VSCode from the Terminal
open vscode's command pallet and type in:

`shell command: install code`

Set theme on .zshrc: `ZSH_THEME="powerlevel10k/powerlevel10k"`

#### Step 8: Update iterm2 preferences
Create new profile, make it default, delete default profile

Set colors to newly created itermcolors files

Set font to SourceCode+PowerLine+AwesomeRegular

#### Step 9: Configure Power Level 10K
Re-launch iterm2 and follow prompts

#### Step 10: Enable suggestions
Clone: `git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`

Add plugin to .zshrc file: `plugins=(zsh-autosuggestions)`

#### Step 11: Configure Vs Code
Update terminal.integrated.fontFamily setting to 
`'SourceCodePro+PowerLine+AwesomeRegular'`


