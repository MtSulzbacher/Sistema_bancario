# Sistema de Gerenciamento Bancário Simples

Este README documenta um simples sistema de gerenciamento bancário implementado em Python. O sistema permite que o usuário realize operações básicas de banco, como depositar, sacar, visualizar extrato e sair do programa.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

- **Depositar (`d`)**: Permite ao usuário adicionar fundos à sua conta, atualizando o saldo.
- **Sacar (`s`)**: Permite ao usuário retirar fundos de sua conta, com verificações para saldo insuficiente, limite de saque e número máximo de saques.
- **Extrato (`e`)**: Exibe todas as transações realizadas, incluindo depósitos e saques, juntamente com o saldo atual.
- **Sair (`q`)**: Encerra o programa.

## Limitações

- O limite de saque é de R$500 por operação.
- O número máximo de saques permitidos é de 3.

## Como Usar

1. Execute o programa.
2. Selecione uma opção do menu principal:
    - Pressione `d` para depositar dinheiro na conta.
    - Pressione `s` para sacar dinheiro da conta.
    - Pressione `e` para visualizar o extrato da conta.
    - Pressione `q` para sair do programa.
3. Siga as instruções na tela para completar a operação desejada.

## Exemplo de Uso

```plaintext
    SELECIONE UMA OPÇÃO
    [d] - Depositar 
    [s] - Sacar
    [e] - Extrato
    [q] - Sair

=> d
Informe o valor do depósito: 100
```

## Notas Adicionais

- O sistema realiza verificações básicas para garantir a validade das operações.
- As mensagens de erro são exibidas para orientar o usuário em caso de valores inválidos ou operações que não podem ser completadas.

Este sistema é uma ferramenta básica e educacional para entender conceitos de programação e gerenciamento de transações bancárias simples.