# ⚡️ NVIM CONFIGURATION 

## 🚨 Prerequisites 

**Version Requirements:**
- zsh 5.9
- HomeBrew 4.1.17
- Nvim 0.9.4

**Installation Steps:**

1. **Install HomeBrew**  
   Open a terminal and paste this command:  
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. **Install iTerm2**
   ```bash
   brew install --cask iterm2

3. **Install Git**
   ```bash
   brew install git

4. **Install OhMyZsh**
   ```bash
   sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

5. **Install PowerLevel10K Theme**
   ```bash
   git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
- Then, open the ~/.zshrc file with your preferred editor and change the value of ZSH_THEME as shown below:
  ```bash
  ZSH_THEME="powerlevel10k/powerlevel10k"
- To apply the changes, restart your terminal or run this command:
  ```bash
  source ~/.zshrc
- To reconfigure the theme, type in the terminal:
  ```bash
  p10k configure

5. **Using Nvim as an IDE**  

- Follow the files below to use nvim as an IDE 🚀

6. **Tips** 🦸🏻‍♀️

- `space`+ `e` => Show/Hiden tree menu
- In the tree menu, hover over a file or folder and press `a` => You will have the option to create a file or a folder.
- `shift` + `e`=> end of word
- `shift` + `b`=> bottom of word
- `shift` + `g`=> last line of the file
- `shift` + `ff` => Open Telescope
- `:Mason` => view all language settings
- If the word is underlined, switch to normal mode, hover over the word, and press `space` + `d` 
- For delete a block => `v` + `G` + `d`
- `ctrl` + `h` => Go to the tree menu
- ressources => https://github.com/rockerBOO/awesome-neovim


# ⚡️ YABAI CONFIGURATION 

1. Install Yabai
   ```bash
   brew install koekeishiya/formulae/yabai

2. Install Skhd
   ```bash
   brew install koekeishiya/formulae/skhd

3. Config Yabai
   Move to `~`
   ```bash
   mkdir .config/yabai
   cd .config/yabai
   touch yabairc
- Follow the files below to use yabai 🚀

4. Config Skhd
   Move to `~`
   ```bash
   mkdir .config/skhd
   cd .config/skhd
   touch skhdrc
- Follow the files below to use skhd 🚀


**Enjoy it! 🌈**
