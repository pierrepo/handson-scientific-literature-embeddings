# Setup environment


## Install uv

`uv` a (relatively new) tool to manage Python environments and dependencies. It is similar to `pipenv` or `poetry`, but with a focus on simplicity and speed.

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
$ uv sync
```

Run Jupyter Lab:

```bash
$ uv run jupyter lab
```

The first part of this hands-on session does not require any code. The goal is to familiarize yourself with import concepts like tokens and embeddings.
The second part will require you to run some code to explore the scientific literature using embeddings. You will use the Jupyter Lab interface to run Python code and interact with the data.

