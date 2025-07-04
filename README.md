# Guide to Advanced LLM Techniques

Este repositório contém notebooks demonstrando técnicas avançadas com LLMs. A
página estática é gerada com [MkDocs](https://www.mkdocs.org/) e utiliza o
plugin `mkdocs-jupyter` para renderizar os arquivos `.ipynb` diretamente.

## Ambiente

Use [Poetry](https://python-poetry.org/) para gerenciar as dependências.
Instale-as com:

```bash
poetry install
```

Para rodar um servidor local com os notebooks:

```bash
poetry run mkdocs serve
```

Sempre que um novo notebook é adicionado ao diretório `docs/`, ele passa a
fazer parte da navegação definida em `mkdocs.yml`.
