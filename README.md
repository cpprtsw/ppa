# PPA

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://spdx.org/licenses/MIT)
![Open Source? Yes!](https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github)

## Install Ubuntu 20.04 'focal'
```
curl -s --compressed "https://cpprtsw.github.io/ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/cpprtsw-ubuntu-focal.list "https://cpprtsw.github.io/ppa/dists/focal/files.list"
sudo apt update
```

## Install Ubuntu 21.04 'hirsute'
```
curl -s --compressed "https://cpprtsw.github.io/ppa/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/cpprtsw-ubuntu-hirsute.list "https://cpprtsw.github.io/ppa/dists/hirsute/files.list"
sudo apt update
```

## Author

Reinventing The Square Wheel - [Github](https://github.com/cpprtsw)

## License

This project is [MIT](https://spdx.org/licenses/MIT) licensed.
