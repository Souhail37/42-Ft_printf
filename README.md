# 42-Ft_printf
42-Cursus : Ft_printf
# ft_printf - Recreating the printf Function

## Description
**ft_printf** is a library that contains the `ft_printf()` function, which is designed to mimic the original `printf()` function from the C standard library. This project involves recoding the `printf()` function in your own way.

## Table of Contents
- [Mandatory Part](#mandatory-part)
- [Bonus Part](#bonus-part)

### Mandatory Part

**Description**:
- The `ft_printf()` function is created to mimic the behavior of the original `printf()` function.

**Conversions to Implement**:
- `%c`: Prints a single character.
- `%s`: Prints a string (as defined by the common C convention).
- `%p`: The `void *` pointer argument has to be printed in hexadecimal format.
- `%d`: Prints a decimal (base 10) number.
- `%i`: Prints an integer in base 10.
- `%u`: Prints an unsigned decimal (base 10) number.
- `%x`: Prints a number in hexadecimal (base 16) lowercase format.
- `%X`: Prints a number in hexadecimal (base 16) uppercase format.
- `%%`: Prints a percent sign.

### Bonus Part

**Bonus List**:
- Manage any combination of the following flags: `-`, `0`, and the field minimum width under all conversions.
- Manage all the following flags: `#`, `+`, and space.
