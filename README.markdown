# Libemqtt

This program is a fork of libemqtt <https://github.com/menudoproblema/libemqtt> developed by Vicente Ruiz, which is a fork of liblwmqtt developed by Filipe Varela.
You can find the original project on <http://code.google.com/p/liblwmqtt/>.

libemqtt aims to be an embedded C client library for the MQTT protocol. It also
provides a binding for Python.

## Status

Under development. I am using it in production and it seems to work fine, but it is a work in progress. I will do what I can to maintain this project in my spare time, but if the need arises and anyone is interested in taking it over (including Vicente Ruiz), feel free. 

## Compile

### C Library

> $ make

### Python binding

> $ make python

## Install

### C Library

### Python binding

> $ sudo ln -fs /home/user/libemqtt/client/libemqtt.so /usr/lib/python2.7/emqtt/libemqtt.so


# Limitations

* Can not subscribe to multiple topics in the same MQTT message.



# Additional

For debugging MQTT development it's possible to use
Wireshark-MQTT (https://github.com/menudoproblema/Wireshark-MQTT)
