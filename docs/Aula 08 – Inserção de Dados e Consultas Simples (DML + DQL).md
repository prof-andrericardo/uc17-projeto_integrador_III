------

# 🧠 Aula 08 – Inserção de Dados e Consultas Simples (DML + DQL)

📅 **Data:** 2025-06-23
 ⏱️ **Duração:** 40 minutos
 👨‍🏫 **Professor:** André Ricardo
 👨‍🎓 **Turma:** 3º Ano do Ensino Médio Técnico em Informática

------

## 🎯 Objetivos da Aula

- Inserir dados fictícios nas tabelas criadas com comandos DML
- Realizar consultas simples utilizando DQL (SELECT)
- Compreender a estrutura básica de filtros e ordenações em SQL

------

## 🧩 Conteúdos Abordados

### ✍️ Linguagem DML (Data Manipulation Language)

- `INSERT INTO nome_tabela (colunas) VALUES (valores);`
- `UPDATE nome_tabela SET coluna = valor WHERE condição;`
- `DELETE FROM nome_tabela WHERE condição;`

### 🔍 Linguagem DQL (Data Query Language)

- `SELECT * FROM nome_tabela;`
- `SELECT coluna1, coluna2 FROM nome_tabela WHERE condição;`
- `ORDER BY`, `LIMIT`, `LIKE`, `BETWEEN`

------

## 📝 Atividade Prática

1. Inserir pelo menos **5 registros** em duas ou mais tabelas do sistema
2. Utilizar o `SELECT` para validar os dados inseridos
3. Aplicar **filtros simples** e **ordenação crescente/decrescente**
4. Testar buscas com `LIKE` e intervalos com `BETWEEN`
5. Salvar os scripts no repositório

------

## 💡 Exemplos

```sql
INSERT INTO tb_usuarios (nome, email, senha) VALUES
('João Silva', 'joao@email.com', '123'),
('Maria Lima', 'maria@email.com', '456');

SELECT nome, email FROM tb_usuarios WHERE nome LIKE 'M%';
```

------

## 📂 Organização no Repositório

- Scripts de inserção e consulta:
   `database/scripts/dml_dql_insercao_consulta.sql`

------

## ✅ Checklist da Aula

-  Dados inseridos em pelo menos duas tabelas
-  Consultas testadas com SELECT + filtros
-  Script comentado salvo no repositório
-  Nomes, e-mails ou outros dados fictícios bem organizados

------

## 📎 Referências

- [Documentação SQL – W3Schools](https://www.w3schools.com/sql/)
- [MySQL 8.0 – INSERT e SELECT](https://dev.mysql.com/doc/refman/8.0/en/insert.html)
- [SQL Style Guide](https://www.sqlstyle.guide/)

------

### 🔗 Paginação

#### ⏪ Voltar: Aula 07 – Criação das Tabelas no Banco

#### 🏠 Início

#### ⏩ Próxima: Aula 09 – Estrutura Inicial do Frontend

------