---
title: Instrument Panel
permalink: /docs/instrument-panel/
---

# Instrument Panel

The instrument panel simulates the typical setup in a steam gauge Cessna 172. I opted to build a steam gauge panel to support training with traditional instruments.
                                                                              
The gauges are [software rendered](#display) and provide physical interaction through hardware controls.

{% include image.html file="instrument_panel.jpg" %}

## Parts List

{% include parts.html %}

## Panel

The instrument panel is constructed from painted 1/4" inch birch plywood with cutouts for mounting instrument bezels and hardware. All parts for the panel are designed to fit into the depth of the panel.

Channels are routed into the panel for wiring the instruments to a terminal block that [connects to an Arduino Mega](/docs/io) through a slot cut into left side the [frame](/docs/frame).

## Display

I use a 23" display (I had an unused Acer V233H lying around) to render the instruments behind the hardware panel. The display is stripped down (case removed) and is mounted directly into the [frame](/docs/frame/).

{% include image.html file="instrument_display.jpg" %}

### Software

The instruments are rendered with [Air Manager](https://www.siminnovations.com/). I have made some minor customizations but most of the instruments that I am using are provided either by Sim Innovations or the community.

{% include image.html file="air_manager.jpg" %}

## Bezels

The instrument bezels provide a clean way for framing the 2d instruments and provide a means for securely mounting rotary encoders into the panel.

{% include image.html file="bezel_lcd.jpg" %}

{% include image.html file="bezels_installed.jpg" %}

### Large Instruments (3 1/2")

#### Tachometer, turn and balance indicator
{% include stl.html file="bezel_large.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/f5/dd/02/7e/b4/bcd29e43e508982c7a6248004207fe23_preview_featured.jpg" %}

#### Airspeed indicator, altimeter, vsi, vor, adf

{% include stl.html file="bezel_large_single_encoder.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/ad/56/ee/d8/c5/c8274b04c022eb560f5eb3016d9ff824_preview_featured.jpg" %}

#### Gyro compass

{% include stl.html file="bezel_large_dual_encoder.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/57/70/aa/95/02/4f2366d3d5626a22a1b49f78964c66ce_preview_featured.jpg" %}
   
#### Attitude indicator

{% include stl.html file="bezel_large_attitude.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/3e/a3/57/92/ad/e1817d9e19f8f73877e49e1d126848e1_preview_featured.jpg" %}

### Small Instruments (2 1/4")

#### vacuum/ammeter, fuel quantity, engine temp/press.
{% include stl.html file="bezel_small.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/7e/19/b4/fa/40/a7908e04e2fe741fddfd757d57ce99ea_preview_featured.jpg" %}

#### EGT/fuel flow

{% include stl.html file="bezel_small_egt.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/c6/26/eb/45/5e/18b6e8353e04c0a28694485bd8a7e288_preview_featured.jpg" %}

#### Clock

{% include stl.html file="bezel_small_clock.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/6c/ef/02/de/13/85495e42e1ecd52ded2b2a4fdee56f2b_preview_featured.jpg" %}
   
#### Clock buttons

{% include stl.html file="bezel_small_clock_button.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/2a/9c/08/7f/c1/aa12695fb33f248eabd996570ed714c9_preview_featured.jpg" %}

### Annunciators

{% include stl.html file="bezel_annunciator.stl" thing=2690541 
   image="https://cdn.thingiverse.com/renders/b6/18/b7/cd/bf/ea642fa15b62c3cd30a555506e826603_preview_featured.jpg" %}
