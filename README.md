# QGISTrotuworld
A QGIS source map for Trotuworld

## How to set it up?
* First, download this repository, as well as [QGIS](https://qgis.org/download/) if you haven't done so.
* Get the rendering files. You can get them here https://drive.google.com/drive/folders/1VCpW3_122YdB7ITGRcrEbsvO2wBmPB4y?usp=sharing
   * Make sure to download all of them, including non image-like file.
* Then, create a new folder called 'rendering' within the repository. DO NOT UPLOAD THIS TO THE REPOSITORY WHEN COMMITING. THEY ARE TOO LARGE.
* Upload all the image files you get from google drive in there. The folder should look like this now.

<img width="533" alt="image" src="https://github.com/UpsideKen/QGISTrotuworld/assets/159201452/a1d0e0ef-2a2e-429f-8d95-4f66947171cd">

* Load up QGIS, and open the project with 'TrotuWorld.qgz'
* If necessary, auto-find any missing directory, otherwise, click remove unavailable layer and proceed.

## Layer convention

The layers are divided into multiple folders. Here is brief description for all of them
BASE: land and ocean layer.
Geography: Graphical layer such as elevation, precipitation (WIP).
Rendering/Reference: This is folder for all the image tracing.
Political Maps: layers for political borders
Water: Layers for river, ocean, and creek.
Human: Road, city, and any other socio-geographical features.


## Quick start QGIS and tips

To get started, make sure that you have some basic understanding of how QGIS work, how to add polygon, line, or other vector type.

If you want to add images into the file of your own, you need to first GEOREFERENCE it. You can do this by going to `layer -> georeferencer...` I highly recommend georeferencing it by manually adding dots into the map, rather than by coordinates.

Play around with edit -> Edit Geometry. They are very handy when it comes to mapping coastline, borders that are touching each other, or splitting territory.

Also try playing around with Toolbox (ctrl + alt + t). Many of these built in toolboxes can really help automate your workflow.
I personally use these the most:
Clip, Clip raster by layer, resterize, difference

I highly recommend turning on snapping under project -> snapping option

Here's some very useful tools for dealing with common problems in mapping
* https://www.youtube.com/watch?v=DMmGTtLx73M
* https://www.youtube.com/watch?v=hPSIW1W3XjY


===========================
=
=
=
=
OLD TUTORIAL BELOW


Renderings are EXCLUDED. For the renders, you can get them here https://drive.google.com/drive/folders/1_4hnoOf6dk0gA0YxmdVipwbrJZP0KEJG?usp=sharing

The folder should look like this:
<img width="533" alt="image" src="https://github.com/UpsideKen/QGISTrotuworld/assets/159201452/a1d0e0ef-2a2e-429f-8d95-4f66947171cd">
