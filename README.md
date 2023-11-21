# Elixir Bumblebee - Text analysis


https://huggingface.co/blog/elixir-bumblebee

## Setup for WSL (Debian)

```shell
sudo apt install elixir erlang-dev erlang-xmerl
sudo apt install build-essential
elixir -v
```

### Generate the app
```
mix local.hex
mix archive.install hex phx_new
mix phx.new hello --no-ecto
```

# Start the app
To start your Phoenix server:

  * Run `mix setup` to install and setup dependencies
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

