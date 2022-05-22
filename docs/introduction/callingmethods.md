# Calling Methods in Ansel

To call a method on a class, use the `:` operator.

for example, after the math library is imported, we can call the `sqrt` method on the `math` class:

```ansel
import 'math'

imt num1 = 25 :: int

log math:sqrt(num1)
```
#### Result
```
5
```