# AI-Generated Wallpapers

All wallpapers in this repository were generated with [Midjourney](https://www.midjourney.com) and upscaled with [Upscaler](https://flathub.org/apps/details/io.gitlab.theevilskeleton.Upscaler).
All wallpapers are free to use under the terms of the [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.

## Burn-My-Windows Wallpapers

I created a wallpaper for each of the effects of the [Burn-My-Windows GNOME Shell extension](https://github.com/Schneegans/Burn-My-Windows).

[![](burn-my-windows.jpg)](burn-my-windows)

## Notes

The montages in this README were generated with [Image Magick](https://imagemagick.org/index.php) like this:

```
montage -label '%f' burn-my-windows/*.jpg -tile 5x4 -geometry 240x150+4+2 burn-my-windows.jpg
```