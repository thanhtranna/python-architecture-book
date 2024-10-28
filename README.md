# python-architecture-book

## Building the containers

_(this is only required from chapter 3 onwards)_

```sh
make build
make up
# or
make all # builds, brings containers up, runs tests
```

## Creating a local virtualenv (optional)

```sh
python3.9 -m venv .venv && source .venv/bin/activate # or however you like to create virtualenvs

# for chapter 1
pip install pytest
```
