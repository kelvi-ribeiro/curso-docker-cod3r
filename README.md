# Docker: Ferramenta essencial para Desenvolvedores

Este repositório possui os exercícios e projetos feitos no curso ministrado pelo Instrutor  [Leonardo Leitão](https://www.udemy.com/user/leonardomouraleitao/) - [Link do Curso](https://www.udemy.com/curso-docker/).


## Comandos do Docker
| Comando | O que faz ?
|---|--|
| `docker container run {image}`| Esse comando baixa a imagem não tiver no cache local do host local, cria o Container a partir dessa imagem, cria o container e executa o container de forma interativa. Comandos implícitos que são executados pelo `docker container run {iamge}`. 1-`dokcer image pull {image}`. 2-`docker container create`. 3-`docker container start`. 4-`docker container exec`.|
| `docker-compose up -d --sclare {service}={instanceNumber}` | Comando para subir um conjunto de servies num arquivo docker-compose.yml e definir quantas instâncias o service vai ter |
| `docker-compose logs -f -t` | Comando para ver os logs gerados de todos os services de uma forma interativa |
| `docker-compose logs -f -t {serve}` | Comando para ver os logs de um service específico de uma forma interativa |