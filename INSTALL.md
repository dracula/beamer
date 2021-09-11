### [Beamer](https://ctan.org/pkg/beamer?lang=en)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/beamer.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/beamer/archive/master.zip) option and unzip them.

#### Activating theme

1. Add the `beamercolorthemedracula.sty` file to your projects root directory 
2. Add `\usecolortheme{dracula}` to your preamble
3. If you are using beamer with R Markdown , add `colortheme: "dracula"` to YAML header
   
```yaml
---
title: "A Dracula Theme for Beamer Presentation"
subtitle: "Using R Markdown"
author: |
   | Your Name (Msc) 
   | example@gmail.com
institute: "Your instiution Name"
date: "1/16/2021"
output: 
  beamer_presentation:
    theme: "default"
    colortheme: "dracula"
---
```
