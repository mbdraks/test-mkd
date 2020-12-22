# test-mkd

docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build
