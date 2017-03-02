Logging is a essential task for implementing and debugging sketches on Arduino or ESP8266 platforms.
As default, in most cases the Serial.print() resp. Serial.println() function is used for this purpose. But these funktions are not very flexibel at all.
SimpleLog provides a class to output the wanted information to any stream-class object, e.g. Serial, Wire and so on. The formatting of the logged data is controlled by a printf-like format-string which knows about several identifier like %s, %d ...


##General:
To install the library, you may download the zip-file or clone the repository into your sketchbook/libraries folder.

