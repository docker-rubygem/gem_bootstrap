[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/gem_bootstrap.svg)](https://hub.docker.com/r/rubygem/gem_bootstrap/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/gem_bootstrap.svg)](https://hub.docker.com/r/rubygem/gem_bootstrap/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/gem_bootstrap.svg)](https://hub.docker.com/r/rubygem/gem_bootstrap/)
[![Gem Downloads](https://img.shields.io/gem/dt/gem_bootstrap.svg)](https://rubygems.org/gems/gem_bootstrap/)
# gem_bootstrap

Auto-Generated Docker image for gem_bootstrap to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/gem_bootstrap`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/gem_bootstrap`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/gem_bootstrap`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/gem_bootstrap/)
