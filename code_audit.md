# Audit C Program
## C language review
* .c file is C source code file
* .h file contains C function declarations and macro definitions to be shared between several source files

### Basic APIS
#### Strings
- strcpy
- strcmp
- strlen
- strncpy
- strcat

#### Output
- printf
- sprintf
- snprintf
- fprintf

#### Data
- memcpy
- read
- write
- sizeof

#### Process Sprawning
- fork
- execve
- system

#### Files
- fopen
- fclose
- fgetc
- fputc
- fread
- fwrite

### Socket programming  
Client needs to  
- Initialise sockaddr struct
- Create a socket()
- Connect() to a server

Server needs to
- Initialise sockaddr struct
- Create a socket()
- Bind(), listen(),accept()

SCI understand -- audit tool
conversion
operator
arrays/pointers
memory
