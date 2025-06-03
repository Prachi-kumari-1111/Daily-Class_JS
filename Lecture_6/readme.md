The var keyword was used in all Javascript from 1995 to 2015. The let and const keywords were to Javascript in 2015. The var keyword should only be used in code written for older browsers.

// When to use var,let,const?

Always declare variables

Always use const if the value should not be changed

Always use const if the type should not be changed (Arrays and Objects)

Only use let if you can't use const

Only use var if you MUST support old browsers.

Javascript Identifiers

All JavaScript variables must be identified with unique names.

These unique names are called identifiers.

Identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

The general rules for constructing names for variables (unique identifiers) are:

Names can contain letters, digits, underscores, and dollar signs.
Names must begin with a letter. Names can also begin with $ and _ (but we will not use it in this tutorial). Names are case sensitive (y and Y are different variables). totalvolume these are different totalVolume identifiers Reserved words (like JavaScript keywords) cannot be used as names.

Variables declared by let have Block scope.