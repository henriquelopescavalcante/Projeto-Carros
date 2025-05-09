🚘 Projeto Carros

Aplicação web desenvolvida com Django para gerenciamento e visualização de anúncios de veículos. O projeto tem como foco a organização do código, boas práticas em desenvolvimento backend com Python e a implementação de funcionalidades essenciais em um sistema CRUD.

🧭 Visão Geral

Este sistema permite:

- Cadastro de veículos (nome, marca, ano e preço)
- Visualização de todos os carros registrados
- Consulta detalhada de um veículo
- Filtro de veículos por nome

A estrutura é simples e objetiva, ideal para demonstrar domínio de conceitos fundamentais do Django, como `models`, `views`, `templates`, `urls` e o uso do ORM.

🛠️ Tecnologias

- **Linguagem:** Python 3
- **Framework:** Django 4
- **Banco de Dados:** SQLite (padrão do Django)
- **Template Engine:** Django Templates
- **Estilização:** Bootstrap (para layout responsivo)

📂 Estrutura do Projeto

projeto-carros/
├── carros/ # Aplicação principal com models, views e templates
├── projeto_carros/ # Configurações globais do projeto Django
├── static/ # Arquivos estáticos (CSS, JS, etc.)
├── templates/ # Templates HTML reutilizáveis
├── db.sqlite3 # Banco de dados SQLite
└── manage.py # Interface de gerenciamento do Django


🚀 Como Executar Localmente


1. Clone o repositório:
git clone https://github.com/henriquelopescavalcante/Projeto-Carros.git
cd Projeto-Carros


Crie um ambiente virtual:
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate


Instale as dependências:

pip install -r requirements.txt


Execute as migrações e rode o servidor:

python manage.py migrate
python manage.py runserver

Acesse no navegador:
http://127.0.0.1:8000/

🎯 Objetivo do Projeto
Este projeto foi desenvolvido com o intuito de demonstrar proficiência em Django,
domínio do padrão MTV (Model-Template-View) e habilidade em estruturar aplicações escaláveis e bem organizadas.
 O código segue uma abordagem limpa e modular, ideal para manutenção e evolução futura.

📬 Contato
https://www.linkedin.com/in/henriquelopescs/ | https://github.com/henriquelopescavalcante
