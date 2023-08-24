[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8276054.svg)](https://doi.org/10.5281/zenodo.8276054)
# VIO-GNSS Dataset: Benchmarking Dataset for Sensor Fusion of Visual Inertial Odometry and GNSS Positioning
[Eetu Pakkanen](https://people.aalto.fi/fi/eetu.pakkanen)

This dataset is for benchmarking and improving different Sensor Fusion implementations/algorithms.

The upload contains two datasets (version 1.0.0):

- urban_with_gnss_dead_zones (7.0 GB, ~16 minutes)
  - City streets
  - A building is passed through on two occasions which makes the GNSS location signal unavailable at times.
  - RTK Fix is acquired at times
- suburban_nature (10.6 GB, ~19 minutes)
  - The route begins on a suburban street but quickly turns into a nature trail. Lots of vegetation
  - The RTK solution is only Float or None most of the route.
