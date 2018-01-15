---
title: Key Switch
permalink: /docs/key-switch/
---
# 5 Position Spring-Return Key Switch

This key switch simulates the 5 positions on a standard Cessna 172 ignition switch (off, right magneto, left magneto, both, and start) and provides a spring return from the start position.

{% include image.html file="key_switch.jpg" %}

The switch is assembled from a 3d printed mount, a filing cabinet lock, and a 5 position rotary switch.

{% include image.html file="key_switch_animation.gif" %}

## Parts List

{% include parts.html %}

## Assembly

The components of the key switch are mounted into a 3d printed mount that allows a cabinet lock to be attached to a rotary switch and the cabinet lock arm to engage a spring when moved into the start position.

{% include stl.html file="key_switch.stl" thing=2687594 
   image="https://cdn.thingiverse.com/renders/5a/88/6d/c2/59/c6c4b9057df0631dab33539f41e4be01_preview_featured.jpg" %}

The rotary encoder is mounted into the small hole and the cabinet lock is pressed through the [panel](../) and into the large hole.

Some modifications must be made to the cabinet lock to allow the shaft of the rotary encoder to be securely attached:

1. Drill out the screw hole in the cabinet lock body to allow the shaft of the rotary encoder to be inserted snugly into the body of the lock. A washer or two may be needed to ensure the bar on the cabinet lock is securely fitted over the square mount on the cabinet lock body.
2. Drill a hole in the side of the cabinet lock body and tap it to allow a hex set screw to be secured against the rotary encoder shaft. A hole must also be made in the cabinet lock barrel to allow access to the set screw
3. Remove the rotational stop from the cabinet lock barrel. This design uses the stops of the rotary switch instead.

The key switch when assembled and mounted into the [panel](/docs/switch-panel/):

{% include image.html file="key_switch_mounted.jpg" %}

For wiring details, see [http://www.simvim.com/ardsimx/wire_dir.html](http://www.simvim.com/ardsimx/wire_dir.html). I used parallel 2k resistors as I did not have any 1k resistors in my parts bin.
