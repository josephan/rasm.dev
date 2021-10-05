# Arithmetic

### `add(a, b)`

Adds "a" and "b", then stores the result in "a".
Example:

```
set(a, 4)
set(b, 5)
add(a, b)   // a is now 9

set(c, 3)
add(c, 1.4) // c is now 4.4
```

### `sub(a, b)`

Subtracts "a" by "b", then stores the result in "a".
Example:

```
set(a, 10)
sub(a, 3)   // a is now 7
```

### `mult(a, b)`

Multiplies "a" by "b", then stores the result in "a".
Example:

```
set(a, 10)
mult(a, 3)   // a is now 30
```

### `div(a, b)`

Divides "a" by "b", then stores the result in "a".
Example:

```
set(a, 9)
div(a, 3)   // a is now 3
```

### `mod(a, b)`

Sets the remainder of dividing "a" by "b" to "a".
Example:

```
set(a, 10)
mod(a, 3) // a is now 1 because the remainder of 10 / 3 is 1

set(b, 2)
mod(b, 2) // b is now 0 because there is no remainder for 2 / 2

set(c, 1)
mod(c, 2) // c is still 1 because 2 can't go into 1 so the remainder is 1
```

### `pow(a, b)`

Raises "a" to the power of "b" and stores the result in a. Also known as an exponent.
Example:

```
set(a, 3)
pow(a, 2) // a is now 9

set(b, 2)
pow(b, 5) // b is now 32
```

### `sqrt(a)`

Square root of a.

```
set(b, 2)
sqrt(b) // b is now 1.4142...
```

### `sin(a)`

Sine of a (in degrees).

### `cos(a)`

Cosine of a (in degrees).

### `tan(a)`

Tangent of a (in degrees).

### `asin(a)`

Inverse sine (aka arcsine) of a (in degrees).

### `acos(a)`

Inverse cosine (aka arccos) of a (in degrees).

### `atan(a)`

Inverse tangent (aka arctan) of a (in degrees).