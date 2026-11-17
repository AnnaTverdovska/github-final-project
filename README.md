# Simple Interest Calculator

[![CI](https://github.com/AnnaTverdovska/github-final-project/actions/workflows/ci.yml/badge.svg)](https://github.com/AnnaTverdovska/github-final-project/actions/workflows/ci.yml)

A small Bash script that calculates simple interest from a principal, an annual
interest rate and a time period in years. It started as the final project of the
IBM *Getting Started with Git and GitHub* course.

```
simple interest = p × r × t / 100

p  principal amount
r  annual rate of interest, in percent
t  time period in years
```

## Usage

Run it interactively and it asks for each value:

```bash
./simple-interest.sh
```

Or pass the three values as arguments:

```bash
./simple-interest.sh 1500 3.5 2
# The simple interest is: 105.00
```

Decimal values are supported; negative numbers and text are rejected.

## Running the tests

```bash
bash tests/test-simple-interest.sh
```

The same tests, plus [ShellCheck](https://www.shellcheck.net/), run on every push
and pull request through GitHub Actions.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and the
[Code of Conduct](CODE_OF_CONDUCT.md). Bug reports and feature requests can be
opened with the issue templates.

## License

[Apache License 2.0](LICENSE) © 2023 Anna Tverdovska
