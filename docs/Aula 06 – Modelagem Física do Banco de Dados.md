------

# 🧠 Aula 06 – Modelagem Física do Banco de Dados

📅 **Data:** 2025-06-09
 ⏱️ **Duração:** 40 minutos
 👨‍🏫 **Professor:** André Ricardo
 👨‍🎓 **Turma:** 3º Ano do Ensino Médio Técnico em Informática

------

## 🎯 Objetivos da Aula

- Transformar o modelo conceitual (DER) em modelo físico
- Utilizar ferramentas de modelagem para gerar o script SQL
- Identificar os principais elementos da modelagem física: tabelas, tipos, PK e FK

------

## 🧩 Conteúdos Abordados

### 🧱 O que é a Modelagem Física?

- Representação detalhada do banco com tipos de dados reais
- Estrutura pronta para ser executada em um SGBD (MySQL)

### 📌 Elementos Essenciais

- **Tabelas**: nome, atributos e domínios
- **Tipos de dados**: `VARCHAR`, `INT`, `DATE`, `BOOLEAN`...
- **Chaves Primárias (PK)** e **Estrangeiras (FK)**
- **Relacionamentos físicos**: 1:N, N:N com tabelas associativas

### 🛠️ Ferramentas

- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
- [dbdiagram.io](https://dbdiagram.io/)
- [drawSQL](https://drawsql.app/)

------

## 📝 Atividade Prática

Cada grupo deverá:

1. Escolher uma das ferramentas de modelagem física
2. Criar o modelo físico a partir do DER já desenvolvido
3. Definir nomes técnicos das tabelas (ex: `tb_usuarios`, `tb_chamada`)
4. Definir os tipos de dados para cada atributo
5. Exportar como imagem (PNG ou PDF) para documentar
6. Se possível, gerar o script DDL para posterior execução

------

## 📂 Organização no Repositório

- Salvar a imagem do modelo físico em:
   `database/diagramas/modelo-fisico.png`
- Salvar o script gerado (DDL) em:
   `database/schema.sql`
- Criar ou complementar o arquivo:
   `docs/06-modelagem-fisica-bd.md`

------

## 🧠 Frase Técnica

> “Modelar bem é programar menos.” – Anônimo

------

## ✅ Checklist de Entrega

-  Modelo físico concluído
-  Tipos e relacionamentos definidos
-  Script SQL gerado (opcional nesta aula)
-  Upload da imagem e script no repositório
-  Documentação criada ou atualizada

------

## 📎 Referências

- [Documentação MySQL Workbench](https://dev.mysql.com/doc/workbench/en/)
- [Guia Prático de Modelagem de Dados](https://www.lucidchart.com/pages/data-modeling)
- [Tipos de Dados MySQL](https://dev.mysql.com/doc/refman/8.0/en/data-types.html)

------

### 🔗 Paginação

#### ⏪ Voltar: Aula 05 – Exportação das Telas

#### 🏠 Início

#### ⏩ Próxima: Aula 07 – Criação das Tabelas no Banco (DDL)

------