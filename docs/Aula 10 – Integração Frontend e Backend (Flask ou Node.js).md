------

# 🧠 Aula 10 – Integração Frontend e Backend (Flask ou Node.js)

📅 **Data:** 2025-08-04
 ⏱️ **Duração:** 40 minutos
 👨‍🏫 **Professor:** André Ricardo
 👨‍🎓 **Turma:** 3º Ano do Ensino Médio Técnico em Informática

------

## 🎯 Objetivos da Aula

- Introduzir o conceito de integração entre frontend e backend
- Criar os primeiros endpoints de API para troca de dados
- Estabelecer a comunicação via requisições HTTP (GET e POST)

------

## 🧩 Conteúdos Abordados

### 🔁 Comunicação Frontend ↔ Backend

- O que é uma API?
- JSON como formato de troca de dados
- Métodos HTTP: `GET`, `POST`

### 🛠️ Ferramentas

- **Flask** (Python) ou **Express** (Node.js)
- Testes com Insomnia ou Postman

### 🌐 Requisição no Frontend

```javascript
fetch('http://localhost:5000/api/usuarios')
  .then(response => response.json())
  .then(data => console.log(data))
```

------

## 📝 Atividade Prática

1. Criar um backend básico com Flask ou Express
2. Criar um endpoint `GET /api/usuarios` que retorne dados simulados
3. Criar um formulário simples no frontend que envie dados via `POST`
4. Fazer a conexão utilizando `fetch` ou `axios`
5. Testar o fluxo completo: tela → API → retorno

------

## 📂 Organização no Repositório

```plaintext
src/
├── backend/
│   ├── app.py (Flask) ou index.js (Node)
│   └── routes/
│       └── usuarios.js (ou .py)
├── frontend/
│   ├── login.html
│   ├── dashboard.html
│   └── js/
│       └── api.js
```

------

## ✅ Checklist de Entrega

-  Backend inicial rodando localmente
-  Endpoint GET funcional testado no navegador ou Insomnia
-  Formulário no HTML se comunica com a API
-  Dados JSON exibidos no console ou tela
-  Estrutura organizada no repositório

------

## 📎 Referências

- [Documentação Flask](https://flask.palletsprojects.com/)
- [Documentação Express](https://expressjs.com/pt-br/)
- [JavaScript Fetch API](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API)
- [Guia de Requisições REST](https://restfulapi.net/)

------

### 🔗 Paginação

#### ⏪ Voltar: Aula 09 – Estrutura Inicial do Frontend

#### 🏠 Início

#### ⏩ Próxima: Aula 11 – Conexão Backend com Banco de Dados

------