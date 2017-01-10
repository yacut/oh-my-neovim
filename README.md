## My workspace

### Upgrade vim config

##### Dependencies:
- https://github.com/neovim/neovim/wiki/Installing-Neovim
- install node npm editorconfig xmllint
- https://github.com/ggreer/the_silver_searcher#installing
- optional install another font: https://github.com/ryanoasis/nerd-fonts#font-installation
- optional ack package: http://beyondgrep.com/install/
- optional for React: 
      - npm install -g babel-eslint eslint-plugin-react
      - add to .eslintrc:
          ```
          "plugins": [
              "react"
          ],
          "parser": "babel-eslint"
          ```

##### Upgrade .vimrc file in home directory:

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/yacut/workspace/master/upgrade_vim_config.sh)"`


### Setup new nodejs project
##### Create .editorconfig, .eslintrc and .tern-project files in current folder:

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/yacut/workspace/master/create_config_files_for_nodejs_project.sh)"`
