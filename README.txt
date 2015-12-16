Welcome to the Pokémon Template for the Magic Set Editor Program. This template is not complete so keep that in mind.

Current Version: 0.25

1: Installation
2: Useful Info
3: Things to do
4: Bugs
5: Credits

### Installation ###
- Installing MSE is easy. If you downloaded the Pokemon.rar file, just extract it somewhere and install all of the fonts. Then run MSE.exe.
- If you already have MSE, then you can download the pokemon-mse.installer file and install it using MSE. Just drag the file to MSE.exe and it will install it. Download fonts.rar and install of them as well.
- If you already have a previous version of the Pokemon template, then just download Pokemon.rar and overwrite all of your files. Make sure to go through each of your cards and correct them, as I can guarantee they probably won't look the same.

### Useful Info ###
- Symbol Font Codes! Icons are used for attack cost, weakness, and resistance. Text are used for the icons in text fields. To use these "codes" simply type them where you want them! For example: "Search your deck for a É Pokémon" will result in "Search your deck for a [P] Pokémon" EASY!
!Note! - Alt Codes only work if you have a numpad. If you don't have one, I'm afraid you will have to copy/paste from this file.
======
Grass (Icon): g1
Grass (text): Í (ALT+0205)
======
Fire (Icon): r1
Fire (text): Ê (ALT+0202)
======
Water (Icon): w1
Water (text): Î (ALT+0206)
======
Lightning (Icon): l1
Lightning (text): È (ALT+0200)
======
Psychic (Icon): p1
Psychic (text): É (ALT+0201)
======
Fighting (Icon): f1
Fighting (text): Ï (ALT+0207)
======
Dark (Icon): d1
Dark (text): Ñ (ALT+0209)
======
Metal (Icon): m1
Metal (text): Ë (ALT+0203)
======
Fairy (Icon): y1
Fairy (text): Ì (ALT+0204)
======
Dragon (Icon): (don't have an icon for it)
Dragon (text): Ò (ALT+0210)
======
Colorless (Icon): c1
Colorless (text): Ð (ALT+0208)
======
Ability Symbol: A!

- This isn't a symbol font code, but you'll probably use this A LOT. It is the accented e. 
=== ALT+0233 ===
é

- Image sizes!
Pokemon, Trainers, and Special Energy all use different image sizes. As such, I've posted a list of resolutions for those who want their image to fit exactly. Keep in mind, MSE has an option to auto-fit images, so resizing images isn't necessary.

= Normal Pokemon (Basic, Stage 1, Stage 2): 307x201
= Trainers: 295x181
= Special Energy: Not yet created
= Evolution Icon (For Stage 1 and 2): 100x100 PLEASE NOTE!!!! Your image must be EXACTLY this. Center the pokemon in the middle of the image. IT HAS TO BE 100x100 OTHERWISE IT WILL LOOK OFF.
= Set Icon: 15x15

- Currently, Pokemon do not work as intended. Right now the only way to make a legal looking card is to make the first slot an Ability. It will open the second slot. Read "Things to do" for more information.

### Things to do ###
- The top thing on my to-do list is to get the slot fields working. Pokemon slot fields are tricky in that their postion is based off the position of the other fields. See this picture for an example: puu.sh/lsGrC.jpg 
This is probably the greatest hurdle in the creation process. 
- Special Energies. This is a low priority but it's not very complicated to get working. I'll get to it someday.
- Pokemon info. This is that little bar that's below the image. Honestly, it's just laziness that's getting the best of me. It's another simple fix, and it's less characters than this sentance. Not even kidding. Okay, I am. It's actually more because of the 3 different If statements I have to add. It's mostly just getting the position and text right that's a hassle.
- An even lower priority is the flavor text field. The box is very small to fit what PCL normally puts in it. Flavor Text is very complex in that the font size is dynamic. MSE has a function "shrink-overflow" but it seems it doesn't work when a mask is in place. Making the font smaller doesn't necessarily work either, because then you would have a situation when there's not that much text to fill the box. 
- 5 Energy attacks. This isn't actually a low priority, and it will actually be worked on when I work on making all of the boxes dynamic position and size. For now though, it doesn't work because the Cost boxes are set widths.
- Rarity symbols. I haven't really added them in because Rarity symbols are for the sake of booster packs. Their use is only aesthetic so I haven't bothered adding the space for them yet. It's on the list of things to do though, but it's more or less for when I want it to look 100% like a Pokemon card.
- EXs, Megas, BREAKS, Ace Specs, Full Arts. All of those will be added at a much later date. Every single one of those cards behaves and functions completely different from the current cards. Not so much Full Arts, but that's not very important. All of those will happen, but it is after I complete (and satisfied) with regular Pokemon cards first.

### Bugs ###
- Pokemon Cards are currently a big bug all in itself.
- Italics do not work in the slot text fields. This is because, for whatever reason, MSE disables styling if symbols are on. This is not something I know how to fix, nor would I be able to as I think the root problem is with MSE itself.

### Credits ###
Nikki !/MSE..tf/2 (veepee on MSE forums) - Template creator
aschefield101 - Card blank creator