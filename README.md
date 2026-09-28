This repository should contain a reference replay for all in-logic strategies for the Impossible Spellcard implementation for Archipelago.
Current progress: 38/75.

Replay filenames will take the following form:
 * 1st character: day of replay (A for 10)
 * 2nd character: scene of replay (A for 10)
 * 3rd character: lowest logic difficulty (N, H, or L)
 * 4th character: first character of main item (F C U Y B L J D M) (X for no item)
 * 5th character: level of main item (character does not exist if no item)
 * 6th character: sub item used, if applicable

So a clear of 6-5 using Fabric level 2 + Decoy Doll sub would be named:
 * th143_ud65NF2D.rpy

and a clear of 6-5 using Fabric level 3 + no sub would be named:
 * th143_ud65NF3X.rpy

In cases where the mallet sub-item only adds uses, the replay may show a higher level item. So the following equivalent strategy:
 * th143_ud65NF1M.rpy

would not have its own replay, as it's identical to NF3X.
There are other cases where a strategy is shown by a stricter one, such as normal requiring jizo sub and hard+ not, or umbrella sub being sufficient so umbrella main is obviously sufficient.

Sometimes there may be multiple strategies with the same requirement - the one I think is easiest will be the main, and other strategies worth showing will have "alt" at the end. There are also a few "-OOL" replays for strategies not included in logic (because strictly lesser requirements on a slightly harder strategy are already included), for cases where having something extra can make things easier, or things that were inconsistent but worth showing as alternatives.

Similarly, the doll sub-item will make no iteming any scene easier. For scenes that are reasonable without it, I will only include the doll-less version.
