# XCode Notes

## Useful Commands

1. print(variableToPrint)
2. assert -- stops executing program if condition is true, shows `message:` as an error message (works during debug only)
![assertion](./Images/assert-1.png)
![assert-example](./Images/assert-example.png)
3. precondition -- similar to assert, but also works during user in use (helpful if needed to stop executing program because of an error happened)
![precondition syntax](./Images/precondition-syntax.png)
![precondition example](./Images/precondition-example.png)
4. fatal error (always returns 'Never' -- used to stop execution with fatal error)
![fatal error syntax](./Images/fatalerror-syntax.png)
![fatal error example](./Images/fatalerror-example.png)

## Shell Commands

1. `po $arg1` -- shows the error text without garbage (po == print object)
2. `watchpoint set variable VariableName` -- sets watching variable. Same is `w s v VariableName`
3. `bp s -o -f File.swift -l 44` -- sets a break point
    - `bp` - breakpoint
    - `s` - set
    - `-o` - one-shot. Breakpoint would be deleted after the first use
    - `-f File.swift` - File where breakpoint would be set
    - `-l 44` - line to set BP

## Breakpoints
    