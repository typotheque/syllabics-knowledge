# ᒐᐦᑭᐯᐦᐃᑲᓇ (cahkipêhikana) (Cree Syllabics)
The Cree Syllabics comprise the largest language user group that identifies the Syllabics as its primary writing system. These language communties stretch geographically west to east from Alberta and the Northwest Territories to northern Québec. Cree language communities West of northeastern Ontario use an orthographic repertoire that is different from those Syllabics-using communities in northern Québec and northeastern Ontario, particularly in the form of finals characters. There are also typographic preference variations between and within Western and Eastern Cree communities that should be considered when developing typefaces and language tools for these individual communities.

## ᓀᐦᐃᔭᐍᐏᐣ (nêhiyawêwin) (Plains Cree)

Plains Cree communities comprise the largest group of speakers who use Syllabics as their primary and preferred writing system, and have a long and vibrant use of Syllabics. Plains Cree Syllabics follow the Round form style, although historically, the Square form style would have also been employed in 19th century and early-to-mid 20th century texts. Note that Plains Cree communities may use the Syllabics hyphen U+1400 ᐀ CANADIAN SYLLABICS HYPHEN and the Syllabics full stop, U+166E ᙮ CANADIAN SYLLABICS FULL STOP, or, the Latin script representations and encoding for these characters.
 
![Plains-Cree-Syllabics Orthography Chart](/static-syllabics-charts/plains-cree-syllabics.png)


❶ Plains Cree Syllabics users may encode "w dot" using may encode the "w dot" as U+1427 ᐧ CANADIAN SYLLABICS FINAL MIDDLE DOT plus the base syllabic glyph (ᐧ + ᐃ = ᐧᐃ) or with the pre-composed base glyphs within UCAS, where "w dot" and the base syllabic are treated as a composite glyph (ᐎ, ᐗ).

❷ Although some system-level Syllabics typefaces and historical texts have represented U+1425 ᐤ CANADIAN SYLLABICS FINAL RING at horizontally centered at the mid line, contemporary texts and communities show the preference for this glyph to be vertically positioned at the top line, consistent with the positioning of all other finals.

❸ There is variation within Plains Cree communities in terms of the representation of the "y series" final character and how it transforms when paired with the "w dot". The common form of this in Plains Cree is a plus mark U+1429 ᐩ CANADIAN SYLLABICS FINAL PLUS; however, some communities prefer to use a superposed dot mark U+141D ᐝ CANADIAN SYLLABICS Y-CREE W, which is graphically distinct from the common "y final". It should be noted that this alternative "y final" form (see example 2 in the below image) should be represented as a combination of a closed "w dot mark" on the bottom, and an open, small ring character at the top, rather than two open ring characters, as is shown in some general, system-level typefaces:

![PLains Cree y-final alternative form](/figures/plains-cree-y-dot.png)

There is also variety in the way that the "y final" transforms when it preceeds the "w dot" modifier. The general w + y final sequence is represented by two inline characters, U+1427 ᐧ CANADIAN SYLLABICS FINAL MIDDLE DOT + U+1429 ᐩ CANADIAN SYLLABICS FINAL PLUS. In some communities, this sequence is preferred to be graphically represented by a combination of two stacked "w dot" marks, with the lower dot taking the same position as "w dot", and the second dot, above, positioned at the top line:

![Plains Cree y + w final transformations](/figures/plains-cree-w-y.png)

This alternative combination is not encoded in Unicode, and must be implemented in any given Syllabics typeface as an alternative glyph, and mapped in a way that agrees with the input method of the client or community members who will use the typeface.


Plains Cree Syllabics Subset:
> ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐍ ᐏ ᐑ ᐓ ᐕ ᐘ ᐚ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᐧ  ᐤ  ᑊ  ᐟ  ᐠ  ᐨ  ᐨ  ᐣ  ᐢ  ᐩ  ᓬ  ᕒ  ᐦ  ᕁ  ᐝ ᛬ ᐀ ᙮



## ᓀᐦᐃᖬᐍᐏᐣ (nīhithawīwin) (Woods Cree)
Woods Cree communities have a strong preference for using Syllabics as their primary writing system and, as in Plains Cree communities, have long history of Syllabics use. The Woods Cree Syllabics typically follow the standard Syllabics glyph representations of the Round form style, and there are no outstanding local typographic or encoding preferences that require accommodating.

![Woods-Cree-Syllabics Orthography Chart](/static-syllabics-charts/woods-cree-syllabics.png)

Woods Cree Syllabics Subset:
> ᐧ ᐁ ᐃ ᐅ ᐆ ᐊ ᐋ ᐁᐧ ᐃᐧ ᐅᐧ ᐆᐧ ᐊᐧ ᐋᐧ ᐯ ᐱ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓄ ᓅ ᓇ ᓈ ᓭ ᓯ ᓱ ᓲ ᓴ ᓵ ᔦ ᔨ ᔪ ᔫ ᔭ ᔮ ᖧ ᖨ ᖪ ᖫ ᖬ ᖭ ᐤ ᑊ ᐟ ᐠ ᐨ ᒼ ᐣ ᐢ ᕀ ᙾ ᓬ ᕒ ᐦ ᕁ ᐀ ᙮




