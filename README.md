# Sistema Bancário em Python 🏦

Um **sistema bancário simples** desenvolvido em Python, que permite simular operações básicas de uma conta bancária, como depósitos, saques, criação de usuários e contas, e consulta de extratos.

## Funcionalidades

O sistema implementa as seguintes operações:

- **Criar usuário**: Cadastro de usuários com CPF, nome, data de nascimento e endereço.  
- **Criar conta**: Criação de conta associada a um usuário existente.  
- **Depositar**: Adicionar saldo à conta do usuário.  
- **Sacar**: Retirar saldo da conta, respeitando limite diário e número máximo de saques.  
- **Extrato**: Exibir todas as movimentações realizadas e o saldo atual.  
- **Listar contas**: Visualizar todas as contas cadastradas com informações de agência, número da conta e titular.  

## Regras do Sistema

- Limite de saque por operação: R$ 500,00  
- Limite de saques diários: 3 saques  
- Depósitos e saques somente com valores positivos  
- Usuários são identificados pelo CPF, que deve ser único  

## Tecnologias

- Linguagem: **Python 3**

## Projeto da DIO

Projeto desenvolvido durante o curso da [Digital Innovation One (DIO)](https://www.dio.me/).

[![DIO](https://img.shields.io/badge/Powered%20by-DIO-%237734BE?style=for-the-badge)](https://www.dio.me/)

