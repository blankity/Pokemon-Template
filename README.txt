Welcome to the Pokémon Template for the Magic Set Editor Program. This template is not complete so keep that in mind.

Current Version: 0.32

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
- Ability Symbol: A!

- This isn't a symbol font code, but you'll probably use this A LOT. It is the accented e. 
=== ALT+0233 ===
é

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
- 5 Energy attacks. This isn't actually a low priority, and it will actually be worked on when I work on making all of the boxes dynamic position and size. For now though, it doesn't work because the Cost boxes are set widths.
- Rarity symbols. I haven't really added them in because Rarity symbols are for the sake of booster packs. Their use is only aesthetic so I haven't bothered adding the space for them yet. It's on the list of things to do though, but it's more or less for when I want it to look 100% like a Pokemon card.
- EXs, Megas, BREAKS, Ace Specs, Full Arts. All of those will be added at a much later date. Every single one of those cards behaves and functions completely different from the current cards. Not so much Full Arts, but that's not very important. All of those will happen, but it is after I complete (and satisfied) with regular Pokemon cards first.

### Bugs ###
- Pokemon Cards are currently a big bug all in itself.

### Credits ###
Nikki !/MSE..tf/2 (veepee on MSE forums) - Template creator
aschefield101 - Card blank creator