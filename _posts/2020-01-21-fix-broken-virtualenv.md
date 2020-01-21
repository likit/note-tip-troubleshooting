---
layout: post
title: Fix A Broken Virtualenv
---

This problem arises when the Python is updated.
[The source of this recipe on stackoverflow is here](https://stackoverflow.com/questions/23233252/broken-references-in-virtualenvs)


## First removed symlinks

`find ~/.virtualenvs/my-virtual-env/ -type l -delete`

## Then, rebuild the virtualenv

`cd ~/.virtualenv/my-virtual-env/`

`virtualenv .`

Done.
