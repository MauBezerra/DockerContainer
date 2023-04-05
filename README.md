Estudo sobre containers em Docker:

Alguns dos principais comandos do Docker incluem:

- docker run: Cria um novo contêiner a partir de uma imagem e inicia a execução do contêiner.
- docker build: Cria uma nova imagem a partir de um arquivo Dockerfile.
- docker pull: Baixa uma imagem do registro do Docker.
- docker push: Envie uma imagem para o registro do Docker.
- docker ps: Lista todos os contêineres em execução no host do Docker.
- docker stop: Para a execução de um contêiner.
- docker start: Inicia a execução de um contêiner que foi parado anteriormente.
- Parar todos os containers: docker stop $(docker container ls -q)
- docker rm: Remove um ou mais contêineres.
- docker rmi: Remove uma ou mais imagens.
- docker history: Mostra todas as camadas de uma imagem
- docker inspect: Motra detalhes sobre uma imagem 
- docker login: Login no portal docker hub

#########################################################################################

Imagens são read only (imutavel)
Container é uma camada temporaria em cima da imagenes, por esse motivo os containers são tão leves.