## ᐃᓂᓂᐎ ᐃᔑᑭᔗᐎᐣ (Ininiwi-Išikišwêwin) (Eastern Swampy Cree)
The Swampy Cree dialect of the larger Cree-Montagnais-Naskapi dialect continuum is broken into two groups: Eastern Swampy Cree, spoken in northern Ontario, and Western Swampy Cree, spoken in Northern Manitoba. Both of these dialects use Syllabics as a primary means of writing their languages, and they typically follow the standardized Syllabics glyph representations found in Unicode, mainly that of the Round form style. Eastern Swampy Cree mixes Eastern and Western Cree Syllabics conventions in a similar way as Oji-Cree, where it uses Western Cree finals characters, and the Eastern Cree practice of placing the "w dot" to the left of the base syllabic that it is modifying.

![Eastern-Swampy-Cree-Syllabics Orthography Chart](/static-syllabics-charts/eastern-swampy-cree-syllabics.png)


❶ Note that Eastern Swampy Cree places the "w dot" mark to the left of the base syllabic it modifies, as in the above chart representation. There may be variation in how the "w dot" is encoded (see Ojibway, Oji-Cree Syllabics, above), however, it is important to provide support for the pre-composed characters provided in Unicode that position the dot to the left of the syllabic, as some users may encode their texts this way.

❷ The only major graphical difference between Eastern and Western Swampy Cree is in an alternative form for the "y final" (ᔾ). The standard form for the "y final" in Eastern Swampy Cree is U+153E ᔾ CANADIAN SYLLABICS Y, which is the only finals character that deviatives from the Western Cree finals forms in the orthography. Some communities may prefer to use the final small ring character U+18DE ᣞ CANADIAN SYLLABICS FINAL SMALL RING. For the correct glyph representation of this character, please see figure 3 in Ojibway Syllabics. 


Eastern Swampy Cree Syllabics Subset:
> ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐍ ᐏ ᐑ ᐓ ᐕ ᐘ ᐚ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓓ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔐ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᕃ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᐤ  ᑊ  ᐟ  ᐠ  ᐨ  ᒼ  ᐣ  ᐪ  ᐢ  ᐡ  ᕀ ᔾ ᣞ ᑉ ᑦ ᒃ ᒡ ᒻ ᓐ ᔅ ᔥ ᕒ  ᐦ  ᕁ ᐀ ᙮





## ᐃᓂᓃᒧᐏᐣ (Ininîmowin) (Western Swampy Cree)
Western Swampy Cree is the other half of the Swampy Cree dialect of Cree. It is noted as being the first language known to have been represented with an orthography that we recongnize as Syllabics today, being the language that was printed in the 1841 _ᓇᑲᒧᐏᓇ ᐅᒪᐢᑮᑯᐘ ᐅᑎᑘᐏᓂᐘᐤ / Swampy Cree Hymn Book_, printed by James Evans at present-day Norway House, Manitoba. This orthography follows the same general conventions as the 1841 text, initiating what would become the Western Cree pattern of using finals distinct from the base syllabic glyphs, which contrasts the convention used by Eastern Cree communities (which uses a superscript version of the "a vowel" from a given series).

![Western-Swampy-Cree-Syllabics Orthography Chart](/static-syllabics-charts/western-swampy-cree-syllabics.png)


❶ Note that Western Swampy Cree places the "w dot" mark to the right of the base syllabic it modifies, following the Western Cree pattern. As in Eastern Swampy Cree, ensure that the corresponding pre-composed Syllabics characters provided in Unicode that follow this pattern are available for those users who encode their texts this way.

❷ Note that, while most users will use Western Cree finals, some users may use the Eastern Cree Syllabics form for the "y series final", U+153E ᔾ CANADIAN SYLLABICS Y. Both of these glyphs should be available in a typeface developed for this community.


Western Swampy Cree Syllabics Subset:
> ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐧᐁ ᐧᐃ ᐧᐄ ᐧᐅ ᐧᐆ ᐧᐊ ᐧᐋ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓓ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔐ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᕃ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᐤ  ᑊ  ᐟ  ᐠ  ᐨ  ᒼ  ᐣ  ᐪ  ᐢ  ᐡ  ᔾ ᣞ ᕐ  ᐦ ᕁ ᐀ ᙮





## ᐃᓕᓖᒧᐎᓐ (Ililîmowin) (Moose Cree)
Moose Cree language speakers adopted the use of Syllabics in the mid-19th century, and it has been the primary way of writing Moose Cree since to the present day. Moose Cree was the primary dialect that diverged from the Western Cree pattern of using graphically-distinct finals characters from the base syllabics in a given series, and rather, using a superscript version of the "a vowel" from a given series, introduced by printer John Horden. Moose Cree follows the standard Syllabics representation of the Round form style, and there are no local typographic or encoding preferences that require special accommodation. Note that Moose Cree uses specially-encoded composite characters to accommodate a stacked ring above the base syllabic: ᢱ ᢰ ᢳ ᢵ ᢴ ᢷ ᢸ ᢺ ᢼ ᢿ ᢾ ᣁ ᣀ ᣄ ᣃ ᣅ, a composite "aay" (ᢲ) character, and the finals glyph U+1509 `ᔉ` CANADIAN SYLLABICS MOOSE-CREE SK, all of which are not used in any other Syllabics orthography.

