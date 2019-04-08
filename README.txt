NASA released a huge mosaic of the Triangulum Galaxy (M33). This repo contains a zoomable viewer for mosaic.

You can view the mosaic at https://freethenation.github.io/hubblem33/

Notes:
* The source image can be found at http://hubblesite.org/image/4305/gallery
* The tile pyramid was generated using 
$ vips dzsave hubblem33.tif dz --layout google --tile-size 512 --suffix '.jpg[Q=95]' --background 0




