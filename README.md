# 📚 Sistema CRUD de Cadastro de Alunos

Este projeto é uma aplicação desktop desenvolvida em Python com interface gráfica utilizando Tkinter e integração com banco de dados MySQL.

## 🚀 Funcionalidades

- ✅ Cadastro de alunos
- ✏️ Atualização de registros
- ❌ Exclusão de dados
- 📊 Visualização em tabela dinâmica (Treeview)
- 🔎 Seleção de registros com duplo clique
- ✔️ Validação de campos obrigatórios

## 🛠️ Tecnologias utilizadas

- Python
- Tkinter (interface gráfica)
- MySQL
- mysql-connector-python

## 💡 Sobre o projeto

O sistema foi desenvolvido com o objetivo de praticar conceitos fundamentais de desenvolvimento, como:

- Integração entre aplicação e banco de dados
- Operações CRUD (Create, Read, Update, Delete)
- Manipulação de eventos em interface gráfica
- Organização de código orientado a objetos (POO)
- Tratamento de erros e validações

## 🗄️ Estrutura do Banco de Dados

Tabela: `aluno`

| Campo  | Tipo        |
|--------|------------|
| id     | INT (PK)   |
| nome   | VARCHAR    |
| email  | VARCHAR    |
| curso  | VARCHAR    |
| valor  | DECIMAL    |

## ▶️ Como executar

1. Instale as dependências:
```bash
pip install mysql-connector-python
