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

PANDAS/
│
├── dados/                             # Conjunto de arquivos utilizados para as análises
│   ├── classificacao_campeonato.xlsx  # Planilha Excel com dados de campeonato
│   ├── dados.csv                      # Base de dados com informações de vendas
│   ├── receitas.json                  # Arquivo JSON com receitas e seus ingredientes
│   └── vendas_categoria.csv           # CSV com categorias de produtos e vendas
│
├── ecommerce.db                       # Banco de dados SQLite gerado via SQLAlchemy
│
├── 1.series.ipynb                     # Introdução a Series com Pandas
├── 2.dataframe.ipynb                  # Criação e manipulação de DataFrames
├── 3.analise.ipynb                    # Análises iniciais de dados
├── 4.operacoes_df.ipynb               # Operações e transformações com DataFrames
├── 5.importa_csv.ipynb                # Importação e leitura de arquivos CSV
├── 6.analise_csv.ipynb                # Análise de dados importados de CSV
├── 7.criarplanilha.ipynb              # Criação e exportação de planilhas Excel
├── 8.analise_planilha.ipynb           # Leitura e análise de arquivos Excel
├── 9.cria_json.ipynb                  # Criação de arquivos JSON com Pandas
├── 10.importa_json.ipynb              # Importação e leitura de arquivos JSON
├── 11.analisa_json.ipynb              # Análise dos dados importados de JSON
├── 12.bd.ipynb                        # Integração com banco de dados SQLite
│
└── README.md                          # Documentação do projeto
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
