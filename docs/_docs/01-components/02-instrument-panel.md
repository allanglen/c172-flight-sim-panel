---
title: Instrument Panel
permalink: /docs/instrument-panel/
---

# Instrument Panel

The instrument panel simulates the typical setup in a steam gauge Cessna 172. I opted to build a steam gauge panel to support training with traditional instruments.

The instrument panel is comprised of a layer of hardware that is mounted over a 23" HDMI display.

{% include image.html file="instrument_panel.jpg" %}

The instruments are rendered with [Air Manager](https://www.siminnovations.com/). I have made some minor customizations but most of the instruments that I am using are provided either by Sim Innovations or the community.
                                                                            
{% include image.html file="instrument_display.jpg" %}

## Parts List

{% include parts.html %}

## Display

I use a 23" display (I had an unused Acer V233H lying around) to render the instruments behind the hardware panel. The display is stripped down (case removed) and is mounted directly into the [frame](/docs/frame/).

{% include image.html file="display_01.jpg" %}

The display is mounted as close to the left as possible given the curve of the glare shield.

{% include image.html file="display_02.jpg" %}

The display is set into the frame and held in place by a [panel](#panel) that is mounted to the frame.

{% include image.html file="display_03.jpg" %}

{% include image.html file="display_04.jpg" %}

{% include image.html file="display_05.jpg" %}

## Panel

The instrument panel is constructed from painted 1/4" inch birch plywood with cutouts for mounting instrument [bezels](#bezels) and hardware.

{% include image.html file="panel_01.jpg" %}

{% include image.html file="panel_02.jpg" %}

{% include image.html file="panel_03.jpg" %}

The electrical components (rotary encoders, buttons, and switches) mount into the rear of the bezels and the wiring is routed via channels cut in the back of the plywood. The channels were cut using a {% include part.html id="dremel" label="Dremel" %} with a router bit.

{% include image.html file="panel_rear_01.jpg" %}

{% include image.html file="panel_rear_02.jpg" %}

{% include image.html file="panel_rear_03.jpg" %}

{% include image.html file="panel_rear_04.jpg" %}

{% include image.html file="panel_rear_05.jpg" %}

{% include image.html file="panel_rear_06.jpg" %}

The wiring bundle is passed through a cutout in the frame and connected to an {% include part.html id="arduino_mega" %}.

{% include image.html file="wiring_routing_01.jpg" %}

{% include image.html file="panel_attach_03.jpg" %}

All parts for the panel are designed to fit into the depth of the panel, allowing the bezels to fit flush against the display.

{% include image.html file="panel_attach_01.jpg" %}

{% include image.html file="panel_attach_02.jpg" %}

{% include image.html file="panel_attach_04.jpg" %}

{% include image.html file="panel_attached_02.jpg" %}

{% include image.html file="panel_attached_01.jpg" %}

## Bezels

The instrument bezels are 3d printed and designed to allow the hardware to be mounted cleanly into the panel. The holes in the plywood were cut using a {% include part.html id="hole_saw_3_125" label='3 1/8" hole saw' %}.

{% include image.html file="bezel_lcd.jpg" %}

{% include image.html file="bezels_installed.jpg" %}

A router guide was designed and 3d printed to cut out the bezel tabs using a flush trim router bit.

{% include stl.html file="bezel_large_router_guide.stl" thing=2690541 
    image="https://cdn.thingiverse.com/renders/63/3c/b3/56/f5/6fda26d00e11bedbcd7b14600c7b7b00_preview_featured.jpg" %}

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
