# Installing and Running Julia

## Installing Julia

If you haven't already done so, visit the Julia [install](https://julialang.org/install/) page and download `juliaup` for your platform. 

Once `juliaup` is installed, install a julia version using `juliaup add release` (or use a different version like `lts` instead of `release`).

## Run Julia

Check that when you execute `julia` the REPL starts, like this:

```
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.11.6 (2025-07-09)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia> println("hello, world!")
hello, world!

julia> (2+3)^2
25

julia> 
```

As shown above, try typing a few commands and checking that they execute as expected.

## You should have learned...

1. How to install Julia
2. How to start the Julia REPL and execute commands
