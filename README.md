# 🏦 PyBankQuery

Sistema backend de consulta e gerenciamento de contas bancárias desenvolvido em Python. O projeto utiliza modelos estruturados para simular operações essenciais de consulta de saldo, extratos e gerenciamento de contas.

---

## 📌 Funcionalidades

* 🔍 **Consulta de contas e saldo**: Verificação de dados bancários de forma rápida e segura.
* 📜 **Extrato e histórico**: Mapeamento de movimentações financeiras.
* 💾 **Banco de dados relacional**: Persistência de dados leve e eficiente via SQLite (`database.db`).
* 🧩 **Arquitetura modular**: Separação clara entre camada de dados (`models.py`), regras de negócio e apresentações/templates (`templates.py`, `view.cpython-311.pyc`).

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem**: [Python 3.11+](https://www.python.org/)
* **Banco de dados**: SQLite
* **ORM / Manipulação de banco**: SQLAlchemy (ou biblioteca nativa `sqlite3`)

---

## 📂 Estrutura do Repositório

```text
.
├── database.db        # Banco de dados SQLite persistente
├── models.py          # Definição das entidades e tabelas (Conta, Cliente, Transações)
├── templates.py       # Padrões de formatação ou respostas/views
├── venv/              # Ambiente virtual Python
└── README.md          # Documentação do projeto
```

## 🚀 Execução do Projeto

Pró-requisitos
* **Python 3.11 ou superior instalado.**

Passo-a-passo:

*1. Clone o repositório*:

```bash
git clone [https://github.com/seu-usuario/PyBankQuery.git](https://github.com/seu-usuario/PyBankQuery.git)
cd PyBankQuery
```

*2.Crie e ative o ambiente virtual (**venv**)*:

* **Linux/macOS**:

```bash
python3 -m venv venv
source venv/bin/activate
```

* **Windows**:

```bash
python -m venv venv
venv\Scripts\activate
```

*3.Instale as dependências (se houver um arquivo **requirements.txt**)*:

```bash
pip install -r requirements.txt
```

*4.Execute a aplicação*:

```bash
python main.py
# ou execute o módulo de visualização/view correspondente
```

## 📝 Boas Práticas e Versionamento (.gitignore)

Recomenda-se não versionar a pasta venv/, arquivos compilados do Python (__pycache__, .pyc) e dados locais sensíveis do SQLite (database.db).

Certifique-se de adicionar um arquivo .gitignore com as seguintes linhas:

```bash
venv/
__pycache__/
*.pyc
*.db
```


