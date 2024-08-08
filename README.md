# Content

## Install

```sh
m='content'; git submodule add "https://github.com/s7357/${m}.git" "${m}"
```

## Update

```sh
git submodule update --recursive --remote --merge
```

## Uninstall

```sh
m='content'; git submodule deinit -f "${m}"; git rm -r --cached "${m}"; rm -rf ".git/modules/${m}"; rm -rf "${m}"
```
