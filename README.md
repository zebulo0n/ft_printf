*This project has been created as part of the 42 curriculum by zoeschne.*

# ft_printf

A re-implementation of  `printf` using variadic functions as a static library.

## Supported conversions

`%c` `%s` `%p` `%d` `%i` `%u` `%x` `%X` `%%`

## Usage

```sh
make   # builds libftprintf.a
cc main.c -L. -lftprintf
```
