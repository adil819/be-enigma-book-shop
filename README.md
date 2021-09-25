# be-enigma-book-shop
Using Java Springboot as a back end to provide API for front end (repo fe-book-shop). Use docker for running the project &amp; mysql

# How to run this project using maven and docker
0. Make sure you are in this project directory when running these commands through terminal/cmd
1. mvn clean package
2. docker build -t be-enigma-shop:1.0 .
3. docker-compose up -d
4. docker compose start
5. curl localhost:8080/book
