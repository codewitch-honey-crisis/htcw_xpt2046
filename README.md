# XPT2046

A device driver for the XPT2046 touch panel

This library allows you to use one of the common touch panels that come on some TFT displays.

```
[env:node32s]
platform = espressif32
board = node32s
framework = arduino
lib_deps = 
	codewitch-honey-crisis/htcw_xpt2046@^1.0.0
lib_ldf_mode = deep
```