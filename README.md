
# Setup Docker Para Projetos Laravel

### Passo a passo
Clone Repositório



Alterne para a branch laravel 9.x
```sh
git checkout laravel-9-com-php-8
```


Remova o versionamento (opcional)
```sh
rm -rf .git/
```


Crie o Arquivo .env
```sh
cp .env.example .env
```



Suba os containers do projeto
```sh
docker-compose up -d
```


Acesse o container app com o bash
```sh
docker-compose exec app bash
```


Instale as dependências do projeto
```sh
composer install
```


Gere a key do projeto Laravel
```sh
php artisan key:generate
```


