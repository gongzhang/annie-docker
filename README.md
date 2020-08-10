# annie-docker

Docker image for the [annie](https://github.com/iawia002/annie) video downloader.

Usage:

```sh
# download video to $PWD
docker run --rm -it --workdir /downloads \
    -v $PWD:/downloads gongzhang/annie \
    annie 'https://www.youtube.com/watch?v=RmPpiyD_oto'
```
