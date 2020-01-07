# Bash Comparison

## Interger Comparison [1]

equal to 
    
    -eq

    exemple: if [ "$a" -eq "$b" ]

not equal to 
    
    -ne

    exemple: if [ "$a" -ne "$b" ]


greater than 

    -gt

    exemple: if [ "$a" -gt "$b" ]


greater than or equal to

    -ge

    exemple: if [ "$a" -ge "$b" ]

less than
    
    -lt

    exemple: if [ "$a" -lt "$b" ]

less than or equal to

    -le 

    exemple: if [ "$a" -le "$b" ]

## Integer Comparison [2]

less than

    <

    example: if (("$a" < "$b"))

less than or equal to 

    <=

    exemple: if (("$a" <= "$b"))

greater than

    >

    exemple: if (("$a" > "$b"))

greater than or equal to 

    >=

    exemple: if (("$a" >= "$b"))

## String Comparison

equal to

    =

    exemple: if [ "$a" = "$b" ]

equal to
 
    ==

    if [ "$a" == "$b" ]

not equal to

    != 

    exemple: if [ "$a" != "$b" ]

less than, in ASCII alphabetical order

    <

    exemple: if [[ "$a" < "$b" ]]

greater than, in ASCII alphabetical order

    >

    exemple: if [[ "$a" > "$b" ]]
 
string is null, that is, has zero length

    -z