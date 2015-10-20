# vim-indent

> Convert between tabs and spaces

Convert the current buffer indentation from tabs to spaces, and vice versa. Adapted from [Super Retab](http://vim.wikia.com/wiki/VimTip1592).

## Features

- Works with smart tabs
- Works within line ranges
- Integrated with buffer `expandtab` and `tabstop` settings


## Commands

| Command | Action |
| ------- | ------ |
| `:[range]IndentSpacesToTabs [tabstop]` | Convert the buffer/range to use tabs |
| `:[range]IndentTabsToSpaces [tabstop]` | Convert the buffer/range to use spaces |
| `:[range]IndentCleanup [tabstop]` | Normalize the buffer/range indentation based on the buffer's `expandtab` setting |

Where specified, `tabstop` is used as the tab width for the conversion. If it is not explicitly passed, it will default to the value of the buffer's `tabstop` setting.
