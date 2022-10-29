# Scex

A simple runner for npm scripts that can execute multiple scripts, in serial or in parallel.

## Install

```sh
npm install -g scex
```

## Usage

Execute multiple npm scripts in serial:

```
scex foo bar baz
```

Execute multiple npm scripts in parallel:

```
scex -p foo bar baz
```

## License

MIT © Fabio Spampinato
