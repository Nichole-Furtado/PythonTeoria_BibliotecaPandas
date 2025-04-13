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
