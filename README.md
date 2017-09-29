# Multimodal maze
Multimodal maze environment based on the SUNCG indoor scenes dataset.

## Dependencies

Main requirements:
- Python 2.7 with Numpy, Scipy and Matplotlib
- [Panda3d](https://www.panda3d.org/) game engine for 3D rendering

To install dependencies on Ubuntu operating systems:
```
sudo apt-get install python-pip python-dev build-essential
sudo pip install --upgrade pip
sudo pip install --upgrade numpy scipy matplotlib panda3d
```
## Installing the library

Download the source code from the git repository:
```
mkdir -p $HOME/work
cd $HOME/work
git clone https://github.com/IGLU-CHISTERA/multimodal-maze.git
```

Note that the library must be in the PYTHONPATH environment variable for Python to be able to find it:
```
export PYTHONPATH=$HOME/work/multimodal-maze:$PYTHONPATH 
```
This can also be added at the end of the configuration file $HOME/.bashrc

## Running unit tests

To ensure all libraries where correctly installed, it is advised to run the test suite:
```
cd $HOME/work/multimodal-maze/tests
./run_tests.sh
```
Note that this can take some time.
