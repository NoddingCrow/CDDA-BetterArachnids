
# Better Arachnids vB 1.0  
*By Crow!*  
*Last Change: UltiCa tileset support and cleanup to Beta 1*  
**Important: This mod REQUIRES Experimental-Branch Cataclysm Dark Days Ahead, and will not work on Stable 0.G or likely 0.H.**  

This is a fairly substantial Overhaul mod for Arachnid Mutants in Cataclysm: Dark Days Ahead, designed in three modules. Each module is designed to operate independently, and so if you don't like the content of a module you're free to delete it!  

Want to stay being a giant spider tank? Go ahead and delete the Slim Chitin. Think cocooning and turning prey into nutrient goo is kinda gross? Me too! Delete Cocoon Digestion. This mod will only appeal to a small subset of users as is; I want you to be able to enjoy it.  

## **Module 1: slim-fit chitin**  
This module rebuilds the spider chitin mutation lines to form a more "dodge tank" oriented playstyle, and allow you to get your fashion on.  

Rather than a fully fledged Arachnid having Epicuticle (Personal Aura Layer), Chitin Carapace (Normal Layer), and Sclerotin Plate Armor (Outer layer) - thus restricting all clothing to only the strapped layer, or outer layer with collision penalties - I've instead squished it all down to just being Epicuticle (Personal Aura Layer) and a new Arachnid Carapace (Skintight Layer).  

Balance and playstyle considerations: The new Arachnid Carapace armor is lightweight and low encumbrance, and can be considered similarly to riot armor. Since this can of course be stacked with e.g. environment suit and ballistic vest, this can be pretty strong! However, the armor counts as HARD, and is full body coverage bar the soles of your feet - you will be flatly unable to wear any further hard armor, which includes ESAPI plates.  

The end result is a very capable natural dodge tank, with respectable armor for taking minor hits from basic and medium tier Zs. However, if pinned down and unable to dodge, and if taking lots of hits per round, the gaps in the coverage will begin to add up and you'll start taking damage. Further, chitin performs rather woefully against ballistic threats; so with the lack of ESAPI plates as well, becoming Too Scary and having the humans start shooting at you is a good way to become a squashed spider! Mutate responsibly!  

This module also adds the extremely cool but unused WALL_CLING flag to the final form of arachnid arms - meaning you can scale sheer walls without needing a stepladder, grappling hook, or furniture to brace off! You'll also have better chances to save yourself when falling adjacent to a wall. This all costs significant stamina, naturally, so wall climb with caution.  

Optional Files:  

`chitin_mutations_override_noThreshold.json.txt` - this file will remove the threshold requirements for Arachnid Limbs, Arachnid Arms, and the web weaving and venom mutations. This will allow you to access nearly the full spider power without having to pass the threshold. **If you wish to use it, simply delete `chitin_mutations_override.json` and remove the .txt extension from this file name.**

`wall_cling_arachnid_arms.json.txt` - in the event you wish to delete module 1 in its entirety, you may first copy this file out if all you want is to add the WALL_CLING flag to arachnid arms. **If you wish to use it, remove the .txt extension from this file name. Note that this file is INCOMPATIBLE with the rest of module 1, and should only be used if you're deleting it.**

## Module 2: eight-legged tailors
This module takes control of the *Rope Webs* base game mutation to make it a little better. 
Using the renamed "Fabric Weaver" active mutation will give you a menu, to spawn your choice of Thread, Heavy Duty Thread, Long String, Long Rope, and new "Bolts of Spidersilk". 
These bolts of spidersilk come in three types: Cottonweave, Nylonweave, and Kevlarweave. Cotton and Nylon have similar costs, with Nylon being slightly more complex. Kevlarweave is considerably more expensive, but still very affordable. The spidersilk can then be deconstructed into ten sheets of the appropriate tailoring material.  
*Exact values may be subject to balance changes!*  

Optional Files:  
`weaver_mutation_override_noThresh.json.txt` - much like the equivalent in module 1, this file will remove threshold requirements for the Fabric Weaver mutation (ROPE_WEBS). **If you wish to use it, remove the .txt extension and delete `weaver_mutation_override.json`.**

## Module 3: cocoon digestion
A port and cleanup of my old *External Digestion 2* mod, this module allows spiders to cocoon whole prey and convert their juicy insides to nutrient slurry at a very high efficiency - approximately 90% of all non-bone mass (calculated based off human dimensions) will be recovered as a nutrient slurry that both feeds and quenches thirst in the spider.  

This module, however, has some of the greatest limiting factors - chiefly that it is impossible to determine any information about the corpses for anything but butchery. The implementation therefore is:  
6 new recipes are added under the ARACHNID tab of the crafting menu. Tiny, Small, Medium, Human, Large, and Huge.  
**This operates as an honor system**. I cannot stop you using rotten corpses, zombie corpses, or using a corpse for the 'wrong size' recipe so getting a Moose's worth of nutrients out of a chicken. It is entirely possible to game this system. If you want to do so, that's entirely your choice.  
The Human cocoon is identical to the Medium Cocoon, but drops a human skull on disassembly when finished, by request.  

Once you've crafted your cocooned corpse, activate it to begin digestion. This will take between around 15 seconds for a tiny squirrel corpse, to 40 hours for a huge corpse the size of a moose. You can leave the active cocoon and come back later, once the process has started.
Come back, and activate the cocoon again. If the required time has passed, you will get a *digested cocoon* filled with liquid nutrient slurry. This has a shelf life of approximately 1 day, extended to 3 while it's in the cocoon.  
Once your cocoon is drained, or before if you want to make a mess, you can disassemble it to recover the bones of your prey if you so choose.  

## License and disclaimers  
This mod is released under Creative Commons Attribution-ShareAlike 3.0 Unported License. See LICENCE.txt for full information.  
Additional attribution must be given to the base game's wonderful tilesets, whose sprites I used with a little recoloring in this mod.  
This mod is released as-is, with no guarantees of future updates or compatibility.  
I ask that this mod is not uploaded onto the Steam Workshop under my name under any circumstances.  
