# HTTP Shortcuts preset for Jotter

[HTTP Shortcuts](https://http-shortcuts.rmy.ch) is an Android app that allows
you to place widgets on your home screen which trigger user-defined HTTP
requests. This repository contains a preset for import into the app that
provides widgets you can use with the
[Jotter](https://github.com/davidhusz/jotter) note and file storage app.

## How to import

In the HTTP Shortcuts app, go to the context menu > `Import / Export` > `Import
from URL` and paste
https://github.com/davidhusz/jotter-http-shortcuts/raw/main/shortcuts.json.
After that, you will have to change the value of the `jotter_server` variable to
the address of your own Jotter instance.

**Note**: If you have existing shortcuts, these will not be lost, however, any
previous versions of the same Jotter shortcuts (i.e. with the same UUID) will
be overwritten.
