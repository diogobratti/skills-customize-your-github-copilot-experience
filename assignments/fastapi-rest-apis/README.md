# API REST com FastAPI

## 🎯 Objetivo

Construa uma API REST usando o framework FastAPI para definir rotas, validar dados com Pydantic e fornecer documentação automática.

## 📝 Tarefas

### 🛠️ Configurar o projeto FastAPI

#### Descrição
Crie um aplicativo FastAPI básico e execute-o localmente para confirmar que o servidor está funcionando.

#### Requisitos
O projeto deve:

- Ter um arquivo `starter-code.py` com uma aplicação FastAPI inicial
- Iniciar o servidor com `uvicorn starter-code:app --reload`
- Mostrar a documentação automática em `http://127.0.0.1:8000/docs`

### 🛠️ Criar endpoints REST

#### Descrição
Implemente endpoints que permitam criar, listar, visualizar, atualizar e excluir recursos simples.

#### Requisitos
A API deve:

- Retornar uma lista de itens em `GET /items`
- Retornar um item específico em `GET /items/{item_id}`
- Aceitar novos itens em `POST /items`
- Atualizar itens existentes em `PUT /items/{item_id}`
- Remover itens com `DELETE /items/{item_id}`

### 🛠️ Validar dados com Pydantic

#### Descrição
Use modelos Pydantic para validar os dados recebidos e garantir respostas consistentes.

#### Requisitos
A API deve:

- Definir um modelo Pydantic para o item
- Validar campos obrigatórios e tipos de dados
- Retornar códigos de status HTTP corretos para erros de validação

### 🛠️ Testar a API e a documentação

#### Descrição
Verifique a API usando a interface Swagger e confirme que cada rota funciona corretamente.

#### Requisitos
A solução deve:

- Exibir a documentação interativa em `/docs`
- Permitir o envio de requisições de teste diretamente do navegador
- Atualizar corretamente os dados armazenados em memória para as operações CRUD
