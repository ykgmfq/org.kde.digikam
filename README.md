# org.kde.digikam Flatpak Manifest
```
flatpak remote-add --no-gpg-verify --if-not-exists local /opt/flatpak/localrepo
flatpak-builder --repo=/opt/flatpak/localrepo build org.kde.digikam.yml
```
