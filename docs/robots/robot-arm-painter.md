# Robot Arm Painter

### `move(state)`

Moves the robot's joints to the specified state snapshots.

Example:

```
// after saving a snapshot in the Robot Arm's window
robot.move(state1)

// can reference another robot's snapshot as well if they have the same number of joints
robot.move(robot2.state1)
```

### `paint()`

Starts the spray painter.

### `stop()`

Stops the spray painter.

### Properties

### `<user_defined_state_snapshots>`

```
// if the robot has any state snapshots
// robot.state1
// robot.state2
// and so on...
robot.move(state1)
robot.move(robot.state1)
```