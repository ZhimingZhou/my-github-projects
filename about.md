---
title: About
layout: page
---

## Why

This website is a showcase of my own repos and the topics they fit into. For my own ease of using in searching and comparing my projects and for sharing them with others beyond the limitations of the standard view of repos on a profile on Github.


## Where

- Github repo: [{{ site.github.owner_name }}/{{ site.github.project_title }}]({{ site.github.owner_url }}/{{ site.github.project_title }})

## What

This project a static website hosted on [Netlify](netlify.com) for free and uses the following tools:

- [![Made with Jekyll](https://img.shields.io/badge/Made%20with-Jekyll-blue.svg)](https://jekyllrb.com)
- [![Jekyll theme](https://img.shields.io/badge/Theme-jekyll%2D-bulma-blue.svg)](https://github.com/jekyll-octopod/jekyll-bulma)
- [![Made with Ruby](https://img.shields.io/badge/Made%20with-Ruby-blue.svg)](https://www.ruby-lang.org)
- [![Made with Github GQL](https://img.shields.io/badge/Made%20with-Github%20GraphQL-blue.svg)](https://developer.github.com/v4/)

## How

On build, a request is done to Github GraphQL API to get repos and their topic labels. For the All Topics page, the structure is inverted such that topics contain repos.

You can fork and reuse this project to make a site showing your own Github repos. Follow the repo's [README](https://github.com/MichaelCurrin/my-github-projects/blob/master/README.md).

## Background

The idea was inspired a quickstart dev portfolio which Github supplies:

- Original repo: [github/personal-website](https://github.com/github/personal-website)
- My site using a fork: [michaelcurrin.github.io/](https://michaelcurrin.github.io/)
