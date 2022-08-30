Live at: https://techbrunch.github.io/patt-mkdocs/

## Run locally:

```
docker pull squidfunk/mkdocs-material
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
```