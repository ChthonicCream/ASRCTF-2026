Challenge: `Shady Activities`<br>
Author: `nmluan`<br>

Description:<br>
A graphics pipeline tool deployed on Space Station GROUND-CTRL-01 was
flagged after an analyst noticed it was writing framebuffer output to a
location with no legitimate display attached. The tool identifies itself
as a SPIR-V shader validator, but nothing about its behaviour lines up
with that claim.<br>

A copy of the binary has been pulled from the station before the system
was taken offline. It produces a 40×1 PPM framebuffer when run; no GPU
is required. Your task is to recover the flag.<br>

Distributed file: shady_activities
