# Ansel Function Declaration

## Named Functions

To declare a named function in Ansel, use the `fun` keyword, followed by the name, parameters, (optionally) `:` and the return type, and the body of the function. For example:

```ansel
fun multiply(num1 :: int, num2 :: int): int 
{
    return num1 * num2
}
```

In the above example, `multiply` is a named function. It takes two parameters, `num1` and `num2`, which are explicitly stated to be integers, and is explicitly stated to return an integer. The body of the function is the code that is executed when the function is called, which is between curly brackets.

If the return type is not specified, it will infer it from what is returned.

If nothing is returned, the return type will be `void`.

