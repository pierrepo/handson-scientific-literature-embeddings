# Hands-on Session: Exploring physical sciences scientific literature using embeddings

Summer school: *Machine Learning in Physical Sciences: Theory and Applications*

Instructor: P. Poulain

[Practical](https://pierrepo.github.io/handson-scientific-literature-embeddings)
| [Source](https://github.com/pierrepo/handson-scientific-literature-embeddings) 


## Content compilation


Install [uv](https://pixi.sh/latest/).

Clone the repository:

```bash
$ git clone https://github.com/pierrepo/handson-scientific-literature-embeddings
$ cd handson-scientific-literature-embeddings
```

Sync environment and install dependencies:

```bash
$ uv sync --dev

```

Compile the content:

```bash
$ uv run jupyter-book build content
```

The HTML version of the practical is located in the `content/_build/html/index.html` directory.


## License

![](content/img/CC-BY-SA.png)

This content is licensed under a [Creative Commons Attribution - ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) license (CC BY-SA 4.0). Please read the [LICENSE](LICENSE) file for more détails.

