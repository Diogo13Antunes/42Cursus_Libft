# Libft

The project aims to create a C library that can be utilized in future projects.

See the [subject](./subject.pdf) for more information.

## Table of Contents (TOC)

- [What is Libft?](#what-is-libft)
- [What's in it?](#whats-in-it)
  - [Libc Functions](#libc-functions)
  - [Additional Functions](#additional-functions)
  - [Bonus Functions](#bonus-functions-functions-for-linked-list-manipulation)

## What is Libft?

Libft is an individual project at 42 that requires us to re-create some standard C library functions including some additional ones that can be used later to build a library of useful functions for the rest of the program.

## What's in it?

### Libc Functions

Some of the standard C functions

- ft_memset
- bzero
- memset
- memcpy
- memccpy
- memmove
- memchr
- memcmp
- strlen
- strdup
- strcpy
- strncpy
- strcat
- strlcat
- strchr
- strrchr
- strstr
- strnstr
- strcmp
- strncmp
- atoi
- isalpha
- isdigit
- isalnum
- isascii
- isprin
- touppe
- tolowe

### Additional functions

- ft_memdel
- ft_memalloc
- ft_strnew
- ft_strdel
- ft_strclr
- ft_striter
- ft_striteri
- ft_strmap
- ft_strmapi
- ft_strequ
- ft_strnequ
- ft_strsub
- ft_strjoin
- ft_strtrim
- ft_strsplit
- ft_itoa
- ft_putchar
- ft_putstr
- ft_putendl
- ft_putnbr
- ft_putchar_fd
- ft_putstr_fd
- ft_putendl_fd
- ft_putnbr_fd

### Bonus Functions: Functions for linked list manipulation

- ft_lstdelone
- ft_lstnew
- ft_lstdel
- ft_lstadd
- ft_lstiter
- ft_lstmap

## How does it Work?

1. Clone the repository.

   ``git clone git@github.com:Diogo13Antunes/42Cursus_Libft.git``

2. Go to the repository.

   ``cd 42Cursus_Libft``

3. Create the library.

   ``make``

4. Execution

   ``gcc example_main.c libft.a``

## License

Check all the terms [here](/LICENSE).
