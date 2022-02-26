# lr-module-gen readme
## Installation
### npm/yarn 
```zsh
npm i -g lr-module-gen
# or #
yarn global add lr-module-gen
```
### from sources
```zsh
# install nodejs + yarn if not yet
# git clone this repo
yarn
yarn run run # will compile cli
yarn link
# to uninstall 
yarn unlink
```
to recompile cli
```zsh
yarn run run
```

## First steps (just to figure out how it works)
1. mkdir & cd to new empty project directory
2. Call `lr-module-gen init` && `lr-module-gen init template-sample`
3. All project info will be placed in `.lr.module.gen` & simple templates inside `templates` directory
4. To generate module call `lr-module-gen gen` or `lr-module-gen gen module`

## Known bugs
- Template module pick when calling `lr-module-gen gen` has some glitches, with double focus on filter & time delay
## External templates check points
- info.js inside template directory included as simple js file, with rw permissions, all templates should be checked & verified by user
- 