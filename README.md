# Identicon

Small Elixir program that generates and stores identicons based on a string.

## Installation

Clone the repo and in the project directory run:
```bash
$ mix deps.get
```

Then to run the project:
```bash
$ iex -S mix
```

Once in the iex console run:
```bash
iex> Identicon.generate(<input_string>)
```
This will generate an identicon based on the input_string and will persist the image in the `priv` directory with the filename same as tje input string.
