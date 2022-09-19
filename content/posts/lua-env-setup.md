---
title: "Lua Env Setup"
date: 2022-09-18T03:29:01+08:00
# bookComments: false
# bookSearchExclude: false
showToc: true
---



## luarocks
a lua package manager

```shell
brew install luarocks  
```

## cjson

install:
```shell
luarocks install lua-cjson2
```

uninstall: 
```shell
luarocks remove lua-cjson2
```

usage:

```lua

local cjson = require "cjson"
cjson.encode(xxx)
```
