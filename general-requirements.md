
## General Syllabics Recommendations
The Syllabics share the word space, punctuation, and numeral glyphs with the Latin script, but require local variations to accommodate the inherent proportions of the writing system in order to maintain readability and legibility for users across all communities.

## Syllabics vertical metrics

When designing a Syllabics typeface, it is important to consider the ideal vertical proportions for the Syllabics glyphs. What must be considered is that the Syllabics will likely need to be used in context with the Latin script. 

This can be both in embedded settings, where Syllabics words may be surrounded by English or French text, and vice versa, where English or French words are embeded within Syllabics paragraphs, which is relatively common. It may also be seen in multilingual documents where Syllabics and Latin text paragraphs run side-by-side. For a good harmony to be achieved, the Syllabics forms should be ideally shorter and generally wider than the typical cap height and proportional width of Latin script characters. Therefore, the full height Syllabics characters should be roughly 10–15% shorter than the Latin capital height in order for the Syllabics to retain it's ideal proportions, while also working in harmony alongisde the Latin script:

![Syllabics vertical metric grid](/figures/syllabics-vertical-metrics.png)

<br>

## Syllabics word space
All Syllabics typefaces must have a word space glyph that is significantly wider than the Latin Script, by comparison:

![Syllabics word space](/figures/word-space.png)

This is essential and non-negotiable in order for Syllabics texts to remain legible and readable. If Syllabics texts use a Latin script width word space, the very narrow Latin space (in comparison to the wide internal counter structures of the Syllabics), the word images within a given sentence or paragraph of text will be undistinguishable. 

From the encoding perspective, the Syllabics, by default, uses the word space character U+0020  SPACE, which is shared with many other writing systems, including Latin, which Syllabics is commonly used alongside.

Note that there is a practice by Syllabics users of encoding a double space character to acheive a wider Syllabics space. This should be considered as a factor towards choosing the best implementation for the users of the typeface that one is developing:

![Double Syllabics word space encoding practice](/figures/double-syllabics-word-space.png)

One option is to provide two parallel typeface families: a Syllabics-specific version that renders the deafult word space at the Syllabics required width, and then provides a separate, parallel Latin script font with an appropriate, narrower glyph width (this allows for accommodating other Syllabics-specific glyph variants as well without relying on complex OpenType Layout Features). 

Alternatively, the Syllabics and Latin-specific in a unified typeface implementation word space glyphs could be mapped to OpenType Stylistic Sets which could be used for script-specific typesetting.

<br>

## Syllabics numerals 

As noted in the above section "Syllabics vertical metrics", Syllabics glyphs should ideally be shorter than the Latin script capital height for harmony to be achieved between both scripts. Syllabics use the same Arabic numerals as the Latin script, however, given the shorter height and wider general proportional width of the Syllabics, it is ideal to design a set of lining numerals adapted to these inherent Syllabics proportions in order to allow numerals to blend harmoniously into Syllabics text settings:

![Syllabics tailored numerals](/figures/syllabics-numeral-proportions.png)

<br>

## Syllabics punctuation

Along with providing Syllabics-specific numerals to address their inherent proportional differences from the Latin, similar adaptations of the common punctuation used in Syllabics typography should be provided in a given font build that would design characters such as the question mark (?) to the height and slightly wider width required to better suit Syllabics, along with vertical positioning adjustments to parenthesis, quote marks, and other punctuation:

![Syllabics specific punctuation](/figures/syllabics-specific-punctuation.png)

The following glyph list presents the standard punctuation marks and special characters that are generally used in the Syllabics:
> ᐀ ᙮ , : ! ? * / \ - – — ( ) { } [ ] “ ” ‘ ’ " ' & $ − × ÷ =