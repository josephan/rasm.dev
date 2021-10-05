# Logical

### `and(a, b)`

Checks if "a" and "b" is true and stores the result in "a".
Example:

```
set(a, true)
set(b, true)
and(a, b) // a is true

set(a, true)
set(b, false)
and(a, b) // a is false
```

### `or(a, b)`

Checks if "a" or "b" is true and stores the result in "a".
Example:

```
set(a, true)
set(b, true)
and(a, b) // a is true

set(a, false)
set(b, true)
and(a, b) // a is true
```

### `not(a)`

Negates the value of "a" and stores the result in "a"
Example:

```
set(a, true)
not(a)   // a is now false
not(a)   // a is now back to true
```