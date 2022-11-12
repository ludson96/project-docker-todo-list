
# Projeto Docker To-do list 

Neste projeto foi feito a conteinerização de aplicações, criação de uma conexão entre elas e orquestrar o seu funcionamento.

Foram criados dois arquivos dockerfiles 1 para aplicação front-end e outro para back-end.

Também criei as imagens para as aplicações e configurei essas imagens com o docker-compose, assim, conectando front-end, back-end e os testes.

O front-end foi fornecido pela Trybe (HTML e CSS)






## Aprendizados

Criação de conteirização para um ambiente front-end e back-end usando a imagem `node:14-alpine`; e

Utilização da conteirização através do docker-compose para conecção do front-end, back-end e testes.



## Uso/Exemplos
Ao fazer o clone do projeto, utilize o seguinte comando para instalar as dependencias necessárias:

```
npm install
```

Entre na pasta ```docker```:

```
cd docker
```
Para executar o container, utilize o seguinte comando (sendo a flag -d para executar em segundo plano):
```
docker-compose up -d
```

##

#### Primeiro projeto usando MySQL

##

> Aplicação em execução fornecida pela Trybe
