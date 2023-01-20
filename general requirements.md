
## General Syllabics Variant Glyphs
The Syllabics share the word space, punctuation, and numeral glyphs with the Latin script, but require local variations to accommodate the inherent proportions of the writing system in order to maintain readability and legibility for users across all communities.

## Syllabics word space
The Syllabics must have a word space glyph that is significantly wider than the Latin Script, by comparison:

![Syllabics word space](/figures/word-space_SyL-Knowledge-figures.png)

This is essential and non-negotiable in order for Syllabics texts to remain legible and readable. If Syllabics texts use a Latin script width word space, the very narrow Latin space (in comparison to the wide internal counter structures of the Syllabics), the word images within a given sentence or paragraph of text will be undistinguishable. 

The Syllabics by default uses the word space glyph U+0020  SPACE, shared with many other writing systems. It is possible to implement a wider word space glyph to accommodate the Syllabics through rendering U+0020 at an appropriate glyph width value for this system, but it will then produce a word space far too wide for the Latin script. One could provide a Syllabics-specific typeface that renders the deafult word space at the Syllabics required width, and then provides a separate Latin script font with an appropriate, narrower glyph width (this allows for accommodating other Syllabics-specific glyph variants as well). Note that in this implementation, it is important to include a basic Latin capital and uppercase characters within the Syllabics font in this arrangement as users expect these glyphs to be present within the Syllabics typeface.

Alternatively, the Syllabics and Latin-specific word space glyphs could be mapped to stylistic sets which could be used for script-specific typesetting.



## Syllabics numerals 



## Syllabics punctuation