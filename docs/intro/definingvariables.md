# Defining Variables in Ansel

Variables in Ansel are mutable by default and are defined by
`name` `=` `value`

Ansel is dynamically typed, however it features optional static typing, by adding the `::` operator, followed by the type of the variable.

For example, the following snippet defines a variable called `str` and assigns it the value `'Hello World'`:

```ansel
str = 'Hello World'
```

The language infers that the type of str is string but to make it explicit, we can declare its type.

```ansel
str = 'Hello World' :: string
```

As stated before, all variables in ansel are mutable by default. To define a variable as immutable, simply add the `imt` modifier, like so.

```ansel
imt str = 'Hello World' :: string
```

Now we have an immutable variable, str, with the value `'Hello World'` and the explicit type of `string`.