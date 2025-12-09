# Projeto TI - Código Base

Estrutura mínima para o site de divulgação de serviços de TI.

Requisitos:
- Node.js (>= 16)

Como executar:
1. Extraia os arquivos.
2. No terminal, entre na pasta do projeto:
   `cd projeto-ti`
3. Instale dependências:
   `npm install`
4. Inicie o servidor:
   `npm start`
5. Abra no navegador:
   `http://localhost:3000`

Observações:
- O projeto usa SQLite para facilitar testes locais (arquivo `database.db` será criado automaticamente).
- Endpoints:
  - GET /api/servicos
  - GET /api/servicos/:id
  - POST /api/contato
