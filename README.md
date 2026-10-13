# Estoque Inteligente — Controle de Estoque para Adega

Este software é um sistema de gerenciamento de estoque para adegas, desenvolvido para realizar funções essenciais de controle de produtos de maneira prática, eficiente e organizada.

O projeto foi desenvolvido durante a graduação em Ciência da Computação, utilizando Python e Django, com banco de dados SQLite e interface web.

## Funcionalidades

- **Visualização Geral dos Produtos:** Exibe todos os itens cadastrados no sistema, oferecendo acesso rápido a todas as funcionalidades do projeto e à opção de exclusão de produtos.
- **Cadastrar um Novo Produto:** Permite o cadastro de novos itens com validação de campos (dados de texto e valores numéricos positivos).
- **Editar Produto:** Efetua a atualização dos dados principais de um produto (nome, marca e valor com limitação de duas casas decimais).
- **Visualizar Produto:** Apresenta a visão detalhada de um único produto, exibindo informações completas e o valor total acumulado no estoque.
- **Registrar Quantidade de Vendas:** Permite registrar a saída/venda de múltiplos produtos de uma só vez, com controle para evitar vendas acima do saldo disponível.
- **Adicionar ao Estoque:** Permite a entrada/reposição de quantidades em estoque de vários produtos simultaneamente com validação de números inteiros.

## Tecnologias Utilizadas

- **Python**
- **Django**
- **HTML5 & CSS3**
- **JavaScript**
- **Bootstrap**
- **SQLite**

## Como Executar o Projeto

### Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina:
- [Git](https://git-scm.com)
- [Python](https://www.python.org/)

### Passo a Passo

```bash
# Clone este repositório
git clone https://github.com/Guilherme-Rodrigues011/Estoque-Inteligente.git
# Acesse a pasta do projeto
cd Estoque-Inteligente

# Crie e ative o ambiente virtual (Windows)
python -m venv venv
venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Execute as migrações do banco de dados
python manage.py migrate

# Inicie o servidor de desenvolvimento
python manage.py runserver

