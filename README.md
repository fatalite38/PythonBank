# Sistema de Gerenciamento de Contas Bancárias

## Funcionalidades

- **Depósito:** Permite ao usuário depositar um valor em uma conta bancária.
- **Saque:** Permite ao usuário sacar um valor de uma conta bancária, respeitando o saldo disponível e as regras de limite de saques.
- **Extrato:** Exibe o extrato das transações realizadas em uma conta bancária.
- **Nova conta:** Permite a criação de uma nova conta bancária associada a um usuário existente.
- **Novo usuário:** Permite a criação de um novo usuário para o sistema.
- **Listar contas:** Exibe uma lista de todas as contas bancárias cadastradas no sistema.

## Estrutura do Código

O código é dividido em várias classes e funções:

- **Cliente:** Classe base que representa um cliente do banco.
- **PessoaFisica:** Classe que representa uma pessoa física, herda de Cliente.
- **Conta:** Classe que representa uma conta bancária.
- **ContaCorrente:** Classe que representa uma conta corrente, herda de Conta.
- **Historico:** Classe que registra as transações de uma conta.
- **Transacao:** Classe abstrata que define uma transação.
- **Saque:** Classe que representa uma transação de saque, herda de Transacao.
- **Deposito:** Classe que representa uma transação de depósito, herda de Transacao.

Além das classes, o código contém diversas funções para interação com o usuário e controle do sistema, como `menu()`, `depositar()`, `sacar()`, `exibir_extrato()`, `criar_usuario()`, `filtrar_usuario()`, `criar_conta()` e `listar_contas()`.

## Executando o Código

Para executar o código, basta rodar o script Python. Ele iniciará um menu interativo onde o usuário pode selecionar as diferentes operações disponíveis.

## Contribuições

Este é um projeto simples, mas há várias oportunidades para contribuições, como a adição de novas funcionalidades, melhorias na interface de usuário, refatoração do código para seguir boas práticas de programação, entre outros. Se você quiser contribuir, sinta-se à vontade para abrir um pull request!
