# GeekHub API 

## Sobre o Projeto 
- O GeekHub API faz parte de um conjunto de três projetos, desenvolvidos para a avaliação final da 5ª Academia de .NET. O projeto Final consiste de três aplicações (Front-End, Back-End e IA, para fazer conexão com ChatGPT e Gerador de imagens) que trabalham em conjunto, neste repositório encontra-se a parte API do Projeto, feita com ASPNET CORE.

- O Back-End consiste de 8 pastas (Context, Controllers, DTOs, Entities, Mappings, Migrations, Repositories e Validation) que compõem uma API REST Sobre o Universo de Mangás e HQs, esta aplicação possui os dados dos mangás e/ou HQs presentes no GeekHub. A aplicação também possui um CRUD onde pode-se cadastrar, editar e remover novas HQs e/ou mangás. Essa aplicação utiliza Autenticação via Token JWT Bearer e CORS. Para realizar o cadastro, edição ou exclusão de HQs e/ou mangás será necessário estar autenticado na aplicação, para isso você  pode criar uma nova conta informando email e senha.

## Vídeo Apresentação do Projeto
- [Apresentação do Projeto]()

## Links para os outros projetos
[Front-End](https://github.com/IsaquePemasi/GeekHub)
</br>
[IAs](https://github.com/IsaquePemasi/GeekHubIA)

## Ferramentas e padrões de desenvolvimento utilizados
- C#
- AspNetCore
- Dotnet 7
- DTO's
- Versionamento de Código com Git e Github
- Swagger
- SQL Server
- Abordagem Code First
- Integração com Front-end
- Token JWT
- CORS
- AutoMapper 
- EntityFrameWork

## Compreendendo a Estrutura da Aplicação

### Contexto, GeekHub.Context
- Este é o lugar onde o contexto do Entity Framework Core é definido, estabelecendo a base para interações com o banco de dados.

### Controladores, GeekHub.Controllers
- Aqui, os controladores são criados para definir os EndPoints da API, indicando como os dados serão manipulados e respondidos.

### DTOs (Objetos de Transferência de Dados), GeekHub.DTOs
- Nesta seção, são criados os Objetos de Transferência de Dados, que desempenham um papel essencial na comunicação entre diferentes partes da aplicação.

### Entidades, GeekHub.Entities
- As entidades de modelo de domínio do projeto são definidas nesta seção, representando os principais objetos que a aplicação manipula.

### Mapeamentos, GeekHub.Mappings
- Aqui, o mapeamento entre os DTOs é configurado usando o AutoMapper, facilitando a conversão de dados entre diferentes formatos.

### Migrações, GeekHub.Migrations
- As migrações geradas, presentes nesta seção, representam as alterações no esquema do banco de dados ao longo do tempo.

### Repositórios, GeekHub.Repositories
- A definição dos repositórios ocorre nesta parte. Dentro da pasta "Repositories", há uma subpasta "Interfaces" para as interfaces, e outra "Repositories" para as classes concretas que implementam essas interfaces.

### Validação, GeekHub.Validation
- Foi criada uma classe que herda da classe Exception com o propósito de validar as entidades do modelo de domínio, garantindo a integridade dos dados.

<h2 align="center">Autor</h2>
<a href="https://github.com/IsaquePemasi/"><img src="https://avatars.githubusercontent.com/u/76749511?v=4" width=115></a>