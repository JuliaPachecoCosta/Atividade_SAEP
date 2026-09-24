# 🗳️ Sistema de Gerenciamento Eleitoral

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,100:8A2BE2&height=200&section=header&text=Sistema%20Eleitoral&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35" />
</p>

<p align="center">
  <strong>💻 Atividade SAEP — Desenvolvimento de CRUD em PHP</strong>
</p>

<p align="center">
  Sistema web desenvolvido para o gerenciamento de
  <strong>eleitores</strong> e <strong>candidatos</strong>,
  utilizando PHP e MySQL.
</p>

---

## 📌 Sobre o Projeto

O **Sistema de Gerenciamento Eleitoral** foi desenvolvido como parte da
**Atividade SAEP — Desenvolvimento de CRUD em PHP**.

O projeto tem como objetivo desenvolver uma aplicação web capaz de
gerenciar informações relacionadas a **eleitores e candidatos**, permitindo
realizar operações de:

- ➕ Cadastro
- 🔎 Consulta
- ✏️ Atualização
- 🗑️ Exclusão

Essas operações fazem parte do conceito **CRUD**:

> **C**reate • **R**ead • **U**pdate • **D**elete

---

## 🎯 Objetivo

Desenvolver um sistema web funcional para o gerenciamento de dados
eleitorais, aplicando conhecimentos de:

- 💻 Desenvolvimento Web
- 🗄️ Banco de Dados
- 🔐 Segurança da Informação
- 🧪 Testes
- 🔄 Metodologia SCRUM

O projeto foi desenvolvido utilizando **PHP** para o processamento das
informações e **MySQL** para armazenamento e gerenciamento dos dados.

---

## 🚀 Funcionalidades

### 👤 Eleitores

O sistema permite:

- ➕ Cadastrar eleitores
- 🔎 Consultar eleitores
- ✏️ Editar informações
- 🗑️ Excluir registros
- 🗳️ Associar um eleitor a um candidato
- ✅ Validar informações cadastradas

### 🗳️ Candidatos

É possível:

- ➕ Cadastrar candidatos
- 🔎 Consultar candidatos
- ✏️ Editar informações
- 🗑️ Excluir registros
- 🏷️ Registrar nome, número e partido
- 🚫 Evitar números de candidatos duplicados

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Utilização |
|------------|------------|
| 🐘 **PHP** | Desenvolvimento e processamento da aplicação |
| 🐬 **MySQL** | Armazenamento dos dados |
| 🔗 **PDO** | Comunicação entre PHP e banco de dados |
| 🔐 **Prepared Statements** | Segurança nas consultas SQL |
| 🌐 **HTML** | Estrutura das páginas |
| 🔄 **CRUD** | Gerenciamento dos registros |
| 📋 **SCRUM** | Organização da equipe |

---

## 📂 Estrutura do Projeto

```text
📦 Sistema-Gerenciamento-Eleitoral
│
├── 📄 .gitattributes
│
├── 🗑️ candidato_excluir.php
├── 📝 candidato_form.php
├── 🗳️ candidatos.php
│
├── ⚙️ config.php
├── 🗄️ database.sql
│
├── 🗑️ eleitor_excluir.php
├── 📝 eleitor_form.php
├── 👥 eleitores.php
│
└── 🏠 index.php
