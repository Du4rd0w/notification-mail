# 📊 Controle Financeiro com Avisos Automatizados

Este projeto integra uma planilha do Google Sheets com um script em Google Apps Script para automatizar o controle de faturas e despesas pessoais. Ele envia avisos por e-mail sobre vencimentos próximos, vencimentos no dia e faturas já pagas, facilitando a gestão financeira mensal.

## 🚀 Funcionalidades

- ✅ Identificação automática de faturas pagas
- ⚠️ Aviso de faturas que vencem hoje
- 📅 Aviso de faturas que vencem nos próximos dias (configurável)
- 📧 Envio de e-mail com resumo em formato de tabela
- 📁 Integração com Google Sheets

## 🧠 Como funciona

O script é acionado conforme configurar no App Script e realiza as seguintes etapas:

1. Acessa a planilha pelo ID.
2. Lê os dados da aba principal.
3. Filtra faturas por status e data de vencimento.
4. Gera uma tabela HTML com os dados relevantes.
5. Envia um e-mail com o resumo das faturas.

## 📋 Estrutura da Planilha

A aba principal deve conter as seguintes colunas:

| Data       | Descrição |                 Tipo            | Valor (R$)|          Categoria            |      Status    |
|------------|-----------|---------------------------------|-----------|-------------------------------|----------------|
| 30/08/2025 |           | Depesa/Receita/Receita Variável |  VALOR    | Fixo/Variável/Receita Variável| Pago/Pendente  |

## ⚙️ Configuração

1. Crie uma planilha no Google Sheets com a estrutura acima ou baixe a do repositório como base
2. Copie o script para o editor de Apps Script vinculado à planilha.
3. Substitua:
   - `ID da planilha` pelo ID real da sua planilha, fica na URL entre d/ e /edit
   - `"Nome da aba"` pelo nome da aba onde estão os dados.
   - `"seu e-mail"` pelo e-mail que receberá os avisos.
4. Configure o acionamento automático como queira.

## 📈 Exemplos de uso

- Controle de despesas mensais
- Acompanhamento de vencimentos de cartões, boletos e assinaturas
- Planejamento financeiro com metas e variáveis

## 🛠️ Tecnologias

- Google Sheets
- Google Apps Script
- HTML (para formatação do e-mail)
- JavaScript

## 📬 Contato

Criado por [Eduardo] — sugestões e melhorias são bem-vindas!

---
