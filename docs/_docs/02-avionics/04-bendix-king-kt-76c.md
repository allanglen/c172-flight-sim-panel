---
title: Bendix King KT-76C
permalink: /docs/avionics/bendix-king-kt76c/
---
# Bendix King KT76C

The [Bendix King KT76C](https://bendixking.com/en/products/productitems/kt-76c) is a 4096 code mode C transponder with a design that is relatively simple to replicate.

I had originally intended to build a Garmin GTX 327 but sourcing an appropriate display proved challenging.

To simulate the KT76C I am using a MAX7219 8-digit 7-segment display that is easy to source and simple to integrate with Arduino.

{% include image.html file="bendix_king_kt76c_mounted.jpg" %}

{% include image.html file="bendix_king_kt76c_mounted_on.jpg" %}

## Parts List

{% include parts.html %}

## Main Assembly

The front of the unit is assembled by sandwiching three layers of acrylic together: the faceplate, the spacer (also used for mounting the 7-segment display), and the hardware mount (for mounting the buttons).

The following image was taken after the three layers were assembled and painted.

{% include image.html file="bendix_king_kt76c_layers.jpg" %}

### Faceplate

The faceplate is laser cut from white acrylic, painted black, and then laser engraved.

{% include svg.html file="faceplate.svg" %}

{% include image.html file="bendix_king_kt76c_faceplate.jpg" %}


### Spacer

The spacer provides a layer for mounting the 7-segment display. The thickness of the 
acrylic provided the perfect depth for mounting a thin layer of darkened plastic in front of the display (see Bezel below).

{% include svg.html file="spacer.svg" %}

{% include image.html file="bendix_king_kt76c_rear.jpg" %}

### Hardware Mount

The hardware mount provides a layer for mounting the push buttons. I used acrylic for mounting the push buttons to simplify construction and to avoid having to create a circuit board. The push buttons are glued into the hardware mount.

{% include svg.html file="hardware_mount.svg" %}

## Frame Mounts

The frame mounts are used to attach the assembly to the [frame](/docs/frame).

{% include image.html file="bendix_king_kt76c_side.jpg" %}

{% include svg.html file="left_frame_mount.svg" %}

{% include svg.html file="right_frame_mount.svg" %}

## Electronics Mount and Mounting Brackets

The electronics mount is used for attaching electronics and attaches the side mounts to the front assembly. The holes and slot are for attaching a multiplexer which I plan to convert to in the future to simplify wiring.

{% include svg.html file="electronics_mount.svg" %}

The 3d printed brackets are used to attach the components together as shown below.

{% include image.html file="bendix_king_kt76c_assembly.jpg" %}

{% include stl.html file="front_bracket.stl" thing=2933873 
   image="https://cdn.thingiverse.com/renders/67/5a/b3/0e/54/809f090a86a41fb306a07d19479f3988_preview_featured.jpg" %}
   
   {% include stl.html file="side_bracket.stl" thing=2933873 
      image="https://cdn.thingiverse.com/renders/8f/55/6f/31/b2/7cb270f7cf0b0fc12d74a7559b9151b3_preview_featured.jpg" %}

## Display Bezel

A 3d printed display bezel is inserted into the faceplate to hold a layer of darkened plastic in front of the display. The plastic layer hides the internals and provide the appearance of a larger display.

{% include stl.html file="bezel.stl" thing=2933873 
   image="https://cdn.thingiverse.com/renders/09/46/45/73/2a/6adf7d57c5af66891184265308b86544_preview_featured.jpg" %}

{% include image.html file="bendix_king_kt76c_display.jpg" %}

{% include image.html file="bendix_king_kt76c_display_bezel.jpg" %}

For the plastic cover, I cut a rectangle from a CD jewel case and applied a layer of darkened film to the underside.

{% include image.html file="bendix_king_kt76c_assembled.jpg" %}

## Mode Switch

The mode switch switches the transponder from between the off, standby, test, on, and altitude-reporting modes using a 5 position switch.

{% include image.html file="bendix_king_kt76c_mode_switch.jpg" %}

## Buttons

The buttons are 3d-printed from white PLA, painted, and laser-engraved. 

All of the buttons are the same size and the svg file contains a layer for each of the labels.

{% include svg.html file="button.svg" %}

{% include stl.html file="display_bezel.stl" thing=2933873 
   image="https://cdn.thingiverse.com/renders/6c/10/b4/38/b0/fd9e4b077ecdf45762ce9707d49869b7_preview_featured.jpg" %}


