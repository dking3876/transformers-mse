Transformers TCG MSE Template version 1.0

About
This package is a collection of images, templates, and tools for the development of custom card faces and collections for the now-defunct Transformers TCG.

Credits: "Readme.txt" by Nate Petersen (https://www.edgeofiacon.com), see "credits.txt" for full credits and acknowledgements for the MSE Template. 

Installation:
If you're reading this, odds are the template has already been installed! If you are reading this otherwise, the Transformers TCG Template is provided as a "mse-installer" file, a zip file with installation instructions for MSE. Double click the file to run; assuming you used the MSE Installer to install Magic Set Editor, the file association will open the installer in MSE and install everything to the appropriate directories. 
If you do not have the file associated, when you double click you will be prompted to pick a program. Select Magic Set Editor from the list if it is present or click "Search for another app on this PC..." and navigate to where you installed MSE to make the association.
If you cannot for some reason utilize the built-in installer, as noted the installer file is a zip file with instructions. Rename the file to "transformers-installer.zip" and open the file with your local or favorite archive software. Extract all of the files therein to the directory where you installed Magic Set Editor. 

Fonts:
The requisite fonts are included in the installer, but will need to be installed on their own. To do so, follow these instructions:
- Open the "fonts" directory located in "transformers.mse-game", which will be located in the data folder where you installed Magic Set Editor.
- Select the desired font, double click to open.
- On the font interface screen, click "Install" 
* MSE may need to be restarted to load the appropriate font.

Using MSE
Magic Set Editor (MSE) is a rather basic point-and-click interface for developing sets of cards for various games provided a "template" has been written for that game and its related styles; that is what this package is for Transformers. 
On opening MSE, you will be prompted to make a new set or open an existing one. Clicking a "New Set" will display options for all of the games installed at the time, and clicking a specific game will reveal the various sub-styles installed for that game. For a full walkthrough, check out the video walkthrough on YouTube: https://youtu.be/EKTiPGa2iN8

Building A Set
Despite each card format for TFTCG being given its own style within MSE, a complete set can be compiled in one file. 
To begin, choose the most common card in your proposed line up; if you are generating a number of characters and the occasional Action or Upgrade card, start with a Character; if the opposite is true, start with the Action or Upgrade. 
Upon starting a new set, make your initial entries in the Set tab; set name, icon, primary artist credit, copyright/credit note. 
As you click a button to add a new card, the card's initial format will be the card style you chose first, which is why you want to begin with your most common card. To change this, select the "Style" tab and pick the new card type you are designing for. Additional options will pop up that allow further formatting decisions to be made;
- Show Collector Info will show/hide the Card Number/(Sub)Set Number for the card
- Use Faction Fonts will enable/disable the MSE Template's feature utilizing faction-based fonts for the Cybertronian text; disabling it uses the same font for all cards while enabling it will use a special font for Autobot, Decepticon, and Unicron assigned cards. 
- Alternate marks the card as an alternate face, which means it is not to be counted in the numbering. This is typically used for Battle Master and Titan Master pieces, the combined form for Weaponizers, and the Alt Mode for the normal character among other types. 

When it comes to the Characters, numbering becomes a tricky aspect; alternate modes are not traditionally counted, but some cards vary in which face is considered their alternate mode. Battlemasters "count" their weapon side, while Stratagems are their own subset of cards separate from the rest of the battle cards. On each card, on the "Style" tab, is an option to mark a card as an "Alternate"; this takes the card out of the counting consideration regardless of anything else set for the card. Doing so you can devise your triple changer's bot mode, your battlemaster's weapon mode, etc. and count the appropriate piece. 
- Battlemasters and Weaponizers count the Upgrade faces; any bot mode face associated with them should be marked as Alternate. 

"Bug Notes":
- Battle Cards & Pips; Due to the sorting method, the Pips are assigned in one of three fields, then sorted & displayed in a second field. As a result, you can assign the top-most field to "None", and the next one or two fields to a colored pip and see them sorted so that the appropriate pick becomes the top-most **displayed** pip, though its assigned field will still be the second or third field as you assigned it. 

- Triple Changers; Due to how MSE updates fields, frequent changes which end up displaying the "Triple Changer" field will not update the "Other Mode" text box. This can be updated by clicking into the field and pressing any key; the scripts will format the appropriate text but it needs to see a "change." Working on linking it to the rest of the template to update accordingly. 

- Numbering; Similar to the above, some changes will not immediately trigger a re-sorting of the cards. This will self-adjust when you type in the name field. This also impacts some shifts from a "normal" card to an alternate or vice versa.

- Foil Layer; Similar to the above again, applying and then disabling the foil layer may result in a delayed response. Click into any field and the layer should update to visible or invisible as the case may be.

-  Faction Pips; Faction pips can be added to the text box via the Format > Insert Symbol dialogue or selected as a pip from the Action and Upgrade cards. The reminder text "Pip + Faction means this works as a X Pip but only for Y Faction" is not coded and will not appear at this time. 

Differences:
Some differences between the official WotC-released cards and this template exist, some are intentional and some are unavoidable (at this time). These are not bugs, but features:  

- None of the fonts are, for now, a perfect match but I have spent a lot of time coming as close to possible without access to every font ever made. There's some good odds some fonts are proprietary to Hasbro and not generally available. The card name font (Just Dance Bold) is probably the closest, while the other fonts (Nunito, Catamaran) are among the closest match I could find to various text elements though there are some minor differences in spacing, kerning, etc. 

- Drop Shadows; a feature of MSE is the ability to add a drop shadow to text. From prior MSE templates this is an effect I appreciate as it helps the text "pop" on the final product. This has been applied to several fields. 

- Faction Fonts; Going back to fonts for a second, the default for the "Cybertronian" text, the duplicate of the name, is to use what I've termed "faction fonts." This assigns a unique font to the text based on the faction of the card. This CAN be disabled, but it adds some character to the cards. There are fonts for generic Cybertronian as well as Autobots (Modern Iaconic), Decepticons (Modern Destron), Unicron (Ancient Autobot), Maximal (Giedi Maximal), and Predacon (Giedi Predacon), all sourced from Neale Davidson/Pixel Sagas. Disabling this on the Style tab sets all cards to the Cybertronian font. 

- Card Frame Variations; There are some minor variations to the card text frames which are not ultimately reflected in the MSE Template. I rebuilt most of the elements from scratch to avoid artifacts and issues with the transparancies and instead of meticulously recreating every frame I built a semi-scalable basic frame. As such, minor proportions won't align with their WotC counterparts, particularly for the Triple Changer and Combiner frames; they are somewhat squater in proportion to the "normal" text frame. The "Combiner" frame became a full-art frame, without the black bars at the edge or down the middle. The Combiner and Micromaster frame's headers, while sized and placed properly, are "off" a bit in their pattern as the base header was scaled as opposed to rebuilding the specific header for these cards individually.

- Titans; Every other card style is designed to match their counterparts at 300 DPI, allowing you sharp, crisp, professional looking cards. Due to the sheer size of the titan frame the base frame itself **IS** laid out at full size at 300 DPI but loaded into and edited within MSE at the same size as normal frames (3.5x5 inches, or 1050 x 1500 pixels). This also results in the traits appearing larger on the frame than they might on an official product. You are more than welcome to use the elements outside of MSE, but MSE just couldn't handle editing a card THAT big reasonably! 

- Various Factions; Various factions have been added to the roster that are not in the official game. This is one part future prep, one part custom work. This includes the Unicron, Maximal, and Predacon factions as well as traits/factions for Minicons, Seacons, Technobots, and others. 

- Hybrid Features; MSE makes it easy to produce visual hybrids. As such, you can easily make Autobot/Decepticon, Decepticon/Unicron, etc. cards. Additionally, hybrid pip symbols have been added to the mix, achievable by typing, for instance, [W/U], or any other pair with a "/" between them. These are less deliberate than some and more intended to offer space for others to grow. 

- New Card Modes; Like the hybrid features, new card modes are added to the Card Mode drop downs. These include "Limb Mode," "Team Mode," and "Minicon." These have little definition behind them aside from what has been added to the template. 

- Upgrade Fields on Stratagems; Stratagems now feature the Upgrade fields for designers who are intending to increase the offense, defense, or health of bots impacted by the stratagem. This makes them visually attractive and reduces text on the card. 

- Artist Credit; Every card has a space for an artist's credit. This sits just above the copyright declaration on the card. 

Art Resources
The following links are artists, collections, and some official channels for spoiler/preview/concept art related to Transformers properties. 

While any resulting cards will of course be fan productions and in no way legal or official, I still encourage everyone to source their artwork responsibly; acquire art from as close to an official source as possible so the artist's intentions and design remain intact, connect with the artist in some way to ask permission or alert them of your use, and credit the artist on the card featuring their work (that is why the artist credit line was added!) as well as any accompanying documentation or showcase efforts. 

Artists: 
- Ken Christiansen (https://www.facebook.com/pg/The-Art-of-Ken-Christiansen-214146041944051/photos/?tab=album&album_id=906012532757395)
- Dan Kahana (https://www.deviantart.com/dan-the-artguy/gallery)
- Evan Gauntt (https://www.deviantart.com/zeromayhem/gallery)
- Thomas Deer (https://www.deviantart.com/teyowisonte/gallery)
- Eryck Webb (https://www.deviantart.com/eryckwebbgraphics/gallery)
- Josh Perez (https://www.deviantart.com/dyemooch/gallery)
- Agni Interactive (https://agniinteractive.carbonmade.com/projects/5248590#1)
- Casey Coller (https://www.deviantart.com/caliber316/gallery )
- Alex Milne (https://www.deviantart.com/markerguru/gallery)
- Marcelo Matere (https://www.deviantart.com/marcelomatere/gallery)
- Liam Shalloo (https://www.deviantart.com/liamshalloo/gallery)
- Jason Cardy (https://www.deviantart.com/jasoncardy/gallery)
- Joana Lafuente (https://www.deviantart.com/khaamar/gallery)
- Andrew Griffith (https://www.deviantart.com/glovestudios)
- (https://www.deviantart.com/yamiza/gallery)
- (https://www.deviantart.com/manbu1977/gallery)
- (https://www.deviantart.com/dcjosh/gallery)

Transformers Legends Collections:
- https://www.flickr.com/photos/114535786@N08/albums/72157639791635313
- https://www.allspark.com/forums/topic/97089-transformers-legends-catch-all-thread/
- http://bottalk.com/board/showthread.php?t=108410
- https://www.pinterest.com/Falcon0822/decepticon-transformers-art-alt-form/
- https://www.pinterest.com/Falcon0822/decepticon-transformers-art-robot-form/
- https://www.pinterest.com/Falcon0822/autobot-transformers-art-robot-form/
- https://www.pinterest.com/Falcon0822/autobot-transformers-art-alt-form/

Transformers War For Cybertron/Fall of Cybertron Collections
- http://www.tfg2.com/read.php?tid-29642-page-1.html

Icons
- https://game-icons.net/

Selecting Pieces
- Characters; The characters are almost always pulled from the files for the mobile game "Transformers Legends." Many of the artists listed above worked on Legends and provided pieces of one stripe or another.
For general consistancy, use similar selections when picking artwork for characters. When working on "themed" collections, choose artwork from related collections, IE all pieces from War/Fall of Cybertron or from IDW's ongoing series.

- Battlecards; Battlecards were pulled from a variety of places, but typically from the IDW Transformers comics. When sourcing this work, look for elements from these sources but try to avoid including speach bubbles or other comic framing elements as that has a tendency to distract. Many of the listed artists have made their finished artwork available on their gallaries or Deviant Art pages without text; try to defer to these before using scans of pages with text elements added. 

- Stratagems; ALL Stratagems officially released feature the artwork of the character card they are updating. This is a reasonable convention as it helps keep their use on the field clear. When devising new Stratagems, aim to use the artwork of the cited card first.

- Sizes: Always start with the largest possible file/version of the image you can. Images can scale down relatively easily in MSE, but you will always end up with poor quality if you scale up. 

When importing an image, watch the "Zoom" rating; anything greater than 100% indicates that MSE is stretching the image to fit the dimensions given which will result in worse quality. Going a little beyond 100% won't be evident right away, but moving past 120% becomes quite clear at a quick glance that the image is low resolution. If an image would be appropriate but is possibly oddly apportioned, open the image in GIMP, Photoshop, or another graphic editor 

Try to leave the settings alone, especially the size at "Size To Fit"; this is MSE automatically sizing a window proportionate to the viewing pane the image will fill. "Force To Fit" crams the whole image into the window and this can result in distortions to the artwork as something is crushed on the sides or top. 

"Original Size" sets the zoom to 100% provided the artwork is bigger than the view port; it will never work on images that are too small. 

"Custom Size" allows you some leeway in stretching the source selection provided the image is big enough but is not recommended.

Design Notes

Specs
The "specs" for a card are actually really simple; with over two hundred character cards released across all five waves and promotional material, there's a really solid pool of data to draw on to determine what is and is not appropriate. The spreadsheet found here (edgeofiacon.com/2020/08/29/design-average-bot-stats/) tracks those details and offers highs, lows, and averages for each stat by both the character's star value and rarity. 

Trait Placement
This describes how traits are assigned to characters, starting with the right-most trait and moving left. As such, a character like Grimlock who (alphabetically) would have the Dinobot, Leader, and Melee traits, would see them assigned (right to left) as Melee, Dinobot, Leader. 

- 1st Tier: The first tier has your function traits; things like "Ranged," "Melee," "Specialist," etc. 
- 2nd Tier: The second tier is primarily alt-modes, things like "Car," "Plane," "Truck" etc. these are almost exclusively found on "Alt Mode"
- 3rd Tier: The third tier is team affiliations; these are usually things like Aerialbots, Constructicons, and the like
- 4th Tier: Fourth tier is simply "Leader"
- 5th Tier: Any relevant "Master" designation; Battle Master, Titan Master, etc.; this gets treated with a separate tier because a character with a Master designation AND Leader will see Leader placed ahead of the Master designation. 

The MSE template has been written to recognize these for the assignment of traits; as such, when checking off traits, they will be placed in the above order regardless of alphabetical sorting or selection order. 

Abilities
Rating brand new abilities is difficult; rather, start with an existing character's ability of similar function. 
If the idea of the ability is similar in concept but tweaked, it may be OK doing a straight-swap; often swapping Bold X for Tough X and vice-versa is usually pretty well balanced. Pierce can be difficult because it becomes guaranteed damage, so a 1-for-1 on values may not be a perfect answer, but around 2/3 of the value should work out well. 

If you want to get into adjusting numbers, this becomes more difficult; if, for instance, an effect gives all attackers you have Bold 1 for a turn, and you want to swap it to Tough 2, you will need to revisit other aspects of the card. Incremental increases come from "somewhere" and either increase the star count value of the character or reduce its potency elsewhere. Increasing a Tough X value, for instance, may mean a point or two reduction in the card's printed Defense. Likewise for Bold X and Offense. 

Lifting complicated abilities from same-star value cards is typically OK. What you do not want to do is take a complex ability from a high-cost character and place it on a low-cost character; this upsets the balance a few ways. The point of the high-cost on the first character is to keep certain abilities from interacting with each other; moving that to a lower-cost character introduces that possibility which the original designers would never have intended. 

Additional costs can help mitigate and/or reduce the frequency of an effect. A common "trigger" or additional cost is shuffling your battle card deck; this happens somewhat frequently during a game but can be harder to time and will not normally trigger several times back to back for instance. This of course can be used, the Nemesis Prime/Cosmos build, for instance, is geared heavily toward that end and can trigger its effects several times in a game. 

Pips
"Pips" are the color-coded battle icons. As a part of the design of battle cards, pips are a major consideration.

The applied order of pips, either as a string of text in an ability or when placed on a battle card, usually goes as such: White (W), Orange (O), Black (B), Blue (U), Green (G). The text boxes in MSE have been written to recognize when pips are used, and to order them accordingly as long as they are contained in brackets ([]); as such, "[WGB]" will render, in the software, as "WBG"

Pips are often, but not always, "cross coded"; a battle card which enhances attack prowess, for instance, will usually have a blue pip whereas a defensive card will usually have an orange pip. 

Direct damage cards, battle cards which deal non-combat damage, are often pip-less.

Green pips are strategically placed on cards which want to be used in various reliable fashion. All Enigmas for the combiner teams, for instance, have a Green Pip. Likewise, Titan support cards will carry a green pip, allowing the Titan player to keep their smaller bots in motion. Straight battle cards who don't serve a specific purpose can have a green card, but these can be dangerous; this is one of the factors that led to the banning of "Press the Advantage" as with the green pip the card was very reliably drawn and used repeatedly in games (PtA breaks several of these rules in fact; it boosts offensive prowess, has an orange pip, and has a green pip which allows it to be recovered easily.) 

Stars
- Characters
Characters' star values can be pretty easily determined using the supplied spreadsheet. Mind, these are ranges, not a guarantee, but they provide a solid outline. Use these outlines when drawing your initial determinations and tweak from there; enhancing one stat should come with a reduction in another, trading values but staying within the ranges provided. 

- Battle Cards
Battle cards have star costs when they are fairly distinctly better than another card to the point it renders the other card obsolete. Zap, for instance, deals 1 damage to a single target; Photon Bomb deals 2 damage to ALL characters. Photon Bomb deals more damage, but it hits your own characters as well, so it has a built in cost. Photon Bomb can do a lot of good, but puts you in a weaker state, whereas Zap can take a character off the board with targeted damage. Both cards are star-less. Bolt of Lightning, on the other hand, deals 3 damage to a single target; a significantly better card than Zap, and a much better card than Photon Bomb because it won't harm your side of the board. 

Battle Masters vs Weaponizers (vs Minicons?!) 
I had to ask a few questions myself about this, so don't feel too badly! 
Functionally, there's no mechanical difference between how Battle Masters and Weaponizers work; its more a matter of how the designation is applied. 

Battle Masters are typically designed as "Micro Master" framed cards; they're small, typically have a low star value (and requisite stats) and give a decent but not bonkers boost. 

Weaponizers are designed on the traditional card frame and present one larger, much more impressive, upgrade or break down into two smaller but still meaty upgrades. 

"Quarteramster" can interact with Battle Master cards, not Weaponizers, while the stratagem "More Guns" interacts with Weaponizers. 

"So wait," you ask. "What's this with MINICONS?! Those aren't in the game!" Minicons represent an element of Transformers lore that's basically sitting right there, waiting to be used, and so has been incorporated into the MSE Template in several ways. 

"Timelines," Edge of Iacon's fan set project, will relrease a handful of Minicons to utilize the function and demonstrate it, but the idea is essentially the same as Battle Masters and Weaponizers, only Minicons have an alt mode, something the other two lack. As a result, Minicons should be designed on the "Combiner" frame, with the alt mode and bot mode each making up 1/2 of the Combiner face, and the Upgrade comprising the back-side. According to lore in Transformers Armada, their debut, Minicons are powerful upgrades to larger bots and as such would recommend that their power levels fall between the Battle Master and Weaponizer cards, hewing closer but not eclipsing the Weaponizers. 

Minicons will begin the game in alt mode, and can move between alt and bot modes as normal; once KO'd, like their predecessors, you instead play their Upgrade side, upgrading a larger 'bot with their powers! 