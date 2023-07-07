# DESAFIO

## INSTRUÇÕES:
* Os arquivos referentes às soluções estão nas pastas do repositório, cujo nome indica qual o exercício referente.
* As bases de dados não estão disponíveis nesse repositório, e devem ser carregadas dentro de uma pasta `/exercise_*/data/` (cada base no pasta respectiva ao exercício)
* Os fluxos das soluções estão completos em formato `.ipynb`, dentro das pastas `/exercise_*/notebooks/`
* Cada exercício contém seu próprio arquivo `requirements.txt` que deverá ser utilizado para criação do ambiente responsável pela execução dos notebooks.

## EXECUÇÃO:
Para execução de cada solução é aconselhado criar kernel-jupyter dentro de um ambiente virtual criado a partir do arquivo `requirements.txt` (disponível na pasta de cada exercício).
Para isso, é possível utilizar os comandos (ambiente interno à pasta da solução):
```sh
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python -m ipykernel install --user --name=KernelEx
```
obs: A solução foi desenvolvida utilizando python 3.10.0.
