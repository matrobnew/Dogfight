# Dogfight--now six versions
based on lovely demo by AJ Campbell, but with a lot more stuff added (increasing skill level with newer versions)

PlayerJet and Enemy AI Jets are based on stock Unity flight sim models (uses their flight controls--this means player jet has auto thrust, you use left/right and up/down for direction), but with many enhancements.  The following describes 4th version, Dogfight 7, and I wouldn't bother with earlier versions; FOLLOWING that are the many changes made to new Dogfight ManyAI versions [itself with a minor and major update]).  Be sure to download the resources folder with the name corresponding to the EXE you want.

1) in Dogfight 7 (the latest version w/only 2 fighter jets) both jets are are armed w/3 machine guns: spacebar shoots for Player jet, AI jet shoots when it's close enough behind you.  AI jet turns slowly and isn't a huge threat when there's only one (which is why I added many more, see "ManyAI"), but if you fly straight for long enough it might shoot you down, until it's killed.  Or you can trick it into flying into the ground, or into enemy flak.  OTOH, it's difficult for you to shoot down enemy IA jet either, except for a) when still taking off, or b) with a missile (see 6)
2) Enemy AI jet will automatically start hunting player jet after AI jet reaches 600 meters
3) in versions thru Dogfight 7, there are also four 747s which fly in line formation around a curcuit of 10 waypoints, each jumbo jet marked by a yellow point light for easier visibility.
4) part of your objective is to shoot these 747s down too.  They are 1st-class-only 747s, so it's ok, you're only killing the rich.
5) each Jumbo is armed with an auto-aiming MG in the tail, full sphere traverse, which starts shooting at you at 800 m--these can be quite lethal esp. if you tackle all four Jumbos at once, but even one will shoot you down if given the chance.  Note: unlike ground AA canon they have no 'tracking' logic, so they're most accurate when you're flying at roughly the same velocity & course as jumbos.
6) The Player jet is also armed with four guided missiles (launched by keys 1/2/3/4), which will each seek out a different 747 (at any range or direction), OR if one or more Jumbo is gone already, will seek out the AI jet (so it's good if you can MG-kill at least one Jumbo to save a missile for the AI jet).  
7) Flak towers on each side of runway, each with dual auto-aiming MGs--they'll wait till Player jet is over 400 meters up before arming, then each have a range of 350 m (beyond their own height).  Irrelevant to air combat, but you have to destroy them if you want to land again at airstrip.  
8) three clusters of additional flak towers around runway, each w/12 towers.  4 towers in each cluster are armed w/more self-tracking coaxial MGs, but more importantly, 6 towers in each cluster are armed with 88 mm AA cannon (actually mounted in Tiger tank turrets, if you look closely). All of these AA cannon will track the player plane and begin firing after you're 150 m up (and up to 2k m altitude).  Beyond the sheer numbers (now eighteen 88mm cannon total) version 7 adds several more things to improve AA accuracy . First, these have timed proximity fuses for airburst, dynamically set to target range at firing time (plus a time-to-target calc), and the airburst shrapnel can kill if its close enough.  Second, the targeting is coded to "lead" you now, based on target's velocity, though of course as with any real AAA that only works if you fly in straight line long enough.  Finally, while one tower cluster had guns targeted individually, the other two clusters has a central targeting mechanism, meaning that you can be straddled by 6 (or 12) airbursts at once, which is fun (and much more like conventional AAA).  You must take out these towers indvidually with MG fire--but if you line up on them from anything but a very low angle (below 150 m), for more than 2 seconds, you're dead.  Remember they ignore you below 150 m, so you basically need to skim in low to take them out.  OR try some kamakazi maneuvers to throw off their aim.  OR...
9) rockets -- there are rocket launchers on each side of player jet nose, which will fire up to 40 rockets (indiv salvos left-shift, full-auto in .2-sec increments alt-left).  Rockets are a bit slower than MG fire and unguided, unlike missiles, so although in theory they represent a lot of firepower, I haven't figured out a way to use them to kill either jumbos (probably hopeless) or many flak towers. Rockets are probably more useful on a much slower ground-attack aircraft/firing platform, where nobody is firing back.  I have basically come to ignore the rockets, but they're there if you want to try them.

