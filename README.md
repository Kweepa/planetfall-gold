# Infocom's Planetfall, modernized

Planetfall is a 1983 interactive fiction game written by Steve Meretzky and published by Infocom.

Further information on Planetfall:

* [Wikipedia](https://en.wikipedia.org/wiki/Planetfall)
* [The Digital Antiquarian](https://www.filfre.net/2013/03/planetfall/)
* [The Interactive Fiction Database](https://ifdb.tads.org/viewgame?id=xe6kb3cuqwie2q38)
* [The Infocom Gallery](http://infocom.elsewhere.org/gallery/planetfall/planetfall.html)
* [IFWiki](http://www.ifwiki.org/index.php/Planetfall)

__What is this Repository?__

This repository is a modification of the original Planetfall source code, with the goal to make it more playable by a modern audience with some minor tweaks.

__Overview of Projected Changes__

* bug fixes (in progress)
* spelling corrections (done)
* removal of need to eat (done)
* removal of some egregious deaths (in progress)
* removal of "walking deads" (in progress)
* addition of CLASSIC and MODERN pseudo-verbs (in progress)

CLASSIC will allow the player to take advantage of the bug fixes while still playing the game as it was intended.
MODERN will allow the player to enjoy the game without having to worry about unfair deaths or hunger.

__Bugs fixed__

* fixed sexlessness of ambassador and Blather when being shot (Cree #6)
* fixed switched off Floyd responding to things (Cree #7, Simpson #36)
* fixed behavior of water level as the days progress (Cree #8)
* prevented the pod from being opened from the webbing (Cree #9)
* prevented diary from interfering with the elevator controls, by removing the diary when you reach the Crag. I might do this a better way later (Simpson #24)
* fixed DROP/THROW dial, goo and liquids (Simpson #28, #29, #30)
* fixed GIVE DIAL/GOO/FLUID/MEDICINE TO FLOYD (Simpson #28, #33)
* prevented kitchen door from being manually closed (Simpson #35)
* fixed Floyd leaving closed rooms when seeing the breastplate, by making the breastplate non-portable. I might do this a better way later (Simpson #37)
* Floyd reacts appropriately to SHOW PLATE TO FLOYD (Simpson #38)
* removed UPPER adjective from the blue door so that SLIDE UPPER THROUGH SLOT works

Where appropriate, taken from
* Graham Cree's list http://graeme.50webs.com/infobugs/planetfa.htm
* Nathan Simpson's list http://www.microheaven.com/InfocomBugs/planetfa.shtml
