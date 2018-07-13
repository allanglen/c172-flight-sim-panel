---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/hero.jpg
  overlay_filter: 0.2
  cta_label: "<i class='fas fa-book'></i> Details"
  cta_url: "/docs/"
excerpt: >-
  Design files, 3d models, wiring diagrams, and code artifacts for building a Cessna 172 Skyhawk flight simulator.<br /><br />
  {::nomarkdown}
  <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=allanglen&repo=c172-flight-sim-panel&type=watch&count=true&size=large&v=2" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>
  <iframe style="display: inline-block;" src="https://ghbtns.com/github-btn.html?user=allanglen&repo=c172-flight-sim-panel&type=star&count=true&size=large" frameborder="0" scrolling="0" width="158px" height="30px"></iframe>
  {:/nomarkdown}
feature_row:
  - image_path: /assets/images/highlight-instrument-panel.jpg
    alt: "steam gauge panel"
    title: "Steam Gauge Panel"
    excerpt: >-
      I opted to build a [steam gauge panel](/docs/instrument-panel) to support training with traditional instruments.<br/><br/>
      The gauges are software rendered on a display with physical interaction provided through hardware controls.
    url: "/docs/instrument-panel/"
    btn_class: "btn--primary"
    btn_label: "Details"
  - image_path: /assets/images/highlight-avionics.jpg
    alt: "avionics stack"
    title: "Avionics Stack"
    excerpt: >-
      I'm building a complete [avionics stack](/docs/avionics) with an audio panel, GPS (GNS530 and GNS430), transponder, and auto-pilot.
    url: "/docs/avionics/"
    btn_class: "btn--primary"
    btn_label: "Details"
  - image_path: /assets/images/highlight-switch-panel.jpg
    alt: "X-Plane compatible"
    title: "X-Plane Compatible"
    excerpt: >-
      The hardware here is designed to work with [X-Plane 11](http://www.x-plane.com/) and is interfaced using [ArdSimX](http://www.simvim.com/ardsimx.html).<br/><br/>
      It should also be possible to use this hardware with other flight sims (FSX, P3D) via [FSUIPC](http://www.schiratti.com/dowson.html).
    url: "/docs/io/ardsimx/"
    btn_class: "btn--primary"
    btn_label: "Details"
intro:
  - excerpt: >-
      I'm building a desk-mounted Cessna 172 flight simulator instrument panel for use as a training device in conjunction with real-world flight training.
      <br/><br/>
      This project is very much a [work in progress](/docs#status) and I'll be adding new content over time.
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}