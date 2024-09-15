# hora-de-codar-5
# Caixa Eletrônico

Este é um projeto de caixa eletrônico desenvolvido como exercício de programação em JavaScript. O sistema permite que o usuário execute operações bancárias básicas, como consultar saldo, fazer depósitos, saques, transferências e visualizar extratos. O acesso às operações requer a validação de uma senha.

## Funcionalidades

1. **Login do Usuário**
   - Solicita o nome do usuário e exibe uma mensagem de boas-vindas.

2. **Operações Bancárias**
   - **Saldo**: Consulta o saldo atual, requer autenticação de senha.
   - **Depósito**: Permite o depósito de um valor no saldo. Valores devem ser positivos.
   - **Saque**: Permite o saque de um valor do saldo. O valor do saque deve ser maior que zero e não deve exceder o saldo disponível.
   - **Extrato**: Exibe o extrato das transações realizadas. Requer autenticação de senha.
   - **Transferência**: Permite a transferência de um valor para uma conta. O número da conta deve ser numérico, e o valor da transferência deve ser maior que zero e não deve exceder o saldo disponível.

3. **Logout**
   - Exibe uma mensagem de agradecimento ao usuário ao sair do sistema.

## Requisitos

- O sistema deve validar a senha antes de permitir o acesso às opções de saldo, extrato e transferência.
- O valor de depósito, saque e transferência deve ser positivo.
- O saldo não pode ficar negativo e as transferências devem ser realizadas somente para contas numéricas válidas.

## Instruções de Uso

1. **Abrir o Caixa Eletrônico**
   - Ao abrir a página, o sistema solicitará o nome do usuário e exibirá uma mensagem de boas-vindas.

2. **Escolher uma Opção**
   - O usuário deve escolher uma das opções do menu:
     1. Saldo
     2. Depósito
     3. Saque
     4. Extrato
     5. Transferência
     6. Sair

3. **Autenticação**
   - Para consultar saldo, visualizar extrato ou realizar uma transferência, o usuário deve inserir a senha correta (3589).

4. **Operações**
   - **Depósito**: Insira o valor a ser depositado.
   - **Saque**: Insira o valor a ser sacado.
   - **Transferência**: Insira o número da conta e o valor a ser transferido.

5. **Sair**
   - Ao escolher a opção de sair, o sistema exibe uma mensagem de agradecimento.


