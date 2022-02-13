### Inicializar o projeto
- yarn init -y

### Instalar o Express
- yarn add express

### Instalar o Nodemon e Sucrase 
- yarn add nodemon sucrase -D

### Instalar o Eslint (padrões dos códigos)
- yarn add eslint -D

### Instalar o Prettier
- yarn add prettier

### Ligar o Prettier e o Eslint
- yarn add prettier eslint-config-prettier eslint-plugin-prettier - D

### Pradonizar todos os arquivos já gerados
- yarn eslint --fix src --ext .js

### Instalar o Sequelize
- yarn add sequelize

### Instalar o Sequelize CLI (interface de linhas de comando)
- yarn add sequelize-cli -D

### Instalar a biblioteca PG e PG-Hstore
- yarn add pg pg-hstore

### Criar uma migration no banco de dados (users é o nome da tabela)
- yarn sequelize migration:create --name=create-users

### Rodar a migration
- yarn sequelize db:migrate

### Instalar a biblioteca para criptografar as senhas
- yarn add bcrypt js

### Instalar a biblioteca para autenticação de usuários
- yarn add jsonwebtoken

### Instalar Yup - trabalhar com validações
- yarn add yup

### Instalar o Cors
- yarn add cors

### Rodar o projeto 
- yarn dev