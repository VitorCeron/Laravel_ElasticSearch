![](https://github.com/VitorCeron/Laravel_ElasticSearch/blob/master/public/1_-4XytO_ISOE7KV11AtERhA.png)

# Projeto Laravel + ElasticSearch

### Descrição

<p> ElasticSearch é um sistema de busca distribuído e nele é possível se trabalhar com diversos tipos de dados, em sistemas de grande escala, uma alternativa para melhorar a performance das buscas é utilizando ElasticSearch. </p>

<p> Laravel é um framework muito utilizado para quem programa em PHP, tem uma comunidade gigante e entre outras coisas. E fica aqui a minha implementação de uma solução com buscas utilizando o Elastic + Laravel de maneira simples. </p>

### Demonstração

<p> Na implementação, coloquei um grau de relevância maior para o título da busca, quando buscar no Elastic, então, quando realiza o filtro pela tag, o sistema realiza uma busca normal, porém quando o sistema localiza a palavra no título, este artigo tem mais relevância do que as tags. </p>

![](https://github.com/VitorCeron/Laravel_ElasticSearch/blob/master/public/laravel.gif)

### Instalação do projeto

#### Pré Requisitos
* Xampp
* ElasticSearch
* Composer
* Laravel

#### Instalação
Clone o repositório:<br>
``` git clone https://github.com/VitorCeron/Laravel_ElasticSearch.git ``` <br><br>
Duplique o .env.example e renomeie para .env, adicione no .env a configuração do ElasticSearch <br>
```
ELASTICSEARCH_ENABLED=true
ELASTICSEARCH_HOSTS="localhost:9200"
```
Entre no diretório do projeto e instale as dependências <br>
```composer install``` <br><br>
Instalar e buildar as dependencias do bootstrap <br>
```npm install && npm run dev``` <br><br>
Inicializar o projeto <br>
```php artisan serve``` <br>
