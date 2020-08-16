# Audit C Program
## C language review
* .c file is C source code file
* .h file contains C function declarations and macro definitions to be shared between several source files

### Basic APIS
#### Strings
strcpy, strcmp, strlen, strncpy, strcat

#### Output
printf, sprintf, snprintf, fprintf

#### Data
memcpy, read, write, sizeof

#### Process Sprawning
fork, execve, system

#### Files
fopen, fclose, fgetc, fputc, fread, fwrite

### Socket programming  
Client needs to  
- Initialise sockaddr struct
- Create a socket()
- Connect() to a server

Server needs to
- Initialise sockaddr struct
- Create a socket()
- Bind(), listen(),accept()  
! handle_client method is where hackers exploit

## Security flaws
- overflow: this is very common, like buffer overflow, integer overflow, stack overflow
- off-by-one: a logic error involving the discrete equivalent of a boundary condition
- command injection
- design
- ASCII/wide

### Memory Allocation
- Validate input(size)
  - prefer hard limits if possible
- Watch for Math when allocation
- Copy needs same Math
- Wild read or write can be a problem (Hearbleed: out-of-bound read bug)

### Kernel and compiler bugs
System code in multiuser system: copy of data from apps, which means double fetch can happen.  
Compiler can remove code, which is patched now.

SCI understand -- audit tool

# Audit C++ Program
## C++ language
C++ is an extension of C which is object-oriented.
