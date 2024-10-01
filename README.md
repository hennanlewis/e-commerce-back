# e-commerce-back
STOODBUY - An e-commerce application for a vast variety of products

Este projeto é uma aplicação de uma plataforma de e-commerce, que os usuários podem se registrar, fazer login, navegar por produtos, adicionar ao carrinho e fazer pedidos. O sistema também implementa autenticação JWT e autenticação por meio de contas Google e Facebook.

## Requisitos

- Python 3.10+
- MySQL 8.0+
- Docker (opcional)

## Tecnologias utilizadas

- **Python** como linguagem principal de desenvolvimento;
- **FastAPI** para a criação de API's sólidas e de fácil implementação;
- **MySQL** para a modelagem e criação de banco de dados;
- **Docker** para conteinerização/isolamento de aplicações e dependências;
- **JSON Web Token** para autenticação e login de usuário;
- **Google OAuth 2.0** para autenticação direta com conta Google;
- **Facebook Login** para autenticação direta com conta do Facebook;
- **Bcrypt** para encriptação de senha de usuário.

## Funcionalidades

- [ ] CRUD de produtos;
- [ ] Listagem de produtos;
- [ ] Adicionar itens ao carrinho de compras;
- [ ] Finalizar pedidos;
- [ ] Registro e login de usuários com autenticação JWT;
- [ ] Login via Google e Facebook;
- [ ] Proteção de rotas para ações de compra com base em JWT.

## Descrição do projeto

Este projeto segue a arquitetura MVC (*Model*-*View*-*Controller*):

- *Model*: Responsável pela estrutura base do banco de dados;
- *Controller*: Contém a lógica da aplicação, incluindo rotas específicas e o tratamento das requisições HTTP;
- *View*: Responsável por retornar as informações fornecidas pelos endpoints/APIs da aplicação, geralmente no formato JSON.

Além disso, para melhor organizar o fluxo entre o *Controller* e os endpoints configurados, as regras de negócios e as funções principais estão localizadas na pasta *Services*.


## Instalação e Execução
Para instalar este projeto, siga os seguintes passos:

1. Clone o repositório
```shell
git clone https://github.com/hennanlewis/e-commerce-back.git
```

2. Navegue até a pasta do projeto
```shell
cd youtube-downloader
```

3. Crie um ambient vitual (opcional, mas recomendado):

```shell
python -m venv .env
source .env/bin/activate    # Linux
.env\Scripts\activate       # Windows
```

4. Instale os pacotes necessários:
```shell
pip install -r requirements.txt
```

Para finalizar o uso do ambiente, utilize o seguinte código:
```shell
deactivate
```

## Licença

Este projeto utiliza uma licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
