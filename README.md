# libft

## 📖 About

**libft** is the first project in the 42 School curriculum. The goal of this project is to build a C library from scratch by reimplementing commonly used functions from the C standard library and creating additional utility functions.

The project provides a better understanding of fundamental C concepts such as memory management, string manipulation, pointers, dynamic memory allocation, and linked lists. The resulting library can also be reused throughout future projects in the 42 curriculum.

## ⚙️ Content & Functions

The library is divided into three main categories:

### 1. Libc Functions

Reimplementations of commonly used C standard library functions with behavior similar to their original counterparts.

**Character Checks**

- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`

**Memory Operations**

- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_memchr`
- `ft_memcmp`
- `ft_calloc`

**String Operations**

- `ft_strlen`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_strnstr`
- `ft_strdup`

**Conversions & Other Utilities**

- `ft_toupper`
- `ft_tolower`
- `ft_atoi`

### 2. Additional Functions

Additional utility functions that are useful throughout the 42 curriculum.

- `ft_substr` — Creates a substring from a given string.
- `ft_strjoin` — Concatenates two strings into a newly allocated string.
- `ft_strtrim` — Removes specified characters from the beginning and end of a string.
- `ft_split` — Splits a string into an array of strings using a delimiter character.
- `ft_itoa` — Converts an integer to a string.
- `ft_strmapi` — Creates a new string by applying a function to each character.
- `ft_striteri` — Applies a function to each character of a string.
- `ft_putchar_fd` — Writes a character to a given file descriptor.
- `ft_putstr_fd` — Writes a string to a given file descriptor.
- `ft_putendl_fd` — Writes a string followed by a newline to a given file descriptor.
- `ft_putnbr_fd` — Writes an integer to a given file descriptor.

### 3. Linked List Functions (Bonus)

Functions for creating and manipulating singly linked lists.

- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstadd_back`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`

## 🚀 Getting Started

### Prerequisites

You will need:

- A C compiler such as `cc` or `gcc`
- `make`

### Compilation

Clone the repository and enter the project directory:

```bash
git clone <repository-url>
cd libft
```

Compile the mandatory part:

```bash
make
```

Compile the bonus part:

```bash
make bonus
```

Other available commands:

```bash
make clean    # Remove object files
make fclean   # Remove object files and libft.a
make re       # Recompile the library
```

After compilation, the `libft.a` static library will be generated.

## 💻 Usage

Include the header file in your C source file:

```c
#include "libft.h"
```

Then compile your program and link it with `libft.a`:

```bash
cc -Wall -Wextra -Werror main.c -L. -lft -I. -o program
```

Run the program:

```bash
./program
```

## 🛠️ Built With

- C
- Make
- GCC / CC

## 🎓 42 Project

This project was developed as part of the curriculum at **42 School**.
