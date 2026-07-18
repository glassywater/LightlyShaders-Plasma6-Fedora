English | [中文](README_zh.md)

# LightlyShaders v3.0

 This effect works correctly with stock Plasma effects. Supports KDE Plasma Version >= 6.7

 ![default](screenshot.png)


# Dependencies:
 
Plasma Version >= 6.7.
 
You will need qt6, kf6 and kwin development packages.

**Arch**:

`sudo pacman -S git make cmake gcc gettext extra-cmake-modules qt5-tools qt5-x11extras kcrash kglobalaccel kde-dev-utils kio knotifications kinit kwin`

**Fedora**:

`sudo dnf install -y cmake gcc-c++ make gettext extra-cmake-modules qt6-qtbase-devel qt6-qtbase-private-devel qt6-qttools-devel kf6-kconfig-devel kf6-kconfigwidgets-devel kf6-kcoreaddons-devel kf6-kcrash-devel kf6-kglobalaccel-devel kf6-ki18n-devel kf6-kio-devel kf6-kservice-devel kf6-knotifications-devel kf6-kwidgetsaddons-devel kf6-kwindowsystem-devel kf6-kguiaddons-devel kf6-kcmutils-devel libepoxy-devel libdrm-devel kwin-devel kdecoration-devel`

# Manual installation
```
git clone https://github.com/glassywater/LightlyShaders-Plasma6-Fedora

cd LightlyShaders-Plasma6-Fedora

mkdir qt6build; cd qt6build; cmake ../ -DCMAKE_INSTALL_PREFIX=/usr && make && sudo make install
```

## Note
After some updates of Plasma this plugin may need to be recompiled in order to work with changes introduced to KWin.
 
