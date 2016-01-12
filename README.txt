Welcome to the Pokémon Template for the Magic Set Editor Program. This template is not complete so keep that in mind.

Current Version: 0.41
-- Changelog --
- Setting up skeleton for 0.50
- Minor adjustments for appearance
- 5 Cost energy attacks are now possible.
- Slot 2 is broken except for Abilities. This is normal as I haven't modified it yet.

# Pokemon Cards - 	%75
# Trainer Cards - 	%100
# Special Energy -	%0
# Pokemon EX - 		%0
# Pokemon M - 		%0
# Pokemon BREAK - 	%0
# Ace Spec Cards - 	%0
# Pokemon Full Art - 	%0
# Trainer Full Art - 	%0 

1: Installation
2: Useful Info
3: Things to do
4: Bugs
5: Credits

### Installation ###
- Installing MSE is easy. Download the git as a ZIP, then extract it somewhere and install all of the fonts. Run MSE.exe and have fun!

### Useful Info ###
- Symbol Font Codes! Full Icons are used for attack cost, weakness, and resistance. Text Icons are used for the icons in text fields. To use these "codes" simply type them where you want them. Text icons, highlight the letter and click the "Star" next to the B and I!  EASY!

= Full Icons - Uppercase
= Text Icons - Lowercase
======
- Grass: G
- Water: W
- Fire: R
- Lightning: L
- Fighting: F
- Psychic: P
- Fairy: Y
- Dark: D
- Metal: M
- Colorless: C
- Dragon: a (Dragon currently does not have a Full Icon. Only a Text Icon. This isn't much of a concern since the Full Icon is only used for Weakness, and Fairy has pretty much taken that spot)
======
Rarity Symbols
- Common: O
- Uncommon: V
- Rare: *
======
Miscellaneous
- Ability Symbol: A!
- EX Symbol: EX
======
Non-Symbol Font Codes (These are important!)
- This is the accented e. Used in Pokémon.
ALT + 0233
é
- This is really important. You MUST use this for Weakness. This is the multiplication x in weakness.
ALT + 0215
×

======
- Image sizes!
Pokemon, Trainers, and Special Energy all use different image sizes. As such, I've posted a list of resolutions for those who want their image to fit exactly. Keep in mind, MSE has an option to auto-fit images, so resizing images isn't necessary.

= Normal Pokemon (Basic, Stage 1, Stage 2): 307x201
= Trainers: 295x181
= Special Energy: Not yet created
= Evolution Icon (For Stage 1 and 2): 100x100 PLEASE NOTE!!!! Your image must be EXACTLY this. Center the pokemon in the middle of the image. IT HAS TO BE 100x100 OTHERWISE IT WILL LOOK OFF.
= Set Icon: Recomended 150x150

- Currently, Pokemon do not work as intended. Right now the only way to make a legal looking card is to make the first slot an Ability. It will open the second slot. Read "Things to do" for more information.

### Things to do ###
- The top thing on my to-do list is to get the slot fields working. Pokemon slot fields are tricky in that their postion is based off the position of the other fields. See this picture for an example: puu.sh/lsGrC.jpg 
This is probably the greatest hurdle in the creation process. 
- Special Energies. This is a low priority but it's not very complicated to get working. I'll get to it someday.
- An even lower priority is the flavor text field. The box is very small to fit what PCL normally puts in it. Flavor Text is very complex in that the font size is dynamic. MSE has a function "shrink-overflow" but it seems it doesn't work when a mask is in place. Making the font smaller doesn't necessarily work either, because then you would have a situation when there's not that much text to fill the box. 
- EXs, Megas, BREAKS, Ace Specs, Full Arts. All of those will be added at a much later date. Every single one of those cards behaves and functions completely different from the current cards. Not so much Full Arts, but that's not very important. All of those will happen, but it is after I complete (and satisfied) with regular Pokemon cards first.

### Bugs ###
- Pokemon Cards are currently a big bug all in itself.
- Slot 2 currently doesn't work. Slot 3 is non-existant.

### Credits ###
Nikki !/MSE..tf/2 (veepee on MSE forums) - Template creator
aschefield101 - Card blank creator