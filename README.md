## Projeto: Análise de Dados com Pandas e Integração com SQL

 - Este projeto apresenta conceitos fundamentais da biblioteca Pandas, manipulação de arquivos .csv e .json, além da integração com banco de dados SQLite utilizando SQLAlchemy. É ideal para iniciantes que desejam aprender análise de dados com Python em um fluxo real de trabalho.

## Visão Geral

- Você aprenderá a:

- Ler e transformar dados com Pandas

- Explorar e criar arquivos JSON

- Criar e analisar vendas em CSV

- Inserir dados em banco de dados SQLite com SQLAlchemy

- Criar Gráficos e planilhas;

- Criar visualizações e análises úteis

## Estrutura do Projeto

```
PythonTeoria_BibliotecaPandas-main/
│
├── dados/
│   ├── dados.csv                # Base de dados com vendas (produto, categoria, preço etc.)
│   └── receitas.json            # Arquivo JSON com receitas e ingredientes
│
├── ecommerce.db                 # Banco SQLite gerado via SQLAlchemy
│
├── imagens/
│   └── (GIFs ou prints utilizados nos notebooks)
│
├── notebooks/
│   ├── analise_receitas.ipynb   # Análise dos dados do arquivo receitas.json
│   └── vendas_sqlite.ipynb      # Leitura de dados de vendas e inserção no banco de dados
│
├── README.md                    # Este arquivo
└── requirements.txt             # Dependências do projeto
```

## Pré-Requisitos

- Python 3.10+
- Pip instalado
- Ambiente virtual (recomendado)

## Instalação

```bash
git clone https://github.com/seu-usuario/PythonTeoria_BibliotecaPandas.git
cd PythonTeoria_BibliotecaPandas
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
```

## Funcionalidades

### 1. Análise de Receitas

No notebook `analise_receitas.ipynb`, você irá:

- Carregar receitas de um JSON
- Calcular o número total de ingredientes por receita
- Gerar um DataFrame organizado para análise

### 2. Importação e Armazenamento de Vendas

No notebook `vendas_sqlite.ipynb`, você aprenderá a:

- Ler um arquivo CSV contendo dados de vendas
- Criar conexão com SQLite usando SQLAlchemy
- Inserir os dados em uma tabela do banco de dados

## Bibliotecas Utilizadas

- pandas
- sqlalchemy
- sqlite3 (via SQLAlchemy)
- jupyter (para notebooks)

## Execução

Abra os notebooks com:

```bash
jupyter notebook
```

Execute cada célula sequencialmente para acompanhar os exemplos e análises.
