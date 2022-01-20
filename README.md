# Projeto Docker Todo List

# Contexto
Projeto desenvolvido no primeiro bloco do módulo de backend da Trybe. Os arquivos no diretório docker-commands são as respostas para os desafios propostos pelo curso. O ultimo desafio era orquestrar através do docker compose três containers: um para o frontend, um para o backend e outro para os testes da aplicação. Os arquivos necessários para as imagens já estão no projeto, para ver a aplicação de lista de tarefas em funcionamento, siga os próximos passos do README. 

## Tecnologias usadas

Docker, docker-compose

## Instalando Dependências
Entre no diretório todo-app do projeto e execute os comandos a seguir:

```bash 
docker build -t todotests ./tests
docker build -t todofrontend ./front-end
docker build -t todobackend ./back-end
``` 

## Executando aplicação

A aplicação roda por padrão na porta 3000. Basta subir a orquestração dos containers usando
  ```
  docker-compose up -d
  ```

Para derrubar os containers execute: 
  ```
  docker-compose down
  ```

