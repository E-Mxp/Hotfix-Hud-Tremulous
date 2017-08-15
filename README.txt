Hotfix Hud v5.3 by E-Mxp.
For Tremulous GPP.

Initially intended as a hotfix, I have added some more things to help make an awesome hud just a tad more awesome.
The best part of Superpie's Tweaked GPP HUD was (in my opinion) the centered hud, however, I found out that the centered hud was made to be perfectly aligned if you have a 4:3 resolution (as you can see if you look at the human inventory arrow and more noticeably, in the alien hud).
While working on the fix I learned more about how the code works and I decided to add more options.


MAIN FEATURES:

    * Hudoptions in the main menu.
	* 3 hud layouts! Default, Centered and Compact!
	* Custom loadingscreen.
    * For all the layouts you have a choice of 3 color schemes:
	 - The Superpie hud color scheme. (Default)
     - The Warrior hud color scheme. Based off the Warrior's Hud by Warrior.
     - The Hellrider hud color scheme. Based off the Hellrider Hud (v1.1) by Hellrider.
    * The option to place the Adv. Good barbs underneath the crosshair.
    * Optional fullscreen radar.
	* Optional stamina progress bar!
    * Optional Human crosshair dot in 3 colors: white, blue and black.
	* Option menu to change the appearance of the console (requires Segfault)
	* Segfault options also contain the option to turn on bloom with preset settings to prevent flicker.
	
NOTES:
All "hud_" (exept "hud_style") commands get applied immediately, so there is no need to restart.
V5.3: CHANGES FROM V5.2
	*Changed the Hellrider human chargebar to its intended colors (was using Superpie's default)!
	*Replaced the default pre-loadingscreen image (moon in front of blue nebula) with a custom one based off the menu.
	*Replaced the default loadingscreen with a custom one based on Kang's hud (with some personal changes).

V5.2: CHANGES FROM V4
	*Merge with the Unvanquished version!
	*Added the staminabars from Dodger's Hud with GeneralScott's full permission, thanks!
	*Fixed Centered inventory in the Default huds so that they don't loop around if you have too many items.
	*As an added bonus: custom alien crosshairs. (beta)
	*Changed red nebula on main menu.
	*Minor tweaks.

V4: CHANGES FROM V3
	*Added hud screenshots to the hudoptions.
	*Added Segfault options to the main menu.
	*Changes to the main menu.

V3: CHANGES FROM V2.5
	*Fixed ammo in Default Superpie hud.
	*Fixed buildpoints for Default aliens hud.

V2.5: CHANGES FROM V2.4
	*Added the option to have the inventory in the center or to have it on the right.
	*Moved the Stagereport to the right on the Centered hud to accompany above mentioned feature.

V2.4: CHANGES FROM V2.3
	*Removed hud_markedBuildPoints option. (Now uses the previous "1" setting.) I removed it because most (if not all) servers use the latest version of gpp, so there is no need to want to change the setting.
	*Moved the inventory to the bottom of the screen on the "Centered" hud. So now also no need for hud_widescreen.

V2.3: CHANGES FROM V2.2
	* Added option to change fontsize

V2.2: CHANGES FROM V2.1
	* Added the Demos menu in the main menu, as added in by revision 2222.

V2.1: CHANGES FROM V2
	* Fixed Centered huds for Superpie and Warrior to be broken.
	* Made the Bolt for the Compact and Centered huds more clear.
	* Changed colors for the build timers on Compact huds to be better visible against the green of an unconstructed structure.
	* Moved the TeamOverlay on the bottom right a bit up, as it was overlapping the stage report. (Thanks to ThisIsBS for reporting!)
	* Added TeamOverlay option to place it on the bottom left.
	* HOTFIX1: Fixed the Default Superpie hud.
	
V2: CHANGES FROM V1.4
	* New hudstyle made by yours truly. The Compact hud, this one is also in 3 color scemes.
	* Changed menu to ask what style of hud you want and then what color sceme for faster selection.

V1.4: CHANGES FROM V1.3

	* Added command "hud_markedBuildPoints" to keep up with changes in gppr2184 (March 02 2011).
	
V1.3: CHANGES FROM V1.2

    * Made all the text on the screen smaller.
    * Lowered the speedometer because it was overlapping the FOLLOWING PLAYER text.
    * Added the Human Dot Chrosshairs in 3 colors; white, blue and black.
    * Minor fixes.
	
	*V1.3a: Fixes typo that breaks the Stage Report.
	
V1.2: CHANGES FROM V1.1

    * Changed the name from Tweaked GPP HUD Hotfixed to the original worktitle: Hotfixhud
    * Added option to change the location of the TeamOverlay from default(center left) to center right and bottom right and back.
    * Some small changes in the options in the menu.
    * Minor fixes.

V1.1: CHANGES FROM v1

    * Hud options now have a different tab on the main menu.
    * Made the fullscreen radar display friendlies as light gray, so that it is not as distracting.
    * I found out that the inventory could still be off-center in different aspect ratios. Added in the crude fix from Meisseli's HUD.


CHANGES FROM Tweaked GPP HUD ( v1.8 )
Fixes (only apply in the Centered version of the hud):

    * Made the hud display as intended for all resolutions.
    * Added back in the bolt icon, but in a way that it isn't distracting. The human bolt icon is shown on the health cross icon. The alien bolt icon is shown over the alien icon.
    * Moved the human radar up a bit for it was overlapping the hud.


Added in:

    * Added an option in the main menu to place the Adv. Good barbs underneath the chrossair.
    * Option to use the Warrior hud color scheme. Based off the Warrior's Hud by Warrior
    * Option to use the Hellrider hud color scheme. Based off the Hellrider Hud (v1.1) by Hellrider


Special thanks to:
Special thanks to:
Superpie, for creating the Tweaked GPP HUD I know and love.
Warrior, for crafting the Warrior's Hud, a hud thats very colorfull and nice.
Hellrider, for spawning the Hellrider Hud, a hud that looks quite cool and not black and white yet.
Meisseli, for making up a very easy way to fix the inventory aspect ratio problem. Try his HUD out!
Mox, for giving me the idea to add pictures to the main menu. His AdjustableHUD is really good, try it!
Oticz, for his dot crosshair code. If you still play 1.1, his HUD is highly recommended!
GeneralScott, for giving me full permission to use his staminabar code, awesome!
Kang's hud, who had the most awesome loadingscreen I have seen in Tremulous!

A great help was this site on Icculus.org (http://icculus.org/~phaethon/q3tamenu/q3tamenu.html) and is recommanded to everyone trying to make huds for Tremulous!