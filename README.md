# e-commerce-back
STOODBUY - An e-commerce application for a vast variety of products

O projeto a seguir terá como objetivo a criação de uma plataforma de e-commerce, que possuirá uma vasta gama de produtos para atender as diversas necessidades dos usuários em diversos 
setores do varejo, como por exemplo:
- Tecnologia;
- Vestuário;
- Móveis;
- Eletrodomésticos;
- Alimentos e bebidas;

A plataforma conterá um robusto sistema de autenticação para garantir a segurança dos usuários que utilizarão nossa plataforma, bem como entregar múltiplas opções de pagamento que facilitem a vida do cliente.


## Tecnologias utilizadas
 
A aplicação back-end contará com as seguintes tecnologias/frameworks;

- **Python** como linguagem principal de desenvolvimento;
- **FastAPI** para a criação de API's sólidas e de fácil implementação;
- **MySQL** para a modelagem e criação de banco de dados;
- **Docker** para conteinerização/isolamento de aplicações e dependências;
- **JSON Web Token** para autenticação e login de usuário;
- **Google OAuth 2.0** para autenticação direta com conta Google;
- **Facebook Login** para autenticação direta com conta do Facebook;
- **Bcrypt** para encriptação de senha de usuário;
 

## Descrição do projeto

A organização/arquitetura que o projeto seguirá será o modelo MVC (*Model*, *View* e *Controller*), onde o *Model* conterá a estrutura base do banco de dados, o *Controller* possuirá a lógica da aplicação com suas rotas específicas e requisições HTTP e o *View* trará as informações retornadas pelos endpoints/API's da aplicação, comumente em formato JSON.

As regras de negócios/funções principais estarão definidas na pasta *Services*, para melhor organizar o fluxo do controller e os endpoints configurados.


## Instalação e Execução

