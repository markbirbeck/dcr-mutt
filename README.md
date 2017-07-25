dcr-mutt
========

Uses Docker Compose to run Mutt.

This saves us having to install Mutt locally.

For an explanation of the thinking behind this module see the blog post [Disposable Laptops With Docker Compose And NPM](http://bit.ly/2tBCYHB).

The Docker image used is [fstab/mutt](https://hub.docker.com/r/fstab/mutt/).

To install, do:

```shell
npm install -g dcr-mutt
```

Once everything is set up as described on the Docker Hub page, run with:

```shell
$ dcr-mutt
```
