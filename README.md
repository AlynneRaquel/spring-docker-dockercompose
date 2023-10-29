# spring-docker-dockercompose
Nesse projeto criei um "padrão" de uma aplicação Spring boot com Docker e Docker Compose.

Nele vamos criar a imagem da nossa aplicação utilizando Dockerfile pelo maven e vamos subir com Docker Compose. Utilizaremos tbm Wait-for-it.sh para controlar a ordem de inicialização dos Containers. Além disso, criaremos uma network própria.
Podemos também escalar nossa aplicação, subindo diversos containers, utilizaremos proxy reverso com Nginx e Redis.

##
**Imagens:**
* mysql
* eclipse-temurin
* alpine
* nginx
* redis
  
**Recursos:**
* Java - 17
* MySql 8
* Spring Boot 3.0
* Spring Session Data Redis
* Spring Web
* Spring Data JPA
* Redis
* Wait-for-it.sh 
* Nginx
* Loombok
* DevTools
