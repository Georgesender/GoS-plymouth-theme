# GoS-plymouth-theme
Plymouth theme for G Operating System, can be easly changed to suit your needs

### Features:
- Dark background
- Centered logo (`gos-logo.png`)
- Animated progress bar (white bar moves left to right)
- Blinking "head" icon at the bottom (`gos-head-grey.png`)
- Fully script-based for maximum control

### Installation:

```bash
sudo cp -r gos-theme /usr/share/plymouth/themes/
sudo plymouth-set-default-theme -R gos
```

# Customization 
simply substitute your logo with the name gos-logo.png (you need to take an image with a size larger than 260*260px)
, and optionally replace or simply delete gos-head-grey.png (if you change it, you need a size of at least 150*150px)
