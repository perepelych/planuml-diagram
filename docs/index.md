# index

# mkdocs-adding
1. Установка .py
2. Добавление через терминал пакета mkdocs
pip install mkdocs-material

## Work with documents
For documentation, we use [Materal for MkDocs](https://github.com/squidfunk/mkdocs-material), built on top of [MkDocs](https://www.mkdocs.org/)
```
# Preparation. Installation in a virtual environment is recommended
pip install mkdocs-material
# View
mkdocs serve
# Update
mkdocs build
cd site
mkdocs gh-deploy --config-file ../mkdocs.yml --remote-branch docs
```