# Docker image with apt tools & cache

Development/testing image to issues `apt` commands.

:bulb: This image contains a pre-populated cache from `apt-get update`, which is not considered best-practice, but this is basically the whole idea of this image.

## Usage examples

Show dependencies for a package

    docker run schmunk42/apt apt-cache depends php5-intl

## Resources

- https://hub.docker.com/r/schmunk42/apt/

---

Built by [dmstr](http://diemeisterei.de)
