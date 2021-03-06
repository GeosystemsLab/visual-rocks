# VisualRocks
> Cambridge Berkeley - Geomechanics

[![License](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://raw.githubusercontent.com/cb-geo/visual-rocks/master/LICENSE)

This uses the [`pyevtk`](https://pypi.python.org/pypi/PyEVTK/1.0.0) package to convert
output from [`SparkRocks`](https://github.com/cb-geo/spark-rocks) to `VTK` format
for visualization in [`Paraview`](http://www.paraview.org/).

## Usage

```
python visualRocks.py <path/to/input/file> <output/file/name/without/file/extension>
```

The outputs generated by `SparkRocks` are provided as input here. This input is
converted to `.vtp` format that can be viewed in `ParaView`. Do not include the
file extension when specifying the desired output file.
