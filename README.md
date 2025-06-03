# Atos Capital API

API REST construída com Flask para gerenciamento de usuários, autenticação JWT, e mais.

---

## Tecnologias usadas

- Python 3.11+
- Flask
- Flask-JWT-Extended (Autenticação JWT)
- Flask-CORS (Cross-Origin Resource Sharing)
- Flask-SQLAlchemy (ORM para banco de dados)
- Flask-Marshmallow (Serialização)
- SQLite (banco de dados padrão, pode ser configurado outro)
- Outros: logging, datetime

---

## Estrutura do projeto

- `app.py` - criação e configuração da aplicação Flask
- `routes/auth.py` - rotas de autenticação e usuários
- `models/user.py` - modelo User com hashing de senha
- `extensions.py` - inicialização de extensões Flask (db, jwt, ma)
- `config.py` - configurações da aplicação (ex: secret key, database URI)
- `utils/security.py` - funções auxiliares para segurança, como validação de senha

---

## Configuração inicial

### 1. Clone o repositório

bash
git clone https://github.com/DevFelipeM/atos-capital-api-front.git
cd atos-capital-api-front


## Rodando o Projeto
python -m venv venv
# Windows
venv\Scripts\activate
ou 
rodando direto o app.py e o html com live server pra desenvolvimento

pip install flask flask-jwt-extended flask-cors flask-sqlalchemy flask-marshmallow marshmallow-sqlalchemy
