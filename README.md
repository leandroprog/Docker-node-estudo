# Estudo

## Comandos
- Cria uma imagem usando o Dockerfile:
  * docker build -t estudo/dockernode .
- Cria um container apartir da imagem criada
  * docker run -p 3000:3000 -d estudo/dockernode
