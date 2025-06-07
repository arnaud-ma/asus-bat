# `asus-bat`

Simple fork of [bat](https://tshaka.dev/x/bat) but renamed to `asus-bat` to avoid name conflicts with the other [bat](https://github.com/sharkdp/bat) (the text file viewer). See [tshaka.dev/x/bat](https://tshaka.dev/x/bat) for the original project.

## Installation

A fork does not supports releases. So you can install it by cloning the repository and building it yourself:

```bash
# cd in any directory you want to clone the repository
git clone https://github.com/arnaud-ma/asus-bat.git
cd asus-bat
make build
chmod +x bin/asus-bat
sudo ln -s $(pwd)/bin/asus-bat /usr/local/bin/asus-bat
```
