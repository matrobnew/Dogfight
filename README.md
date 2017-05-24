# Dogfight--now five versions
based on lovely demo by AJ Campbell, but with a lot more stuff added for those of us with shorter attention spans.

PlayerJet and Enemy AI Jet are based on stock Unity models (uses their flight controls), but... (the following describes 4th version, Dogfight 7; FOLLOWING that are the manges changes made to new Dogfight ManyAI version [itself updated once]).  Be sure to download the resources folder with name corresponding to the EXE you want.

1) in Dogfight 7 (latest version w/only 2 fighter jets) both jets are armed with 3 MGs, based on AJ's model but 3 instead of 1, because more is better--spacebar shoots for Player jet, AI jet shoots when it's close enough behind.  AI jet turns slowly and isn't an immediate threat (in fact it's almost never killed me, vs the other threats), but if you fly straight for long enough it might shoot you down, until it's killed.  Or you can trick it into flying into the ground, or possibly enemy flak.  OTOH, it's almost impossible for you to shoot down enemy IA jet either, except for a) when still taking off, or b) with a missile (see 6)
2) Enemy AI jet will automatically start hunting player jet after AI jet reaches 600 meters
3) four 747s (my addition) fly in line formation around a circular curcuit of 10 waypoints, each jumbo jet marked by a yellow point light
4) part of your objective is to shoot these down too--eventually I'll find appropriate bomber models, but for now these will do.  They are 1st-class-only 747s, so it's ok, you're only killing the rich.
5) each Jumbo is armed with an auto-aiming MG in the tail, full sphere traverse, which starts shooting at you at 800 m--these can be quite lethal esp. if you tackle all four Jumbos at once, but even one will shoot you down if given the chance.  Note: unlike ground AA they have no 'tracking' logic, so they're most accurate when you're flying at roughly the same velocity & course as jumbos.
6) The Player jet is also armed with four guided missiles (launched by keys 1/2/3/4), which will each seek out a different 747 (at any range or direction), OR if one or more Jumbo is gone already, will seek out the AI jet (so it's good if you can MG-kill at least one Jumbo to save a missile for the AI jet).  Missiles are also my addition.  Emission trail is greatly improved in Dogfight 6.
7) Further addition: Flak towers on each side of runway, each with dual auto-aiming MGs--they'll wait till Player jet is over 400 meters up before arming, then each have a range of 350 m (beyond their own height).  Irrelevant to air combat, but you have to destroy them if you want to land again at airstrip.  
8) three clusters of additional flak towers around runway, each w/12 towers.  4 towers in each cluster are armed w/more self-tracking coax MGs, but more importantly, 6 towers in each cluster are armed with 88 mm AA cannon (actually mounted in Tiger tank turrets, if you look closely). All of these AAA cannon will track the player plane and begin firing after you're 150 m up (and up to 2k m altitude).  Beyond the sheer numbers (now eighteen 88mm cannon total) version 7 adds several more things to improve AA accuracy . First, these have timed proximity fuses for airburst, dynamically set to target range at firing time (plus a time-to-target calc), and the airburst shrapnel can kill if its close enough.  Second, the targeting is coded to "lead" you now, based on target's velocity, though of course as with any AA that only works if you fly in straight line long enough.  Finally, while one tower cluster had guns targeted individually, the other two clusters has a central targeting mechanism, meaning that you can be straddled by 6 (or 12) airbursts at once, which is fun (and much more like conventional AAA).  You must take out these towers indvidually with MG fire--but if you line up on them from anything but a very low angle, for more than 2 seconds, you're dead.  Remember they ignore you below 150 m, so you basically need to skim in low to take them out.  OR try some kamakazi maneuvers though off their aim.  OR...
9) rockets -- there are rocket launchers on each side of player jet nose, which will fire up to 40 rockets (indiv salvos left-shift, full-auto in .2-sec increments alt-left).  Rockets are a bit slower than MG fire and unguided, unlike missiles, so although in theory they represent a lot of firepower, I haven't figured out a way to use them to kill either jumbos (probably hopeless) or many flak towers (in time it should be possible).  Rockets are probably more useful on a much slower ground-attack aircraft/firing platform, where nobody is firing back.  I have considered PAVE-type smart bombs instead, but I'm already using enough 1990s tech against 1950s targets.

************NEW in "ManyAI" version--all prev versions still available, just make sure you match exe w/resource folder ************

1) the 747s are gone, replaced by much more numerous and interesting targets
2) namely, rather than just a single AI enemy jet, which was frankly a trivial threat, there are now TWELVE enemy AI jets.  Four are immediately visible and will take off and start pursuing you after you've reached 400 meters (down from 600 before).  The second flight of four will appear after 20 second of game time and join the others in pursuit of you, and the final flight of four 20 sec after that. A handy counter (below altimeter) keeps track of the remaining number of enemy jets
3) enemy jets' armament remains the same-- 3 mgs each.  They still have no missiles, as you would not survive a missile-armed enemy, esp en masse (I am contemplating a version with missile-vs-missile dogfighting, including countermeasures, but that would require an extensive heads-up display as well as mad coding).  But with 12 on one, they do have a significant chance of shooting you down now, esp if you fly in one direction too long (though that's also the best way to bunch them together so you can kill them w/MGs)
4) you now have SIX missiles, all for the enemy jets.  Launch w/1,2,3,4,5, m (or just 'm' to launch multiple at once). I'd suggest waiting until 8 jets are manifest before launching.  For the rest, if you are very lucky you can kill one or two with MG fire, esp if you can find them in close formations, but it's much easier to just wait for them to be killed by flak, or run into the ground or into a tower. Flak fire generally trails you when its inaccurate, so...
5) when the enemy jets are largely eliminated, your chief concern remains the flak towers.  Flak still kills me about 60% of the time.  Again, remember that your best best is to fly in below 150 meters, where they won't fire, and take out the towers that way w/as many passes as necessary.  With 12 jets now (up from 8 in first ManyAI version), you'll usually need to start klling flak towers with 4-5 jets left--this isn't a problem if you remember to juke horizontally frequently enough in your low runs. Once the towers are all gone, you can even land w/2 or even 3 jets left, as these will reliably crash once you've landed. 
