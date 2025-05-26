# Setup environment


## Install uv

Uv a (relatively new) tool to manage Python environments and dependencies. It is similar to `pipenv` or `poetry`, but with a focus on simplicity and speed.

Install `uv` on your user account (on Linux / macOS):

```bash
$ wget -qO- https://astral.sh/uv/install.sh | sh
```

For alternative installation methods, see the [uv documentation](https://docs.astral.sh/uv/getting-started/installation/#installation-methods).


## Clone the repository

```bash
$ git clone https://github.com/pierrepo/handson-scientific-literature-embeddings
$ cd handson-scientific-literature-embeddings
```

Sync environment and install dependencies:

```bash
$ uv sync --dev
```

Run Jupyter Lab:

```bash
$ uv run jupyter lab
```

Then create a new notebook and follow the instructions provided in the next sections of the practical.

