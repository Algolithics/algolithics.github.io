---
layout: post
title: Generating sounds in Python - must use float64!
---
Was playing with generating binaural sounds in Python.
Almost ended debugging my sound card - strange glitches appeared.
My bad was thinking float32 will is enough for calculations. Few seconds of audio quickly builds millions of samples and even small error gets multiplied by milions quickly.
The result - it can shift frequency by 10Hz after 12-15 sec depending on sampling!
Plus there are some glitches to different frequency bands and it's not always visible on spectrum like in Audacity - but for some parts it was.
Didn't expect that.
Most important - generate the time scale in float64 but better/quicker - do all float64- so that no need to debug deeply.

