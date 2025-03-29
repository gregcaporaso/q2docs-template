# {{book_title}} source

[![Copier](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/copier-org/copier/master/img/badge/badge-grayscale-inverted-border-orange.json)](https://github.com/copier-org/copier)

```
cd {{ module_name }}
conda env create -n {{ book_id }} --file environment-files/readthedocs.yml
make fast-preview
```
