# Laser Sensor

Laser sensors do not have any commands.

### Properties

### `activated`

Returns `true` if there is an object hit by it's laser. Otherwise returns `false`.

Example:

```
// wait until laser_sensor.activated returns true
conveyor.start()
wait(laser_sensor.activated, true)
conveyor.stop()
```