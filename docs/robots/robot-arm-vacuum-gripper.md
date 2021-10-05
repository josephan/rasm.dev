# Robot Arm Vacuum Gripper

### `move(state)`

Moves the robot's joints to the specified state snapshots.

Example:

```
// after saving a snapshot in the Robot Arm's window
robot.move(state1)

// can reference another robot's snapshot as well if they have the same number of joints
robot.move(robot2.state1)
```

### `hold()`

Activates the vacuum gripper if there is an object right below it and holds the object.

Example:

```
// The grippers highlight red if there is an object nearby it can hold
robot.hold()
```

### `drop()`

Drops any object the vacuum gripper is holding.

Example:

```
robot.drop()
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