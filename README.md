# CAPTION.Ninja

This is a free-to-use captioning tool.


### How to use

To use this app, accept the microphone permissions on page load and then just say something outloud.

The output of this app is mirrored here: https://caption.ninja/overlay?room={someromoname}.

Please note that this app uses your default microphone as the audio input source. You can't change the default audio source from within the app, but you can change it at your system level by changing the default recording device. You can also change audio sources by using a virtual audio cable, such as this one. Using it, it becomes possible to select other sources, including microphones, speakers, and other applications.

Using Google Chrome is strongly recommended for best results.

If you wish to save the translations, just select-all when done (ctrl+a), copy the selected text(ctrl+c), pasting it into text editor (ctrl+v).

### Studio integration

Add it to OBS, VMix or other studio software as a browser source overlay if wishing to use it for a live stream. It also works with the Electron Capture app, which can allow you to pin the app on-top of other apps on your desktop with ease. https://github.com/steveseguin/electroncapture

### Language Codes
Language codes options available; default is `&lang=en-US`.  Just change the en-ES to a language code of your choosing.  A list of codes is here: https://cloud.google.com/speech-to-text/docs/languages

### Self-hosting
You can sign up at https://www.piesocket.com/ for a free account if you wish to use your own API server for transferring data. You can use the API key given to specify that via the URL in Caption.Ninja, such as:

```https://caption.ninja/?room=XLk5tqU&pie=ZCu96UFf9ezeQeClK7BOCkq6Q0x0lxWAPJcgxjz5```

You can also deploy your own basic websocket server with this code: https://github.com/steveseguin/websocket_server/

### Manual text entry
Manual text entry mode is also supported via https://caption.ninja/manual.html

### Disclaimers
I am not responsible if this app fails to work or whatever else. It is provided as-is without warranty or support. I do not take responsibility for any liability.
