# Ponysay docker container

This is just a Dockerfile to generate an alpine container which have 'ponysay' installed inside.

I' allways find hard to keep ponysay running in my computer due the existence of multiple python versions installed, and ponysay is one of the favorite programs of my daughter, so the better solution was containerize it and aliase it in bash

## Usage

```
docker run theist/ponysay ponysay "clever quote"
```
