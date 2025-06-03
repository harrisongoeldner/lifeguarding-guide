# lifeguarding-guide
Harrison's Guide to Lifeguarding

These are a collection of documents intended for education purposes. If you are interested in contributing, feel free to make a PR. 

## Contributing

How to actual run and test the documents. The easiest way is to use poetry but honestly you can also use pip.

1. Install [`poetry`](https://python-poetry.org/) and [`pyenv`](https://github.com/pyenv/pyenv) (recommended).
2. Fork and clone the repo to your device.
3. In the repo folder type:
```
poetry install
```
4. This will install all the required dependancies. Activate the poetry enviroment for your shell environment by running
```
eval $(poetry env activate)
```
Alternatively you can setup poetry shell and run `poetry shell`.

5. Build the documentation:
```
mkdocs serve --config-file src/mkdocs.yml
```
Make the intended edits and then merge back to `main` as a PR. 

## Hosting Provider

Currently the site is hosted using Github Pages. However the long term plan is to move to Cloudflare Pages as it has better AI scrapping protections.
