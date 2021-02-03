# Kinvoa Drake

Code for controlling a Kinova Gen3 Manipulator via Drake.

## Dependencies

- [Drake](https://drake.mit.edu/)
- [Meshcat](https://github.com/rdeits/meshcat) visualizer
- GStreamer (for accessing camera streams)
- OpenCV with GStreamer bindings
- [Open3d](http://www.open3d.org/docs/latest/introduction.html) point cloud library

## Running examples

There are basic examples of various things (both simulation and hardware) in the `examples` directory. These must be run
from this directory with, e.g., `python3 -m examples.peg_pickup_demo`.
