# fizzbuzz-cli
A CLI for [Phoenix FizzBuzz](https://github.com/simonewebdesign/phoenix-fizzbuzz)'s JSON API.

It's very simple to use: just download the `fizzbuzz` binary, put it somewhere in your machine and execute it. The only catch is, you need to have a running API on your localhost:4000.

Linux and Mac are supported.

## Synopsis

    Usage: fizzbuzz [PAGE] [LIMIT]
    Makes an HTTP request to fetch a page from the fizzbuzz sequence.

    Options:
        [PAGE]              The page number to fetch           (default: 1)
        [LIMIT]             The number of results to fetch     (default: 100)
        -h --help           Show this help text
        -v --version        Print version

    Examples:
        fizzbuzz 5          Get page 5, 100 results            (from 401 to 500)
        fizzbuzz 3 50       Get page 3, 50 results             (from 151 to 200)

    Status codes:
        0 - successful
        1 - illegal option
        2 - failed to fetch
