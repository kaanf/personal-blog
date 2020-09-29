---
layout: post
title: "Practice Jekyll & Ruby"
categories: Blog
tags:
- blog
status: publish
type: post
published: true
meta: {}
---

## Getting Started

My first personal GitHub Pages built on **Jekyll & Ruby** with the Minima theme and inspired by **Krause**. Thanks for the contribution.

### Important

For security reasons, Github does not allow plugins (under _plugins/) when deploying with Github Pages. This means: that you need to generate your site locally and push the resulting HTML `/jekyll` to a Github repository.

### Ruby & Jekyll Installation

- First, you need the Ruby package. Download Ruby Devkit 2.7.1. from the [download page.](https://rubyinstaller.org/downloads/) 

- After the setup, open the command prompt and run the `ridk install` as administrator.

- Open a new command prompt window, install the **Jekyll** and **Bundler**. `gem install jekyll bundler`

- Check if Jekyll installed. `jekyll -v`

### Repository Usage

- git clone `https://github.com/kaanf/personal-blog`

- `bundle install`

- `gem uninstall eventmachine`

- `gem install eventmachine --platform ruby`

- `bundle exec jekyll serve --livereload`

- Open port and enjoy.

### Deploy

- In VS Code, press `Ctrl+P` and `>Git Sync`

**If you have any questions, you can contact them via e-mail.**



