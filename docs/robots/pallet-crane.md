# Pallet Crane

### `move(a, b)`

### `move_async(a, b)`

### `extend(a)`

Extends the fork to the provided distance. Where -1 ≤ a ≤ 1.

### `raise()`

Raises the fork the lift the pallet underneath it.

### `lower()`

Lowers the fork to drop the pallet. **Note: always lower the pallet on the crane's platform before calling `move`.**