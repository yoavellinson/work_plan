# Spring SW workplan

## TDL

### Yoav
- [ ] Try the full [demo](https://gitlab.inria.fr/spring/wiki/-/wikis/Robot%20Behavior%20Integration%20Demo%20INRIA). The [compose-file](https://gitlab.inria.fr/spring/dockers/-/blob/erm/docker-compose.yml) on branch "erm". Check on pulling the containers on screen session "spring" on bari_server.
- [ ] Create a ROS application using a mock Detection of Activity (DOA) - use ReSpeaker DOA at first for a rough estimation.
- [ ] Send ERM new docker versions.
- [ ] Create a ROS application using a mock for speaker extraction (place holder app).
- [ ] Write unit tests for all ROS packages.

### Ariel
- [ ] Speaker extraction - implement strategies: 1. select a second of audio from the buffer, 2. insert one secind of audio with 4 seconds of silence. 3. repet with 2 seconds of audio.
- [ ] Experiments - record separation vs extraction

### Ohad

- [ ] DOA class with a get_angle() method.
- [ ] Experiments - RIRs, babble (eglish and french)
- [ ] Create an offline audio-pipeline.


## Mordechay
 - [ ] clean separation package 
