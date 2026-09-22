# Aplicativo da operação

Sistema web da equipe, em Next.js e TypeScript. Foi criado do zero e está em uso.

## O que a pessoa encontra

- Filas da operação e acompanhamento do dia
- CRM operacional, no rastreio
- CRM comercial, com funil e cotação
- Financeiro da casa: contas, caixa e fechamento
- Indicadores para gestão
- Portal de colaborador e gestor

## Acesso

Cada função tem permissão própria. Ver a empresa inteira não abre o mesmo que lançar na própria unidade. Dado financeiro não abre com o acesso genérico do sistema.

A sessão fica no servidor. Segredo de API não vai para o navegador.

## Onde isso conversa

O CRM recebe o WhatsApp da operação e a linha oficial do comercial. Os painéis leem o PostgreSQL alimentado pelo ERP. O detalhe de cada canal está em [WhatsApp](canais.md) e em [Dados](dados.md).
