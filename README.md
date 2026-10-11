# 🛒 Gerenciador de Lista de Compras

Projeto desenvolvido em **Python** com o objetivo de praticar lógica de programação e conceitos fundamentais da linguagem.

O programa funciona pelo terminal e permite ao usuário adicionar, listar e remover produtos de uma lista de compras, utilizando um menu interativo.

## ⚙️ Funcionalidades

- **Inserir:** adiciona novos produtos à lista.
- **Listar:** exibe os produtos cadastrados com seus índices.
- **Apagar:** remove um produto pelo índice informado.
- **Tratamento de erros:** impede que o programa seja encerrado por índices inexistentes ou entradas numéricas inválidas.
- **Sair:** encerra a execução do programa.

## 🧠 Conceitos utilizados

- `import os` — Importação do módulo para limpar o terminal.
- `os.system('cls')` — Limpeza da tela no Windows.
- `list` — Estrutura utilizada para armazenar os produtos.
- `while True` — Repetição contínua do menu.
- `input()` — Recebimento das informações do usuário.
- `print()` — Exibição de mensagens no terminal.
- `if / elif / else` — Estruturas condicionais para controlar as opções.
- `for` — Percorre os elementos da lista.
- `enumerate()` — Exibe os produtos com seus índices.
- `append()` — Adiciona produtos à lista.
- `del` — Remove produtos utilizando seus índices.
- `int()` — Converte a entrada do usuário para número inteiro.
- `try / except` — Tratamento de erros durante a execução.
- `IndexError` — Tratamento de índices inexistentes.
- `ValueError` — Tratamento de entradas que não podem ser convertidas em números.
- `break` — Encerra o laço de repetição.
- `f-string` — Formatação das mensagens exibidas.

## 💻 Como executar

Com o Python instalado, execute o arquivo pelo terminal:

`python gerenciador.py`

**Observação:** o programa utiliza o comando `cls` para limpar o terminal no Windows.

---

Projeto desenvolvido para fins de estudo e prática em Python.
