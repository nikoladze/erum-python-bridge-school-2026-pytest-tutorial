# pytest tutorial

Created for the [ErUM Python Bridge School 2026](https://indico.desy.de/category/1202).

To run the notebook you need to install (e.g. in a virtualenv) the packages from requirements.txt

With uv you can run jupyter in a temporary environment with necessary dependencies using

```bash
uv run --with-requirements requirements.txt jupyter lab
```

Or, when using VS Code you can set up a virtual environment in `.venv`

```bash
uv venv
uv pip install -r requirements.txt
code .
```
