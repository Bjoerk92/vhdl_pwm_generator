# vhdl_pwm_generator
Vhdl module for PWM generation.


## how to build using GHDL

to analyse the work use the followning command
> ghdl -a pwm.vhdl

to elaborate the work use the following command
> ghdl -e pwm 

to run the work use the following command 
> ghdl -r pwm

To record the running of the work use
> ghdl -r pwm --stop-time==100ns --wave=pwm.ghw

you can then use gtkwave to watch the wave.ghw file.

