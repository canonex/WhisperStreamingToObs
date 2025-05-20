# Whisper Streaming To Obs
Transcribe or Translate to Obs session


This script listens to the audio interface [Whisper Streaming](https://github.com/ufal/whisper_streaming) and receives the text (transcribed or translated). After some transformations to remove the timecode and filter the content, it sends it, without timecode, to the Obs Websocket.

A maximum number of characters per line can be set and shorter lines are merged with a minimum character limit.

You must install dependencies and customise the scripts with the appropriate information.

## Dependencies

[Whisper Streaming](https://github.com/ufal/whisper_streaming)
[Websocat](https://github.com/vi/websocat)

## Customization

...


