API Futebol
Este projeto é uma API desenvolvida para gerenciamento de competições esportivas. A API permite criar, listar, atualizar e excluir informações sobre partidas, equipes e resultados, promovendo uma organização eficiente das competições. Além disso, fornece endpoints bem documentados para interação com o sistema.

🛠️ Tecnologias Utilizadas
Python 3.12 : Linguagem de programação principal.
FastAPI : Framework para construção de APIs rápidas e eficientes.
Uvicorn : Servidor ASGI para rodar a aplicação.
SQLAlchemy : ORM para gerenciamento de banco de dados.
Pydantic : Validação e tipagem de dados.
Docker : Contêinerização do ambiente de desenvolvimento.
PostgreSQL : Banco de dados relacional.
Git : Controle de versão.
🚀 Como usar o projeto
1. Pré-requisitos
Certifique-se de ter os seguintes softwares instalados:

Docker e Docker Compose
Git
2. Clonar o Repositório
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
3. Configuração com Docker
Enviar os contêineres:

  docker-compose up --build
Acesse o aplicativo no navegador:

  http://localhost:8000
Teste as rotas na documentação interativa:

    http://localhost:8000/docs
4. Uso de Jinja2 para modelos
O aplicativo utiliza Jinja2 para renderizar modelos HTML. A partir de agora, ao acessar o sistema, você pode ver as páginas com o conteúdo dinâmico sendo geradas diretamente pelo servidor.
