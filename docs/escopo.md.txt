# Escopo do projeto

## Objetivo
Sistema de integração de pagamentos com a API da Stripe.
Serve de portfólio, simulando um sistema de mercado.

## Dentro do escopo
- Criar pagamentos
- Cancelar pagamentos (somente pagamentos em PENDING)
- Consultar pagamentos
- Receber Webhooks da Stripe para atualização do status do pagamento

## Fora do escopo (MVP)
- Login de usuário
- Reembolso de pagamentos
- Carrinho

Ficam para o futuro. O MVP foca na integração com a Stripe e na estrutura do projeto.

## Estados do pagamento
PENDING, SUCCEEDED, FAILED e CANCELED