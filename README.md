# Nimbus

Nimbus is a minimal weather applet.

![Nimbus Screenshot](https://raw.github.com/danrabbit/nimbus/master/data/screenshot.png)

## Building, Testing, and Installation


You'll need the following dependencies:
* libgtk-3-dev
* libgweather-3-dev 
* meson
* valac

Run `meson build` to configure the build environment and then change to the build directory and run `ninja` to build

    meson build
    cd build
    mesonconf -Dprefix=/usr
    ninja

To install, use `ninja install`, then execute with `com.github.danrabbit.nimbus`

    sudo ninja install
    com.github.danrabbit.nimbus
