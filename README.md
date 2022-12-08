# Preparation

- [asdf-python](https://github.com/asdf-community/asdf-python)
- [asdf-poetry](https://github.com/asdf-community/asdf-poetry)
- [asdf-R](https://github.com/asdf-community/asdf-R)
- [asdf-julia](https://github.com/rkyleg/asdf-julia)
- [IRkernel](https://github.com/IRkernel/IRkernel)
  - Install and register IRkernel in R console after entering virtual env using `poetry shell`.
- [IJulia](https://github.com/JuliaLang/IJulia.jl)

# Run jupyter

Firstly, install the required packages.

```zsh
poetry install
```

For starting jupyter lab/notebook, execute the following command.

```zsh
$ poetry run jupyter lab
or
$ poetry run jupyter notebook
```

# Reference

- [Jupyter Notebook Kernels: How to Add, Change, Remove](https://queirozf.com/entries/jupyter-kernels-how-to-add-change-remove)
  - In this project, these kernel operation run through `poetry run`.
  - If jupyter sets not existing kernel, you have to remove the old kernel setting and redo IRkernel installation and registration.
