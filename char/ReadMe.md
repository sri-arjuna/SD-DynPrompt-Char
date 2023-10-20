# SD DynPrompt - Char

Got tired of "creating new characters"? \
Try this random char generation!

It supports 2 "modes":
* SFW === CivitAI TOS protection (if your image gets flaged, its due to the SD-model, not the keywords)
* Sexy === For local or anime characters, hot and spicy!

That said, it offers also:
* Fantasy RP characters (Dwarf, Elf, Succubus, Furry, Fae, Angel)
* Sci-Fi Clothing


## Basic Usage:

This excludes Fantasy RP characters.

	__char/aio-sfw__

If you want to dress the character on your own, just skip the "aio" part:

	__char/sfw__


## Clothing:

So, you have your character and want different clothings but are tired to trying? \
Try this:

	__char/cloth/sfw__

Get me right, its all random! \
No guarantee for aproriate or matching clothing, but you'll definitly get ***a lot*** of differenty outfits!





In my conquest to get "an easy as possible" prompt, with as many things "automated" as possible, "SD DynPrompt Char" is just one of multiple packages.

It is ment to be either "standalone" if you want to define your backgrounds on your own, or as dependency if you want to use my "SD DynPrompt Landscape XL" which provides stunning and awesome landscape prompts.



# Structure - Basic

You can call either of these keyword: 
char/race:		This will provide keyword to represent ANY race at random, see below if you want to access different races specificly.
char/body:		From athletic or curvy to slender or thin, anything but fat or obese. (if you want those, feel free to add them to the textfiles yourself!)
char/body-sfw		This will not containt any keywords that might trigger the automatic detection of CivitAI.com (as in, avoid TOS violation when used with celebrities)
char/dress		This will dress the female in regular "tame" clothing. (SD will still show cleavage at times).
char/dress-sexy		This will dress the female in various sexy, skimpy or even naughty clothing.


__pose__
__pose-sexy__
__pose-behind__



# Structure - AIO (All In One)
char/aio-sfw		
char/aio-sexy

char/aio-close
char/aio-far
