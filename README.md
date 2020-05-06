[![Docker Build Status](https://img.shields.io/docker/cloud/build/eagle2000/deepspeech-0.7.0-server-docker)](https://hub.docker.com/r/eagle2000/deepspeech-0.7.0-server-docker/builds)
[![Docker Automated Status](https://img.shields.io/docker/cloud/automated/eagle2000/deepspeech-0.7.0-server-docker)](https://hub.docker.com/r/eagle2000/deepspeech-0.7.0-server-docker)

# DeepSpeech Server v.0.7.0

How to use it 

``` ./build_images.sh ```

``` ./start_container.sh ```

``` rm -rf *.wav
youtube-dl --extract-audio --audio-format wav --output "test.%(ext)s" "https://www.youtube.com/watch?v=u9U6mXL3t_c"
ffmpeg -y -i test.wav -ss 00:00:58 -to 00:01:30 -ac 1 -ar 16000 test_o.wav
curl -X POST --data-binary @test_o.wav http://localhost:4243/transcribe
```
where u9U6mXL3t_c - id video

Thank you very much [JoachimVeulemans](https://github.com/JoachimVeulemans/deepspeech-server-docker)


