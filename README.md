# cmake-nanovg
This repo contains the cmake file for building the nanovg library from https://github.com/memononen/nanovg

## How to use

1. Clone the nanovg source

```
git clone https://github.com/memononen/nanovg.git
```

2. Enter the directory

```
cd nanovg
```

3. Add this as a submodule 
```
git submodule add -b master https://github.com/copotron/cmake-nanovg.git
```

4. Build and install nanovg library

```
cd cmake-nanovg
mkdir build
cd build
cmake ..
make
sudo make install
```






