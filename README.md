Simple Image Gallary
====================

A simple way photo gallery container using
[FGallary](https://github.com/wavexx/fgallery).

Usage
-----

At its core, this uses the [NGinX container](https://hub.docker.com/_/nginx/)
so options from there work here.

Images to put in the gallery should be in the `/images` directory.

    docker run --rm -v ~/Downloads/kittens:/images -p 80:80 image-gallery
