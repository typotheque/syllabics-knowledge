# ᑐᑊᘁᗕᑋᗸ (Dulk'wah ke) (Dakelh Syllabics) (Carrier Syllabics)
> **Note on nomenclature:** The term "Carrier" is used to mark the specific characters encoded within the Unicode Standard intended for representing the Dakelh Syllabics. "Dakelh" is the name for the language and community in the Dakelh language, which was once known commonly as "Carrier" by English and French settlers in British Columbia. "Dulk wah’ke" refers to the Dakelh language's name for their Syllabics writing system, translating to "little toad feet". As the name "Carrier" persists within the Unicode code charts for this language's Syllabics encoding representation, both names are used for clarity towards font development purposes, with the settler name in parenthesis following the community's proper name.

The Dakelh (Carrier) Syllabics are an active Syllabics writing system within the Dakleh Nation of central British Columbia, and the preferred means of writing Dakelh within many communities. The Dakelh  Syllabics diverge quite considerably from the other Syllabics orthographies used within Indigenous communities across Canada, and as such, there are many differences between the Carrier Syllabics and the Algonquian, Inuktut, or Dene Syllablics in regards to orthographic and typographic requirements. 

In 2021, a proposal was accepted by the Unicode Technical committee to amend errors in the accurate representation of the Dakelh Syllabics in the character code charts for [UCAS](https://www.unicode.org/charts/PDF/U1400.pdf) and [UCAS Extended](https://www.unicode.org/charts/PDF/U18B0.pdf), which took affect with the release of version 15.0 of the Unicode Standard on 13 September, 2022. For more information on these glyph changes, please see the proposal [L2/21-141](https://www.unicode.org/L2/L2021/21141-ucas-revisions.pdf). As a result of these changes, the glyph representations in the below subsection "Dakelh Syllabics Subset" may not align with the accurate representations of these glyphs as the Dakelh community expects of these characters. The below Dakelh Syllabics orthography shows the complete and accurate representations of all glyphs required for Dakelh, as the community requires them to appear. 

The Dakelh Syllabics should be represented in the same manner as the Square Form style, with all syllabics glyphs occupying generally the same height and width propotion. Additionally, all finals glyphs should be vertically positioned at the mid line, vertically centered on the syllabics glyphs between the top and baselines.


![Dakelh-(Carrier)-Syllabics](https://user-images.githubusercontent.com/17300547/204646633-23e1388e-35f6-47d1-bcde-296c9b73536e.png)


❶ Unicode provides dedicated characters for most of the Dakelh Syllabics repertoire, however, there are some finals glyphs which are shared with other Indigenous language communities for their Syllabics orthographies which cause a conflict for Dakelh, primarily the finals characters: ᐦ ᐥ ᐪ ᐟ ᐠ ᐣ ᒼ ᑊ ᒡ ᐩ. These characters are used by other Cree, Ojibway, and Inuktut Syllabics-using communities, which position these glyphs at the top line, while in Dakelh they should be positioned at the mid line. It is possible to accommodate this by providing a customized build specific to the Dakelh Syllabics, rendering these glyphs in the locally-preferred Dakelh positions, or, mapping them as substitutions via OpenType Layout.

![Dakelh (Carrier) Midline finals vertical positioning](/figures/dakelh-finals-position.png)


❷ Note that there are two graphically-identical "final plus" glyphs in Unicode: U+1429  ᐩ  CANADIAN SYLLABICS FINAL PLUS and U+1540  ᕀ  CANADIAN SYLLABICS WEST-CREE Y. Dakelh encodes this glyph as U+1429  ᐩ  CANADIAN SYLLABICS FINAL PLUS and as all finals in Dakelh Syllabics, should be positioned at the mid line, along with all other finals.

❸ This character, which represents the foreign loan sound "f" for rendering foreign loan words in Dakelh (Carrier), is encoded by the community as U+1DA3  ᶣ  MODIFIER LETTER SMALL TURNED H. This glyph should be represented to match the graphic style of the other Dakelh Syllabics finals, and it should also be positioned at the mid line. 
> Note that this glyph may be shared with other Syllabics orthgraphies and uses within the same type family that may be covering a wider UCAS range, or, may be represented in general text environments in a different style and position.


❹ Dakelh Syllabics uses the modifier U+18DF ᣟ CANADIAN SYLLABICS SYLLABICS FINAL RAISED DOT, which marks the glottal stop in the Dakelh language. The vertical position of this glyph is often incorrectly represented in common system-level typefaces. In contrast to the other finals glyphs in the Dakelh Syllabics, it should sit at the top line, and not floating above, the full height of the syllabic glyphs, as it is intended to harmonize with the general rhythm of Syllabics texts.

![U+18DF Carrier raised dot glottal stop correct vertical position](/figures/dakelh-18DF.png)


###### Dakelh (Carrier) Syllabics Subset
> ᐊ ᐅ ᐈ ᐉ ᐃ ᐁ ᐸ ᐳ ᐶ ᐷ ᐱ ᐯ ᗏ ᗌ ᗍ ᗎ ᗋ ᗊ ᗉ ᗆ ᗇ ᗈ ᗅ ᗄ ᗕ ᗒ ᗓ ᗔ ᗑ ᗐ ᗛ ᗘ ᗙ ᗚ ᗗ ᗖ ᑕ ᑐ ᑓ ᑔ ᑎ ᑌ ᗡ ᗞ ᗟ ᗠ ᗝ ᗜ ᗧ ᗤ ᗥ ᗦ ᗣ ᗢ ᗭ ᗪ ᗫ ᗬ ᗩ ᗨ ᗴ ᗱ ᗲ ᗳ ᗰ ᗯ ᗺ ᗷ ᗸ ᗹ ᗶ ᗵ ᘀ ᗽ ᗾ ᗿ ᗼ ᗻ ᘇ ᘄ ᘅ ᘆ ᘃ ᘂ ᘍ ᘊ ᘋ ᘌ ᘉ ᘈ ᘓ ᘐ ᘑ ᘒ ᘏ ᘎ ᘛ ᘗ ᘘ ᘙ ᘖ ᘔ ᘡ ᘞ ᘟ ᘠ ᘝ ᘜ ᘧ ᘤ ᘥ ᘦ ᘣ ᘢ ᘭ ᘪ ᘫ ᘬ ᘩ ᘨ ᘳ ᘰ ᘱ ᘲ ᘯ ᘮ ᘹ ᘶ ᘷ ᘸ ᘵ ᘴ ᘿ ᘼ ᘽ ᘾ ᘻ ᘺ ᙅ ᙂ ᙃ ᙄ ᙁ ᙀ ᙍ ᙊ ᙋ ᙌ ᙉ ᙈ ᙓ ᙐ ᙑ ᙒ ᙏ ᙎ ᙙ ᙖ ᙗ ᙘ ᙕ ᙔ ᙠ ᙝ ᙞ ᙟ ᙜ ᙛ ᙦ ᙣ ᙤ ᙥ ᙢ ᙡ ᙬ ᙩ ᙪ ᙫ ᙨ ᙧ ᙬ ᙩ ᙪ ᙫ ᙨ ᙧ ᐪ ᗮ ᐟ ᐠ ᘁ ᐣ ᓑ ᒼ ᑊ ᒡ ᙆ ᙇ ᔆ ᣵ ᙚ ᐩ ᶣ ᣟ - .

#### Acknowledgements
We would like to acknowledge and thank with gratitude Dakelh language keepers ᗮᘧᐣᙒᔆ  ᗮᘦᐣᙆ (Francois Prince) and ᑓᐣᘆᔆ  ᗷᒼᗫᐩᘧᐣᐪ (Dennis Cumberland) for sharing their knowledge of Dakelh Syllabics, and for our continued collaboration together.

#### Sources
- ᗮᘧᐣᙒᔆ  ᗮᘦᐣᙆ (Francois Prince), ᑓᐣᘆᔆ  ᗷᒼᗫᐩᘧᐣᐪ (Dennis Cumberland), Kevin King, "Proposed changes to the representative glyphs of the Unified Canadian Aboriginal Syllabics code charts", [L2/21-141], The Unicode Consortium, 7 July 2021
 
- ᑓᐣᘆᔆ  ᗷᒼᗫᐩᘧᐣᐪ (Dennis Cumberland), ‘Discussing the history of the Dakelh (Carrier) Syllabics.’ 10 March 2021, Telephone interview with Kevin King.

- ᑓᐣᘆᔆ  ᗷᒼᗫᐩᘧᐣᐪ (Dennis Cumberland), ᗮᘧᐣᙒᔆ  ᗮᘦᐣᙆ (Francois Prince), ‘Question about Syllabics rotation in Morice document & single ‘s’ and ‘z’ sound character shapes.’Email correspondence with Kevin King recieved 21 April 2021, 4:13 am EST and 23 April 2021, 11:43 am EST


- International Organization for Standardization, *Information technology—Universal Multiple-Octet Coded Character Set (UCS): Part 1: Architecture and Basic Multilingual Plane: Amendment 11: Unified Canadian Aboriginal Syllabics*. From ISO/IEC 10646–1:1993, FDAM 11, L2/98–128, 1998

- Adrien-Gabriel Morice, *ᗫᣟ ᑐᔆᘼᔆ ᐅᙨᑐᐟᣟᐈᑋ / Carrier reading-book*. Fort Saint James, 1894.

- Adrien-Gabriel Morice, *Mission Papers (ᑐᔆᘼᔆ ᘇᗘᑊᘄᐟ), Second Edition (ᗪᒡ   2   ᑐᔆᘼᔆ), Volume 11 (ᗪᒡ   11   ᙓᘄᐣ)*, 1891.

- Adrien-Gabriel Morice, *ᑐᔆᘼᔆ ᐁᘁᗒᐪ ᗟᑕᙆᑐᘬ, ᙖᐣ ᙠ, ᘤᗴᑓᙘᔆ ᙠ, ᗙᗴᑐᘦᐟ ᐅᘬ ᐉ ᙠ ᙫᘓᐁᑋ ᗪᣳ ᐅᘒᐣᗣᐥ / Carrier prayer book, contaning together with the usual formularies a complete collection of hymns, catechisms, directions relative to various points of Catholic life*. Stuart’s Lake Mission, 1901

- Adrien-Gabriel Morice, *The new methodical, easy and complete Dene syllabary*. Stuart’s Lake Mission, 1890
