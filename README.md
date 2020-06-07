# 42 Libft

This is a re-encoding general use C functions for 42 cursus projects

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

For the correct compilation and use of these functions we must have installed in the system the GNU GCC compiler as well as the make tool to be able to mount the library.

```
	In OS X only need to have installed Xcode, the developer IDE from Apple. Linux users, need install GCC compiler and developer tools using following commands:

	$ sudo apt install gcc
	$ sudo apt install build-essential
```

### Installing

To make this example functional we'll have to compile the library. To do this after downloading it, we'll include it in our project inside a folder named libft and execute the following command:

```
	  make all
		or
	  make re
```

## Deployment

You can use the functions contained in this library simply by adding it to your application header files, note that at compile time you will need to have the path to the libft.a file correctly included in your headers.

...
	#include "./libft/lift.h"

	int main (void)
	{
		text = "Hola";

		ft_isnumber(text);

	}
...

## Built With

* [GNU GCC](https://gcc.gnu.org) - The C Compiler used
* [Xcode](https://developer.apple.com/xcode/) - IDE GUI Editor to deploy
* [Visual Studio Code](https://code.visualstudio.com/docs/) - IDE GUI Editor to deploy
* [VIM](https://www.vim.org/download.php) - Terminal Editor to deploy
* [LLDB](https://lldb.llvm.org) - Debuger aplication

## Versioning

Version 1.0 

## Authors

* **Isaac Rodrigo** - *Initial work* - [irodrigo-42Mad](https://github.com/irodrigo-42Mad/libft)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## Acknowledgments

* To the 42 Network students and staff who made the creation of this code possible.

