# Libft

`Libft` is a custom C standard-library subset for the 42 curriculum. It builds a static archive containing character checks, memory helpers, string helpers, conversion functions, and file-descriptor output helpers.

## What is included

From [`libft.h`](libft.h), the current library includes:

- character checks: `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`
- case conversion: `ft_toupper`, `ft_tolower`
- memory helpers: `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`, `ft_calloc`
- string helpers: `ft_strlen`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strdup`, `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_strmapi`, `ft_striteri`
- conversion helpers: `ft_atoi`, `ft_itoa`
- fd output helpers: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`
- BSD-style size helpers: `ft_strlcpy`, `ft_strlcat`

## Build

```bash
make
```

This creates:

```text
libft.a
```

## Use it in another project

```bash
cc your_program.c libft.a -I. -o your_program
```

## Project files

```text
Libft/
├── libft.h
├── ft_*.c
└── Makefile
```

## Verified during this documentation pass

- the library was rebuilt with `make`
- `libft.a` was produced successfully

## Notes

This repository is the foundation dependency that also appears inside some of the other 42 projects in this portfolio.
