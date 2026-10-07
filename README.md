# SP-404MKII Sound Generator experiments

Experiments with the Sound Generator built into the Roland SP-404MKII (firmware 5.52).

## Type 15+ Wave Lab

A playable browser page with the 17 waves the DOOM OS fork adds to the Sound Generator. On the SP they come after Noise2 as types 15–31. Each one is built only from the cycle position and the Duty knob. Stock Saw and Pulse are included for comparison.

**Play it:** https://tracelistener.github.io/sp404mk2-sound-generator/

Use the pads (or keys 1–4, Q–R, A–F, Z–V), sweep Duty, and switch types with the arrow keys. Everything runs in your browser; nothing on the page talks to the SP-404MKII.

## On the SP

The waves are in the DOOM OS fork: https://github.com/tracelistener/doom-os-etc.

Open the patcher at https://tracelistener.github.io/doom-os-etc./, load the stock 5.52 `SP404MKII_APP1.bin` and select **Sound Generator (4 voices + 17 new waves)**. Use the patched APP1 with the stock 5.52 APP0. It's experimental: back up first and keep Roland's update for rollback.

The wave math is the same as on this page. The SP adds four voices, a fixed loudness table for every type and Duty step, and raw whole-step Duty with no smoothing.

This repository contains no Roland firmware. Not affiliated with or endorsed by Roland.
