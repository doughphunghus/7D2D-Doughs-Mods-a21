**For game**: [7 Days to Die](https://7daystodie.com)

**Description:**
This modlet attempts to make sky have the wasteland biome look, buy making all biomes have the same spectrum as the wasteland (which appears to be "burnt_forest" oddly enough, but without the smoke effects)

**Notes:**
- I'm not sure if a biome has particle effects defined (some do), or denser ones (via mods), if this will make the sky or ambient lighting "way too dark". If so... too bad I guess, thats just going to happen as I'm not setting/overriding/removing any particle effects in this mod yet.

- The "burnt forest" spectrum is only defined for the toplevel biome(s), there are other weather spectrums that can override it, but its usually when fog and rain/precipitation occur. For now, if the sky clears up a bit when precipitation is occurring think of it as "the dirt/particles in the sky are being cleaned up by the falling the water/snow or fog moisture".  Once the game goes gold it will hopefully be easier to fine tune the sky look and weather and such is still listed as a "to work on" by the devs so teh underlying XML will likely change so I'm a bit uninterested in fine tuning this mod for sky+weather until the weather code/effects/xml is stable.

**Known incompatibilities:**
If used with my "Doughs-Weather-Core" mod, the sky effect will liekly be overridden by settings in the weather mod, as it normally loads after this mod, so to make it "work"
you will have to rename this mods toplevel folder to be alphabetically after "Doughs-Weather-Core". One way to do this would be to rename the "Doughs-Ambiance-SkyIsBurntForestInAllBiomes" folder to something like "Doughs-zAmbiance-SkyIsBurntForestInAllBiomes". Though I hope this works, I don't plan to try to really "support" loading both mods maybe until the game goes gold.  My future hopes are I can always have "all of my mods loaded" without having conflicts or renaming workarounds, but I want to wait and see what options/tools/methods are available after the game goes gold and Steam workshop support exists/etc.

