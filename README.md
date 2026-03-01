# 🌌 Star Wars Datapipe - Desafio Globo

Este projeto consiste em um pipeline de **ETL (Extract, Transform, Load)** que consome dados da [SWAPI](https://swapi.dev/) (Star Wars API), realiza a normalização e persiste as informações em um banco SQLite para análises analíticas.

---
## 🛠️ Ferramentas e Bibliotecas
- **Python 3.x** -> Linguagem base do projeto.
- **Pandas** -> Manipulação, limpeza e transformação de DataFrames.
- **Requests** -> Consumo da API REST (Extração).
- **SQLite / SQLAlchemy** -> Persistência de dados e execução de consultas relacionais.
- **Jupyter Notebook** -> Ambiente para desenvolvimento, testes e documentação do processo.
---

## 👷 Como rodar
# 1. Clonar o repositório
```bash
git clone https://github.com/huguds/globo-data-engineering-challenge.git
```

# 2. Entrar na pasta do projeto
```bash
cd globo-data-engineering-challenge
```

# 3. Instalar as dependências necessárias
```bash
pip install pandas requests sqlalchemy
```

# 4. Executar o Pipeline
- Abra o notebook 'swapi_etl_pipeline.ipynb' em sua IDE (VS Code, Jupyter, etc.) 
- Execute todas as células para gerar o banco de dados.
