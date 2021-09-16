These assignments require OpenCV as a prerequisite. The easiest way to install is probably with conda.

To install OpenCV in a conda environment.
```
conda create -n cs344 -y
conda activate cs344
conda install -y -c anaconda opencv
```

To build
```
cd assignments
mkdir build
cd build
cmake ..
make
```
The binaries will then be contained within `assignments/bin`.

# HW1 Passing Instructions
From the `HW1` directory.

Run `../bin/HW1 HW1/cinque_terre_small.jpg'`