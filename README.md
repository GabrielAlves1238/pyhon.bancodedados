# pyhon.bancodedados
# 📘 Sistema de Gerenciamento de Usuários

## 🧠 Introdução

Este projeto tem como objetivo desenvolver um sistema simples de gerenciamento de usuários utilizando Python e banco de dados SQLite. A aplicação permite realizar operações de cadastro, listagem, busca, atualização e exclusão de usuários através de um menu no terminal.

---

## 💃 Estrutura do Banco de Dados

O projeto utiliza um banco de dados SQLite chamado `loja.db`, com uma única tabela chamada `usuarios`.

### 📋 Tabela: `usuarios`

| Campo  | Tipo     | Descrição                         |
|--------|----------|-----------------------------------|
| `id`   | INTEGER  | Identificador único (auto incremento, chave primária) |
| `nome` | TEXT     | Nome do usuário (obrigatório)     |
| `email`| TEXT     | Email do usuário (obrigatório)    |

---

## 🤪 Capturas de Tela

### ✅ Execução do Menu no Terminal

![Sistema rodando no terminal](blob:https://web.whatsapp.com/5e66a0e6-032c-4fe7-b451-771eec77fd45)

> 💡 *Adicione aqui imagens reais da execução do código no terminal, como por exemplo o menu, um usuário sendo cadastrado, listagem, etc.*

---

## 📦 Bibliotecas Utilizadas

| Biblioteca | Motivo de uso                                   |
|------------|--------------------------------------------------|
| `sqlite3`  | Biblioteca nativa do Python para banco de dados SQL. Usada para criar e gerenciar a base de dados `loja.db`. |

> 🔸 *Nenhuma biblioteca externa precisa ser instalada com pip neste projeto.*

---

## ⚙️ Funcionalidades Implementadas

- [x] **Adicionar usuário**: Insere um novo usuário com nome e email.
- [x] **Listar usuários**: Exibe todos os usuários cadastrados no banco.
- [x] **Buscar por nome**: Busca parcial ou completa de usuários pelo nome.
- [x] **Buscar por ID**: Encontra um usuário específico com base no seu ID.
- [x] **Atualizar usuário**: Permite editar o nome e email de um usuário existente.
- [x] **Deletar usuário**: Remove um usuário com base no seu ID.
- [x] **Menu interativo**: Sistema amigável para navegação e uso no terminal.

---

## 📝 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/GabrielAlves1238/pyhon.bancodedados/tree/main
   cd seurepositorio
   ```
