# AutoCorrect-AHK-2.0

## About and Credits

This is an [AutoHotKey](https://www.autohotkey.com/) script for AutoCorrect.

Credits to: </br>
The original author/creator of the script file, [Jim Biancolo](http://www.biancolo.com/blog/autocorrect/) </br>

My script **AutoCorrect-AHK-2.0** is an amalgamation of the 2007 [AutoHotkey AutoCorrect script](http://www.autohotkey.com/download/AutoCorrect.ahk) as well as [endolith's](https://gist.github.com/endolith/876629) script (as of 2020-11-05) with my customisations and additions. </br>

Further credits are listed in the script itself. 

My script contains a large amount of new content from : http://en.wikipedia.org/wiki/Wikipedia:Lists_of_common_misspellings </br>
(additions since the original 2007 script was made)
the Main list has increased from **5900+-** corrections up to **8200+-**. 

## Attention

* Ensure the script file is saved and encoded in **"UTF-8-BOM"**, **UTF-8** is not sufficient. </br> My script has been converted and saved as **UTF-8-BOM** and as such should work correctly. </br> Though I mention this, should it have changed at any point at your end. </br> You will get strange behaviour when converting letters with sepcial characters if not encoded as **UTF-8-BOM**. </br> E.g.  touché, will output touchÃ© </br> You can use [**Notepad++**](https://notepad-plus-plus.org/downloads/) to convert files, open the file in **Notepad++** and then in the top menu **Encoding > Convert to UTF-8-BOM**, </br> then save your file. 
* If your output word contains a \` (Grave accent) character (as a standalone, not as an accent to a letter), </br> you need to type it twice, this is due to AHK using \` as an escape character. </br> E.g. Password123\`! would output as Password123! (without the \` ) so to output correctly use Password123\`\`! </br> (the first one is treated as a escape character and the second is the character to remain)

## NOTE
The script contains separate secetions for **British English** and **American English** </br>

By default the script is enabled for **British English** </br>
See **American English** commented section within the script with instructions to enable it (and Disable British English)

## Changelog 

* Added **British to American and American to British sections within the script.** )Still needs a lot of work to remove the duplicates in the main list, allowing to easily uncomment and comment entire sections you prefer.)
