# Pipeline ETL com Python

Projeto desenvolvido durante bootcamp de dados, aplicando extração de CSV, consumo de APIs e carga em banco de dados MySQL.

## Tecnologias
- Python 3.x
- Pandas
- Requests
- SQLAlchemy + pymysql
- Jupyter Notebook

## O que esse projeto faz
- **Extração**: leitura de arquivos CSV com parâmetros avançados do `pd.read_csv` e consumo de APIs REST
- **Transformação**: tratamento de valores nulos, criação e categorização de colunas, conversão de tipos, manipulação de datas com `datetime`
- **Carga**: escrita e leitura em banco de dados MySQL via SQLAlchemy

## Aprendizados principais
- Como estruturar um pipeline ETL completo do zero
- Boas práticas de tratamento e transformação de dados reais
- Integração Python com banco de dados relacional

## Como executar
```bash
pip install -r requirements.txt
jupyter notebook
``
