Projeto de sistema Imobiliária que busca facilitar o cotidiano do corretor e da imobiliária na gestao dos imoveis, na parte administrativa, financeira e de venda. Utilizamos no projeto Python, versão 3.6, como linguagem principal de programação com seu framework DJANGO versao 2.2. Neste projeto consta com um REST API para retornar dados como de imóveis, corretores, clientes, proprietários e outros.

Como configurar:
Supondo que python3 e pip esteja instalado no servidor:

Clonando o projeto para o servidor: git clone <url-repositorio>
Dentro do diretorio clonado instalamos as dependências: pip install -r requirements.txt
Migrando os dados, tabelas, para o banco de dados: python manage.py migrate
Executando o servidor django: python manage.py runserver
REST API: End-Points
