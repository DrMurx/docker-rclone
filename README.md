# Rclone Docker Image

This image allows to run an one-off command of [Rclone](http://rclone.org/).

Rclone is a command line program to sync files and directories to and from

* Google Drive
* Amazon S3
* Openstack Swift / Rackspace cloud files / Memset Memstore
* Dropbox
* Google Cloud Storage
* Amazon Cloud Drive
* Microsoft One Drive
* Hubic
* Backblaze B2
* Yandex Disk
* The local filesystem

## Installation

Pull [the latest image](https://hub.docker.com/r/drmurx/rclone/) from Docker Hub:

    docker pull drmurx/rclone

Run an rclone command using `docker run`:
    
    docker run -ti -v /path/to/files:/files drmurx/rclone <PARAMETERS>

## Licence

Code licensed under The MIT License (MIT).

Based on https://github.com/valentine/docker-rclone-sh
