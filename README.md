# IMBD Data Analytics with Python
## Guia de Análise Exploratória de Dados com Python e Linguagem SQL

Neste Mini-Projeto vamos apresentar um guia básico de análise exploratória de dados usando Linguagem Python, Linguagem SQL e Banco de Dados SQLite. Usaremos dados reais disponíveis publicamente, dados sobre filmes no IMDB.

Ao aplicar Análise Exploratória de Dados vamos responder a estas 10 perguntas:

1. Quais São as Categorias de Filmes Mais Comuns no IMDB?
2. Qual o Número de Títulos Por Gênero?
3. Qual a Mediana de Avaliação dos Filmes Por Gênero?
4. Qual a Mediana de Avaliação dos Filmes Em Relação ao Ano de Estréia?
5. Qual o Número de Filmes Avaliados Por Gênero Em Relação ao Ano de Estréia?
6. Qual o Filme Com Maior Tempo de Duração? Calcule os Percentis.
7. Qual a Relação Entre Duração e Gênero?
8. Qual o Número de Filmes Produzidos Por País?
9. Quais São os Top 10 Melhores Filmes?
10. Quais São os Top 10 Piores Filmes?

## Pré-Requisitos

- python 3.9 ou superior

## Instalando Gerenciador de Pacotes - Poetry (linux)

```sh
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

## Inicializando e Instalando Dependências do Projeto

Na pasta raiz do projeto execute:
```sh
# inicializando pasta de depêndencias
poetry shell

# instalando dependências do projeto
poetry install
```

## Inicializando Editor Jupyter Notebook
Na pasta raiz do projeto execute:
```sh
jupyter notebook
```