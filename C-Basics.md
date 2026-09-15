# C Basics

## 1. Data Types

| Data Type | Description |
|---|---|
| `int` | Used to store whole numbers without decimal values. |
| `float` | Used to store decimal numbers with single precision. |
| `double` | Used to store decimal numbers with higher precision than `float`. |
| `char` | Used to store a single character. |
| `bool` | Used to represent Boolean values such as true or false. |
| `void` | Represents the absence of a value or data type. |

## 2. Format Specifiers

| Format Specifier | Description |
|---|---|
| `%d` | Used to display a signed decimal integer. |
| `%u` | Used to display an unsigned decimal integer. |
| `%o` | Used to display an integer in octal format. |
| `%x` | Used to display an integer in hexadecimal format using lowercase letters. |
| `%X` | Used to display an integer in hexadecimal format using uppercase letters. |
| `%f` | Used to display a floating-point value in decimal notation. |
| `%e` | Used to display a floating-point value in scientific notation. |
| `%c` | Used to display a single character. |
| `%s` | Used to display a string of characters. |
| `%ld` | Used to display a long integer. |

## 3. Input/Output Functions

### scanf()

`scanf()` is used to take formatted input from the user. It reads values according to the format specifier provided.

### printf()

`printf()` is used to display formatted output on the screen. It can display integers, floating-point values, characters, and strings.

### getchar()

`getchar()` reads a single character from the standard input.

### putchar()

`putchar()` displays a single character on the screen.

### fgets()

`fgets()` is used to read a line of text or a string from the input. It can read spaces within the input.

### puts()

`puts()` displays a string on the screen and automatically moves the cursor to a new line.

## 4. Escape Sequences

Escape sequences are special character combinations that begin with a backslash (`\`) and are used to represent special characters or formatting.

| Escape Sequence | Meaning | Example |
|---|---|---|
| `\n` | New line | `printf("Hello\nWorld");` |
| `\t` | Horizontal tab | `printf("Name:\tAli");` |
| `\"` | Double quotation mark | `printf("He said \"Hello\"");` |
| `\\` | Backslash | `printf("C:\\Program");` |
| `\'` | Single quotation mark | `printf("\'A\'");` |

## 5. Precision

Precision is used to control the number of digits displayed after the decimal point for floating-point values.

It is specified by placing a dot followed by the required number of digits between `%` and the format specifier.

For example:

```c
printf("%.2f", VALUE);
printf("%.4f", VALUE);
printf("%.6f", VALUE);
