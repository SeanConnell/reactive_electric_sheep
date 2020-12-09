# reactive_electric_sheep
An attempt to make music reactive electric sheep.

The basic idea is to be able to take music beat and cue information (TODO decide on format, hopefully there's a standard, else invent one) and 
combine it with an existing sheep xml document to modify (lightly!) the sheep to flow with the music. If that's too easy, figure out how to do it real time.

# TODO: Research
* https://github.com/librosa/librosa is popular for analysis, likely a good starting ground for prototyping. 
* flam3 editors and other approaches.

# Ideas
* a DAW style editor for user inputs on how to mix the sheep. This would be an alternate path to auto-generating the mixing and would allow a human to cheoreograph shows. I believe there exist solutions for this today for VJ-ing and various led driver packages. It would probably be good to pick one and modify it to alter sheep.
* sheep visualizer as a service. Send music in and get sheep out (at some phase delay). If it worked well enough you could use it live with whatever small buffer is typical of those shows. 

