# Desafio Fullcycle 3.0 Nginx e Nodejs

A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:

```html
<h1>Full Cycle Rocks!</h1>
```

- Lista de nomes cadastrados no banco de dados.

# Executando o projeto

Para rodar o projeto execute o seguintes comandos

dentro da pasta node

```bash
npm install
```

na raiz do projeto

```bash
docker compose up -d
```

# Acessando a aplicação

OBS: caso apresente erro 502, aguarde mais alguns segundos e atualize a página.
[http://localhost:8080/](http://localhost:8080/)
