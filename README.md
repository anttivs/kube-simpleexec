# Web shell on Kubernetes

## Guideline

This is a very simple test deployment to act as a basis for various kinds of Kubernetes hardening tests. The deployment is a simple web shell (see source code) that allows executing arbitrary commands within the Docker container.

If you deploy with unmodified YAML files, the container will be pulled off my Docker Hub repository. If you want to make further commands available to the web shell, you need to edit the Dockerfile appropriately.

## Lineage

The web shell and the container are a fork from https://github.com/LiamRandall/simpleexec. See README-original.md for the original background.