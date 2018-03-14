# trentm/json Docker Wrapper
This repo simply wraps http://trentm.com/json in an convenient Docker image.

## Alias
Creating an alias like
```shell
alias json='docker run --rm -i matthewadams12/json json'
```
is pretty darned convenient.

### Run with alias
```shell
$ echo '"foo"' | json
foo
$ echo '{"foo":"bar"}' | json foo
bar
```
etc...
