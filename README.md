# ProjetoFakePinterest
Clone do Pinterest desenvolvido em Flask e Python como parte de estudos de backend e web development.

## Tecnologias usadas
- Python 3.13
- Flask (framework principal)
- Flask-Login (Autenticação de usuários)
- Flask-SQLAlchemy (ORM para banco de dados)
- Flask-WTF + WTForms (formulários e validações)
- Flask-Bcrypt (criptografia de senhas)
- SQLite (banco de dados local)
- HTML, CSS (interface)

## Funcionalidades
- Criar perfil / Fazer login
- Adicionar imagens (post)
- Olhar o feed (Página de post de vários usuários)
- Achar usuário pelo post
- Fazer Logout

## Como rodar o projeto

### 1. Clone este repositório
git clone https://github.com/miguel-goncalves-pirote-dev/ProjetoFakePinterest

### 2. Crie e ative um ambiente virtual
python -m venv .venv (Cria o ambiente)
.venv\Scripts\activate (Ativa ambiente no Windows)
source .venv/bin/activate (Ativa ambiente em Linux/Mac)

### 3 Instale as dependências
pip install -r requirements.txt

### 4 Execute o arquivo main.py
python main.py

### 5 Acesse pelo navegador
http://127.0.0.1:5000
