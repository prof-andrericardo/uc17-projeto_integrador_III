------

# 🧠 Aula 11 – Conexão Backend com Banco de Dados

📅 **Data:** 2025-08-11
 ⏱️ **Duração:** 40 minutos
 👨‍🏫 **Professor:** André Ricardo
 👨‍🎓 **Turma:** 3º Ano do Ensino Médio Técnico em Informática

------

## 🎯 Objetivos da Aula

- Conectar o backend (Flask ou Node.js) ao banco de dados MySQL
- Executar consultas SQL diretamente da API
- Retornar e manipular dados reais no frontend

------

## 🧩 Conteúdos Abordados

### 🔗 Bibliotecas e Ferramentas

- **Python/Flask:** `mysql-connector-python` ou `SQLAlchemy`
- **Node.js:** `mysql2` + `dotenv`
- Variáveis de ambiente para proteger senhas e conexões

### 📚 Exemplos

#### 🔸 Flask (Python)

```python
import mysql.connector
conn = mysql.connector.connect(
  host="localhost",
  user="root",
  password="senha",
  database="sistema_escolar"
)
```

#### 🔹 Node.js

```js
const mysql = require('mysql2')
const conn = mysql.createConnection({
  host: 'localhost',
  user: 'root',
  password: 'senha',
  database: 'sistema_escolar'
})
```

------

## 📝 Atividade Prática

1. Criar uma conexão segura com o banco de dados
2. Implementar um endpoint que execute um `SELECT *` na tabela de usuários
3. Retornar os dados em formato JSON para o frontend
4. Exibir os dados em tabela simples (HTML)

------

## 📂 Organização no Repositório

```plaintext
src/
├── backend/
│   ├── db/
│   │   └── conexao.py / conexao.js
│   └── routes/
│       └── usuarios.py / usuarios.js
├── frontend/
│   └── dashboard.html
```

------

## ✅ Checklist de Entrega

-  Conexão com banco de dados MySQL testada
-  Endpoint GET retorna dados reais da tabela
-  Frontend consome os dados e renderiza na tela
-  Uso correto de variáveis `.env` para proteção de credenciais

------

## 📎 Referências

- [MySQL Connector para Python](https://dev.mysql.com/doc/connector-python/en/)
- [mysql2 para Node.js](https://www.npmjs.com/package/mysql2)
- [Como usar variáveis de ambiente com dotenv](https://www.npmjs.com/package/dotenv)
- [Flask e SQLAlchemy](https://flask.palletsprojects.com/en/2.3.x/patterns/sqlalchemy/)

------

### 🔗 Paginação

#### ⏪ Voltar: Aula 10 – Integração Frontend e Backend

#### 🏠 Início

#### ⏩ Próxima: Aula 12 – Apresentação Parcial do Projeto

------