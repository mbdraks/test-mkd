# test-mkd


## Create site
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .

## Test locally
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build

## Configure deploy with GH Actions
Check ci.yml file

## Enable GH Pages on the repo
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site