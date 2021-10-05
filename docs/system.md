# System

### `set(a, b)`

Set stores the value b in  a variable named, "a".
Example:

```
set(pi, 3.14)
set(five, 5)
set(is_pizza_delicious, true)
```

### `wait(a)`

The program halts for the specified number of seconds.
Example:

```
wait(4)
wait(1.5)
```

### `wait(a, b)`

The program halts until the value of "a" is equal to "b".
Example:

```
// waits until laser_sensor's activated property is true
wait(laser_sensor.activated, true)
```

### `run(filename)`

Runs the specified RASM program synchronously from start to finish before continuing to the next command.
Example:

```
run(weld_doors.rasm)
```

### `run_parallel(filename)`

Runs the specified RASM program asynchronously without halting the program it was called in. **Warning**: programs running in parallel can access and edit variables set in other running programs. This can lead to unexpected behaviour.
Example:

```
run_parallel(start_conveyors.rasm)
```

### `print(a)`

Prints the value of "a" to the terminal. Helpful for debugging.
Example:

```
print(123) // prints 123
set(a, 99)
print(a)   // prints 99
```

### `break()`

Pauses the execution of the program at the current line. Helpful for debugging.