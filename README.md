# Implement Behavior Planning From Scratch in C++
Implement a behavior planner for highway driving. It will use prediction data to set the state of the ego vehicle to one of 5 values:

* "KL" - Keep Lane
* "LCL" / "LCR"- Lane Change Left / Right
* "PLCL" / "PLCR" - Prepare Lane Change Left / Right

# Instructions
Implement the update_state method in the vehicle.cpp class.
Hit Test Run and see how your car does! How fast can you get to the goal without colliding?

# Build

```bash
$ mkdir build
$ cmake ..
$ make
```