# spider-solitaire-  
What is?  
Spider Solitaire is a fun game  
but could it be more fun?  
maybe even more game?  
  
To do:  
- [X] game can load when you click load in version 4p2v3 and up (hopefully, don't count on it until i test it more lol)  
- [X] Save states (probably a cookie that allows one single save game per device that gets erased upon load)  
- [X] Redo (one single step back per game for people who may have made an oopsie doopsie)  
- [] more fancy animations  
- [] better keyboard controls which are kinda broken and also there's no way to turn off event listener for all at once  
- [] modularity is pretty good but im still experimenting with different platforms and possibly an envelope for quicker android touch controls since android is very unique  
- [] i have to fix the bathroom still  
  
feel free to share this link V V V V  
  
# SPIDER SOLITAIRE  
## Click below!  
https://docpoacher.github.io/website/spider_solitaire.html  
### Click above!  
  
A Brief History of Milestones:  
-April 8th, 2023: Classic made in a day. Alpha version.  
-April 10th, 2023: Tarantula added.  Beta version.  
-April 14th, 2023: Fixes.  
-June 7th, 2023: Rewrote from scratch.  Version 2.  
-June 21st, 2023: Custom working.  
-June 29th, 2023: Custom Pips added.  
-July 31st, 2023: No refresh on pulldown.  Not really a big deal...  
-Dec 8th, 2023: First attempt at cookie.  
-July 5th, 2024: Added "Last State" cheat.  
-August 19th, 2024: Cookies almost working.
-August 30th, 2024: Cookies mostly working. Not on big games. Fails to load cookie after maybe 200 cards... have not fully tested it.  
-September 11, 2024: Last release pending catasrophe.  Began work on Xspider which will be next itineration.  
-February 10th, 2025: Microsoft defender and Edge no longer loads htmlpreview correctly. Moved to github pages website. Edge seems to be unable to load cookies.  


**BETA COOKIE VERSION: Load closed or crashed game should work.  NOTE: will load previous state, so if you do something and it does not work it will keep the previous state (same goes for if you get stuck, it will load the previous state).  I have not extensivly tested it.  If you close the window, click LOAD GAME!! to load previous tableu.  Happy focusing!  **  
*This link might trip your Microsoft defender.  Please use above link*  
https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/spider4p2v3.html  
  
  
**STABLE NO LOADING PREVIOUS GAME.  Step backwards does work** https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/spider4p2v2.html  
  
(keyboard play not ready yet, I will remap all of the event listeners so some other commands might work. ((javascript does not possess the ability to kill ALL event listeners so I would have to enable and disable them individually)))  
  
**previous versions:** https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/spider4point2.html  
  
(no longer refreshes with pull down or zoom out please let me know if it resets mid game for you)  
  
  
For keyboard play: https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/spider4point3.html  
  
  
08/something/2023  
  
Cookies work, so now you can close browser or crash game and previous state will load.  I purposely have it load previous state because I feel this is a more desireable option.  The disadvantage is some people might be discomboulated by their previous state being loaded up.  If ENOUGH people complain I might change it but this way there will be less chance of a crash effecting the cookie and destroying the game state.  (E.G. if the browser has a stroke and encodes the cookie incorrectly and you try to load the state but it can not because the cookie is now corrupted)  I forgot to update the log so here it is like 2 weeks later I guess.  Am still researching local save cookie but not very seriously tbh.  
  
07/31/2023  
  
Hello all, I have finally disabled pull down refresh (works on android have not tested apple).  I had several close calls on my long vacation.  I have been testing every one of the options and so far everything appears to work well.  Will O' Wisp has become a new favorite.  Keeping the same version number since I did not debug any game feature only added code to the HTML style.  
  
06/29/2023  
I made my own pips.  Plans for the future pips include rose and pink flower thing.  The blue thing is supposed to be a fish but it looks more like the barefoot wine logo.  I apologize for my shade thrown at one of the testers.  I did not realize that they did not use android phone.  I jumped to the conclusion because they mentioned they would need to use someone elses apple laptop to test the game and I wrongly assumed this meant they did have an apple phone.  That fact aside, they may have had a windows phone from 20 years ago or one of those new linux phones.  Also, it is possible that they had a grandpa flip phone or maybe no cell phone at all.  This brings up an interesting idea: maybe there are people out there still using magic jack to call people from a computer?  It is possible that they might consider their PC as their phone.  
  
After testing there will be the final release of version 1.0.  2.0 will have animations and 3.0 will have a Excel Spreadsheet interpretation.  
  
https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/spider4point2.html  
  
06/22/2023#2  
if you enter a game and attempt to start another game without refreshing your browser you will not be able to use the android keyboard or any keyboard for that matter to change the custom values.  for the time being the increase and decrease buttons are only available for PC users and some apple devices
android is becoming increaseingly frustrating to work with  
for the time being all the pips have been replaced with alternatives.  I hope the game is still playable for all of the two of you.  also, some old code was in that was preventing entry of numbers into the android version of the custom menu, meaning the TWO OF YOU were either not trying the custom menu or were not sure what you should have been doing.  
Cloud pip looks too soft (too cloudy) so we'll use something else maybe  
06/22/2023  
work begins on making all of my own suit pips (heart, club, spade, and diamond ((the hardest one))) it seems "there is no way to control the rendering of emojis" and compatibility is zero for the appearance of the suits.  it shouldn't take long (it might take ages) but in the mean time I might default the pips to something else instead of the classic four since blue heart even comes up as a red heart for android.   Apparently, edge may do this as well, however, i have not tested edge as i do not have it installed.  
https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/spider4and1.html  
  
  
06/21/2023  
Custom menu: wild card works. Randomize increases difficulty chance each click by design. (i.e. one click is easy random, two clicks is harder and so on) Suit number counter hidden to prevent game breaking also it was pointless(haha get it no pointer haha) now I will test it by playing a bazillion games.  New modes in development.
06/20/2023 Custom menu: wildcard still broken.  Randomize breaks the game.  Suit number has to match highlighted pip or game will break.  Everything else works probably'  
  
https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/SOLITAIR4.HTML  
  

06/07/2023  
New graphics, menu, includes 5 game modes (9legs designed by me) custom menu (wild card dont work do not use wild card)  
https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/scratch_spider_2_beta.html  

  
spider solitair but lightweight and more fun  
  
to test any HTML just add:  
https://htmlpreview.github.io/?  
  
before the address of the git I.E:   
  
https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/gameBeta01mediumtext.html  
  
or click on the links below:  
  
<a href="https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/gameBeta01.html">
easy regular beta
</a>  

<a href="https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/gameBeta01mediumtext.html">
two suit regular beta
</a>  
  

<a href="https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/gameBeta01hardtext.html">
hard (four suit) regular beta
</a>  
  

<a href="https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/gameBeta03-tarantula.html">
four suit tarantula
</a>  
  

<a href="https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/tarantula medium beta.html">
two suit tarantula (fixed problem with only two suits of hearts and six of spades)
</a>  
  

<a href="https://htmlpreview.github.io/?https://github.com/docPoacher/spider-solitaire-/blob/main/gameBeta03-tarantulaeasy.html">
easy tarantula
</a>  
  
