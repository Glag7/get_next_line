# From the subject

__Summary:__  
This project is about programming a function that returns a line
read from a file descriptor.  
Version: 10  
  
• Repeated calls (e.g., using a loop) to your get\_next\_line() function should let
you read the text file pointed to by the file descriptor, one line at a time.  
• Your function should return the line that was read.
If there is nothing else to read or if an error occurred, it should return NULL.  
  
__bonuses:__  
• Develop get\_next\_line() using only one static variable.  
• Your get\_next\_line() can manage multiple file descriptors at the same time.  

# Usage

`cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 get_next_line.c get_next_line_utils.c`.  
BUFFER\_SIZE is optional. The bonus files are the same.  
Call get\_next\_line(fd).  
```c
char	*get_next_line(int fd);
```
