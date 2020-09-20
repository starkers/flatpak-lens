More AppImages in flatpak :-/



# build and install

```
flatpak-builder --force-clean build-dir org.flatpak.Lens.yaml --install --user
```

# launch

```
flatpak run org.flatpak.Lens
```

# cleanup-uninstall

```
flatpak --user uninstall -y org.flatpak.Lens
```

