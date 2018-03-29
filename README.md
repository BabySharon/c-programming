## C Programming in Linux
To run a program you need to have a compiler. Fortunately the C compiler can be found in the **[GNU Compiler Collection](https://en.wikipedia.org/wiki/GNU_Compiler_Collection)** or **GCC**. 
Follow these steps to use Linux for coding in C

### 1. Install GNU C Compiler

If you are using Fedora, Red Hat, CentOS, or Scientific Linux, use the following yum command to install GNU c/c++ compiler:
```
# yum groupinstall 'Development Tools'
```
If you are using Debian or Ubuntu Linux, type the following apt-get command to install GNU c/c++ compiler:
```
$ sudo apt-get update
$ sudo apt-get install build-essential manpages-dev
```

### 2. Code :)

Open any editor and type your program. Save your program with `.c` extension.

### 3. Compilation

Type the following command in terminal to compile your program.
```
gcc program-source-code.c -o executable-file-name
```
This command will invoke the GNU C compiler to compile the file program-source-code.c and output (-o)
the result to an executable called executable-file-name.

### 3. Execution

Type the command
```
./executable-file-name.
```

**_Let's see a simple example: Program to add two numbers_**

```
#include<stdio.h>
void main()
{
int a=3,b=7,c;
c = a+b;
printf("Sum = %d",c);
}
```

**_Output_**
```
Sum = 10
```

PS: If you are a beginner in c programming and want to learn more, [go through this pdf](http://windegger.org/docs/c-programming-in-linux.pdf)
