# Music Spectrum Analyzer for Plasma

![alt tag](https://github.com/apachelogger/plasma-analyzer/blob/master/data/preview.gif)

# Installing

```
mkdir build
cd build
cmake .. -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Release
make
sudo make install
```

## Compilation dependencies
### ArchLinux
```
sudo pacman -S extra-cmake-modules
```

### Ubuntu
```
sudo apt install libpulse-dev libfftw3-dev
```

### Fedora
```
sudo dnf install pulseaudio-libs-devel fftw-devel qt5-devel qt5-qtdeclarative-devel plasma-framework-devel extra-cmake-modules
```

# KDE Store
https://store.kde.org/p/1953779
