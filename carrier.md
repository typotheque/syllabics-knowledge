# ᑐᑊᘁᗕᑋᗸ (Dulk wah’ke) (Dakelh Syllabics) (Carrier Syllabics)
> **Note on nomenclature:** The term "Carrier" is used to mark the specific characters encoded within the Unicode Standard intended for representing the Dakelh Syllabics. "Dakelh" is the name for the language and community in the Dakelh language, which was once known commonly as "Carrier" by English and French settlers in British Columbia. "Dulk wah’ke" refers to the Dakelh language's name for their Syllabics writing system, translating to "little toad feet". As the name "Carrier" persists within the Unicode code charts for this language's Syllabics encoding representation, both names are used for clarity towards font development purposes, with the settler name in parenthesis following the community's proper name.

The Dakelh (Carrier) Syllabics are an active Syllabics writing system within the Dakleh (Carrier) Nation of central British Columbia, and the preferred means of writing Dakelh (Carrier) within many communities. The Dakelh (Carrier) Syllabics diverge quite considerably from the other Syllabics orthographies used within Indigenous communities across Canada, and as such, there are many differences between the Carrier Syllabics and the Algonquian, Inuktut, or Dene Syllablics in regards to orthographic and typographic requirements. 

In 2021, a proposal was accepted by the Unicode Technical committee to amend errors in the accurate representation of the Dakelh (Carrier) Syllabics in the character code charts for [UCAS](https://www.unicode.org/charts/PDF/U1400.pdf) and [UCAS Extended](https://www.unicode.org/charts/PDF/U18B0.pdf), which took affect with the release of version 15.0 of the Unicode Standard on 13 September, 2022. For more information on these glyph changes, please see the proposal [L2/21-141](https://www.unicode.org/L2/L2021/21141-ucas-revisions.pdf). As a result of these changes, the glyph representations in the below subsection "Dakelh (Carrier) Syllabics Subset" may not align with the accurate representations of these glyphs as the Dakelh (Carrier) community expects of these characters. The below Dakelh (Carrier) Syllabics orthography shows the complete and accurate representations of all glyphs required for Dakelh (Carrier), as the community requires them to appear. 

The Dakelh Syllabics should be represented in the same manner as the Square Form style, with all syllabics glyphs occupying generally the same height and width propotion. Additionally, all finals glyphs should be vertically positioned at the mid line, vertically centered on the syllabics glyphs between the top and baselines


![Dakelh-(Carrier)-Syllabics](https://user-images.githubusercontent.com/17300547/204646633-23e1388e-35f6-47d1-bcde-296c9b73536e.png)


❶ Unicode provides dedicated characters for most of the Dakelh (Carrier) Syllabics repertoire, however, there are some finals glyphs which are shared with other Indigenous language communities for their Syllabics orthographies which cause a conflict for Dakelh (Carrier), primarily the finals characters: ᐦ ᐥ ᐪ ᐟ ᐠ ᐣ ᒼ ᑊ ᒡ ᐩ. These characters are used by other Cree, Ojibway, and Inuktut Syllabics-using communities, which position these glyphs at the top line, while in Dakelh (Carrier) they should be positioned at the mid line. It is possible to accommodate this by providing a customized build specific to the Dakelh (Carrier) Syllabics, rendering these glyphs in the locally-preferred Dakelh positions, or, mapping them as substitutions via OpenType Layout.

<img src="https://user-images.githubusercontent.com/17300547/204646272-ae7a2931-4ff0-45b5-995f-904272532f40.png" width="780">


❷ Note that there are two graphically-identical "final plus" glyphs in Unicode: U+1429  `ᐩ`  CANADIAN SYLLABICS FINAL PLUS and U+1540  `ᕀ`  CANADIAN SYLLABICS WEST-CREE Y. Dakelh (Carrier) encodes this glyph as U+1429  `ᐩ`  CANADIAN SYLLABICS FINAL PLUS and as all finals in Dakelh Syllabics, should be positioned at the mid line, along with all other finals.

❸ This character, which represents the foreign loan sound "f" for rendering foreign loan words in Dakelh (Carrier), is encoded by the community as U+1DA3  `ᶣ`  MODIFIER LETTER SMALL TURNED H. This glyph should be represented to match the graphic style of the other Dakelh Syllabics finals, and it should also be positioned at the mid line. 
> Note that this glyph may be shared with other orthgraphies and uses within the same type family, or, may be represented in general text environments in a different style and position.


❹ Dakelh (Carrier) Syllabics uses the modifier U+18DF ᣟ CANADIAN SYLLABICS SYLLABICS FINAL RAISED DOT, which marks the glottal stop in the Dakelh language. The vertical position of this glyph is often incorrectly represented in common system-level typefaces. In contrast to the other finals glyphs in the Dakelh Syllabics, it should sit at the top line, and not floating above, the full height of the syllabic glyphs, as it is intended to harmonize with the general rhythm of Syllabics texts.

<img src="https://user-images.githubusercontent.com/17300547/204646370-351e2624-a046-422f-9a8b-d38717e2a081.png" width="800">


###### Dakelh (Carrier) Syllabics Subset
> ᐊ ᐅ ᐈ ᐉ ᐃ ᐁ ᐸ ᐳ ᐶ ᐷ ᐱ ᐯ ᗏ ᗌ ᗍ ᗎ ᗋ ᗊ ᗉ ᗆ ᗇ ᗈ ᗅ ᗄ ᗕ ᗒ ᗓ ᗔ ᗑ ᗐ ᗛ ᗘ ᗙ ᗚ ᗗ ᗖ ᑕ ᑐ ᑓ ᑔ ᑎ ᑌ ᗡ ᗞ ᗟ ᗠ ᗝ ᗜ ᗧ ᗤ ᗥ ᗦ ᗣ ᗢ ᗭ ᗪ ᗫ ᗬ ᗩ ᗨ ᗴ ᗱ ᗲ ᗳ ᗰ ᗯ ᗺ ᗷ ᗸ ᗹ ᗶ ᗵ ᘀ ᗽ ᗾ ᗿ ᗼ ᗻ ᘇ ᘄ ᘅ ᘆ ᘃ ᘂ ᘍ ᘊ ᘋ ᘌ ᘉ ᘈ ᘓ ᘐ ᘑ ᘒ ᘏ ᘎ ᘛ ᘗ ᘘ ᘙ ᘖ ᘔ ᘡ ᘞ ᘟ ᘠ ᘝ ᘜ ᘧ ᘤ ᘥ ᘦ ᘣ ᘢ ᘭ ᘪ ᘫ ᘬ ᘩ ᘨ ᘳ ᘰ ᘱ ᘲ ᘯ ᘮ ᘹ ᘶ ᘷ ᘸ ᘵ ᘴ ᘿ ᘼ ᘽ ᘾ ᘻ ᘺ ᙅ ᙂ ᙃ ᙄ ᙁ ᙀ ᙍ ᙊ ᙋ ᙌ ᙉ ᙈ ᙓ ᙐ ᙑ ᙒ ᙏ ᙎ ᙙ ᙖ ᙗ ᙘ ᙕ ᙔ ᙠ ᙝ ᙞ ᙟ ᙜ ᙛ ᙦ ᙣ ᙤ ᙥ ᙢ ᙡ ᙬ ᙩ ᙪ ᙫ ᙨ ᙧ ᙬ ᙩ ᙪ ᙫ ᙨ ᙧ ᐪ ᗮ ᐟ ᐠ ᘁ ᐣ ᓑ ᒼ ᑊ ᒡ ᙆ ᙇ ᔆ ᣵ ᙚ ᐩ ᶣ ᣟ - .