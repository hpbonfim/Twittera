# CRUD Rails


## Estrutura API

### Users
* create
* update
* destroy
* current
* show
* following
* followers

### Tweet
* index
* show
* create
* update
* destroy

### Like
* create
* destroy

### Follow
* create
* destroy

### Search
* index

### Trending
* index

### sqlite/postgres
```
rails db:create
rails db:migrate
```

### Generate Routes
```
rails generate controller Produtos
```
### Generate Models
```
rails generate model Produtos
```
### Create Models
```
rails generate model Produtos nome: string, descricao: text, preco: decimal, quantidade: decimal
```
### Add Bootstrap
add on Gemfile: gem 'twitter-bootstrap-rails'

```
bundle install
rails generate bootstrap:install static
```
