---
title: >-
  It takes too much time to configure the environment, so try to use good out-of-the-box tools
date: 2024-11-23 13:10:09
tags: [Essay, Development Environment, Tool]
categories: [Essay]
---

### Background

Since I wanted to update my local development environment, I tried to redeploy the my Neovim Script. I once wrote a Neovim configuration script purely in Lua language, which basically suits my uasage habit. It has some features such as syntax highlighting, fuzzy search of file and word, word auto-completion, code snippets, and on-click deployment.

Here is my Neovim Script Link: [JackNvim](https://github.com/zsdfbb/JackNvim). Friends in need may refer to it.

However, recently I found that the packer.nvim plugin manager used by JackNvim has stopped being maintained :cry:. If I continue to use Neovim, I need to migrate to other plugin managers, which is really troublesome! So I am considering using an out-of-the-box editor to replace Neovim in command line.

<!-- more -->

### New Tool

Currently, I use the VS Code as my main development editor. It can simply connect to my development server via remote-ssh plugin. Its configuration is very simple and intuitive. But for some simple file editing tasks, an elegant and out-of-the-box editor is also quite necessary.

After some research, I found the Helix Editor, a text editor similar to Vim. Its opeartion and usage method is very similar to Vim, which makes me comfortable with it. And it comes with  capabilities such as syntax highlighting, file search, and text search by itself, I don't need to install plugins. I think it is a good choice for me!

Here is the official comparison introduction. ![Comparison of Vim and Helix](1.png)

Currently, the Helix is still in the development, but it can alreay be used as my daily command line tool. :smile: 

[JackHelix](https://github.com/zsdfbb/JackHelix) is my configuration for Helix, and I will gradually improve it later.