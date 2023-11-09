<h1 align="left">
  0x16. C - Simple Shell
</h1>



## Environment:

this project is built and tested on Ubuntu 14.04 LTS.

## Available Commands
This shell has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| ls [dir]            | List the content of the present working dir                                               |
| cd [dir]            | Change the directory.                                                                     |
| env                 | Print the environment.                                                                    |
| setenv [var][value] | Set an environment variable and value. If the variable exists, the value will be updated. |
| alias[name[='value]]| Reads aliases name                                                                        |
| unsetenv [var]      | Remove an environment variable.                                                           |
| help [built-in]     | Read documentation for a built-in.                                                        |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| pwd [dir]           | Prints the present working directory                                                      |


## Usage
  
  ```
  git clone https://github.com/harbiehorla/simple_shell
  ```

- Create an executable by running the following command:
- `gcc -Wall -Werror -Wextra -pedantic *.c -o (output file name)`
- From there, type in the following command and press your enter button.
- `./the name og the file use choosed`


## Example

  ```
  gcc -Wall -Werror -Wextra -pedantic *.c -o test

  ./test

  pwd
  ```

## sample usage

[smaple Usage](simpleshell.mp4)
