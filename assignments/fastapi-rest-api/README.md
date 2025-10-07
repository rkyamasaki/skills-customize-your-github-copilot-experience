# 📘 Assignment: Construindo APIs REST com FastAPI

## 🎯 Objective

Aprender a criar APIs REST modernas e eficientes utilizando o framework FastAPI em Python. O objetivo é construir uma API simples para gerenciar uma lista de tarefas (to-do list), praticando conceitos de rotas, métodos HTTP, validação de dados e documentação automática.

## 📝 Tasks

### 🛠️ Criar uma API REST para To-Do List

#### Description
Implemente uma API que permita criar, listar, atualizar e remover tarefas de uma lista. Utilize o FastAPI para definir as rotas e os métodos HTTP adequados para cada operação.

#### Requirements
Completed program should:

- Permitir adicionar novas tarefas via método POST
- Listar todas as tarefas cadastradas via método GET
- Atualizar o status ou descrição de uma tarefa via método PUT
- Remover uma tarefa via método DELETE
- Utilizar modelos Pydantic para validação dos dados
- Expor documentação automática da API em /docs

### 🛠️ (Opcional) Persistência Simples

#### Description
Implemente uma forma simples de persistir as tarefas, como salvar em um arquivo JSON ou usar um dicionário em memória.

#### Requirements
Completed program should:

- Manter as tarefas salvas mesmo após reiniciar a aplicação (se optar por persistência em arquivo)
- Documentar no README como executar e testar a API

