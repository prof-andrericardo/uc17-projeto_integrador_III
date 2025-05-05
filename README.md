# 💻 Projeto Integrador III – UC17  
![GitHub repo size](https://img.shields.io/github/repo-size/prof-andrericardo/uc17-projeto_integrador_III)
![GitHub license](https://img.shields.io/github/license/prof-andrericardo/uc17-projeto_integrador_III)
![GitHub last commit](https://img.shields.io/github/last-commit/prof-andrericardo/uc17-projeto_integrador_III)
![GitHub issues](https://img.shields.io/github/issues/prof-andrericardo/uc17-projeto_integrador_III)
![GitHub forks](https://img.shields.io/github/forks/prof-andrericardo/uc17-projeto_integrador_III)
![GitHub stars](https://img.shields.io/github/stars/prof-andrericardo/uc17-projeto_integrador_III)

📘 Repositório oficial da disciplina **UC17 – Projeto Integrador III** do **3º Ano do Ensino Médio Técnico em Informática**, sob orientação do professor **André Ricardo**, no **Colégio Victorino**.

---

## 🎯 Objetivo Geral

Desenvolver um sistema completo aplicando os conhecimentos adquiridos ao longo do curso técnico, envolvendo: levantamento de requisitos, prototipação, modelagem de dados, codificação backend/frontend, versionamento com Git e apresentação técnica.

---

## 🧩 Tecnologias Utilizadas

| Finalidade         | Tecnologia                                                   |
| ------------------ | ------------------------------------------------------------ |
| Protótipo          | [Figma](https://figma.com)                                   |
| Banco de Dados     | [MySQL 8.0](https://www.mysql.com/)                          |
| Backend            | [Flask (Python)](https://flask.palletsprojects.com/) ou [Express (Node.js)](https://expressjs.com/) |
| Frontend           | HTML5 + CSS3 + JavaScript                                    |
| Controle de Versão | [Git e GitHub](https://github.com/)                          |
| Testes de API      | [Insomnia](https://insomnia.rest/)                           |

---

## 🗂️ Estrutura de Diretórios

```bash
uc17-projeto_integrador_III/
├── docs/                          # Documentação e materiais de aula
│   ├── aulas/                     # Aulas em formato Markdown
│   └── planejamento_2ºtrimestre.md
├── prototipos/                   # Protótipos e imagens do Figma
│   ├── figma-link.md
│   └── telas-png/
├── database/                     # Banco de dados e scripts
│   ├── schema.sql                # Script principal com tabelas
│   └── scripts/                  # DML, consultas e extras
├── src/
│   ├── backend/                  # Backend (Flask ou Node)
│   │   ├── app.py / index.js
│   │   ├── db/                   # Conexão com MySQL
│   │   └── routes/               # Rotas por entidade
│   └── frontend/                 # Interface do usuário
│       ├── login.html
│       ├── dashboard.html
│       └── css/
│           └── style.css
├── .gitignore
├── README.md
├── LICENSE
├── requirements.txt              # Dependências do Flask
└── package.json                  # Dependências do Node.js
```

------

## 📄 Documentação Detalhada

Todos os materiais da disciplina estão documentados em Markdown:

- 📌 Planejamento do 2º Trimestre
- 📚 Aulas completas em `docs/aulas/`
- 📷 Protótipos exportados em PNG em `prototipos/telas-png/`
- 📑 Link oficial do Figma em `prototipos/figma-link.md`
- 📂 Scripts SQL organizados por tipo (DDL, DML, DQL)

------

## ⚙️ Arquivos de Configuração

| Ferramenta | Arquivo            | Finalidade                       |
| ---------- | ------------------ | -------------------------------- |
| Git        | `.gitignore`       | Ignorar arquivos desnecessários  |
| Python     | `requirements.txt` | Instalação de dependências Flask |
| Node.js    | `package.json`     | Gerenciamento com npm            |
| DotEnv     | `.env.example`     | Modelo para variáveis sensíveis  |

> ⚠️ Recomenda-se **NUNCA versionar** o arquivo `.env`, apenas o modelo `.env.example`.

------

## 🚀 Como Executar

### 🐍 Flask (Python)

```bash
# Backend
cd src/backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

### ⚙️ Node.js

```bash
# Backend
cd src/backend
npm install
npm start
```

> 🔄 O frontend pode ser aberto diretamente no navegador via `login.html`.

------

## 🧪 Como Testar

- 🔎 Teste suas rotas com o [Insomnia](https://insomnia.rest/)
- 🧱 Verifique o banco de dados com o MySQL Workbench ou DBeaver
- 🌐 Acesse as telas no navegador e use `fetch` para integrar com a API

------

## 🏷️ Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais informações.

------

## 👨‍🏫 Contato

**Professor:** André Ricardo
 📧 [andrericardo@colegiovictorino.com.br](mailto:andrericardo@colegiovictorino.com.br)
 🏫 Colégio Victorino

------

## 📌 Referências

- [Markdown Guide](https://www.markdownguide.org/)
- [MySQL Docs](https://dev.mysql.com/doc/)
- [Node.js Docs](https://nodejs.org/)
- [Flask Docs](https://flask.palletsprojects.com/)
- [Figma Help](https://help.figma.com/)

------

### ✨ Sinta-se livre para contribuir com melhorias, pull requests e sugestões!

