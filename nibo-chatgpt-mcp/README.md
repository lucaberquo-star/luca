# Nibo + ChatGPT MCP

Projeto de integração entre Nibo Gestão Financeira e Model Context Protocol (MCP).

## Objetivo
Criar ferramentas financeiras de leitura para consultar o Nibo em linguagem natural.

## Progresso
- Node.js configurado
- API do Nibo validada
- Autenticação via variável de ambiente validada
- Servidor MCP local via stdio
- MCP Inspector conectado
- list_payables validada
- list_receivables exposta

## Próximas etapas
- filtros por período, status, fornecedor, categoria e centro de custo
- totais e resumo financeiro
- paginação automática
- DRE e fluxo de caixa
- MCP remoto HTTPS autenticado
- integração com ChatGPT
- operações de escrita com aprovação humana

## Segurança
Credenciais não são versionadas. A primeira versão permanece somente leitura. Operações de escrita deverão exigir confirmação e auditoria.

Projeto de portfólio sem dados financeiros reais ou credenciais.
