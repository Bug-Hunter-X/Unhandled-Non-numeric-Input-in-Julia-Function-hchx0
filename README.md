# Unhandled Non-numeric Input in Julia Function

This repository demonstrates a common error in Julia:  lack of error handling for unexpected input types.  The `bug.jl` file contains a function that squares the input if it's positive and returns the negative of the square if it's negative. However, it fails if the input is not a number.

The `bugSolution.jl` file provides a corrected version with improved error handling.