************NEW in "ManyAI" version--all prev versions still available, just make sure you match exe w/resource folder ************

1) the 747s are gone, replaced by much more numerous and interesting targets
2) namely, rather than just a single AI enemy jet, which was frankly a trivial threat, there are now TWELVE enemy AI jets.  Four are immediately visible and will take off and start pursuing you after they've reached 400 meters alt (down from 600 before).  The second flight of four will appear after 20 second and join the others in pursuit of you, and the final flight of four 20 sec after that. A handy counter (below altimeter) keeps track of the remaining number of enemy jets
3) enemy jets' armament remains the same-- 3 mgs each.  They still have no missiles, as you would not survive a missile-armed enemy, esp en masse (I am contemplating a version with missile-vs-missile dogfighting, including countermeasures, but that would require an extensive heads-up display as well as mad coding).  But with 12 on one, they do have a significant chance of shooting you down now, esp if you fly in one direction too long (though that's also the best way to bunch them together so you can kill a few w/MGs)
4) you now have SIX missiles, all for the enemy jets.  Launch w/1,2,3,4,5, and 'm' (or just 'm' to launch multiple missiles at once). I'd suggest waiting until 8 jets are manifest before launching missiles.  For the rest, if you are very lucky you can kill one or two with MG fire, esp if you can find them in close formations, but it's much easier to just wait for them to be killed by flak, or run into the ground or into a tower. Flak fire generally trails you when its inaccurate, so there's that.
5) when the enemy jets are largely eliminated, your chief concern remains the flak towers.  Flak still kills me about 60% of the time.  Again, remember that your best best is to fly in below 150 meters, where they won't fire, and take out the towers that way w/as many passes as necessary.  With 12 jets now (up from 8 in first ManyAI version), you'll usually need to start klling flak towers with 5 or more jets left--this isn't a problem if you remember to juke horizontally frequently enough in your low runs. Once the towers are all gone, you can even land w/2 or even 3 jets left, as these will reliably crash once you've landed. 

***********************NEW in ManyAI Buildings version *********************************************************

1) after you master the first ManyAI version, and can easily take out all the flak towers with low passes, it's time to make things more interesting by adding BUILDINGS: there is a 'wall' of skyscrapers around all four sides of airfield/flak zone, about twice as high as the towers.   There are significant gaps at each of the four corners, and you can also fly between some of the skyscrapers once you're good enough.  You'll need to do one or other to make a surviveable pass at the flak towers now--you can try to approach over them instead but usually the flak will get you then.
2) while at first they're scary, once you get used to them the building are your friend, as they provide significant new obstacles for enemy jets to crash into (the AI jets don't have enough AI to avoid obstacles).   Hug the buildings and/or fly between them.  Once you've taken out the flak towers, you can sometimes land with 3 or 4 jets still around, and they will typically crash harmlessly around you.
3) I would NOT suggest starting right off with this version: it requires precision flight and gun control, good judgment on when to launch missiles, and even then be ready to be killed repeatedly before you 'win' (ie, landing anywhere with all flak towers and jets killed).

***************************NEW in Missiles version ****************************************************************

1) enemy jets back down to six, but now each is armed, like you, with 6 guided missiles.  
2) this would not be surviveable, trust me, except that you now have a heads-up (slightly to the right) radar display showing enemy planes (red dots) and their missiles (orange dots).
3) this STILL wouldn't be surviveable, except that you now have decoy counter-measures launched from the left-alt key (30 pairs total, so just tap lightly) -- wait till the enemy missiles are visible and see how many you can get with just a pair of counter-measures.  
4) Do all this while still taking out the flak towers and zooming among the buildings, if you're bad-ass.  You could of course just kill the 6 enemy jets with your own missiles, but that's wimpy.  Real pilots don't hide behind their missiles...
