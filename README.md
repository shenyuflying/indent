# indent

indent - A C code format tool

    which will detect following format defects
       1. space before and after == && != >> << + - -= += > <
       2. space after if for
       3. space after , 
       4. tailing blanks
    after the code is formatted, indent will invoke vimdiff
    for you to mannualy merge the code use the following command
       ']c' command to move next difference 
       '[c' command to move previous difference 
       'po' command to merge the current difference
Bugs:  1. failed to format '*' '/'
       2. failed to format when partial correct such as a+ b to a + b
       3. will format comments which not wanted
                      report more bugs to  shenyufly@163.com

