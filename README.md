# flatpak-qgis
<BR>Flatpak builds of KADAS QGIS from git https://github.com/kadas-albireo/QGIS as base for KADAS Albireo, trying to keep it fairly minimal.
<BR>
<BR>Build:
<BR>clear && flatpak-builder --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir org.qgis.qgis.yml
<BR>
<BR>Build & Install:
<BR>clear && flatpak-builder --user --install --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir org.qgis.qgis.yml
<BR>
<BR>Or download an artifact from https://github.com/mattiasegly/flatpak-qgis/actions/workflows/flatpak-builder.yml
