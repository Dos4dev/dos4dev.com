# dos4dev.com

This repo contains the source code of the [dos4dev.com](https://dos4dev.com) website.
It is built using [Hugo](https://gohugo.io/) and hosted on [GitHub Pages](https://pages.github.com/).

## Editing

Launch a local Hugo server including live reload by running (append `-F` for including future posts):

```
hugo server -D --debug
```

## Deployment

Deployment to GitHub pages happens automatically upon pushing the master branch to the upstream repository by means of a GitHub Action.

In order to deploy to GitHub pages manually, commit all changes, then run:

```
./publish_to_ghpages.sh && git push upstream gh-pages
```
## Credits

The material was originally created by Gunnar Morling (https://github.com/gunnarmorling) and forked from https://github.com/gunnarmorling/morling.dev

