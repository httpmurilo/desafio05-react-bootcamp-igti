Projeto do desafio do Bootcamp do Instituto de Gestão e Tecnologia da Informação.

- A API foi criada com NodeJS.
- O Projeto do Front-End é em ReactJS.

### Instalação

É necessário [Node.js](https://nodejs.org/) v6 para execução e para o front-end o [Yarn](https://yarnpkg.com/).

Instalando as dependências para iniciar as aplicações;

```sh
$ git  clone https://github.com/httpmurilo/desafio05-react-bootcamp-igti.git
$ cd Source.Api && npm install && npm start
```

Para o front ;

```sh
$ git  clone https://github.com/httpmurilo/desafio05-react-bootcamp-igti.git
$ cd Source.Web && npm install && yarn start
```


Atividades

1. Implementar, utilizando React, uma aplicação denominada "react-salario" que
possuirá um input editável e diversos outros inputs somente-leitura para exibir
informações sobre o cálculo de salário conforme as leis da CLT em 2020. Só
devem ser considerados os cálculos de desconto de INSS e IRPF, ou seja, outros
descontos e dependentes devem ser ignorados. Os valores a serem exibidos são:

    -  Salário bruto (editável pelo usuário).
    -  Base INSS (somente-leitura).
    -  Desconto INSS (somente-leitura).
    -  Base IRPF (somente-leitura).
    -  Desconto IRPF (somente-leitura).
    -  Salário líquido (somente-leitura)

