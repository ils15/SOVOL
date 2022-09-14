cfg files to use in Sovol SV04
You need to develop your start/end gcode instead.
I put my settings for reference

the archive dual extruder handle nozzle parking and offset
you can adjust offsets individually for T0 and T1. I prefer to adjust only T1 offset. You can use diffent Z offset to handle nozzle T0 and T1 (instead knob adjust).
Only need to insert SET_GCODE_OFFSET Z=OFFSET_VALUE
