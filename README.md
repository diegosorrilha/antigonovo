# antigonovo
Exemplo de webiste em Django

[![Build Status](https://travis-ci.org/diegosorrilha/antigonovo.svg?branch=master)](https://travis-ci.org/diegosorrilha/antigonovo)
[![Updates](https://pyup.io/repos/github/diegosorrilha/antigonovo/shield.svg)](https://pyup.io/repos/github/diegosorrilha/antigonovo/)
[![Python 3](https://pyup.io/repos/github/diegosorrilha/antigonovo/python-3-shield.svg)](https://pyup.io/repos/github/diegosorrilha/antigonovo/)
[![codecov](https://codecov.io/gh/diegosorrilha/antigonovo/branch/master/graph/badge.svg)](https://codecov.io/gh/diegosorrilha/antigonovo)


Para instalar ambiente de desenvolvimento:

Instale o python 3

Cria um virtualenv na raiz do projeto:

```
python3 -m venv .venv
```

Ative o virtualenv e instale as dependências de desenvolvimento:

```
source .venv/bin/activate
pip install requirements-dev.txt
```

Confira se o código está de acordo com a PEP8:

```
flake8 .
```