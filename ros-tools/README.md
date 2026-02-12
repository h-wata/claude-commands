# ros-tools

ROS2 and Kachaka API log analysis commands.

## Installation

```
/install ros-tools@h-wata/claude-commands
```

## Commands

### `/analyze-logs`
Analyze ROS and Kachaka API logs to identify errors.

```
/analyze-logs /path/to/log --time 15:34
/analyze-logs /path/to/log --error
/analyze-logs /path/to/log --pattern "Map name mismatch"
```

### `/ros-analyze`
Analyze live ROS2 system state.

```
/ros-analyze status
/ros-analyze topics /cmd_vel
/ros-analyze errors
/ros-analyze fleet
```
