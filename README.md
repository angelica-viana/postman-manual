# Teste Manual de API com Postman e Swagger

Este projeto foi criado com o propósito de praticar a criação e execução de CRUD **Testes Manuais de API** dos endpoints do Swagger. Onde foi levado em consideração analisar os endpoints documentados no Swagger.

Para isso, utilizei , e executei cada operação:

🔸 GET – consultando os dados <br>
🔸 POST – criando um novo registro <br>
🔸 PUT – atualizando informações <br>
🔸 DELETE – removendo o registro <br>


## Ferramentas

- Site utilizado para gerar JSON para teste de contrato [Liquid] (https://www.liquid-technologies.com/online-json-to-schema-converter)

![Site Liquid](/img/liquid.PNG)

- Site utilizado para consulta de API [Swagger UI] (https://fakerestapi.azurewebsites.net/index.html)

![Site Swagger UI](/img/Swagger.PNG)

- Plataforma de API [Postman] (https://www.postman.com/)

![Site Postman](/img/Postman.PNG)

### Apresentação do Projeto

Na aba Collection irá encontrar a aba de nome "FakeRESTAoi.Web V1" onde irá conter todas as pastas pertencentes a ele.

![Imagem da apresentação do projeto](/img/Collections.PNG)

### Apresentando pastas e métodos executados da Collections

Na aba "FakeRESTAoi.Web V1" irá conter as pastas "Activities, Authors, Books, CoverPhotos e Users ", onde estarão localizados as requests feitas nestes endpoints:

- GET ALL: Foi efetuado testes de Status Code, tipo de retorno "se é um Array, Objeto, etc...", e contrato.

- GET ID: Foi efetuado testes de Status Code, tipo de retorno "se é um Array, Objeto, etc...", e contrato em um ID especifico.

- POST: No body criamos um novo registro. E efetuado testes de Status Code, tipo de retorno "se é um Array, Objeto, etc...", contrato e validamos a criação do novo registro.

- PUT: No body atualizamos um registro já existente. E efetuado testes de Status Code, tipo de retorno "se é um Array, Objeto, etc...", contrato e validamos a alteração que fizemos no registro.

- DEL: Efetuado testes de Status Code.

![Imagem da apresentação da pasta Activities](/img/Activity.PNG) <br> <br>
![Imagem da apresentação da pasta Authors](/img/ID.PNG) <br> <br>
![Imagem da apresentação da pasta Books](/img/POST.PNG) <br> <br>
![Imagem da apresentação da pasta CoverPhotos](/img/PUT.PNG)<br> <br>
![Imagem da apresentação da pasta Users](/img/Delete.PNG)


### Environment

Na aba Environments irá conter a aba "FakeRESTApi_test, nela contem a baseURL do site utilizado e as variaveis globais criadas durante os testes

![Imagem da apresentação do Environment](/img/environment.PNG)
