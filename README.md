# GNOME Builds for MSVC

[![Build](https://github.com/ruifengx/gnome-build/actions/workflows/build.yaml/badge.svg)](https://github.com/ruifengx/gnome-build/actions/workflows/build.yaml)

The following libraries are built:
- the `gtk` bundle: everything inside `https://gitlab.gnome.org/GNOME/gtk.git`
- `gobject-introspection`: prerequisite for `librsvg` (optional) and `libadwaita`
- `libxml2`: prerequisite for `librsvg` and therefore `pixbufloader-svg.dll`
- `librsvg`: necessary for `pixbufloader-svg.dll`, used by GTK to load scalable icons

The following libraries are planned:
- [`libadwaita`](https://gitlab.gnome.org/GNOME/libadwaita): Building blocks for modern GNOME applications
- [`adwaita-icon-theme`](https://gitlab.gnome.org/GNOME/adwaita-icon-theme): Mostly private use system icons
