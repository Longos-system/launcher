# Launcher

LongOS的全屏应用程序启动程序。 

## 依赖包
Arch Linux/Manjaro 依赖包
```shell
sudo pacman -S gcc cmake qt5-base qt5-quickcontrols2 kwindowsystem
```
Debian/Ubuntu 依赖包
```shell
sudo apt install gcc cmake qtbase5-dev qml-module-qtquick-controls2 qml-module-org-kde-kwindowsystem qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev libkf5windowsystem-dev
```

## 构建和安装

```
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.
