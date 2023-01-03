# Repositório do projeto Docker To-do list 

 ## Módulo: BACK-END
 
  Repositório possui projeto desenvolvido no período que estive na <b>Trybe</b>, abordando os conceitos de conteinerização utilizando o docker. 
  
## Informações de aprendizados

- Este é um projeto desenvolvido para me ajudar a aprender `Docker`.
- Utilização da conteinerização através do docker-compose para conexão do front-end, back-end e testes.
- Meu primeiro projeto utilizando `conteinerização com docker`.

## Linguagem usadas

[![Docker][Docker-logo]][Docker-url]

## O que foi desenvolvido

Foram criados dois arquivos dockerfile 1 para aplicação front-end e outro para back-end.

Também criei as imagens para as aplicações e configurei essas imagens com o docker-compose, assim, conectando front-end, back-end e os testes.

> O front-end foi fornecido pela Trybe (HTML e CSS)

## Instruções para instalar e rodar

1. Clone o repo:
```
  git clone git@github.com:Ludson96/project-docker-todo-list.git
```
2. Instale as suas dependências:
```
  npm install
```
Entre na pasta ```docker```:

```
cd docker
```
3. Para executar o container, utilize o seguinte comando (sendo a flag -d para executar em segundo plano):
```
docker-compose up -d
```

### Observação

Dentro da pasta `docker/docker-commands` tem todos os comandos referentes aos requisitos propostos pela Trybe.

<details>

  - 1. Crie um container em modo interativo, sem rodá-lo, nomeando-o como `01container` e utilizando a imagem `alpine` na versão `3.12`

  ---

  - 2. Inicie o container `01container`

  ---

  - 3. Liste os containers filtrando pelo nome `01container`

  ---

  - 4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele

  ---

  - 5. Remova o container `01container`

  ---

  - 6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container

  ---

  - 7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro

  ---

  - 8. Pare o container `02images` que está em andamento

  ---

  - 9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`

  ---

  - 10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`

  ---

  - 11. Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`

  ---

  - 12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar

  ---
  
</details>



> Aplicação em execução fornecida pela Trybe

[Docker-logo]: https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white
[Docker-url]: https://www.docker.com