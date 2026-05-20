# Exercício 2 — Integração Eclipse + PostgreSQL (CRUD em Java)

Projeto desenvolvido na disciplina **Trabalho Interdisciplinar II: Back-End (PUC Minas)**, com foco na integração entre Java e banco de dados PostgreSQL utilizando o ambiente Eclipse.

---

## 📌 Objetivo

O objetivo deste exercício é desenvolver uma aplicação Java com persistência de dados em PostgreSQL, aplicando os conceitos de CRUD (Create, Read, Update, Delete).

A aplicação deve conter:

- Classe modelo (entidade)
- Classe DAO para manipulação de dados
- Classe principal com menu interativo
- Integração com banco de dados PostgreSQL

---

## 🛠️ Tecnologias Utilizadas

- Java
- Eclipse IDE
- PostgreSQL
- JDBC
- Git e GitHub

---

## 🧱 Estrutura do Projeto

```bash id="ex2tree"
TI2IntegracaoPostgreSQL/
│
├── src/
│   ├── model/        # Classe entidade X
│   ├── dao/          # Classe DAO (CRUD)
│   └── main/         # Classe Principal (menu)
│
├── sql/
│   └── script.sql    # Criação da tabela no PostgreSQL
│
└── README.md
