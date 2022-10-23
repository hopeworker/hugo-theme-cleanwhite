---
title:       "Setup your website using 'clean white' theme"
subtitle:    ""
description: ""
date:        2022-10-16
author:      ""
image:       ""
tags:        ["tag1", "tag2"]
categories:  ["Tech" ]
---

## doc
https://gohugo.io/getting-started/quick-start/
https://www.git-scm.com/book/en/v2/Git-Tools-Submodules
https://themes.gohugo.io/
https://themes.gohugo.io/themes/hugo-theme-cleanwhite/
https://themes.gohugo.io/themes/hugo-theme-cleanwhite/#comment-systems

## install
brew install hugo
hugo version
hugo new site myhugowebsite

## download theme
cd myhugowebsite
git init
cd themes
git clone https://github.com/hopeworker/hugo-theme-cleanwhite.git
cp -r hugo-theme-cleanwhite/exampleSite/** ../

## add content
hugo new post/my-first-post.md

## launch
hugo server -D

## build static pages
hugo -D


