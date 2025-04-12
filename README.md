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

![image](https://github.com/user-attachments/assets/58c58dd8-10a5-4858-bb37-dd4f29ea6858)
![image](https://github.com/user-attachments/assets/86db1467-af45-44e1-99c7-5324b4f8a5ba)
![image](https://github.com/user-attachments/assets/c88cf126-26e1-4981-b090-e37afccb25cb)
![image](https://github.com/user-attachments/assets/32271288-640b-440d-9dcb-74ac1345dfd2)
![image](https://github.com/user-attachments/assets/da71db7f-e0cb-44f1-9d34-67d91758643a)
![image](https://github.com/user-attachments/assets/c287d603-41f8-4983-a72d-32a06f56e59e)
![image](https://github.com/user-attachments/assets/e5b8b688-b9dd-4352-8d24-2c3bb7cd7230)


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
