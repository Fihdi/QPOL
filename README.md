# 8hp Quad Pole Phaser
![](https://github.com/Fihdi/QPOL/blob/main/QPOL-Front.png?raw=true)

QPOL is an 8hp Eurorack phaser module with four voltage controllable all pass filters. A variety of frequency responses can be achieved by mixing the phase shifted output back to the input signal. Chaining multiple phaser modules together allows for phasing with 4, 8, 12, 16 etc poles.

![](https://github.com/Fihdi/QPOL/blob/main/QPOL-BLOCK.png?raw=true)
# IN
Connect an audio signal to the **IN** jack. The input signal is internally mixed together to the output of the **FDBK** section. This mixed signal is then fed to the four all pass filters. The **IN** signal is also routed to the **OUT** jack where it is mixed together the filter output **P4** with variable strength.
# SHIFT
The **SHIFT** knob, **CV** jack, as well as its attenuverter knob, set the the cutoff frequency of the all pass filters. By modulating the **SHIFT** parameter, the filter changes the phase shift of the **IN**. An LED indicates the level of modulation.
# FDBK
The FDBK attenuverter controls the amount and polarity of feedback from the filter output **P4**, which is added back to the input signal. An external signal from the **EXT** input jack can be routed to the FDBK attenuverter with the **P4 EXT** switch.
# P4, OUT and MIX

The **P4** jack directly outputs the fourth stage of the all pass filter core. When chaining multiple modules together to allow for more than four stages of phasing, this output can be used

The **MIX** knob sums the **IN** signal to the filter output **P4** with variable strength. By changing the Jumper on the back of the module from "Direct"

The final output is available at the **OUT** jack.
