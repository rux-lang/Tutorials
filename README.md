# Rux Examples

Example projects and programming tutorials for the [Rux](https://rux-lang.dev) language.

## List of Projects

- **[Hello](Hello/)** — print "Hello, World!", the minimal Rux application
- **[Greeting](Greeting/)** — iterate over a string array and print greetings in multiple languages
- **[Primitive](Primitive/)** — declare and print all primitive types: integers, floats, booleans, and characters
- **[Factorial](Factorial/)** — calculate and print factorial values with a loop
- **[Array](Array/)** — use a dynamic array with manual memory management (`Alloc`, `Zero`, `Free`)
- **[File](File/)** — write text to a file with WinAPI (Windows only)
- **[Circle](Circle/)** — read input from stdin, parse a string to a number, and match on the result
- **[Version](Version/)** — select code at compile time with `when` and the compiler version

## Running an Example

Each example is a standalone Rux package with its own `Rux.toml`, and requires Rux 0.4.0 or newer.

```sh
cd Hello
rux run
```

If necessary, install the dependencies first:

```sh
cd Hello
rux install
rux run
```

To build and type-check an example without running it:

```sh
cd Hello
rux check
```

## License

Licensed under the [MIT License](LICENSE.md).
