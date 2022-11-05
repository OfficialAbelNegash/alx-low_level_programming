# 0x09. C - Static libraries

## Description

0-Create the static library libmy.a containing all files given:

| **Steps on CLI**

_gcc -Wall -pedantic -Werror -Wextra -std=gnu89 -c _.c |
ar -rc libmy.a \*.o |

1 - Create a script called create_static_lib.sh that creates a static library called liball.a from all the .c files that are in the current directory.
