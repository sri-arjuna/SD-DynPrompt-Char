# SD DynPrompt - Char

Got tired of "creating new characters"? \
Try this random char generation!

--------------------

--> Requires [DynamicPrompt](https://github.com/adieyal/sd-dynamic-prompts), will NOT work with AutomaticWildcards! <--

* For images generated with this dynamic prompt, please see: [CivitAI](https://civitai.com/models/178779/dynamicprompt-char)
* Full description and most recent versions on [GitHub](https://github.com/sri-arjuna/SD-DynPrompt-Char)
* Designed to be used with [DynPrompt - BG](https://github.com/sri-arjuna/SD-DynPrompt-BG) (or see images of that on [CivitAI](https://civitai.com/models/160192/background-xl))

--------------------

It supports 2 "modes":
* SFW === CivitAI TOS protection (if your image gets flaged, its due to the SD/XL-model or pose, not the keywords)
* Sexy === For local or anime characters, hot and spicy!

That said, it offers also 3 styles, of races and clothing:
* Modern clothing
* Fantasy RP characters (Dwarf, Elf, Succubus, Furry, Fae, Angel)
* Sci-Fi Clothing

The main purpose is for "modern use", thus, for RP and Sci-Fi, the use varies slightly. \
See Basic Usage.

## Installation:

* Extract the contained ./char folder to your wildcard directory.
* So it looks like: (WebUI_DIR)./extensions/sd-dynamic-prompts/wildcards/char


## Basic Usage:

This excludes Fantasy RP and Sci-Fi styles.

	__char/aio-sfw__

If you want to dress the character on your own, just skip the "aio" part:

	__char/sfw__

### RP / Fantasy

Now, RP/Fantasy and Sci-Fi offers a similar approach:

	__char/rp-sfw__

This would generate a SFW body with a RP race (off chance for human). \
There is no RP/Fantasy clothing prepared, either you rely on the AI for aproriate clothing, or define it yourself.

# Science Fiction:

Or, of course:

	__char/scifi-sexy__

Which would produce a NSFW body and a scifi char (android, cyborg) with an off chance for human), using the the scifi-sexy clothing file.

## Clothing:

So, you have your character and want different clothings but are tired to trying? \
How about:

	__char/cloth/aio-sfw__

Get me right, its all random! \
No guarantee for aproriate or matching clothing, but you'll definitly get ***a lot*** of differenty outfits!



# Call - List:

Please keep in mind, you should use this syntax:

	{ __char/aio-sfw__ | __char/rp-sfw__ }

I use the style below only to make the list/table shorter:

> Keep in mind, always use ``__char/<CALL>__``

| Call 				| Result		|
|-------------------|---------------|
| aio-{sfw/sexy}	| Generates body, race, modern clothing 		|
| rp-{sfw/sexy}		| Generates body, fantasy race 					|
| scifi-{sfw/sexy}	| Generates body, scifi race, scifi clothing 	|
| race 				| Returns a random race (human), 100% or mixed	|
| race/any 			| Returns a random race (human), 100% only		|
| race/mixed		| Returns a mixed race 							|
| race/rp 			| Returns: Dwarf, Elf, Succubus, Furry, Fairy, Angel |
| race/scifi 		| Returns: ANY, Cyborg, Android 				|


## Additions:

| Call 				| Result		|
|-------------------|---------------|
| body/sfw 			| Returns a SFW body |
| body/sexy 		| Returns a sexy body, using more explicit keywords (that might trigger CivitAI filter)
| cloth/aio-{sfw,sexy} 		| Returns a 'set' of modern clothing, matching the keyword (sfw or sexy)
| cloth/scifi-{sfw, sexy} 	| Returns a 'set' of science fictional clothing, matching the keyword (sfw or sexy)
| facial/bad 		| Returns: angry or contempt facial expressions 														|
| facial/flirt 		| Returns: aroused (like: seductive, flirtatious) or NSFW (incl: blushing, panting) facial expressions 	|
| facial/good 		| Returns: happy, neutral or otherwise smiling facial expressions 	(best pick for most images)			|
| facial/shock 		| Returns: fearful, confused or surprised facial expressions 											|
