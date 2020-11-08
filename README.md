# AutoCorrect-AHK-2.0

## About and Credits

This is an [AutoHotKey](https://www.autohotkey.com/) script for AutoCorrect.

This is a combination of the 2007 [AutoHotkey AutoCorrect script](http://www.autohotkey.com/download/AutoCorrect.ahk) as well as [endolith's](https://gist.github.com/endolith/876629) script (as of 2020-11-05) with my customisations and additions.
Further credits are listed in the script itself. 

My script contains a large amount of new content from : http://en.wikipedia.org/wiki/Wikipedia:Lists_of_common_misspellings </br>
(additions since the original 2007 script was made)
the Main list has increased from **5900+-** corrections up to **8200+-**. 

## Attention

* Ensure the script file is saved and encoded in **"UTF-8-BOM"**, UTF-8 is not sufficient. (My script has been converted and saved as UTF-8-BOM. I mention this should it have changed at any point at your end). </br> You will get strange behaviour when converting letters with sepcial characters if not encoded at **UTF-8-BOM**. E.g.  touché, will output touchÃ© 
* If your output word contains a ` character, you need to type it twice, this is due to AHK using ` as an escape character. E.g. Password123`! would output as Password123! (without the `) so to output correctly use Password123``! (the first one is treated as a escape character and the second is the character to remain)

## Changelog 

**NOTE:** My script has been extensively edited **specifically for British English, NOT American English.** (e.g. customise / customize )

* Added **British to American and American to British sections within the script.** )Still needs a lot of work to remove the duplicates in the main list, allowing to easily uncomment and comment entire sections you prefer.)
