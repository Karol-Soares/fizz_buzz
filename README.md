# FizzBuzz

**Problem:**

- Multiples of 3 replaced by Fizz
- Multiples of 5 replaced by Buzz
- Multiples of 3 and 5 replaced by FizzBuzz

[1, 2, 3, 4, 5, 15] -> [1, 2, Fizz, 4, Buzz, FizzBuzz]
[1, 2, 4, 8, 10] -> [1, 2, 4, Buzz]

This feature reads a list from some file and if doesn't exist, we show an error mensage for user.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed
by adding `fizz_buzz` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:fizz_buzz, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at [https://hexdocs.pm/fizz_buzz](https://hexdocs.pm/fizz_buzz).

