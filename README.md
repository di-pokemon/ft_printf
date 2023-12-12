# ft_printf
This project involved recreating the well-known C library function, printf. This provided a valuable learning opportunity in variadic arguments and structures, particularly if we intend to incorporate additional flags into our implementation of print.

## HOW TO USE
#### 1º - Clone the repository
```git
git clone git@github.com:di-pokemon/ft_printf.git
```

#### 2º - Enter the project folder and run `make`
```bash
cd ft_printf/ft_printf
make
```

#### 3º - To use in your code, include the header
```c
#include "ft_printf.h"
```

#### MAKEFILE RULES

`make` or `make all` - Compile ft_printf files.

`make clean` - Delete all .o (object files) files.

`make fclean` - Delete all .o (object files) and .a (executable) files.

`make re` - Use rules `fclean` + `all`.