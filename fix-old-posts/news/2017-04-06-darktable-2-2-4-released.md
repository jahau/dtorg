---
author: houz
comments: true
date: 2017-04-06 18:33:08+00:00
layout: post
link: http://www.darktable.org/2017/04/darktable-2-2-4-released/
slug: darktable-2-2-4-released
title: darktable 2.2.4 released
wordpress_id: 4757
categories:
- announcement
- darktable release
- news
---

we're proud to announce the fourth bugfix release for the 2.2 series of darktable, 2.2.4!

the github release is here: [https://github.com/darktable-org/darktable/releases/tag/release-2.2.4](https://github.com/darktable-org/darktable/releases/tag/release-2.2.4).

as always, please don't use the autogenerated tarball provided by github, but only our tar.xz. the checksum is:

    
    $ sha256sum darktable-2.2.4.tar.xz
    bd5445d6b81fc3288fb07362870e24bb0b5378cacad2c6e6602e32de676bf9d8  darktable-2.2.4.tar.xz
    $ sha256sum darktable-2.2.4.6.dmg
    b7e4aeaa4b275083fa98b2a20e77ceb3ee48af3f7cc48a89f41a035d699bd71c  darktable-2.2.4.6.dmg


Important note: to make sure that darktable can keep on supporting the raw file format for your camera, please help us by visiting [https://raw.pixls.us/](https://raw.pixls.us/) and making sure that we have the full raw sample set for your camera under CC0 license!

and the changelog as compared to 2.2.3 can be found below.


## New features:





 	
  * Better brush trace handing of opacity to get better control.

 	
  * tools: Add script to purge stale thumbnails

 	
  * tools: A script to watch a folder for new images




## Bugfixes:





 	
  * DNG: fix camera name demangling. It used to report some wrong name for some cameras.

 	
  * When using wayland, prefer XWayland, because native Wayland support is not fully functional yet

 	
  * EXIF: properly handle image orientation '2' and '4' (swap them)

 	
  * OpenCL: a few fixes in profiled denoise, demosaic and colormapping

 	
  * tiling: do not process uselessly small end tiles

 	
  * masks: avoid assertion failure in early phase of path generation,

 	
  * masks: reduce risk of unwanted self-finalization of small path shapes

 	
  * Fix rare issue when expanding $() variables in import/export string

 	
  * Camera import: fix ignore_jpg setting not having an effect

 	
  * Picasa web exporter: unbreak after upstream API change

 	
  * collection: fix query string for folders ( 'a' should match 'a/b' and 'a/c', but not 'ac/' )




## Base Support:





 	
  * Fujifilm X-T20 (only uncompressed raw, at the moment)

 	
  * Fujifilm X100F (only uncompressed raw, at the moment)

 	
  * Nikon COOLPIX B700 (12bit-uncompressed)

 	
  * Olympus E-M1MarkII

 	
  * Panasonic DMC-TZ61 (4:3, 3:2, 1:1, 16:9)

 	
  * Panasonic DMC-ZS40 (4:3, 3:2, 1:1, 16:9)

 	
  * Sony ILCE-6500




## Noise Profiles:





 	
  * Canon PowerShot G7 X Mark II

 	
  * Olympus E-M1MarkII

 	
  * Lge Nexus 5X

