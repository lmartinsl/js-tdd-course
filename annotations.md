# js-tdd-course
**Curso sobre Testes na prática**

### Inicializar projeto Git 
- git init

### Configuração npm
- npm set init-author-name "name"
- npm set init-email "email"
- npm set init-author-url "url"
- npm set init-license "license"

### Login 
- npm adduser
- Digitar userName criado
- Digitar password
- Digitar email (Público)

### Lançar pacote 
- npm publish

### Inicializar lib 
- npm init
- Criar package

### Pacote gitignore 
- npm install gitignore -g
- gitignore -types (*Listagem dos tipos*)
- gitignore rails

### Instalação ESLint
- npm install eslint --save-dev ``Localmente``
- ./node_modules/.bin/eslint --init ``Inicialização do ESLint``

### Buscar por erros em todo arquivo .js dentro de ./src
- ./node_modules/.bin/eslint src/*.js

### Husky
- Husky é um script que permite criar hooks do git de maneira mais fácil
- Hooks(Gancho): Scripts que rodam antes de alguma tarefa do git, podendo ser antes ou depois
- npm install husky --save-dev
- lista de scripts do husky: [LISTA](https://github.com/typicode/husky)