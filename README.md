# Cards

A small app that creates a deck, shuffles it and deals a hand. It lets you save your current hand to a file and load it later.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add `cards` to your list of dependencies in `mix.exs`:

    ```elixir
    def deps do
      [{:cards, "~> 0.1.0"}]
    end
    ```

  2. Ensure `cards` is started before your application:

    ```elixir
    def application do
      [applications: [:cards]]
    end
    ```
