# Identicon

An app which is used to create github like profile picture.
Here we have used md5 for creating hash out of the username.


## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `identicon` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:identicon, "~> 0.1.0"}]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/identicon](https://hexdocs.pm/identicon).

Run in iex console as:

```
iex(4)> Identicon.main "mahendra"
:ok
```
You will be able to see a file named mahendra.png in the current directory.
