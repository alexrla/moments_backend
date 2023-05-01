### Instalação
- **Criando um novo projeto:**

  ```shell
  npm init adonis-ts-app@latest nome-do-projeto
  ```

- **Estrturas de projeto:**

  - **`api`: estrutura ideal para criar um servidor de API;**



### Iniciando o servidor de desenvolvimento

```shell
node ace serve --watch
```


### lucid (ORM)
- **Utilizada para a comunicação com o banco;**
- **Oferece suporte a vários bancos SQL (MySQL, PostgreSQL, MariaDB, etc.);**
- **Instalação:**
  ```shell
  npm i @adonisjs/lucid
  ```
- **Configuração:**
  ```shell
  node ace configure @adonisjs/lucid
  ```



### Criando Model
- **Criando o model e gerando uma `migration`;**
  ```shell
  node ace make:model NomeModel -m
  ```



### Rodando a Migration
```shell
node ace migration:run     
```



### Criando Controller
```shell
node ace make:controller NomeModel
```



### Listando as rotas existentes
```shell
node ace list:routes
```