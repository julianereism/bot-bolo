# Nana Reis — Bot de Delivery de Bolos no Telegram

Um bot feito com Python e `python-telegram-bot` para receber pedidos de bolos de forma simples e automatizada via Telegram. Os dados dos pedidos são armazenados automaticamente em uma planilha Excel, e o pagamento é realizado via Pix manual.

## Funcionalidades

- Menu interativo com botões no Telegram
- Escolha de sabores de bolo
- Coleta de informações: nome, endereço e forma de pagamento
- Confirmação do pedido com resumo
- Pagamento via Pix manual (com chave Pix informada)
- Registro automático dos pedidos em um arquivo `pedidos.xlsx`

## Tecnologias Utilizadas

- Python 3.10+
- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/) — para manipular Excel
- [python-dotenv](https://github.com/theskumar/python-dotenv) — para gerenciar o token do bot


