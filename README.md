# sofar-crane-simulator
First practical assignment for the SOFAR course. The project consists in a 2D simulation of a crane, developed with ROS2/Python, performing pick and place operations.

## Dependencies

The project targets ROS2 distributions. It has been successfully tested with Galactic and Humble distros (desktop installation).

The only external depencency needed is Arcade library (see [Instructions for Linux install](https://api.arcade.academy/en/latest/install/linux.html))

## Execution

Clone the repository in your workspace and compile as usual.

Run the simulation node with:
```ros2 run sofar_crane_simulator crane_sim_node```
