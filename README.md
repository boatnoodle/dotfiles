## Problems & Inspiration

I’ve had problem in a long time about moving to the new Mac. Because I didn’t remember my application I used, even un count the unmanageable dotfiles I still can’t remember anything. Luckily, I’m inspired by P’Noom (Narze) that the way he organized his dotfile stuff. 

This is the original repo https://github.com/narze/dotfiles

## My Dotfile Repo

[https://github.com/boatnoodle/dotfiles](https://github.com/boatnoodle/dotfiles)

## How to automate

1. Run below command to install `homebrew`, `ohmyzsh`, `chezmoi` accordingly. After finishing those installation, it will read through the `.chezmoiscripts`  and set up packages, applications respectively.
    
    ```python
     /bin/bash -c "$(curl -fsSL [https://raw.githubusercontent.com/boatnoodle/dotfiles/main/install.sh](https://raw.githubusercontent.com/boatnoodle/dotfiles/main/install.sh))"
    ```
    
    - Essential commands for managing `chezmoi`
        - `chezmoi add $FILE` - to add any dotfile
        - `chezmoi apply` - to apply all backup dotfile
        - `chezmoi cd` - to jump in a local git that is the place we can organize our dotfiles repo.
            - `exit` - we can use exit command to jump out to the home directory.
2. Do the manual task
    1.  karabiner-elements
        1. create `~/.config/karabiner/karabiner.json`
        2. create  `default` name profile in karabiner app 
        3. run `goku` 
        4. boom finish!
    2. iterm2
        1. go to `setting->preferences`
        2. tick Load preferences from a custom folder on URL
        3. browse to `~/iTerm2`
        4. should works

## My Dotfiles

- ~~zsh~~
    - *`.zshrc`*
- ~~oh-my-zsh~~
    - `~/.oh-my-zsh`
- powerlevel10k
    - `~/.p10k.zsh`,
- ~~karabiner-elements~~
    - create `~/.config/karabiner/karabiner.json`
    - create  `default` name profile in karabiner app
    - run `goku`
    - boom finish!
- keyboard meastro
    - [https://forum.keyboardmaestro.com/t/backup-keyboard-maestro-export-all-macros-clipboards-and-variables/11427/5](https://forum.keyboardmaestro.com/t/backup-keyboard-maestro-export-all-macros-clipboards-and-variables/11427/5)
    - [https://wiki.keyboardmaestro.com/manual/How_do_I#How_do_I_backuptransfer_my_installation_to_another_Mac](https://wiki.keyboardmaestro.com/manual/How_do_I#How_do_I_backuptransfer_my_installation_to_another_Mac)
    - ****How do I backup / migrate / transfer my installation to another Mac?****

## List of my applications 2023

- Devtools
    - VS code
    - Iterm2
    - Insomnia
    - NoSqlBootster
    - Linear
    - Docker
    - Android Studio
    - Raycast
- Browser
    - Arc
    - Chrome
    - Firefox?
- Productivity  tools
    - Rectangle/Yabai?
    - karabiner
    - keyboard meastro
    - Be Focused [ lack ]
- Social media
    - Line [lack]
    - Discord
    - Slack
- Note
    - Notion
