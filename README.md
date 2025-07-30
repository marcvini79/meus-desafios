# Sistema de Gestão de Transações Bancárias Pessoais

## Descrição

Este projeto é um sistema simples de gerenciamento de transações financeiras pessoais via linha de comando. Ele permite:

- Visualizar relatórios financeiros
- Cadastrar novas transações
- Editar transações existentes
- Excluir transações
- Consultar transações por ID

O sistema armazena os dados em arquivo JSON para persistência entre execuções.

---

## Instalação e execução

### Requisitos

- Python 3.6 ou superior

### Rodando o sistema

1. Clone o repositório ou baixe os arquivos.

2. Garanta que exista a pasta `./data/` com o arquivo `settings.py` contendo as configurações das categorias e seed.

3. Execute o programa:

```bash
python nome_do_arquivo.py
