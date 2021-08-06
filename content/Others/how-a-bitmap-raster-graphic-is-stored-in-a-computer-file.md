---
title: "how a bitmap (‘raster’) graphic is stored in a computer file "
--- 
How is bitmap stored :

- Made up of pixels
- Each pixel is represented by bits
- 1 to 64 bits per pixel
- Number of pixels depending on colour depth
- Bits representing pixels packed in rows for bmp
- Rows rounded to 32 bit words
- Padding needed for loading into memory locations
- Usually stored from bottom left up to top right of image. 