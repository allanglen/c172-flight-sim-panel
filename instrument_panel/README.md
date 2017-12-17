# Instrument Panel

The instrument panel simulates the typical setup in a steam gauge Cessna 172.

![switch_panel](images/instrument_panel.jpg)



## Panel

The instrument panel is constructed from painted 1/4" inch birch plywood with cutouts for mounting instrument bezels and hardware. All parts for the panel are designed to fit into the depth of the panel.

Channels are routed into the panel for wiring the instruments to a terminal block that [connects to an Arduino Mega](../io) through a slot cut into left side the [frame](../frame).

## Instrument Bezels

The instrument bezels provide a clean way for framing the 2d instruments that are rendered on the LCD (via [Air Manager](https://www.siminnovations.com/)) and provide a means for securely mounting rotary encoders into the panel.

There are models for each bezel type (`bezel_large.FCStd`, `bezel_small.FCStd`, `bezel_annunciator.FCStd`) and components in each model can be toggled on/off to produce STL files for all of the required instruments.

### Large Instruments (3 1/2")

`bezel_large.stl` (tachometer, turn and balance indicator)

![large_bezel.stl](https://cdn.thingiverse.com/renders/4f/a6/b1/d0/d8/bcd29e43e508982c7a6248004207fe23_preview_featured.jpg)

`bezel_large_single_encoder.stl` (airspeed indicator, altimeter, vsi, vor, adf)

![bezel_large_single_encoder.stl](https://cdn.thingiverse.com/renders/ad/56/ee/d8/c5/c8274b04c022eb560f5eb3016d9ff824_preview_featured.jpg)

`bezel_large_dual_encoder.stl` (gyro compass)

![bezel_large_dual_encoder.stl](https://cdn.thingiverse.com/renders/57/70/aa/95/02/4f2366d3d5626a22a1b49f78964c66ce_preview_featured.jpg)

`bezel_large_attitude.stl` (attitude indicator)

![bezel_large_attitude.stl](https://cdn.thingiverse.com/renders/3e/a3/57/92/ad/e1817d9e19f8f73877e49e1d126848e1_preview_featured.jpg)

### Small Instruments (2 1/4")

`bezel_small.stl` (vacuum/ammeter, fuel quantity, engine temp/press.)

![bezel_small.stl](https://cdn.thingiverse.com/renders/7e/19/b4/fa/40/a7908e04e2fe741fddfd757d57ce99ea_preview_featured.jpg)

`bezel_small_egt.stl` (egt/fuel flow)

![bezel_small_egt.stl](https://cdn.thingiverse.com/renders/c6/26/eb/45/5e/18b6e8353e04c0a28694485bd8a7e288_preview_featured.jpg)

`bezel_small_clock.stl` (clock)

![bezel_small_clock.stl](https://cdn.thingiverse.com/renders/6c/ef/02/de/13/85495e42e1ecd52ded2b2a4fdee56f2b_preview_featured.jpg)

`bezel_small_clock_button.stl` (clock buttons)

![bezel_small_clock_button.stl](https://cdn.thingiverse.com/renders/2a/9c/08/7f/c1/aa12695fb33f248eabd996570ed714c9_preview_featured.jpg)

### Annunciators

`bezel_annunciator.stl` (annunciators)

![bezel_annunciator.stl](https://cdn.thingiverse.com/renders/b6/18/b7/cd/bf/ea642fa15b62c3cd30a555506e826603_preview_featured.jpg)

## Parts List

| Component                          | Part                                     | Quantity  | Source                 |
| ---------------------------------- | ---------------------------------------- | --------- | ---------------------- |
| Panel                              | 1/4" birch plywood                       | 14" x 24" |                        |
| Screws (for attaching instruments) | \#6-32 x 1/4" Phillips Pan Head Screws   | 55        | http://amzn.to/2yMTstO |
| Screws (for attaching panel)       | \#8 x 3/4" Phillips Truss Head Screws    | 12        | http://amzn.to/2zjDXx6 |
| Encoders                           | Low-profile rotary encoders, 6mm shaft   | 9         | http://amzn.to/2BmVPXe |
| Buttons (for clock)                | Tactile push buttons (6x6x4.3mm)         | 3         | http://amzn.to/2kC8qxS |
| Annunciator switch                 | 3 position 2P3T Micro Right Angle Slide Switch | 1         | http://amzn.to/2kFSRVM |

