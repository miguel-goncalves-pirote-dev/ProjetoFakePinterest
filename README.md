# ProjetoFakePinterest
Clone do Pinterest desenvolvido em Flask e Python como parte de estudos de backend e web development.

## Tecnologias usadas
- **Python 3.12.8** (ou superior)
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
```bash
git clone https://github.com/miguel-goncalves-pirote-dev/ProjetoFakePinterest
```

### 2. Crie o ambiente virtual
```bash
python -m venv .venv
```
**OU**
```bash
py -3.12 -m venv .venv  # para evitar conflitos
```

### 3 Ative o ambiente virtual
```bash
.venv\Scripts\activate  # Ativa ambiente no Windows
```
```bash
source .venv/bin/activate  # Ativa ambiente em Linux/Mac
```

### 3 Instale as dependências
```bash
pip install -r requirements.txt
```

### 4 Execute o arquivo main.py
```bash
python main.py
```

### 5 Acesse pelo navegador
```bash
http://127.0.0.1:5000
```
