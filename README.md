# LOVE VSCode Fennel Game Template
Combining Template from several sources
https://sheepolution.com/learn/book/bonus/vscode
https://github.com/Keyslam/LOVE-VSCode-Game-Template
https://gitlab.com/alexjgriffith/min-love2d-fennel

# Other Sources

https://github.com/a-mt/docker-love2d/tree/master
https://github.com/pfirsich/makelove

## Features

## External Libs

Functions
https://github.com/rxi/lume

Animation
https://github.com/kikito/anim8

Collision
https://github.com/kikito/bump.lua

Tiled
https://github.com/karai17/Simple-Tiled-Implementation


## Prerequisites


## Running

Running Love
```.sh
love .
```

## Structure
```
├── /Game
│   ├── /assets         Contains the game's assets
│   ├── /lib            Contains external libraries
│   └── /src            Contains the game's source code
│
├── Tools
│   ├── /build          Contains the makelove.toml
│   └── package.json    Contains all scripts to use with NPM Scripts
│
├── Resources           Contains resources for you game that should not be shipped, like raw audio
│
├── Builds              Contains the builds of your game made with makelove
│
└── Root                Root access to the workspace
```

## Release Command

CTRL + SHIFT + B to run build task

or

Go to tools/ and run npm run Build


## Links
https://wiki.fennel-lang.org/Editors

## Todo

- [ ] Add prettier
- [ ] Add eslint
- [ ] Add more documentation
- [ ] Add more tests
- [ ] Add binary build
- [ ] Add quick start config script
- [☑️] Add alexjgriffith's Fennel Template (https://gitlab.com/alexjgriffith/min-love2d-fennel)
- [☑️] Add Keyslam's Template (https://github.com/Keyslam/LOVE-VSCode-Game-Template)
- [☑️] Add Makelove.toml (https://github.com/pfirsich/makelove)
