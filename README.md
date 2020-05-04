![](https://github.com/justlep/neutron-osc-sync-mod/blob/master/header.jpg?raw=true)

# OSC SYNC mod for Behringer Neutron     

A description of how I modified my Behringer Neutron synthesizer,
adding circuitry known from the `Prophet 5 rev3`, allowing for a much cleaner OSC SYNC 
sound than the Neutron's native one. An added flip-switch on the front panel now allows me to 
toggle between the Neutron's harsh default sync and the smooth, modded behavior that is 
also heard in the `Behringer Pro-1`.

## Inspiration / Must-Reads
* This Reddit from the guy who once published this mod (but then completely removed it from the web):  
  https://www.reddit.com/r/synthesizers/comments/9h5aem/behringer_neutron_sync_mod_by_some_clever_guy/
* electricdruid's fantastic article on the 3340 VCO:  
  https://electricdruid.net/cem3340-vco-voltage-controlled-oscillator-designs/  
  I used the sync circuit from the `Sequential Prophet 5 Rev.3` scheme in that article.
* This discussion on Gearslutz:  
  https://www.gearslutz.com/board/electronic-music-instruments-and-electronic-music-production/1199238-behringer-neutron-semi-modular-182.html

## Sound demo/comparison of native vs. modded OSC SYNC
  
See [this YouTube video](https://youtu.be/Zf8RpgcNlwU).
  
## Requirements
The whole circuit is extremely inexpensive. I had old, used SMD components lying around,
so it cost me nothing except for the €1 flip switch from Amazon. 
* BC859 PNP transistor  
  (because I had one at hand; the other guy used a BC858, and the Prophet scheme suggests a 2N4250)
* resistor 10k
* resistor 47k
* cap 100nF
* cap 200pF
* 1 flip switch (3-pole, ON-ON)
* you will also want enough shrinkwrap at hand
  
## Full description in a single image

![](https://github.com/justlep/neutron-osc-sync-mod/blob/master/behringer-neutron-osc-sync-mod.jpg?raw=true)


## Disclaimer

* Modifying your Neutron will void its warranty.  
* This repo is a pure "works for me" description of how _I_ modified _my_ Neutron.  
* I am NOT a professional electronics engineer, and I do NOT guarantee correctness or harmlessness of anything.
* You alone are responsible for damages you do to yourself or your device.
