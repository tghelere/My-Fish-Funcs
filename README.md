<h1 align="center">Welcome to My-Fish-Funcs :bulb:</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />  
  <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  <a href="https://www.gnu.org/licenses/gpl-3.0.en.html" target="_blank">
    <img alt="License: GNU GPLv3" src="https://img.shields.io/badge/License-GNU GPLv3-yellow.svg" />
  </a>
  <a href="https://twitter.com/tghelere" target="_blank">
    <img alt="Twitter: tghelere" src="https://img.shields.io/twitter/follow/tghelere.svg?style=social" />
  </a>
</p>

> Some of my utility fish functions


## Install

```sh
git clone git@github.com:tghelere/My-Fish-Funcs.git ~/.config/fish/functions/
```
OR
```sh
cd ~/.config/fish/
git clone git@github.com:tghelere/My-Fish-Funcs.git functions
```

## Usage

Run the following command on your [fishshell](https://fishshell.com/)
```sh
$ fishing
```
`fishing` command is referent the [fishing.fish](https://github.com/tghelere/My-Fish-Funcs/blob/master/fishing.fish) file of the functions folder created by this repository

#### Code of the 'fishing' function:
```bash
# this command just go to the functions folder and list functions
function fishing
  cd /home/$USER/.config/fish/functions
  ll
end
```

Each function is documented in code comments to better exemplify/explain what the function does

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />
Feel free to check [issues page](https://github.com/tghelere/My-Fish-Funcs/issues). You can also take a look at the [contributing guide](https://github.com/tghelere/My-Fish-Funcs/blob/master/CONTRIBUTING.md).

## ⭐️ Show your support

Give a star if this project helped you!

## 📝 License

Copyright © 2020 [Thyago Ghelere](https://github.com/tghelere).<br />
This project is [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html) licensed.

## 👤 Author

**Thyago Ghelere**
* Github: [@tghelere](https://github.com/tghelere)
* Twitter: [@tghelere](https://twitter.com/tghelere)
* LinkedIn: [@ghelere](https://linkedin.com/in/ghelere)