[![CI](https://github.com/dig1t/dlib/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/dig1t/dlib/actions/workflows/ci.yml)
[![Docs](https://github.com/dig1t/dlib/actions/workflows/docs.yml/badge.svg?branch=main)](https://github.com/dig1t/dlib/actions/workflows/docs.yml)
[![Coverage Status](https://coveralls.io/repos/github/dig1t/dlib/badge.svg?branch=main)](https://coveralls.io/github/dig1t/dlib?branch=main)

# dLib
Modules and Libraries for development in Roblox.

# Installing
## Installing with wally
Add the below line to your wally.toml file
```toml
dLib = "dig1t/dlib@1.1.10"
```
## Installing with Roblox Studio
Download the rbxm file from the [releases](https://github.com/dig1t/dlib/releases) tab and insert it into ReplicatedStorage or your location of choice.

### Usage
```lua
local ReplicatedStorage = game:GetService("ReplicatedStorage")

-- Require dLib from your installation location
-- For this example we'll use ReplicatedStorage as dLib's parent location
-- and we'll import dLib's built in Palette module
local import = require(ReplicatedStorage.dLib).import
local Palette = import("dLib/Palette")

print(Palette.get("blue", 500))
```

[Click here](https://dig1t.github.io/dlib/api/dLib) to learn how to import your first dLib module.
