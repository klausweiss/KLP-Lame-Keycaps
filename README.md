![](./Assets/KLP_Lame_Preview_All.jpg)

# KLP Lamé — Kailh Choc & MX Keycaps

This is a fork of https://github.com/braindefender/KLP-Lame-Keycaps. 
Refer to that repository for more info.


## The purpose of this fork

The main repository was forked to provide STLs of Choc versions which are easier to print with your FDM printer.

New models are to be found in [`STL/Choc/fdm/stl`](https://github.com/klausweiss/KLP-Lame-Keycaps/tree/master/STL/Choc/fdm/stl).

At the time of forking there were 8 distinct Choc keycap models.
Each of them was split to the top of the keycap and a common [stem](https://github.com/klausweiss/KLP-Lame-Keycaps/blob/master/STL/Choc/fdm/stl/legs.stl).

Printing the original model in one part is risky, as if you don't print the stem sideways, it can break off and stay in the switch.
Thanks to the way the models were split you can print the stem sideways, which will greatly improve the sturdiness of it.


## How to print and assemble the keycaps

Print lots of stems first, it will come in handy if you are in need to print more switches.
I print with a 0.4mm nozzle. Layer height doesn't matter this much for stem.

Then print the tops of the keycaps.
I use a layer height of 0.1mm.
Unfortunately the layer transitions are a bit noticeable, but you get used to it pretty quickly.
The models are already in correct orientation for printing.
You will need to print with supports underneath the bottom of the key.

As far as printing and supports go, here's what I recommend:
- **grid style** and
- whatever Quentin from [bastardkb.com](https://bastardkb.com/) recommends [here](https://docs.bastardkb.com/help/dactyl_print.html#supports) for printing Dactyls:
    - 75% XY separation
    - 0.1-0.25mm Z distance
    - 3-4 layer interface*
    - 100% fan speed (except for 1st layer)
    - 0.2mm interface spacing

When both stem and top are printed and supports removed from underneath the keycap top, glue them together with a fair amount of Super Glue.
If you use too little, the two are likely to break apart after a couple of days of use.
Luckily even if that happens, you take the intact stem out of the switch and glue to the top of the key again (but this time using more glue).
There is a pit in the top of the keycap where you insert the stem.

