# HeatTags

Para a criação deste projetos se utilizaram as seguintes tecnologias:

- Postgresql
- Elixir
- Phoenix
- Visual Studio Code

Rodando o projeto :

  * Instalar as dependências com `mix deps.get`
  * Criar e migrar o banco de dados com `mix ecto.setup`
  * Rodar o endpoint de Phoenix com `mix phx.server` ou dentro do Elixir interativo (IEx) `iex -S mix phx.server`

O porto está configurado em -> [`localhost:4000`](http://localhost:4000)

Rotas:

*POST* - /api/message
Registra um username, um email e uma mensagem
- exemplo de body:
```
{
  "username": "elixir test",
  "email": "test@elixir.com",
  "message": "mensagem elixir"
}
```
