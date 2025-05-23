# 💰 Caixa Eletrônico – Hora de Codar 5

Este projeto simula um **Caixa Eletrônico (ATM)** desenvolvido em **JavaScript** como exercício prático de lógica de programação. O sistema permite ao usuário realizar operações bancárias comuns, como consultar saldo, fazer depósitos, saques, transferências e visualizar o extrato. Algumas funcionalidades exigem autenticação por senha para garantir a segurança das operações.

---

## ✅ Funcionalidades

### 🔐 Login do Usuário
- Solicita o nome do usuário ao iniciar.
- Exibe uma mensagem personalizada de boas-vindas.

### 💼 Operações Bancárias

1. **Consultar Saldo**
   - Exibe o saldo atual da conta.
   - Requer autenticação por senha.

2. **Realizar Depósito**
   - Permite adicionar um valor positivo à conta.
   - Valores negativos não são aceitos.

3. **Realizar Saque**
   - Permite sacar valores positivos, desde que não excedam o saldo disponível.

4. **Visualizar Extrato**
   - Exibe um histórico das transações realizadas.
   - Requer autenticação por senha.

5. **Transferência Bancária**
   - Permite transferir valores positivos para outra conta.
   - O número da conta de destino deve ser válido (numérico).
   - Não permite transferências superiores ao saldo atual.
   - Requer autenticação por senha.

6. **Logout / Encerrar Sessão**
   - Exibe uma mensagem de agradecimento ao encerrar o sistema.

---

## 🔒 Regras de Segurança e Validação

- A senha padrão do sistema é **3589**.
- Apenas usuários autenticados podem acessar as opções de saldo, extrato e transferência.
- Valores inseridos devem ser **positivos**.
- O sistema **não permite saldo negativo**.
- Contas de destino em transferências devem conter apenas **números válidos**.

---

## 🧪 Como Usar

1. **Inicie o sistema**
   - Abra o arquivo HTML correspondente no navegador.
   - Digite seu nome para iniciar a sessão.

2. **Selecione uma opção**
   - Um menu será apresentado com as opções disponíveis:
     ```
     1. Consultar Saldo
     2. Depósito
     3. Saque
     4. Extrato
     5. Transferência
     6. Sair
     ```

3. **Autentique-se quando necessário**
   - Ao tentar acessar saldo, extrato ou realizar transferências, o sistema solicitará a senha (**3589**).

4. **Realize as operações desejadas**
   - Siga as instruções exibidas na tela para cada operação.

5. **Saia com segurança**
   - Ao escolher a opção "Sair", o sistema exibirá uma mensagem de encerramento.

---

## 🛠 Requisitos

- Navegador moderno (Chrome, Firefox, Edge, etc.)
- Nenhuma dependência externa
- Apenas HTML + JavaScript puro

---

## 📌 Objetivos do Projeto

- Praticar lógica condicional e estruturas de repetição
- Trabalhar com `prompt()`, `alert()`, `confirm()` e variáveis
- Simular fluxos reais de sistemas bancários
- Aplicar validações e autenticação básica

---

## 👨‍💻 Desenvolvido para fins educacionais

Este projeto faz parte do desafio **Hora de Codar 5** e tem como objetivo reforçar os conceitos fundamentais de programação com **JavaScript**. Ideal para iniciantes que desejam praticar lógica com aplicações interativas e realistas.

---
