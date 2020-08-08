# Overview

## Documentation with Docker


`docker run --rm -it -v /${PWD}:/docs squidfunk/mkdocs-material new .`

`docker run --rm -it -p 13005:8000 -v /${PWD}:/docs squidfunk/mkdocs-material`