![Moose-Cree-Syllabics](/static-syllabics-charts/moose-cree-syllabics.png)

❶ Note the representation of the two marks above U+18B2 ᢲ CANADIAN SYLLABICS AAY should be a sequence of an open "ring" and closed "dot" mark, left to right, as seen in the representative chart, above.


Moose Cree Syllabics Subset:
> ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐌ ᐎ ᐐ ᐒ ᐔ ᐗ ᐙ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᕓ ᕕ ᕖ ᕗ ᕘ ᕙ ᕚ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᕞ ᕠ ᕢ ᕤ ᕥ ᕦ ᕧ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓓ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔐ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᕃ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᢱ ᢲ ᢰ ᢳ ᢵ ᢴ ᢷ ᢸ ᢺ ᢼ ᢿ ᢾ ᣁ ᣀ ᣄ ᣃ ᣅ ᐤ ᑉ ᕝ ᑦ ᕪ ᒃ ᒡ ᒻ ᓐ ᓪ ᔅ ᔥ ᔾ ᕐ ᐦ ᒽ ᔉ ᐀ ᙮





## ᐄᓅ ᐊᔨᒨᓐ  (Înû Ayimûn) / ᐄᔨᔫ ᐊᔨᒨᓐ (Îyiyû Ayimûn) (East James Bay Cree) 

East James Bay Cree (sometimes referred to as East Cree) is an umbrella term to refer to a collection of subdialects that share close linguistic features. These subdialects are primarily the coastal James Bay Cree communities, and those inland. Orthographically speaking, these sub dialects are all represented by the same system, and align on typographic and encoding preferences. The East James Bay Cree Syllabics follow the standard Syllabics representation in Unicode of the Round form style, with finals glyphs positioned vertically at the top line.

![East-Cree-Syllabics Orthography Chart](/static-syllabics-charts/east-cree-syllabics.png)


❶ Note that it is important in the East James Bay Cree Syllabics to have the "sh series" (ᔐ ᔓ ᔕ ᔑ) [represented in the Round form style and orientation](https://www.eastcree.org/cree/en/resources/how-to/cree-fonts/syllabic-font-orientation/), as shown in the below comparative figure:

![Round versus Square form "sh series" orientation and form](/figures/sh-series.png)



East James Bay Cree Syllabics Subset:
> ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐌ ᐎ ᐐ ᐒ ᐔ ᐗ ᐙ ᐯ ᐺ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑆ ᑌ ᑗ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑣ ᑫ ᑴ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒀ ᒉ ᒒ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒞ ᒣ ᒬ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᒸ ᓀ ᓉ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓍ ᓓ ᓜ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓨ ᓭ ᓶ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔂ ᔐ ᔗ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔣ ᔦ ᔯ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᔳ ᕃ ᣎ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᕎ ᕓ ᐧᕓ ᕕ ᕖ ᕗ ᕘ ᕙ ᕚ ᕛ ᕞ ᐧᕞ ᕠ ᕢ ᕤ ᕥ ᕦ ᕧ ᕨ ᐤ ᑉ ᑦ ᒃ ᒄ ᒡ ᒻ ᒽ ᓐ ᓪ ᔅ ᔥ ᔾ ᕐ ᕝ ᕪ ᣞ ᐦ ᐀ ᙮

#### Acknowledgements
We would like to acknowledge and thank with gratitude Louise Campbell, Ken Papanakis, and the Swampy Cree CLDR Working Group and Bill Jancewicz for sharing his knowledge of Cree and the Algonquian Syllabics.

#### Sources
- Arok Wolvengrey, *ᐊᐎᔹᑖᒋᐏᓂᓴ / wawiyatācimowinisa / Funny little stories*. University of Regina Press, 2007.

- James Evans, *ᓇᑲᒧᐏᓇ ᐅᒪᐢᑮᑯᐘ ᐅᑎᑘᐏᓂᐘᐤ (Swampy Cree Hymn book)*. Norway House, 1841.

- Ervin Bird Glass, John McDougall, *The ritual of the Methodist Church, with forms of prayer, Methodist Missionary Society*, Toronto, 1899
  
- John Horden, *Bible and Gospel history, in Saulteux, Society for Promoting Christian Knowledge*, London, 1860

- Marie-Odile Junker, "[Syllabic font orientation](https://www.eastcree.org/cree/en/resources/how-to/cree-fonts/syllabic-font-orientation/)", In *East Cree Language Resources*, EastCree.org
  
- [British and Foreign Bible Society], *The four Gospels and the Acts of the Apostles*. British and Foreign Bible Society, London, 1903
- [Canadian Standards Association], [Proposed pDAM for Unified Canadian Aboriginal Syllabics](https://www.evertype.com/standards/sl/n1441-en.html). ISO/IEC JTC1/SC2/WG2 N1441, 10 June 1996
  
