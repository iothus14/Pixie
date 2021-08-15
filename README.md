# Pixie

<img src="https://user-images.githubusercontent.com/15040017/129494510-5d543a6a-266e-4b64-ae32-f8f9b0853c07.png" width="320" height="217" />

## Product Overview

Pixie is a WiFi LED controller made to drive different types of addressable LEDs. The controller has 4 independent hardware channels and can drive 4 different types of addressable LED strips. The device can be fully controlled over MQTT. Animation light effects, static light effects, light transitions, settings of every channel can be set over MQTT messages. The device has a web-based UI where it can be configured to connect to a WiFi access point as well as the inbuilt MQTT client to connect to any MQTT broker. The WebUI provides possibilities to control all light channels as well.


## Supported LEDs

Pixie supports different types of 5V driven addressable LEDs such as WS2812 / WS2812b / WS2812d / WS2811 / SK6812 (RGB) / SK6812 (RGBW) / APA102. 


## Animation light effects

There are many light animation effects which Pixie can drive on the connected LED strips. Each effect can be configured by two different parameters to adjust animation speed and animation intensity. Many light animation effects have a solid color as an input parameter to drive the effects in a different color palette.  

## Static light patterns

Besides the animations Pixie has configurable static light patterns as well as a static pattern which can be fully configured by a user to light up certain LEDs on an LED strip in certain colours. This can be even useful if the user wants to create their own slow custom animation effects by sequentially sending one pattern by another. For instance to display a fully controllable progress bar on an LED strip or emulate a traffic light with certain LEDs.


## Light transitions

There are transition light effects which Pixie can drive to animate a transition from one solid color to another. The transition effects can be used to gradually turn on / turn off the LEDs. For example to emulate a sunset / sunrise on the LEDs or simply turn off LEDs with a programmable transition. 


## OTA

The controller can update its software by receiving a new firmware version over the air (OTA) It requires only a connection to a WiFi network with an internet access.


## Documentation

Pixie has a detailed document with many examples of how to control or configure the device for any needs. The device can be easily integrated into any smart home system like Home Assistant or similar.
