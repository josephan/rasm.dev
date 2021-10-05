# Robot Arm Spot Welder

### `move(state)`

Moves the robot's joints to the specified state snapshots.

Example:

```
// after saving a snapshot in the Robot Arm's window
robot.move(state1)

// can reference another robot's snapshot as well if they have the same number of joints
robot.move(robot2.state1)
```

### `weld()`

Activates the spot welder and welds if the 3 objects are nearby:

1. Base object to weld onto
2. Child object to weld
3. Child object's weld spot (indicated by the white circle)

After welding, the weld spot turns black.

Example:

```
// The welders highlight red if there is a weldable spot nearby
robot.weld()
```

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