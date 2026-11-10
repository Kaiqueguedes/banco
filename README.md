# Banco — Sistema bancário em Portugol

Simulação de caixa eletrônico escrita em Portugol, desenvolvida no Portugol Studio como exercício de lógica de programação. Foi um dos meus primeiros programas com menu, laço de repetição e validação de entrada — antes de trabalhar com uma linguagem de programação de fato.

## O que o programa faz

O usuário começa com saldo zero e navega por um menu em loop, com cinco opções:

| Opção | Ação |
| :--- | :--- |
| 1 | Mostrar o saldo atual |
| 2 | Sacar, com verificação de saldo insuficiente |
| 3 | Depositar, com recusa de valores negativos |
| 4 | Ver o extrato de todas as operações realizadas |
| 0 | Sair |

## O que pratiquei

- Laço `enquanto` para manter o menu ativo até o usuário sair.
- Estrutura de decisão `escolha/caso` no lugar de vários `se` encadeados.
- Validação de entrada: valor de saque não pode ser negativo nem maior que o saldo.
- Acúmulo de histórico em uma variável de texto, usada como extrato.
- Organização do código em uma função de início.

## Como executar

1. Baixe o Portugol Studio.
2. Abra o arquivo `Banco.por`.
3. Clique em executar.

## Estrutura

```
banco/
└── Banco.por   # todo o programa
```

O trecho final do arquivo guarda informações do próprio Portugol Studio (posição do cursor e pontos de parada). Pode ser apagado sem afetar o programa.
