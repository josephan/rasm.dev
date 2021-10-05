# Pointers

### `addr(a, b)`

Gets the address of the variable "b" and stores it in variable "a".

```
set(a, 123)        // the address of a is an integer, in this case 0
addr(a_addr, a) // a_addr is now 0
```

### `peek(a, b)`

Gets the value located in memory specificied by the address "b" and then stores it in the variable "a". "b" must be an integer.

```
set(pi, 3.14) // store 3.14 in variable "pi"
addr(b, pi)   // get the address of variable "pi"
peek(a, b)    // "a" is now 3.14
```

### `poke(a, b)`

Updates the value of the given address "a" by the given value "b".

```
set(is_even, true) // set "is_even" to false
addr(b, is_even)   // get the address of "is_even"
poke(b, false)     // the variable "is_even" is now false
```

### `alloc(a, b)`

Allocates a contiguous block of memory. The length is specified by "b" (must be an integer). Then the address of the first element is stored in "a".