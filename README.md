# mario-paint-plotter
A simple scrap of python to do image plotting in Mario Paint on the SNES via Bizhawk's TASStudio

# Notice

***This repository is archived. It has been consolidated into a more general repository for TAS-related code. Please go there for the most recent version, updates, etc. This version will no longer be updated.***

https://github.com/greysondn/tas-stuff

This was planned really badly. I had really planned to just let this code sit and maybe do a couple unit tests and work towards fixes. The TAS it led to, however, was more well received than I expected, and as a result I would like to try to get this working much better.

# Environment
```
Python  3.7.2rc1
Pillow  8.0.1
Bizhawk 2.6.1

SNES - BSNES core, controller set to first port mouse, second port joypad

Matching ROM Image (GoodTools):
Mario Paint (JU) (!).smc
```

# How?
The code is largely self-documenting. Obnoxiously so in some cases, due to my own bad memory and obsessive note taking.

Run `plotter.py` under Python 3 for a REPL. Examine the code itself for a headache and stuff you can probably make use of with a little work.

The strange looking lines the plotter spits out and waits for you to see are copy/pastable directly into TASStudio.

# Why
I just really wanted to color a dinosaur, man.

The run this was built for has now been submitted; please see:  
http://tasvideos.org/7073S.html
