PhpStorm Protocol
=================
This app allows to use "pstorm://" protocol to open a file in a PhpStorm IDE the same way as it's done in TextMate.

Following string must be specified as editor in your app: pstorm://open/?url=file://%file&line=%line

Also look at [http://pla.nette.org/en/how-open-files-in-ide-from-debugger] for more details about custom url handlers.