# Buildyard

Buildyard is deprecated, and has be replaced by CMake superproject
builds. Each project build is now self-contained. For example, building
Equalizer should be as simple as:


```
git clone https://github.com/Eyescale/Equalizer.git
mkdir Equalizer/build
cd Equalizer/build
cmake ..
make
```
