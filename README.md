# Dogfight--now two versions
based on lovely demo by AJ Campbell, but with a lot more stuff added for those of us with shorter attention spans.

PlayerJet and Enemy AI Jet are based on stock Unity models (uses their flight controls), but... (the following describes 2nd version, Dogfight 4)

1) both jets are armed with 3 MGs, based on AJ's model but 3 vs 1, because more--spacebar shoots for Player jet, AI jet shoots when its close enough behind.  AI jet turns slowly and isn't an immediate threat, but if you fly straight for long enough it will shoot you down, until it's killed.  Or you can trick it into flying into the ground
2) Enemy AI jet will automatically start hunting player jet after AI reaches 600 meters
3) four 747s (my addition) fly in close line formation around a circular curcuit of 10 waypoints, each jet marked by a yellow point light
4) part of your objective is to shoot these down too--eventually I'll find appropriate bomber models, but for now these will do.  They are 1st-class-only 747s, so it's ok.
5) each Jumbo is armed with an auto-aiming MG in the tail, full sphere traverse, which starts shooting at you at 800 m--these can be quite lethal esp. if you tackle all four Jumbos at once.
6) but the Player jet is also armed with four guided missiles (launched by keys 1/2/3/4), which will each seek out a different 747 (at any range or direction), OR if one or more Jumbo is gone already, will seek out the AI jet (so it's good if you can MG-kill at least one Jumbo to save a missile for the AI jet).  Missiles are also my addition.  Emission trail is wip.
7) final addition: flak towers on each side of runway, each with dual auto-aiming MGs--they'll wait till Player jet is over 400 meters in altitude before arming, then each have a range of 350 m (beyond their own height).  Irrelevant to air combat, but you have to destroy them (with MGs) if you want to land again.  I have not yet succeeded in getting both.
8) as part of stock flight controls, throttle is automatic but airbrake is left-control.  Airbrake is your friend for aiming.
