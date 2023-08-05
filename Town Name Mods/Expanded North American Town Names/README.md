original link = https://www.tt-forums.net/viewtopic.php?t=11365

[Released] Expanded North American Town Names

Post by Overlord1191 » 24 Oct 2004 04:21
I modified the North-American Names group to include a good bit more. Also, this makes a great guide to work up your own town name prototypes.

-----------------------------------------------------------------------------------

Upon trying to understand and control the way the game creates names I've discovered some interesting things as well and trying to improve what's there. :idea:

For example (as ReFa already discovered) xml object "types" are include in certain situations:

type 0 = seems to be universal these towns are present everywhere
type 1 = seems to be universal but much more rare than type 0
type 2 = towns at high altitudes
type 3 = i can't make type 3 display :?
type 4 = coastal areas
type 5 = works in coastal areas but more rare than type 4 but I can't determine more functionality

Also the "numempty" variable in the structure category can limit how often the prefix or suffix is used. Setting this to 0 seems to make it happen always. Setting it to 20 or 30 makes it much more unlikely to use the data. 8)

I still would like to make a particular item not carry any prefix or suffix (for instance Indian names in America do not follow the British style names).

I was actually surprised that none of the town types seem to follow certain terrain types. I expected to find some types of towns that build only on desert but I didn't find anything after extensive testing. :o

Anyway, discuss further with me please if you discover anything else.