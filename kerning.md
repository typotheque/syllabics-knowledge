# Syllabics Kerning
Within the context of Syllabics typography, kerning has very rarely – if ever – been implemented into any typeface, despite the dramatic positive impact it has on improving the legibility and readability of Syllabics texts across all user communities. 

![Syllabics Kerning](/figures/syllabics-kerning.png)
##### The above image shows a simple comparison of a Nattilingmiutut Syllabics text, without (top) and with (bottom) kerning. The word image is obscured in unkerned example, top, causing the word to break apart. In the kerned example, bottom, the two words are clearly defined, and can be read with much greater clarity and ease. 
<br>


In this repository, you will find a `csv` document that provides kerning data specific to Syllabics: kerning pairs and suggested classes for implementing into Syllabics typefaces.The kerning pairs and classes are suggested, and kerning tables for a given Syllabics font implementation should take into consideration the direct requirements of each specific community and their language patterns.

<br>

## Methodology
As noted above, kerning is a relatively uncommon in Syllabics typography. As such, there are not very many resources available from a font design and development standpoint towards implementing support for kerning into Syllabics typefaces.

The main spacing issue that is encountered in Syllabics texts where kerning can help is in common and frequent sequences where the raised finals characters pre or proceed the larger syllabic base characters, especially the medial height syllabic characters with finals:

![Syllabics glyph boundary](/figures/syllabics-kerning-glyph-bounds.png)

Note that in the above example, the inherent structure of these particular combinatinations, of medial height, full size syllabic characters with the raised final produces a large void of excess white space within the bounds of a glyph's left and right sidebearings. These large pockets of white space push word spacing apart, and have the effect of making words appear ambiguous and harder to decipher. This of course effects the ability of readers to identify words during reading and to comfortably consume a given text. In other words, it has a significant effect on the reading experience.

By applying kerning to these sequences (along with other sequences of full height syllabic characters to finals, as shown in the above example), a more legible and readable word image can be attained for Syllabics readers, which results in a much improved reading experience:

![Kerning applied to Syllabics glyphs](/figures/syllabics-kerning-applied.png)

This is particularly true for the Algonquian and Inuktut Syllabics, who follow the Round form style of Syllabics, which contain many sequences of medial-height-syllabic-to-raised finals characters. Dakelh (Carrier) Syllabics, for example, follow the Square form Syllabics style pattern and are largely disunified from the Algonquian and Inuktut Syllabics in Unicode, and should be treated as a separate set for kerning purposes.

## Kerning Classes
One reasonable concern for implementing kerning for a pan-UCAS Syllabics font (a Syllabics font that supports the enture Unified Canadian Aboriginal Syllabics encoding in Unicode) is the sheer size of the work. Luckily, the inherent behaviour of rotation within the writing system can be leveraged to significantly reduce the workload by grouping common syllabic and finals shapes together into kerning classes.

As a result of the Syllabics's principle of rotation, many of the medial height and full height syllabic characters that require kerning are repeated shapes, only that their orientation has changed. Furthermore, many of the medial height syllabic glyphs that cause a large amount of white space preceeding or proceeding a finals character (ᓇᓚᖤᕆ) have a similar volume of white space above them which allow them to be grouped together.

The finals characers – which either follow the pattern of being a superscripted version of the a-vowel in a series, or, a distinct, superscript-sized mark – share for a very large part the same general width proportion, and occupy a relatively similar amount of general space. Although there are exceptions, a large portion of these finals characters can be kerned to the same value as one another, and therefore, they can be grouped together into kerning classes to reduce the amount of pairs that have to be individually treated.