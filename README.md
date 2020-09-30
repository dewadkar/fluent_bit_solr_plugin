# Fluent-Bit Solr Output Plugin

Updated work of solr plugin for CPU input inside docker :

## Original Work:  ## https://github.com/oleewere/fluent-bit-solr-plugin

[![Docker Pulls](https://img.shields.io/docker/pulls/oleewere/fluent-bit.svg)](https://hub.docker.com/r/oleewere/fluent-bit/)
[![Go Report Card](https://goreportcard.com/badge/github.com/oleewere/fluent-bit-solr-plugin)](https://goreportcard.com/report/github.com/oleewere/fluent-bit-solr-plugin)
![license](http://img.shields.io/badge/license-Apache%20v2-blue.svg)

Fluent Bit Solr plugin

Clone the repo and go inside the folder of the repository and build the docker image.

$docker build -t <docker-image-name> <dir_path or . DOT as current directory>
    
Then use the path to specify the build image and create a ccontainer     


docker run -it --rm -v < /fluent-bit-solr-plugin/examples > :/fluent-bit/examples --name <image_name> <image_name> /fluent-bit/bin/fluent-bit -e /fluent-bit/out_solr.so -c /fluent-bit/examples/example.conf

This will run the configuration specified in example.conf

