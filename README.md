# Content

## Install

```
git submodule add 'https://github.com/site-0002/content.git' 'content'
```

## Update

```
git submodule update --recursive --remote --merge
```

## Uninstall

```
git submodule deinit -f 'content'; git rm -r --cached 'content'; rm -rf '.git/modules/content'; rm -rf 'content'
```
