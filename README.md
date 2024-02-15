# flatpak-qgis
<BR>Flatpak builds of QGIS as base for KADAS Albireo, trying to keep it fairly minimal.
<BR>This is a test/staging area for flatpak-kadas, so it's very experimental and might not work.
<BR>
<BR>Build:
<BR>clear && flatpak-builder --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir org.qgis.qgis.yml
<BR>
<BR>Build & Install:
<BR>clear && flatpak-builder --user --install --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir org.qgis.qgis.yml
