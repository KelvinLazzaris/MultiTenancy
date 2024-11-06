# Sistema de Gerenciamento de Tenants com Multi-Tenancy

Este projeto oferece um sistema robusto para **gestão de múltiplos tenants** em uma única aplicação, ideal para arquiteturas SaaS (Software as a Service) que exigem isolamento seguro e eficiente de dados para diferentes clientes.

## Principais Funcionalidades
- **Gerenciamento Completo de Tenants**: Inclui operações CRUD completas, permitindo criar, listar, atualizar e excluir tenants facilmente.
- **Endpoints Simples e Eficientes**: Com uma estrutura de API RESTful, possibilita interações claras com o sistema usando HTTP para operações de gerenciamento.
- **Configuração Personalizável**: Configure rapidamente sua conexão de banco de dados e inicie a aplicação localmente.

## Passo a Passo de Configuração
1. Clone este repositório.
2. Instale **Node.js**, **npm**, e **MySQL**.
3. Configure o banco de dados e as informações de conexão no arquivo `config/db.js`.
4. Instale as dependências do projeto com `npm install`.

## Como Usar
Inicie o servidor com `node app.js` e utilize ferramentas como **Postman** para enviar requisições HTTP aos endpoints:

- **Criar Tenant**: `POST /api/tenants`
- **Listar Tenants**: `GET /api/tenants`
- **Obter Tenant por ID**: `GET /api/tenants/:id`
- **Atualizar Tenant**: `PUT /api/tenants/:id`
- **Excluir Tenant**: `DELETE /api/tenants/:id`

> **Nota:** Certifique-se de enviar as requisições com o cabeçalho `Content-Type: application/json`.
