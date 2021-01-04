# Home Assistant Config

## Rhasspy
I am running Rhasspy on an Ubuntu Intel NUC 10i3FNK. The NUC serves as the base station, taking care of speech to text, intent recognition, text to speech, and intent handling. I have a Raspberry Pi serving as a satellite, taking care of care of wake word detection, audio recording, and audio playback.

## Node-Red
I am also running Node-Red on the NUC through Docker.

My flow requires the following nodes:
* node-red
* node-red-contrib-huemagic
* node-red-contrib-looptimer-advanced
* node-red-contrib-mytimeout
* node-red-contrib-play-audio
* node-red-contrib-play-sound
* node-red-node-openweathermap
* node-red-node-rbe
* node-red-node-tail
