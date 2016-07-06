Simple Image Gallery
====================

A simple way photo gallery container using
[FGallery](https://github.com/wavexx/fgallery).

Usage
-----

At its core, this uses the [NGinX container](https://hub.docker.com/\_/nginx/).

Images to put in the gallery should be in the `/images` directory.

    docker run \
      --rm \
      -v ~/Downloads/kittens:/images \
      -p 80:80 \
      -e "GALLERY_TITLE=My Photos"
      docwhat/image-gallery
