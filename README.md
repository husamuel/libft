# Libft

<img width="1920" height="1126" alt="image" src="https://github.com/user-attachments/assets/853a2263-2e31-44d7-bc73-61ba63a0359b" />


Welcome to **Libft**, my first project as a cadet at 42. This project is a C function library that implements common and useful functionalities, recreating some standard libc functions and adding custom ones. The library is divided into two parts: **Mandatory** and **Bonus**.

## How to Compile?

To compile the library and generate the `libft.a` file, use the provided Makefile with the following commands:

```bash
make
make clean
```

- `make`: Compiles all functions and creates the `libft.a` file.
- `make clean`: Removes object files generated during compilation.

To fully recompile, you can use:
```bash
make fclean
make
```

## Project Structure

The library is organized into two parts:

### Mandatory

This section contains essential functions that recreate standard libc functionalities, along with other utilities:

| Function      | Description                                                                                   |
|---------------|-----------------------------------------------------------------------------------------------|
| ft_atoi       | Converts an ASCII string to an integer.                                                       |
| ft_bzero      | Fills a string with zeros.                                                                    |
| ft_calloc     | Allocates memory and fills it with NULL.                                                      |
| ft_isalnum    | Checks if a character is alphanumeric.                                                         |
| ft_isalpha    | Checks if a character is a letter.                                                            |
| ft_isascii    | Checks if a character is ASCII.                                                               |
| ft_isdigit    | Checks if a character is a digit.                                                             |
| ft_isprint    | Checks if a character is printable.                                                           |
| ft_itoa       | Converts an integer to an ASCII string.                                                       |
| ft_memchr     | Searches for the first occurrence of a character in the first n bytes of a string.            |
| ft_memcmp     | Compares the first n bytes of two strings.                                                    |
| ft_memcpy     | Copies the first n bytes from one string to another.                                          |
| ft_memmove    | Copies the first n bytes from one string to another, handling memory overlap safely.          |
| ft_memset     | Copies a character to the first n bytes of a string.                                          |
| ft_putchar_fd | Writes a character to the specified file descriptor.                                          |
| ft_putendl_fd | Writes a string with a newline to the specified file descriptor.                              |
| ft_putnbr_fd  | Writes an integer to the specified file descriptor.                                           |
| ft_putstr_fd  | Writes a string to the specified file descriptor.                                             |
| ft_split      | Splits a string into multiple substrings based on a delimiter.                                |
| ft_strchr     | Locates the first occurrence of a character in a string.                                      |
| ft_strdup     | Creates a copy of the input string.                                                           |
| ft_striteri   | Applies a function to each character of a string, with its index.                             |
| ft_strjoin    | Concatenates two strings into a new string.                                                   |
| ft_strlcat    | Concatenates two strings with a limited size.                                                 |
| ft_strlcpy    | Copies a defined number of bytes from one string to another.                                  |
| ft_strlen     | Returns the length of a string.                                                               |
| ft_strmapi    | Applies a function to each character of a copy of the input string.                           |
| ft_strncmp    | Compares the first n characters of two strings.                                               |
| ft_strnstr    | Locates the first occurrence of a substring in a string.                                      |
| ft_strrchr    | Locates the last occurrence of a character in a string.                                       |
| ft_strtrim    | Removes characters from a set from the start and end of a string.                             |
| ft_substr     | Creates a substring starting from a given index with a maximum length.                        |
| ft_tolower    | Converts uppercase letters to lowercase.                                                      |
| ft_toupper    | Converts lowercase letters to uppercase.                                                      |

### Bonus

This section includes additional functions for manipulating linked lists:

| Function        | Description                                                                                   |
|-----------------|-----------------------------------------------------------------------------------------------|
| ft_lstadd_back  | Adds a new element to the end of a list.                                                      |
| ft_lstadd_front | Adds a new element to the beginning of a list.                                                |
| ft_lstclear     | Removes the current element and all subsequent elements from a list.                          |
| ft_lstdelone    | Removes a single element from a list using a deletion function.                                |
| ft_lstiter      | Applies a function to the content of each element in a list.                                  |
| ft_lstlast      | Returns the last element of a list.                                                           |
| ft_lstmap       | Applies a function to the content of each element in a copy of a list.                        |
| ft_lstnew       | Creates a new list element.                                                                   |
| ft_lstsize      | Returns the size of a list.                                                                   |
