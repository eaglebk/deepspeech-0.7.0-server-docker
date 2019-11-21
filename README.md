[![Docker Build Status](https://img.shields.io/docker/cloud/build/joachimveulemans/deepspeech-server-docker)](https://hub.docker.com/r/joachimveulemans/deepspeech-server-docker/builds)
[![Docker Automated Status](https://img.shields.io/docker/cloud/automated/joachimveulemans/deepspeech-server-docker)](https://hub.docker.com/r/joachimveulemans/deepspeech-server-docker)

# deepspeech-server-docker

This repository contains a Dockerfile to set up a DeepSpeech server

## Inference

`curl -X POST --data-binary audio/2830-3980-0043.wav http://localhost:8080/stt`
