# Gerenciador de Conta Bancária

Um simples programa em Python que simula um gerenciador de conta bancária, permitindo depósitos, saques e visualização de extrato.

## Funcionalidades

- Depositar dinheiro na conta.
- Sacar dinheiro da conta.
- Visualizar extrato da conta.
- Encerrar o programa.

## Executando o Programa

Certifique-se de ter o Python instalado em sua máquina.

1. Clone este repositório em sua máquina local:
``` git clone https://github.com/seu-usuario/nome-do-repositorio.git ```


2. Navegue até o diretório do projeto:
``` cd nome-do-repositorio ```


3. Execute o programa:
``` python nome-do-arquivo.py ```


## Uso

**Ao executar o programa, você será apresentado a um menu com as seguintes opções:**

* [D] Deposito - Para fazer um depósito, digite "D" e informe o valor que deseja depositar quando solicitado.
* [S] Saque - Para fazer um saque, digite "S" e informe o valor que deseja sacar quando solicitado.
* [E] Extrato - Para visualizar o extrato da conta, digite "E".
* [Q] Quit - Para encerrar o programa, digite "Q".


## Observações

- O saldo inicial da conta é zero.
- Existe um limite de saques diários, definido pela variável `LIMITE_SAQUES`.
- O valor máximo permitido para saque é definido pela variável `valor_saque`.
- O extrato exibirá as movimentações realizadas na conta.
- O programa terminará sua execução ao digitar "Q" no menu.

## Contribuindo

Se você quiser contribuir com este projeto, fique à vontade para fazer um fork e enviar suas propostas de melhoria através de pull requests.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).
