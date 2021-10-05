# Control Flow

Labels are locations where your program can "jump" to. You can change the line location of the running program with jumps.
Labels are any text ending in a colon and they can be placed anywhere in your program (the order in which the jump and the label declaration appears does not matter).

### `jump(LABEL)`

Jumps to the specified label.
Example:

```
jump(LABEL_ONE)
// this section of code is skipped because
// we jump to LABEL_ONE
set(a, 1)
add(a, 2)
print(a)

LABEL_ONE:
// more code ...
```

### `jump_if(a, LABEL)`

Jumps to the specified label, only if "a" is `true`.
Example:

```
set(a, true)
jump_if(a, SOME_LABEL)  // this jump will work

SOME_LABEL:
// some code...

set(b, false)
jump_if(b, SOME_LABEL) // this jump will not work because "b" is false
```