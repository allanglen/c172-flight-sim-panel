---
title: Garmin GNS 530
permalink: /docs/avionics/garmin-gns-530/
---
# Garmin GNS 530

The [Garmin GNS 530](https://buy.garmin.com/en-US/US/p/119) has a larger, higher-resolution display than the smaller [Garmin 430](/docs/avionics/garmin-gns-430). Both are no longer in production but continue to be very common in general aviation aircraft.

This GPS is specifically designed for use with X-Plane 11.10 (or greater) and uses the [screen-only popup instrument window](https://developer.x-plane.com/2017/09/three-lesser-known-aircraft-features-for-11-10/) feature to render the GPS screen on an HDMI display that is integrated into the assembly.

{% include image.html file="garmin_gns_530_map.jpg" %}

{% include image.html file="garmin_gns_530_airports.jpg" %}

{% include image.html file="garmin_gns_530_mounted_right_view.jpg" %}

## Parts List

{% include parts.html %}

## Faceplate

The faceplate is laser cut from white acrylic, painted black, and then laser engraved.

{% include svg.html file="faceplate.svg" %}

## Hardware Mount

The hardware mount provides a layer for mounting the push-buttons and the display. I used acrylic for mounting the push buttons to simplify construction and to avoid having to create a circuit board. The push buttons are glued into the hardware mount.

{% include svg.html file="hardware_mount.svg" %}

## Frame Mounts

The frame mounts are used to attach the assembly to the [frame](/docs/frame).

{% include image.html file="frame_mount_left.jpg" %}

{% include svg.html file="frame_mount_left.svg" %}

{% include svg.html file="frame_mount_right.svg" %}

### Frame Mount Brackets

The frame mounts are attached to the hardware mount with these brackets and \#4 x 1/2" flat head screws.

{% include stl.html file="display_mounting_clips.stl" thing=2764205 
   image="https://cdn.thingiverse.com/renders/c6/3f/43/48/b0/d1ef4514cb0441461229379ad1ca340c_preview_featured.jpg" %}
   
The frame mounts also secure the display to the hardware mount and to the faceplate. A shallow 1/8" hole is drilled into the rear of the faceplate. The clips are designed to work with \#6-32 x 1/2 pan head screws.

{% include image.html file="hardware_mount.jpg" %}

{% include image.html file="garmin_gns_530_off.jpg" %}

### Electronics Mount

The electronics mount is used to attach the display electronics (HDMI controller board) and IO multiplexers to the assembly (more on the wiring coming soon).

{% include svg.html file="electronics_mount.svg" %}

Two 3d printed blocks are used for attaching the acrylic electronics mount to the frame mount brackets. The parts are attached with \#4 x 1/2" flat head screws.

{% include stl.html file="display_electronics_mount_block.stl" thing=2764205 
   image="https://cdn.thingiverse.com/renders/3b/c3/ea/1a/80/05e5d92b41b487360761c2e1b10e862a_preview_featured.jpg" %}

{% include image.html file="electronics_mount.jpg" %}

{% include image.html file="electronics_mount_zoom.jpg" %}

### Display Bezel

A 3d printed display bezel frames the active pixels on the display is similar to the bezel profile on a real GNS 530.

{% include stl.html file="display_bezel.stl" thing=2764205 
   image="https://cdn.thingiverse.com/renders/c4/ef/45/e5/b0/6adf7d57c5af66891184265308b86544_preview_featured.jpg" %}

{% include image.html file="garmin_gns_530_bezel.jpg" %}

## Buttons

The GPS buttons are 3d-printed from white PLA, painted, and laser-engraved.

### Small Buttons

{% include svg.html file="button_small_engrave.svg" %}

### Medium Buttons

{% include svg.html file="button_medium_engrave.svg" %}

### Zoom Button

{% include svg.html file="button_zoom_engrave.svg" %}

### Flip Flop Buttons

{% include svg.html file="button_medium_vertical_engrave.svg" %}

## Knobs

### Dual-Rotary Knobs

The knobs for the dual concentric rotary encoders are designed to match those found on a real GNS 530 and are 3d printed from white PLA, painted, and laser-engraved.

{% include stl.html file="knob_inner.stl" thing=2764205 
   image="https://cdn.thingiverse.com/renders/a4/0d/92/bc/c6/16d938061b9438ff41fe295429974ba8_preview_featured.jpg" %}

{% include stl.html file="knob_outer.stl" thing=2764205 
   image="https://cdn.thingiverse.com/renders/dd/38/54/c6/78/aeeb571b9cadac25ff907b3bd9abecea_preview_featured.jpg" %}

{% include svg.html file="knob_engrave.svg" %}

### Volume Knobs

The knob is 3d printed from white PLA, painted, and laser-engraved.

{% include stl.html file="volume_knob.stl" thing=2764205 
   image="https://cdn.thingiverse.com/renders/e1/85/6a/1f/8b/1576670b45151153a2681a1a933a3951_preview_featured.jpg" %}

{% include svg.html file="knob_volume_engrave.svg" %}
