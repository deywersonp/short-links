# Sistema de Encurtamento de URLS

- Repositório com configurações básicas para o Typescript baseada na versão do  Node.
https://github.com/tsconfig/bases

- Para o caso de não utilizar o Docker, podemos utilizar Postgres e Redis gratuito para conseguir uma URL e fazer o set do banco de dados.
  - Postgres Gratuito: https://neon.tech/
  - Redis Gratuito: https://upstash.com/

- Imagens do `bitnami`: As imagens do bitnami são prontas para uso em produção. Já vem com algumas questões de segurança habilitadas, como por exemplo a obrigatoriedade de iniciar o banco Redis com a utilização de senha.

### Comandos Docker
- `docker compose up -d` 
- `docker compose down` 
- `docker ps`

### Bancos de Dados
- Postgres: Utilizado para armazenar qualquer tipo de dado estruturado;

- Redis: Utilizado para armazenar dados cache. Disponibiliza os dados de maneira mais rápida. Redis não é um banco para salvar dados estruturados.

### Extensões VSCode
- Rest Client: Extensão no VSCode que permite a criação de arquivos com a extensão `.http` para execução de rotas http dentro do próprio VSCode.

- Comment tagged templates: Extensão no VSCode que permite adicionar highlight em literal strings ao comentar o tipo de dado que aquela literal string vai conter.
Ex: `await sql/*sql*/`