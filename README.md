# Classificadores k-NN + LVQ - Aprendizagem de Máquina

O Objetivo do projeto é a realização de experimentos utilizando o k-NN normal junto com os algoritmos LVQ1, LVQ2.1 e LVQ3 na fase de pré-processamento dos dados. As duas bases de dados foram retiradas do repositório [Promise](http://promise.site.uottawa.ca/SERepository/datasets-page.html).

### Requisitos

- pip
- virtualenv
- pacotes texlive
  - sudo apt install texlive texlive-latex-extra texlive-fonts-recommended dvipng cm-super


### Passos

Caso não possua o ambiente virtual:

```
virtualenv -p /usr/bin/python3 <virtual_env>
```

Ativação:

```
source <virtual_env>/bin/activate
```

Instalação dos pacotes:

```
pip install -r requirements.txt
```

Execução:

```
python src/main.py
```