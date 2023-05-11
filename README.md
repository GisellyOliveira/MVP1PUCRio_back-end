# Meu MVP

Este projeto faz parte do primeiro MVP do curso de pós-graduação em Engenharia de Software do ano de 2023, pela PUC-Rio. O Projeto consiste no desenvolvimento de uma API onde:

    - A API aponte pelo menos três rotas, onde uma delas deve implementar o método Post.
    - A API faz uso de um banco de dados SQLite ou PostgreSQL com, pelo menos, uma tabela.
    - Apresentação da documentação da API em Swagger.
    
Enquanto isso, é exigido para o fron-end:

    - O desenvolvimento de uma SPA (single page application) criativa e interativa onde sejam apresentados itens em listas.
    - Que, ao longo do código, seja feita a chamada a todas as rotas implementadas pela API.

A apresentação do MVP seguindo os requisitos citados, assim como aqueles especificados durante a disciplina, são extremamente necessários para a finalização da disciplina de Desenvolvimento Full Stack Básico.

Este projeto foi desenvolvido pela aluna Giselly da Silva Oliveira.

## Como executar 


Será necessário ter todas as libs python listadas no `requirements.txt` instaladas.
Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

> É fortemente indicado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).

```
(env)$ pip install -r requirements.txt
```

Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.

Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Abra o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.
