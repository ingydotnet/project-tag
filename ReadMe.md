## Name

project-tag - Group your repos together nicely

## Synopsis

    cd ~/src/
    git clone git@github.com:ingydotnet/project-tag ++
    cd ++/<tag-name>/<repo-name>
    …hack hack hack…

## Description

If you are like me you have dozens of projects involving hundreds of repos.
Many repos serve several projects. How do you organize them well?

This idea came to me in a dream. Symlinks are man's best friend. Here's how I
use them:

I clone all my repos into `~/src/` including this one. I rename the dir `++` so
it displays at the top and stands out. This repo contains tag-names, and
anything related to that tag becomes a symlink in that dir. This allows you to
easily assign multiple tags toa repo.

So simple. So powerful. Enjoy.
