# ElixirExample

Basic Elixir example app with Cowboy 2 HTTP Server & Plug.

## Installation

```bash
mix deps.get
mix run --no-halt
```

## Routes

1. `/`: 200 - Hello World
2. `/:something`: 404 - Not Found
3. `/sample/:message`: 200 - [message] 

## Running

`mix local.hex --force` 
`mix local.rebar --force`
`mix deps.get`
`mix compile`
`mix run --no-halt`
