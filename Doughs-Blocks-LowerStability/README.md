**For game**: [7 Days to Die](https://7daystodie.com)

**Description:**
This mod is not for everyone, please read this! It is likely *not* server side safe
as it may tend to cause structures to collapse very easily (looking like drop mining)

This modlet adds lowers the block stability of several block types quite a bit

Blocks will not hold as much weight, horizontally, and thus buildings/POIs/player
built structures will likely suffer collapses much more/easier than usual.
For example: standing/placing/breaking a block in/on a POI or any previously built
structure can cause structural collapse.

Building will be more difficult as long horizontal runs of blocks in the air will not be possible,
and you must have more horizontal support below to support blocks.

NOTE: 
- When testing, POI's do not appear to collapse without first being "modified", meaning it appears that block support/stability is only calculated once a block is destroyed (by a player or a zed, etc). so an existing POI may violate stability rules but it will not take effect until block(s) within the POI are destroyed. This means a POI may have large amount of collapse/disintegration by simply destroying 1
block, even a decorative one like a cardboard box as that triggers the stability calculation. 
- Since "modified" is also "placing a block" I have seen placing a wood frame
"on top" of other blocks initiate a stability calculation and thus, some collapse.  Because the block had weight!

NOTE: On a multiplayer server, this mod may cause what looks like "drop mining" as
buildings (and possibly ground blocks) will likely start falling/collapsing with very little initial block damage.

Generally:
The "strength" or "horizontal stability" is *a lot* less than 50% of the vanilla settings, with some adjustments made to be this "order of strength".  The "mass/weight" of the blocks is not changed, just how much weight a block can hold, horizontally.

The "carrying capacity" of blocks, if you will, generally will follow these rules, which are mostly "the block upgrade path"
when a block can be upgraded.  Basically: the more a block is upgraded the less support it needs.
- a21: same?
- a20: same?
- a19: glass < wood < weak or thin metal|cobblestone < stone < metal < brick|bulletproof glass < concrete < iron < steel < stainless steel
