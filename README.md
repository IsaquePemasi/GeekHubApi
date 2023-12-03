<h1 align="center">GeekHub API</h1>

<p align="center">
  <img alt="Principal linguagem do projeto" src="https://img.shields.io/github/languages/top/IsaquePemasi/GeekHubApi?color=56BEB8">

  <img alt="Quantidade de linguagens utilizadas" src="https://img.shields.io/github/languages/count/IsaquePemasi/GeekHubApi?color=56BEB8">

  <img alt="Tamanho do repositório" src="https://img.shields.io/github/repo-size/IsaquePemasi/GeekHubApi?color=56BEB8">

  <img alt="Licença" src="https://img.shields.io/github/license/IsaquePemasi/GeekHubApi?color=56BEB8">
</p>

<p align="center">
  <a href="#sobre-o-projeto">Sobre</a> &#xa0; | &#xa0;  
  <a href="#vídeo-apresentação-do-projeto">Vídeo</a> &#xa0; | &#xa0;
  <a href="#links-para-os-outros-projetos">Links para os outros projetos</a> &#xa0; | &#xa0;
  <a href="#ferramentas-e-padrões-de-desenvolvimento-utilizados">Ferramentas utilizadas</a> &#xa0; | &#xa0;
  <a href="#compreendendo-a-estrutura-da-aplicação">Estrutura da Aplicação</a> &#xa0; | &#xa0;
  <a href="#como-reproduzir">Como reproduzir</a> &#xa0; | &#xa0;
  <a href="#autor" target="_blank">Autor</a>
</p>

<h2 align="center">Sobre o Projeto</h2> 

- O GeekHub API faz parte de um conjunto de três projetos, desenvolvidos para a avaliação final da 5ª Academia de .NET. O projeto Final consiste de três aplicações (Front-End, Back-End e IA, para fazer conexão com ChatGPT e Gerador de imagens) que trabalham em conjunto, neste repositório encontra-se a parte API do Projeto, feita com ASPNET CORE.

- O Back-End consiste de 8 pastas (Context, Controllers, DTOs, Entities, Mappings, Migrations, Repositories e Validation) que compõem uma API REST Sobre o Universo de Mangás e HQs, esta aplicação possui os dados dos mangás e/ou HQs presentes no GeekHub. A aplicação também possui um CRUD onde pode-se cadastrar, editar e remover novas HQs e/ou mangás. Essa aplicação utiliza Autenticação via Token JWT Bearer e CORS. Para realizar o cadastro, edição ou exclusão de HQs e/ou mangás será necessário estar autenticado na aplicação, para isso você  pode criar uma nova conta informando email e senha.
  
<h2 align="center">Vídeo Apresentação do Projeto</h2>

- [Apresentação do Projeto]()

<h2 align="center">Links para os outros projetos</h2>

[Front-End](https://github.com/IsaquePemasi/GeekHub)
</br>
[IAs](https://github.com/IsaquePemasi/GeekHubIA)
<h2 align="center">Ferramentas e padrões de desenvolvimento utilizados</h2>
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
<h2 align="center">Compreendendo a Estrutura da Aplicação</h2>

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
<h2 align="center">Como Reproduzir</h2>

### Passo 1: Instalar as Ferramentas Necessárias

Certifique-se de ter as seguintes ferramentas instaladas:

- [Visual Studio](https://visualstudio.microsoft.com/pt-br/downloads/) ou [Visual Studio Code](https://code.visualstudio.com/)
- [.NET Core SDK](https://dotnet.microsoft.com/download)

### Passo 2: Clonar o Repositório

Clone o repositório que contém a API Web ASP.NET Core. Você pode fazer isso usando o Git no terminal:

```bash
git clone https://github.com/IsaquePemasi/GeekHubApi
```

### Passo 3: Abrir o Projeto

Navegue até o diretório clonado e abra o projeto usando o Visual Studio ou o Visual Studio Code:

```bash
cd GeekHubApi
code .   # se estiver usando o Visual Studio Code
```

### Passo 4: Restaurar as Dependências

Certifique-se de que todas as dependências do projeto estão instaladas. No terminal, execute o seguinte comando:

```bash
dotnet restore
```

### Passo 5: Configurar o Banco de Dados (se necessário)

Você precisará configurá-lo, isso pode incluir a criação do banco de dados, aplicando migrações, etc. Execute os comandos apropriados, por exemplo:

```bash
dotnet ef database update
```

### Passo 6: Compilar e Executar a Aplicação

Compile e execute a aplicação para garantir que tudo está funcionando corretamente. Execute o seguinte comando:

```bash
dotnet run
```

Acesse a API em um navegador ou usando uma ferramenta como [Swagger](https://swagger.io/) para testar os endpoints.

<h2 align="center">Autor</h2>
<a href="https://github.com/IsaquePemasi/"><img src="https://avatars.githubusercontent.com/u/76749511?v=4" width=115></a>