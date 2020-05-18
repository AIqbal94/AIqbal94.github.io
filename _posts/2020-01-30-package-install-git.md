---
layout: post
title: "Installing python packages from Git"
date: 2020-01-30
published: true
---

To install an updated version of a python package from Git (using python3);

```bash
pip3 install git+https link to the git repository --user
```

For example;

```bash
pip3 install git+https://github.com/mpg-age-bioinformatics/AGEpy.git --user
```
