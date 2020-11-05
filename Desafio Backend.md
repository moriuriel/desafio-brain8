<img alt="GoStack" src="https://cdn.discordapp.com/attachments/773905846903635978/773906429357719552/brain-logo-horizontal-branca.png" width="450"/>

# Brain 8 - Desafio Backend

### Sobre o desafio: 

Nesse desafio, você estará criando uma aplicação utilizando Node.js, TypeScript e uso de banco de dados com o TypeORM

Essa aplicação deve permitir que o usuário consiga realizar as operações de **CRUD** do pokemon

### Template da aplicação

Para te ajudar nesse desafio, criamos para você um modelo que você deve utilizar como um template do Github.

O template está disponível na seguinte url: **[Acessar Template](https://github.com/moriuriel/desafio-backend-brain8)**

Agora navegue até a pasta criada e abra no Vs Code, lembre-se de executar o comando `yarn` no seu terminal para instalar todas as dependências.

### Rotas da aplicação: 

- **`POST /pokemon`**: Essa rota deve receber os `id`, `nome`, `type`, `mais dois atributos de sua escolha`. Ao cadastrar um novo pokemon, ele deve ser armazenado dentro do seu banco de dados e deve ser retornado o pokemon

- **`GET /pokemon`**: Essa rota deve retornar uma lista com todos os pokemon cadastrados no banco de dados

- **`GET /pokemon/:id`**: Essa rota deve receber como parametro o id e retornar o pokemon especifico

- **`PUT /pokemon/:id`**: Essa rota deve receber o id como parametro e no corpo da requisição os dados do pokemon e retornar os dados do pokemon atualizado

- **`DELETE /pokemon/:id`**: Essa rota deve receber o id como parametro e retornar uma resposta vazia

## Entrega

Esse desafio deve ser entregue até o dia 12/11/2020 ás 18:00, envie o link do repositório que você fez suas alterações via e-mail ou whatsapp.

### Links úteis

- [TypeORM](https://typeorm.io/#/)
- [Postgresql](https://www.postgresql.org/docs/)
- [Pokedex](https://pokeapi.co/)