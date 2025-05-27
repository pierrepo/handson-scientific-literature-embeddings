# Setup an environment


## Install uv

`uv` is a (relatively new) tool to manage Python environments and dependencies. It is similar to `pipenv` or `poetry`, but with a focus on simplicity and speed.

Install `uv` on your user account (on Linux / macOS):

```bash
$ wget -qO- https://astral.sh/uv/install.sh | sh
```

For alternative installation methods, see the [uv documentation](https://docs.astral.sh/uv/getting-started/installation/#installation-methods).

If `uv` is properly installed, you should be able to run the following command to check `uv`'s version:

```bash
$ uv self version
uv 0.7.8
```

## Clone the repository

```bash
$ git clone https://github.com/pierrepo/handson-scientific-literature-embeddings
$ cd handson-scientific-literature-embeddings
```

Create a Python virtual environment and install dependencies:

```bash
$ uv sync
```

Run Jupyter Lab:

```bash
$ uv run jupyter lab
```

The first part of this hands-on session does not require any code. The goal is to familiarize yourself with important concepts like tokens and embeddings.
The second part will require you to run some code to explore scientific literature using embeddings. You will use the Jupyter Lab interface to run Python code and interact with the data.
