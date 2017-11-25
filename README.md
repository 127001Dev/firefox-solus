# firefox-solus
firefox build that enables werender and servo.

Double check your about:config and about:support to make sure they are enabled.

Turn webrender/acceleration on:
turn off layers.async-pan-zoom.enabled
turn on gfx.webrender.enabled
turn on gfx.webrendest.enabled
turn on gfx.webrender.layers-free
add and turn on gfx.webrender.blob-images
turn on layers.acceleration.force-enabled

Turn servo on:
layout.css.servo.enabled set it to true.

Just change the settings back to disable webrender and servo.
