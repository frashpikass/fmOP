#fmOP - A Pure Data FM synthesizer inspired by Yamaha DX7

##(C) 2017-2018 Frash Pikass

##Setup

These patches have been developed using the Purr Data 2.0 distro, which you can find [here](http://l2ork.music.vt.edu/main/make-your-own-l2ork/software/).

It will probably work in Pd-l2ork and Pd-Extended too, but I haven't tested it yet.

They might work in Vanilla, provided you have these libraries installed:
- zexy
- iemlib
- IEMguts
and provided you substitute the output abstraction in testOutput.pd with your favourite DAC abstraction.


##Usage
1. Plug in a MIDI keyboard.
2. Launch main.pd.
3. Set up your synth or load a preset.
4. Select the correct modwheel channel (if any -- you can find it by looking at PD's "Media > Test audio and MIDI" option).
5. Turn the DSP on.
6. Play.


##How to build a synth

You have many options:
- you could manually set every parameter by hand;
- you could start by selecting one of the available FM algorithms (wait a minute for the parameters to load!)
- you could start by loading a preset.

Make sure the DSP is on before playing!

Also, take some time look at the available documentation.
