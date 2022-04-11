# ExChat :: Phoenix
A small Phoenix Web Application to communicate with your friends.

> ## 🙇🏻 Why?
Working with Phoenix and Elixir (+ Websockets in this example) is fun, why not? :D

> ## 👼🏻 How?

```
$ git clone https://github.com/vKxni/exchat
$ cd exchat
$ code . 
```

Make sure to rename `dev.example` (config folder) to `dev.exs` and fill out your database informations.

> Commands

```elixir 
$ mix deps.get # install dependencies
```
```elixir 
$ mix test # runs all the test (make sure db is running)
```
```elixir
$ mix ecto.create # creates the database table
```

```elixir
$ mix ecto.migrate # migrate the database
```