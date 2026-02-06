# Changelog

## Releasing new versions

- update changelog below
- verify copyright years in `LICENSE`, and when adding new Lua versions, update the license details
- create a new rockspec file
- update version constant in `src/cluacov/version.lua`
- push updates to a new branche `release/x.x.x` and create a PR
- after merging, tag the commit with the new version and push the tag
- upload to LuaRocks should be automatic through the deploy workflow, after the tag is pushed

## 1.0.0 (2026-02-06)

Added Lua 5.5 compatibility.

## 0.1.4 (2024-08-27)

Updated LuaJIT embedded header to luajit-2.1 rolling release code
and Lua 5.4 embedded source to Lua 5.4.7.

## 0.1.3 (2024-05-14)

Updated LuaJIT and Lua 5.4 embedded sources.

## 0.1.2 (2020-08-20)

Lua 5.4 support.

## 0.1.1 (2018-05-05)

Updated dependency on luacov to 0.13.0.

## 0.1.0 (2016-06-29)

Initial release.
