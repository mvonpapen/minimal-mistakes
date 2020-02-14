# my homepage

Made with [Minimal Mistakes Jekyll theme](https://mmistakes.github.io/minimal-mistakes/)

1. fork full [Minimal Mistakes theme](https://github.com/mmistakes/minimal-mistakes)
2. delete docs and test
3. use Gemfile with
```
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem 'jekyll-include-cache'
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
```
4. edit `_sass/_reset.scss` to have smaller font
5. edit `data/navigation.yml` to define the header menu
6. delete `index.html` and instead create `_pages/home.md` with the following yml header
```
---
layout: home
author_profile: true
permalink: /
title: About
---
```

