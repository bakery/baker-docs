---
title: Generating App Icons
permalink: /icons.html
---
# Generating App Icons

Baker helps you generate app icons for Android and iOS. The image resizing is done with ImageMagick so make sure you have ImageMagick's `convert` command available in the command line.

To generate the icons, name your original 1024x1024 icon `icon.png` and place it in `/app/assets`.

You can generate the icons by running:

```
npm run icons
```

You can also generate Launch Images. Since Launch Images don't have constant ratios, should use a logo with a full color background and pass the background color as the parameter. The tool will automatically fill in the remaining space with the background color.

The `logoScale` parameter defines the ratio of the logo to the shortest screen side (width or height depending on orientation).

You can configure the parameters in `/app/assets/icon.png`:

```
{
  "originalIconFilename": "./app/assets/icon.png",
  "originalLogoFilename": "./app/assets/icon.png",
  "logoScale" : 1,
  "backgroundColor": "rgba(255,255,255,1)"
}
```

