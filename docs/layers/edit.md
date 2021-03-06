---
title: "SpaceVim edit layer"
description: "Improve code edit expr in SpaceVim, provide more text opjects."
---

# [Available Layers](../) >> edit

<!-- vim-markdown-toc GFM -->

- [Description](#description)
- [Features](#features)
- [Options](#options)
- [Key bindings](#key-bindings)

<!-- vim-markdown-toc -->

## Description

This layer provides many edit key bindings for SpaceVim, and also provides more text objects.

## Features

- change surround symbol via vim-surround
- repeat latest action via vim-repeat
- multiple cursor
- align
- highlight whitespace at the end of a line
- load ditorconfig config, need `+python` or `+python3`

## Options

- `textobj`: specified a list of text opjects to be enabled, the avaliable list is :`indent`, `line`, `entire`

## Key bindings

Key binding           | desc
---                  | ---
`SPC x a {delimiter}` | align content based on delimiter

**default delimiters**

- `=`: align `===`, `==`, `!=`, `>=` etc.
- `&`: align `&`
- `¦`: align `¦`
- `;`: align `;`
- `:`: align `:`
- `,`: align `,`
- `.`: align `.`
- `[`: align `[`
- `(`: align `(`
- `{`: align `{`
- `]`: align `]`
- `}`: align `}`
- `)`: align `)`

