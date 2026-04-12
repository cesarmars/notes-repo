# Compilation and executation
**compilation**
-> gcc file.c 
gcc stands for GNU compiler collection for c programs.

If you are in vim editor, you can
-> !gcc % or !gcc file.c

The ! means vim will run a external shell, meaning a interface between user and OS.

The % is just the place holder of the file.c inside vim.

**executation**
-> ./a.out
./ means "the current directory"
a.out is just the name for the execution after compiling.

If you are in vim editor, you can
-> !./a.out 

# main function in C
Package 
-> #include <stdio.h>
Math package
-> #include <math.h>

**stdio.h** = standard input output header

Main function
->
"#include <stdio.h>
int main () {
	printf("Hello World!\n");
	return 0;
}

We return 0 after printf in our main function because "return 0" tells the program it ran
successfully. 

Another main function you can use
-> 
"#include <stdio.h>
int main(int argc, char '* argv[]) {
	printf("Hello Again.\n");
	return0;
}

int main -> a standard main function that does not takes no arguments.
int main(int argc, char '* argv[]) -> receives input, a bit more useful.

# functions
We have **main functions** as stated above.

We have **void functions**. Void functions do not return a value. It performs an action like 
printing a statement

-> void sayHi() {
	printf("Hello friend!\n");
}

We have **return type functions**. These functions return values.

-> int addition(int a, int b) {

	if (a == b) {
		return a * a;	
	}
	
	else {
		return (a + b)
	}
}


We have **structure functions**. These functions are user-defined for the purpose of
declaring variables under one functions.

-> Struct holder {
	int x;
	int y;
}

We have **constructor function**. 

->
struct Pointer {
	char name[20];
	int age;
}
// This is the contructor. You should always implement a struct function before implementing a constructor.
struct Pointer makePointer(const n[20], int a) {

	struct Pointer p;
	strcpy(p.name = n);
	p.age = a;
	return p;

}

# Characters and Strings

A **single character**

-> char letter = 'a'

A line **string of characters**

-> char name[]= "Joe Martin"

or

-> char name[20]; // a string variable of length 20.




	
