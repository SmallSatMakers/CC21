# The C with Classes 2021 (CC21) Standard
C with Classes is a standard developed to allow for the utility and functionality of C++ classes while also maintaining the simplicity and readability of C. CC21 is targeted towards embedded systems.

# Authors
Mit Bailey  
Sunip K. Mukherjee  

# Requirements
- CC programs must be compiled using C++11.
- No C++ (.hpp) headers may be included; only C libraries and/or headers (such as stdio.h) may be used.
- C11-compliant header code files must use the .h file extension.
- C11-compliant source code files must use the .c file extension.
- CC21 source code files must use the .cc file extension.
- CC21 header code files must use the .hcc file extension.

# Recommendations

## Formatting

Below are listed types of formatting with examples and use cases.

__snake_case__
- Variables  
`int my_int;`

- Functions  
`void my_function(...) {...}`

- Type-Defined Variables (requires _t suffix)  
`typedef uint8_t byte_t;`

- Type-Defined Struct (requires _t suffix)  
`typedef struct {...} my_struct_type_t;`

__UPPER_SNAKE_CASE__
- Constants  
`const int MY_CONSTANT = 0;`

- Hash-Defines  
`#define SOME_VALUE 42`

__camelCase__
- Class Objects  
`MyClass classObject;`

- Class Variables  
`int myInt;`  
`classObject.someValue;`

__PascalCase__
- Class Names  
`class MyClass {...};`


- Methods (Class Functions)  
`int GetValue(...) {...}`  
`classObject.GetValue(...);`  
`MyClass::SomeOperation(...);`

# Best Practices