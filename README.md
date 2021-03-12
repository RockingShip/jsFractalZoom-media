\[click on image to start `zoomer` at shown position\]  
[![favimage.jpg](assets/favimage-840x472.jpg)](https://rockingship.github.io/jsFractalZoom/jsFractalZoom.html?x=-1.4858120997711768&y=0.03723940037753004&r=2.664650726631176e-11&a=0&density=0.1227&iter=6000&theme=6&seed=140161044)

!!  
!! This repository contains about 1G of media files  
!!

# jsFractalZoom

## Welcome to the Wonderful World of (fractal) zooming and video codec.

*When illustrations are 14622x larger than the code...*

This project contains the media files for project `jsFractalZoom` [https://github.com/RockingShip/jsFractalZoom](https://github.com/RockingShip/jsFractalZoom)

## Manifest

  - [https://rockingship.github.io/jsFractalZoom/jsFractalZoom.html](https://rockingship.github.io/jsFractalZoom/jsFractalZoom.html)  
    The interactive fractal zoomer.

  - [gallery/index.html](https://rockingship.github.io/jsFractalZoom-media/gallery/index.html)  
    The fractal zoomer image gallery.

  - [videos/select-ade.html](https://rockingship.github.io/jsFractalZoom-media/videos/select-ade.html)  
    `splash` codec demo: "ADE" PixelsPerFrame selector (contains flashing white lights).

  - [videos/select-gta.html](https://rockingship.github.io/jsFractalZoom-media/videos/select-gta.html)  
    `splash` codec demo: "GTA" PixelsPerFrame selector (contains reckless driving).

  - [videos/ade-sbs-900x506.webp](https://rockingship.github.io/jsFractalZoom-media/videos/ade-sbs-900x506.webp)  
    Side-By-Side video of above for settings `PPF`=100 and upscaled 90x50.

  - [videos/gta-sbs-900x506.webp](https://rockingship.github.io/jsFractalZoom-media/videos/gta-sbs-900x506.webp)  
    Side-By-Side video of above for settings `PPF`=100 and upscaled 90x50.

  - [videos/ade-border.webp](https://rockingship.github.io/jsFractalZoom-media/videos/ade-border.webp)  
    Video displaying how `splash` constructs a single frame of "ADE".  
    The border displays processed scan row/columns.  
    The number in the lower left corner is progress (ranging 0-1).  
    `ffmpeg -loglevel warning -stats -r:v 240/1 -i ade-border-1920x1080.mp4 -vf scale=840:472 -r 12/1 ade-border-840x472.webp`

## Versioning

Using [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/RockingShip/jsFractalZoom-media/tags).

## License

This project is licensed under the GNU General Public License v3 - see the [LICENSE.txt](LICENSE.txt) file for details
