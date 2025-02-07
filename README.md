# Lua Nil Handling Bug

This repository demonstrates a common error in Lua: improper handling of `nil` values in arithmetic operations. The `foo` function attempts to add two numbers but does not correctly handle cases where one or both inputs are `nil`. This can lead to unexpected `nil` results or runtime errors.

The `bug.lua` file contains the erroneous code.  The solution, demonstrating proper nil handling, is in `bugSolution.lua`.