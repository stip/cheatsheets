---
title: neovim
category: vi
layout: 2017/sheet
tags: [Featured]
weight: -5
description: neovim configuration and usage 
---


## Keymappings
{: .-two-column}


### finding keymappings

to get the source of a keymapping use
```:verbose map `<key>` ```

### code navigation key bindings

{: .-prime}

#### language server

| Shortcut | Description                     |
| -------- | ------------------------------- |
| `gd`  | go to definition of symbol         |
| `gD`  | go to declaration of symbol        |
| `K`   | display information about the symbol under the cursor in a floating window |
| `gr`    | show all references of symbol under the cursor |
{: .-shortcuts}

#### nvim-telescope

| Shortcut | Description                     |
| -------- | ------------------------------- |
| `<leader>f`  | find in files         |
{: .-shortcuts}

### nvim-comments

#### normal mode

| Shortcut | Description                     | 
| -------- | ------------------------------- |
| `gcc` | toggles the current line using linewise comment |
| `gbc` | toggles the current line using blockwise comment |
| [count]`gcc` | toggles the number of line given as a prefix-count using linewise |
| [count]`gbc` | toggles the number of line given as a prefix-count using blockwise |
| `gc`[count]{motion} | (op-pending) toggles the region using linewise comment |
| `gb`[count]{motion} | (op-pending) toggles the region using linewise comment |
{: .-shortcuts}

#### visual mode

| Shortcut | Description                     | 
| -------- | ------------------------------- |
| `gc` | toggles the current line using linewise comment |
| `gb` | toggles the current line using blockwise comment |
{: .-shortcuts}

### nvim-tree

#### with NvimTree open

| Shortcut | Description                     | 
| -------- | ------------------------------- |
| `a` | add file or directory (trailing / in name) at selected location. |
| `r` | rename file at selected location |
| `d` | remove file at selected location |
| `o`, `<CR>` | open file or directory |
| `v` | open file in vertical split | 
{: .-shortcuts}


#### open / close NvimTree

| Shortcut | Description                     |
| -------- | ------------------------------- |
| `<leader>e`  | toggle file explorer to the left (width 30)  |
{: .-shortcuts}

{: .-three-column}

### window / buffer navigation

{: .-prime}

#### window

| Shortcut | Description                     |
| -------- | ------------------------------- |
| `<C-h>`  | go to split window to the left  |
| `<C-j>`  | go to split window below        |
| `<C-k>`  | go to split window above        |
| `<C-l>`  | go to split window to the right |
{: .-shortcuts}

#### buffer

| `<S-l>`  | go to next buffer 							 |
| `<S-h>`  | go to previous buffer					 |
{: .-shortcuts}

#### tabs
| :newtab | open new tab ("collection of windows") 

{: .-one-column}

* [Xpath test bed](http://www.whitebeam.org/library/guide/TechNotes/xpathtestbed.rhtm) _(whitebeam.org)_
