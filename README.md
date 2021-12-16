<h1>Web API - Contos Pizza</h1>

<p>Projeto de api para estudos utilizando .Net 6* e C#.</p>
<p>Com a utilização da manipulação dos dados estáticos.</p>

<h3>Dependências</h3>

  - [.Net 6](https://dotnet.microsoft.com/en-us/download/dotnet/6.0)
  

<h3>Utilização</h3>

- Realize o clone do projeto:
    ```bash 
        git clone https://github.com/paulocfj/contos_pizza_WebAPI.git
    ```
- Realize a utualização dos pacotes do projeto:
    ```bash
        dotnet restore
    ```
-  Realize o primeiro compilação do projeto:
    ```bash
        dotnet build
    ```
- Rode o projeto:
    ```bash
        dotnet run
    ```
    O projeto será inicializado na porta 5156, http://localhost:5156

<h3>Rotas</h3>
  
- /Weatherforecast [GET]
- /pizza [GET] [GET{id}] [POST] [PUT{id}] [DELETE]

<h3>Curso</h3>

- Curso tutorial disponibilizado pela a [microsoft learn](https://docs.microsoft.com/pt-br/learn/)