# JavaScript Block Scope Confusion with `let`

This example demonstrates a common point of confusion in JavaScript related to block scope when using the `let` keyword.  Many developers expect the variable `x` to be modified within the `if` block and retain the modified value in the outer scope. This is not the case.  The `let` keyword creates a new variable `x` within the `if` block, which is distinct from the `x` declared in the outer scope.

## How to Solve
The solution involves understanding and carefully managing variable scope within blocks. Avoid shadowing variables (using the same name in inner and outer scopes) unless you explicitly intend to create separate variables with different scopes.