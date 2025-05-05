------

# 🧠 Aula 07 – Criação das Tabelas no Banco (DDL)

📅 **Data:** 2025-06-16
 ⏱️ **Duração:** 40 minutos
 👨‍🏫 **Professor:** André Ricardo
 👨‍🎓 **Turma:** 3º Ano do Ensino Médio Técnico em Informática

------

## 🎯 Objetivos da Aula

- Compreender o que é DDL (Data Definition Language)
- Criar as tabelas do sistema com base na modelagem física
- Executar os comandos SQL no SGBD (MySQL)
- Preparar o banco para inserção de dados reais

------

## 🧩 Conteúdos Abordados

### 🗃️ Linguagem DDL

- DDL = Data Definition Language (Linguagem de Definição de Dados)
- Comandos principais:
  - `CREATE TABLE`
  - `ALTER TABLE`
  - `DROP TABLE`
  - `SHOW TABLES`

### 🔧 Componentes de uma Tabela

- Nome da tabela (`tb_usuarios`)
- Colunas com tipo e restrições (PK, NOT NULL, AUTO_INCREMENT)
- Chaves primárias e estrangeiras (PK / FK)
- Relacionamentos entre tabelas

------

## 📝 Atividade Prática

Cada grupo deverá:

1. Utilizar o script gerado na aula anterior (ou escrevê-lo manualmente)
2. Criar as tabelas no MySQL localmente (Workbench ou terminal)
3. Testar os comandos com `SHOW TABLES` e `DESCRIBE nome_tabela`
4. Corrigir erros de sintaxe com apoio do professor
5. Comentar o código SQL (boas práticas)

------

## 💡 Exemplo Básico

```sql
CREATE TABLE tb_usuarios (
  id_usuario INT AUTO_INCREMENT PRIMARY KEY,
  nome VARCHAR(100) NOT NULL,
  email VARCHAR(100) UNIQUE,
  senha VARCHAR(255) NOT NULL
);
```

------

## 📂 Organização no Repositório

- Salvar o script principal em:
   `database/schema.sql`
- Scripts auxiliares ou em desenvolvimento:
   `database/scripts/`

------

## 📎 Referências

- [Manual de Referência MySQL 8.0 – DDL](https://dev.mysql.com/doc/refman/8.0/en/sql-syntax-data-definition.html)
- [W3Schools SQL Create Table](https://www.w3schools.com/sql/sql_create_table.asp)

------

## ✅ Checklist de Entrega

-  Script `CREATE TABLE` funcional
-  Testes realizados via terminal ou Workbench
-  Estrutura coerente com o modelo físico
-  Script salvo e versionado no GitHub

------

### 🔗 Paginação

#### ⏪ Voltar: Aula 06 – Modelagem Física do Banco

#### 🏠 Início

#### ⏩ Próxima: Aula 08 – Inserção de Dados e Consultas Simples

------