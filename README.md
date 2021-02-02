# Desafio Imersão Full Stack && Full Cycle

## Informações do desafio
Nesse desafio você deverá montar seu ambiente de desenvolvimento com Docker utilizando o Dockerfile e docker-compose de nosso projeto prático.

Crie uma struct de User com ID (uuid), Name e Email. Além disso, implemente uma função NewUser que seja capaz de validar que ID, Name e Email são obrigatórios, caso o contrário, ela deve retornar um erro.

## Instruções

- Para rodar os serviços com Docker:
`docker-compose up -d`

- Para acessar o container da aplicação: 
`docker exec -it imersao-fullstack-fullcycle_app_1 bash`
