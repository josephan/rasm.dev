# Comparison

### `eq(a, b)`

Checks if "a" is equal to "b" and stores the result in "a".
Example:

```
set(a, 1)
set(b, 1)
eq(a, b) // a is now true

set(a, 1)
set(b, 2)
eq(a, b) // a is now false
```

### `approx(a, b)`

Checks if "a" is approximately equal to "b" (within an Epsilon) and stores the result in "a". Handy for comparing floats of real world values.
Example:

```
set(a, 1.0000001)
set(b, 1)
eq(a, b) // a is now true

set(a, 1.1)
set(b, 1)
eq(a, b) // a is now false
```

### `neq(a, b)`

Checks if "a" is **not** equal to "b" and stores the result in "a".
Example:

```
set(a, 1)
set(b, 1)
eq(a, b) // a is now false

set(a, 1)
set(b, 2)
eq(a, b) // a is now true
```

### `lt(a, b)`

Checks if "a" is less than "b" and stores the result in "a".
Example:

```
set(a, 1)
set(b, 2)
lt(a, b) // a is now true
```

### `gt(a, b)`

Checks if "a" is greater than "b" and stores the result in "a".
Example:

```
set(a, 3)
set(b, 2)
lt(a, b) // a is now true
```

### `lte(a, b)`

Checks if "a" is less than or equal to "b" and stores the result in "a".
Example:

```
set(a, 1)
set(b, 2)
lt(a, b) // a is true

set(a, 2)
set(b, 2)
lt(a, b) // a is still true
```

### `gte(a, b)`

Checks if "a" is greater than or equal to "b" and stores the result in "a".
Example:

```
set(a, 3)
set(b, 2)
lt(a, b) // a is true

set(a, 2)
set(b, 2)
lt(a, b) // a is still true
```