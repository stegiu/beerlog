# Beerlog

From Python Week 2022 - Linux Tips

## Instruções

## Preparando o ambiente

## Requisitos

Este template utiliza o gerenciador de pacotes **poetry**

`execute o comando abaixo para instalar o Poetry no Linux`

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

## Instalando o ambiente

O comando a seguir instala as dependências do projeto.

```bash
poetry install
```

O comando a seguir ativa o ambiente virtual do poetry

```bash
poetry shell
```

Executando o programa

```bash
beerlog
# ou
python -m beerlog
```

### Poetry

```
pip install poetry
poetry install
poetry shell
```

Ou execute `source start_poetry` que é um script que automatiza os comandos acima.

### Autocomplete não funciona?

Após ativar o poetry digite no terminal

```
which python 
```
A saida será algo como

```
/home/gitpod/.cache/pypoetry/virtualenvs/beerlog-DlEBh_72-py3.8/bin/python
```

Copie este path ^

Agora digite `F1` no gitpod ou `Ctrl + Shift + P` no Vscode local e selectione a opção `Python: Select Interpreter`
Cole o path `/home/gitpod/.cache/pypoetry/virtualenvs/beerlog-DlEBh_72-py3.8/bin/python` e digite enter.

> **OBS**: Pode ser que o caminho seja outro, o importante é terminar com `/bin/python`