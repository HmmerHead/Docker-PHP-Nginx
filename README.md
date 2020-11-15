## Pratica Docker

Um simples projeto docker. O intuito é realizar uma simples integração entre dois conteiners.

Um container Nginx, e um container utilizando um microframework PHP (Slim).

Para atualizar o vendor

```bash
composer install
```

Criar a Imagem

```bash
docker-compose up --build -d
```

