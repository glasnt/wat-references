# Elixir

[elixir-lang.org](https://elixir-lang.org/)

## Run these examples yourself

### docker

```
# Run the launch helper for the current directory
. ../launch ${PWD##*/}
```

### macOS

```
brew install elixir
iex
```

# Strings are just lists of characters

[The Definitive All Dancing, All Complete, "WTF Happened to my nice list of integers in Elixir?" Post, cursingthedarkness.com](http://www.cursingthedarkness.com/2015/10/the-definitive-all-dancing-all-complete.html)

> The reason Elixir has this logic in it's List Inspect implementation is that Elixir is built on top of Erlang and all Erlang functions are perfectly valid Elixir functions. This is
one of the great strengths of Elixir. Elixir users get 20+ years of solid software engineering that is used to manage a large percentage of the world's cell phone traffic. Unfortunately, this comes with a price. 

https://hexdocs.pm/elixir/1.12/Inspect.Opts.html

> When the default :infer, the list will be printed as a charlist if it is printable, otherwise as list. See List.ascii_printable?/1 to learn when a charlist is printable.

https://hexdocs.pm/elixir/1.12/List.html#ascii_printable?/1

> A printable charlist in Elixir contains only the printable characters in the standard seven-bit ASCII character encoding, which are characters ranging from 32 to 126 in decimal notation, plus the following control characters:



