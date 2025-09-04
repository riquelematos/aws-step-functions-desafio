# 🚀 Desafio AWS Step Functions - DIO

Este repositório contém a solução do desafio proposto pela DIO,
que consiste em criar um fluxo automatizado utilizando AWS Step Functions e funções Lambda,
simulando o processamento de um pedido em um sistema serverless.

## 📦 Objetivo

Demonstrar a aplicação prática dos conceitos aprendidos sobre orquestração de serviços com AWS Step Functions, 
integrando múltiplas funções Lambda em um fluxo lógico e funcional.

## 🧠 Fluxo Implementado

O fluxo representa o ciclo completo de um pedido de e-commerce, com as seguintes etapas:

1. **ReceberPedido** – Recebe os dados do pedido do cliente.
2. **VerificarEstoque** – Verifica se o produto está disponível.
3. **ProcessarPagamento** – Realiza o pagamento do pedido.
4. **ConfirmarPedido** – Confirma o pedido no sistema.
5. **EnviarNotificacao** – Envia uma notificação de confirmação ao cliente.

## 🔧 Tecnologias Utilizadas

- AWS Step Functions
- AWS Lambda
- Python

## O que aprendi:
- Criar fluxos automatizados com Step Functions
- Integrar funções Lambda em diferentes etapas
- Documentar projetos no GitHub
