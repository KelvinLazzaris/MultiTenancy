Sistema de Gerenciamento de Tenants

Este sistema permite a gestão de múltiplos tenants em uma única aplicação. Guia para usá-lo:.

Configuração:

- Clone o repositório em sua máquina local.
- Instale o Node.js e npm em seu ambiente de desenvolvimento.
- Instale as dependências. (npm install)
- Instale o MySQL
- Edite o arquivo config/db.js com suas informações de conexão.

Inicialização do Servidor:
Após configurar o banco de dados, inicie o servidor:

- node app.js (O servidor estará pronto para aceitar solicitações).

Operações CRUD
O sistema permite as seguintes operações:

Criar Tenant: Crie um novo tenant.
Listar Tenants: Obtenha uma lista de todos os tenants.
Obter Tenant por ID: Detalhes de um tenant específico.
Atualizar Tenant: Atualize um tenant existente.
Excluir Tenant: Exclua um tenant existente.
Use ferramentas como Postman para enviar requisições HTTP para os endpoints.

Endpoints
Criar Tenant: POST /api/tenants
Listar Todos os Tenants: GET /api/tenants
Obter Tenant por ID: GET /api/tenants/:id
Atualizar Tenant: PUT /api/tenants/:id
Excluir Tenant: DELETE /api/tenants/:id
Certifique-se de usar o cabeçalho Content-Type: application/json nas requisições.

