# Youtube-Radio-Template

A simple solution for hosting an easily accessible online radio

This small utility was created for the convenience of the author. It is an one-liner to launch a web radio stream, hosted on youtube, from a windows machine.

It utilizes FFmpeg as the encoder. Make sure FFmpeg is installed and in your Windows `PATH`.

Information that should be provided for the one-liner to work is the following:

- Your input device's name at `AUDIO_DEVICE`. You can find its name with `ffmpeg -list_devices true -f dshow -i dummy`.

- Your `STREAM_URL` and `STREAM_KEY` respectively, both of which can be found on your youtube stream's page. Keep the key a secret!

More info on device capturing commands [here](https://trac.ffmpeg.org/wiki/Capture/Desktop).

Stop streaming by pressing `q`.

---

A binary of FFmpeg  for 64-bit Windows can be found [here](https://ffmpeg.zeranoe.com/builds/win64/static/ffmpeg-4.2.3-win64-static.zip).

Licensing / Legal matters for of the FFmpeg binary are explained in detail [here](https://ffmpeg.org/legal.html).
