# Icebreaker One Technical Docs

Icebreaker One technical specifications. This repository contains the sources for a [mkdocs-material](https://squidfunk.github.io/mkdocs-material/)
build of the technical specifications, including operational guidelines, for the Icebreaker One Trust Framework.

## Viewing the docs

Once released, this documentation will be hosted at https://docs.icebreakerone.org

## Installation

Building the documentation requires [Python 3](https://www.python.org/) or later.

### Install Python dependencies using pipenv

You will need to have [pipenv installed](https://pipenv.pypa.io/en/latest/installation.html)

```bash
pipenv install
```

## Local editing and testing

### Activate the pipenv shell (only required once)

```bash
pipenv shell
```

### Preview changes locally

```bash
mkdocs serve
```

### Publish changes to github pages

```bash
mkdocs gh-deploy
```
