# banco-api-tests

## 🎯 Objetivo

Este projeto contém a automação de testes para a [Banco
API](https://github.com/juliodelimas/banco-api).\
Os testes foram desenvolvidos em **JavaScript**, utilizando bibliotecas
populares de teste para contribuir com a qualidade da API REST.
Validando endpoints da API **Banco API**, assegurando que funcionalidades
principais atendam aos requisitos esperados.

## 🛠️ Stack Utilizada

-   JavaScript (Node.js) - Linguagem
-   [Mocha](https://mochajs.org/) - Estrutura de testes
-   [Chai](https://www.chaijs.com/) - Biblioteca de asserções
-   [Supertest](https://github.com/visionmedia/supertest) - Testes de
    integração com APIs REST, bivlioteca de requisições
-   [Mochawesome](https://github.com/adamgruber/mochawesome) -
    Relatórios de execução em HTML, biblioteca de asserções
-   [dotenv] (Gerenciamento de variáveis de ambiente)

## 📂 Estrutura do Diretório

    banco-api-tests/
    ├── test/                       # Casos de testes
    │   └── login.test.js           # Arquivos de teste
        └── transferencia.test.js   # Arquivos de teste
    ├── mochawesome-report/         # Relatórios HTML gerados automaticamente
    ├──.env                         # Arquivo para configuração da variável BASE_URL
    ├──.gitignore
    ├── package.json                # Dependências e scripts
    └── README.md                   # Documentação do projeto

## ⚙️ Arquivo `.env`

O projeto utiliza variáveis de ambiente para configuração.\
Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

    BASE_URL=http://localhost:3000

-   `BASE_URL` → URL base da API **Banco API** a ser testada.

## ▶️ Execução dos Testes

Instale as dependências:

``` bash
npm install
```

Execute os testes:

``` bash
npm test
```

## 📊 Relatórios

Após a execução, um relatório HTML é gerado automaticamente em:

    ./mochawesome-report/mochawesome.html

Abra-o no navegador para visualizar os resultados.

## 📚 Documentações das Dependências

-   [Mocha](https://mochajs.org/)
-   [Chai](https://www.chaijs.com/)
-   [Supertest](https://github.com/visionmedia/supertest)
-   [Mochawesome](https://github.com/adamgruber/mochawesome)
