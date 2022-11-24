# Syllabics Knowledge
The purpose of this repository is to provide resources to those interested in developing Canadian Syllabics typefaces for the various Indigneous communities in North America that use this writing system. In this repo, you will find 

## Syllabics typographic guidelines and local typographic preferences
The following article is a good resource towards understanding a wider scope of the Syllabics in regards to the general principles and typographic concepts inherent to the writing system, as well as historical and contemporary context towards local typographic preferences and orthographic needs as they vary across the many First Nations and Inuit communities in Canada that use this script. It is also a useful article for understanding how to look at the `UCAS` (Unified Canadian Aboriginal Syllabics) encoding range in Unicode, to understand how Unicode encodes and represents the Syllabics, and how this differs from various local Syllabics-using Indigenous communities. For a better understanding of how to view the Syllabics within their seaparate typographic traditions, please see section two:
https://www.typotheque.com/articles/syllabics_typographic_guidelines

In order to work on font development for the Canadian Syllabics, it is important to become acquainted with the behaviours and concepts that are inherently unique to this writing system. The above article has been prepared to outline these concepts that are unique to the Syllabics, and is a good starting point towards understanding the terminology and concepts provided within these development materials.

The following sections provide an overview of the local typographic preferences and orthographic requirements for each individual Indigenous language community that uses the Syllabics, with the purpose of typeface design and development in mind. For each community, their local Syllabics preferences have been presented graphically in the form of their Syllabics orthography chart, accompanied by footnotes were necessary beneath the chart. 

Below these charts is a subset of the required glyph set for each community. In these subsets, please note that the glyph representations will in some cases differ from the graphical representation in the orthography charts above. This is expected, as UCAS harmonizes many of the Syllabics orthographies into one unified set, although a much greater diversity of glyph representations exists within the scope of Syllabics communities. These subsets are useful for developing typefaces for specific Indigenous language communities, where one may not need to cover the entire UCAS encoding range, which is quite large.

Furthermore, each section contains any relevant notes that may be applicable towards accommodating specific local typographic preferences and variations, or issues surrounding encoding.

## ᐊᓂᐦᔑᓈᐯᒧᐎᓐ / Anishinaabemowin (Ojibway)
Although all Ojibway language communities could use Syllabics to accurately represent their languages, it is important to note that not all Ojibway communtiies use this writing system. It is particularly the communities of northern Ontario and western Ojibway dialect speakers of Manitoba and Saskatchewan that have a current use of Syllabics. All other communities use a number of roman orthography systems to write their local dialects, including Algonquin, Odawa, Eastern Ojibwe, and Central Ojibwe. There is a relatively high degree of variation in the local typographic and orthographic preferences for Ojibway Syllabics between communities, particularly for communities in northern Ontario. This is particularly evident in northern Ontario communities, and can be seen primarily in the form and orientation of finals characters and their vertical positioning. The following chart shows the preferred representation of the Ojibway Syllabics orthography:


![Ojibway-Syllabics](https://user-images.githubusercontent.com/17300547/203140290-fc2d3876-7cde-4455-af8c-30646ee1826d.png)


❶ A major distinction towards local typographic preferences amongst Northern Ontario Ojibwe communities is in the preferred form or orientation of finals characters. This is notably the difference between Western and Eastern Cree finals forms, and the i-pos and a-pos orientation scheme of finals glyphs. This can vary between communities, and between users within the same community. Some northern Ontario Ojibwe communities may follow the form of the Western Cree finals shapes, while others the Eastern Cree. For those who use the Eastern Cree finals forms, they may follow either the `a vowel (ᐊ ᐸ ᑲ ᓇ)` position or `i vowel (ᐃ ᐱ ᑭ ᓂ)` position orientation, a convention unique to Ontario Ojibwe Syllabics. There can also be mixing of these two orientation positions within the same text. Unicode encodes both the `a` and `i` position finals orientations to accommodate these preferences.

❷ Note that there is a local preference for a horizontally-centered `n final (ᓐ)` for some Northwestern Ojibwe communities.

<img src="https://user-images.githubusercontent.com/17300547/203145739-5a0d22d9-1f4e-473a-a854-27bfab760007.png" width="700">


❸ There is variation in the preferred positioning of the `w dot` in relation to the syllabic that it is modifying. Traditionally, Western Cree and Ojibwe communities place the w-dot to the right of the base syllabic, while Eastern Cree and Ojibwe communities will place the dot to the left of the syllabic, to lead the base character it is modifying. There is variation within 

There is also variation in how this dot is encoded in texts between communities and individual users within communities. Some users will encode the `w dot` as two distinct code points: `U+1427 FINAL MIDDLE DOT (ᐧ)` plus the base syllabic glyph (`ᐧ` + `ᐃ` = `ᐧᐃ`). Others will encode these sequences of `w dot` with the pre-composed base glyphs within UCAS, where `w dot` and the base syllabic are treated as a composite glyph (`ᐎ`, `ᐗ`).

###### Ojibway Syllabics Subset
`ᐧ ᐁ    ᐃ    ᐅ    ᐊ    ᐄ    ᐆ    ᐋ ᐯ    ᐱ    ᐳ    ᐸ    ᐲ    ᐴ    ᐹ ᑌ    ᑎ    ᑐ    ᑕ    ᑏ    ᑑ    ᑖ ᑫ    ᑭ    ᑯ    ᑲ    ᑮ    ᑰ    ᑳ ᒉ    ᒋ    ᒍ    ᒐ    ᒌ    ᒎ    ᒑ ᒣ    ᒥ    ᒧ    ᒪ    ᒦ    ᒨ    ᒫ ᓀ    ᓂ    ᓄ    ᓇ    ᓃ    ᓅ    ᓈ ᓭ    ᓯ    ᓱ    ᓴ    ᓰ    ᓲ    ᓵ ᔐ    ᔑ    ᔓ    ᔕ    ᔒ    ᔔ    ᔖ ᔦ    ᔨ    ᔪ    ᔭ    ᔩ    ᔫ    ᔮ ᕓ    ᕕ    ᕖ    ᕗ    ᕘ    ᕙ    ᕚ ᕞ    ᕠ    ᕢ    ᕤ    ᕥ    ᕦ    ᕧ ᐎ ᐄ ᐐ    ᐆ ᐕ ᐓ ᐗ    ᐋ ᐙ ᑊ    ᑉ    ᣔ    ᐟ    ᑦ    ᣕ ᐠ    ᒃ    ᣖ ᐨ    ᒡ    ᣗ    ᒻ    ᣘ ᐣ    ᓐ    ᣙ    ᐢ    ᔅ    ᣚ     ᐡ    ᔥ    ᣛ    ˚    ᔾ     ᕝ    ᕪ ᐤ ᣜ    ᣝ ᓫ    ᕑ ᐦ    ᐞ
` 


## ᐊᓂᐦᔑᓂᓃᒧᐏᐣ (Anishininiimowin) (Oji-Cree)

Orthographically and typographically speaking, Oji-Cree follows the same general pattern as Western Cree and Ojibwe Syllabics: `w dot` positioned to the right, following the syllabic, and employing the Western Cree finals forms. The difference from Cree being that Oji-Cree requires the `sh series (ᔐ ᔑ ᔓ ᔕ)` in its orthography. Additionally, Oji-Cree may use Latin script full stop and hyphen in contemporary texts, rather than the local Syllabics characters.

![Oji-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/203162141-18a99ee9-149a-4322-b74c-c2943c9c0a20.png)


❶ While variation exists within Northwestern Ojibway communities in regards to the positioning of the `w dot` between users in contemporary texts, Oji-Cree users always follow the Western Cree convention of placing `w dot` to the right of the modified base syllabic.

There is variation, though, in how `w dot` is encoded in texts between communities and individual users within Oji-Cree communities. As in Northern Ojibway communities, users may encode the `w dot` as two distinct code points: `U+1427 FINAL MIDDLE DOT (ᐧ)` plus the base syllabic glyph (`ᐧ` + `ᐃ` = `ᐧᐃ`). For an example of this encoding practice, see [ᐧᐊᐧᐊᑌ ᐊᒋᒧᐧᐃᓇᐣ / Wawatay News](https://wawataynews.ca/list-newspaper). Others may encode `w dot` sequences with the pre-composed base glyphs within UCAS, where `w dot` and the base syllabic are treated as a composite glyph (`ᐎ`, `ᐗ`).


###### Oji-Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐅ ᐊ ᐄ ᐆ ᐋ ᐌ ᐎ ᐒ ᐗ ᐧᐄ ᐧᐆ ᐧᐋ ᐯ ᐱ ᐳ ᐸ ᐲ ᐴ ᐹ ᑌ ᑎ ᑐ ᑕ ᑏ ᑑ ᑖ ᑫ ᑭ ᑯ ᑲ ᑮ ᑰ ᑳ ᒉ ᒋ ᒍ ᒐ ᒌ ᒎ ᒑ ᒣ ᒥ ᒧ ᒪ ᒦ ᒨ ᒫ ᓀ ᓂ ᓄ ᓇ ᓃ ᓅ ᓈ ᓭ ᓯ ᓱ ᓴ ᓰ ᓲ ᓵ ᔐ ᔑ ᔓ ᔕ ᔒ ᔔ ᔖ ᔦ ᔨ ᔪ ᔭ ᔩ ᔫ ᔮ ᐤ ᑊ ᐟ ᐠ ᐨ ᒼ ᐣ ᐢ ᐡ ᔾ ᓬ ᕒ ᐦ ᐀ ᙮ - .`



## ᓇᐦᑲᐌᒧᐎᐣ (Nakawêmowin) (Western Ojibwe)
Western Ojibwe is the dialect of Ojibwe spoken by the communities west of Ontario. As a result of their proximity to neighbouring Western Cree communities, the orthographic and typographic conventions tend to follow verry closely that of the Plains and Western Swampy Cree Syllabics, where `w dot` is positioned right of the base syllabic. Note that Western Ojibwe requires the `sh series (ᔐ ᔑ ᔓ ᔕ)` in it's orthographic repertoire – as does Oji-Cree – not needed in the Cree language orthographies.

![Western-Ojibwe-Syllabics](https://user-images.githubusercontent.com/17300547/198724625-1364a42d-901b-4517-a12b-039831bac3ca.png)

❶ While Western Ojibwe typically follows the style Round form style of Syllabicsm, consistent with other Western Cree communities, it is possible that these communities prefer to have the glyphs `ᔓ` and `ᔕ` represented in the Square form style, while Eastern Ojibwe and Cree communities would represent this glyph in the Round form style.


###### Western Ojibwe Syllabics Subset
`ᐧ ᐁ ᐃ ᐅ ᐊ ᐄ ᐆ ᐋ ᐯ ᐱ ᐳ ᐸ ᐲ ᐴ ᐹ ᑌ ᑎ ᑐ ᑕ ᑏ ᑑ ᑖ ᑫ ᑭ ᑯ ᑲ ᑮ ᑰ ᑳ ᒉ ᒋ ᒍ ᒐ ᒌ ᒎ ᒑ ᒣ ᒥ ᒧ ᒪ ᒦ ᒨ ᒫ ᓀ ᓂ ᓄ ᓇ ᓃ ᓅ ᓈ ᓭ ᓯ ᓱ ᓴ ᓰ ᓲ ᓵ ᔐ ᔑ ᔓ ᔕ ᔒ ᔔ ᔖ ᔦ ᔨ ᔪ ᔭ ᔩ ᔫ ᔮ ᐧᐁ ᐧᐃ ᐧᐅ ᐧᐊ ᐧᐄ ᐧᐆ ᐧᐋ ᑊ ᐟ ᐠ ᐨ ᒼ ᐣ ᐢ ᐡ ᕀ ᐤ ᓬ ᕒ ᐦ ᕁ ᐀ ᙮ - .`




## ᓱᖽᐧᖿ (Siksiká) (Blackfoot) *** historical ***

The historical Blackfoot Syllabics encoded in UCAS are no longer in use by the community. This system of writing the Blackfoot language was developed in 1888 by John William Timms, although it never gained traction with the local language communities. Instead, Blackfoot has been written using a standardized roman orthography for over a century, although there have been recent efforts to develop a new Syllabics orthography for the Blackfoot language, which is distinct from this writing system.

![Historical-Blackfoot-Syllabics](https://user-images.githubusercontent.com/17300547/203148917-6c8a81be-1df8-483d-b98d-5c0a023e497e.png)

❶ The primary distinction that one would notice regarding the graphic representation of the historical Blackfoot Syllabics is the use of the Square Form style, which is consistent with the common form of Syllabics used in Western Canada for the Dene Syllabics. As well, some Plains and Woods Cree communities also used the Square Form style historically, in the late 19th century. As a result of proximity and the sharing of type material, the historical Blackfoot Syllabics featured this stylistic form, which would be seen in glyphs such as `ᑫ ᑭ ᑯ ᑲ` `ᓭ ᓯ ᓱ ᓴ` `ᔦ ᔨ ᔪ ᔭ`.


###### Blackfoot Syllabics Subset
` ᖳ ᖰ ᖱ ᖲ ᑫ ᑭ ᑯ ᑲ ᒣ ᒥ ᒧ ᒪ ᖿ ᖼ ᖽ ᖾ ᒉ ᒋ ᒍ ᒐ ᖻ ᖸ ᖹ ᖺ ᓭ ᓯ ᓱ ᓴ ᔦ ᔨ ᔪ ᔭ ᖷ ᖴ ᖵ ᖶ ᐤ  ᐨ  ᘁ  ᐢ  ᐡ  ᔈ ᐧ ᐟ ᑉ ᐠ ᙿ ᑊ  ᐦ ᐀ ᙮ - .`


## ᓀᐦᐃᔭᐍᐏᐣ (nêhiyawêwin) (Plains Cree)

Plains Cree communities comprise the largest group of speakers who use Syllabics as their primary and preferred writing system, and have a long and vibrant use of Syllabics. Plains Cree Syllabics follow the Round form style, although historically, the Square form style would have also been employed in 19th century and early-to-mid 20th century texts. Note that Plains Cree communities may use the Syllabics hyphen `U+1400 (᐀) CANADIAN SYLLABICS HYPHEN and the Syllabics full stop `U+166E (᙮) CANADIAN SYLLABICS FULL STOP`, or, the Latin script representations and encoding for these characters.

![Plains-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/198723126-9f012023-f062-4f4d-9de5-1949be50b803.png)

❶ Plains Cree Syllabics users may encode `w dot` using may encode the `w dot` as `U+1427 FINAL MIDDLE DOT (ᐧ)` plus the base syllabic glyph (`ᐧ` + `ᐃ` = `ᐧᐃ`) or with the pre-composed base glyphs within UCAS, where `w dot` and the base syllabic are treated as a composite glyph (`ᐎ`, `ᐗ`).

❷ Although some system-level Syllabics typefaces and historical texts have represented `U+1425 (ᐤ) CANADIAN SYLLABICS FINAL RING` at horizontally centered at the mid line, contemporary texts and communities show the preference for this glyph to be vertically positioned at the top line, consistent with the positioning of all other finals.

❸ There is variation within Plains Cree communities in terms of the representation of the `y series` final character and how it transforms when paired with the `w dot`. The common form of this in Plains Cree is a plus mark `U+1429 (ᐩ)`; however, some communities prefer to use a superposed dot mark `U+141D (ᐝ)`, which is graphically distinct from the common `y final`. It should be noted that this alternative `y final` form (see example 2 in the below image) should be represented as a combination of a closed `w dot mark` on the bottom, and an open, small ring character at the top, rather than two open ring characters, as is shown in some general, system-level typefaces:

<img src="https://user-images.githubusercontent.com/17300547/203813233-91eb71e0-955e-4f9a-9f70-963bea4a0cdb.png" width="820">

There is also variety in the way that the `y final` transforms when it preceeds the `w dot` modifier. The general w + y final sequence is represented by two inline characters, `U+1427 (ᐧ)` + `U+1429 (ᐩ)`. In some communities, this sequence is preferred to be graphically represented by a combination of two stacked `w dot` marks, with the lower dot taking the same position as `w dot`, and the second dot, above, positioned at the top line:

<img src="https://user-images.githubusercontent.com/17300547/203815106-05711ef8-676d-4959-8268-2b9c8250e4b4.png" width="820">

This alternative combination is not encoded in Unicode, and must be implemented in any given Syllabics typeface as an alternative glyph, and mapped in a way that agrees with the input method of the client or community members who will use the typeface.


###### Plains Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐍ ᐏ ᐑ ᐓ ᐕ ᐘ ᐚ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᐧ  ᐤ  ᑊ  ᐟ  ᐠ  ᐨ  ᐨ  ᐣ  ᐢ  ᐩ  ᓬ  ᕒ  ᐦ  ᕁ  ᐝ ᛬ ᐀ ᙮`



## ᓀᐦᐃᖬᐍᐏᐣ (nīhithawīwin) (Woods Cree)

![Woods-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/198723194-3e930b9b-8617-4f26-85bb-fce722a9ba60.png)

###### Woods Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐅ ᐆ ᐊ ᐋ ᐁᐧ ᐃᐧ ᐅᐧ ᐆᐧ ᐊᐧ ᐋᐧ ᐯ ᐱ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓄ ᓅ ᓇ ᓈ ᓭ ᓯ ᓱ ᓲ ᓴ ᓵ ᔦ ᔨ ᔪ ᔫ ᔭ ᔮ ᖧ ᖨ ᖪ ᖫ ᖬ ᖭ ᐤ ᑊ ᐟ ᐠ ᐨ ᒼ ᐣ ᐢ ᕀ ᙾ ᓬ ᕒ ᐦ ᕁ ᐀ ᙮`





## ᐃᓂᓂᐎ ᐃᔑᑭᔗᐎᐣ (Ininiwi-Išikišwêwin) (Eastern Swampy Cree)

![Eastern-Swampy-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/198723259-6d7622aa-4fb4-4a10-bfc3-d7c75d4f5ba1.png)


###### Eastern Swampy Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐍ ᐏ ᐑ ᐓ ᐕ ᐘ ᐚ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓓ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔐ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᕃ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᐤ  ᑊ  ᐟ  ᐠ  ᐨ  ᒼ  ᐣ  ᐪ  ᐢ  ᐡ  ᕀ ᔾ ᕒ  ᐦ  ᕁ ᐀ ᙮`



## ᐃᓂᓃᒧᐏᐣ (Ininîmowin) (Western Swampy Cree)

![Western-Swampy-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/198723422-8fe98fcf-37b1-4e51-bdab-f5c0d567f0d0.png)


###### Western Swampy Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐧᐁ ᐧᐃ ᐧᐄ ᐧᐅ ᐧᐆ ᐧᐊ ᐧᐋ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓓ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔐ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᕃ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᐤ  ᑊ  ᐟ  ᐠ  ᐨ  ᒼ  ᐣ  ᐪ  ᐢ  ᐡ  ᔾ ᣞ ᕐ  ᐦ ᕁ ᐀ ᙮`



## ᐃᓕᓖᒧᐎᓐ (Ililîmowin) (Moose Cree)

![Moose-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/198723524-b68686fa-e3c6-44ce-acc2-d950c32de0b9.png)

###### Moose Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐌ ᐎ ᐐ ᐒ ᐔ ᐗ ᐙ ᐯ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᕓ ᕕ ᕖ ᕗ ᕘ ᕙ ᕚ ᑌ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᕞ ᕠ ᕢ ᕤ ᕥ ᕦ ᕧ ᑫ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒉ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓓ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓭ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔐ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔦ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᕃ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᢱ ᢲ ᢰ ᢳ ᢵ ᢴ ᢷ ᢸ ᢺ ᢼ ᢿ ᢾ ᣁ ᣀ ᣄ ᣃ ᣅ ᐤ ᑉ ᕝ ᑦ ᕪ ᒃ ᒡ ᒻ ᓐ ᓪ ᔅ ᔥ ᔾ ᕐ ᐦ ᒽ ᔉ ᐀ ᙮`


## ᐄᓅ ᐊᔨᒨᓐ  (Înû Ayimûn) / ᐄᔨᔫ ᐊᔨᒨᓐ (Îyiyû Ayimûn) (East James Bay Cree) 

East James Bay Cree (sometimes referred to as East Cree) is an umbrella term to refer to a collection of subdialects that share close linguistic features. These subdialects are primarily the coastal James Bay Cree communities, and those inland. Orthographically speaking, these sub dialects are all represented by the same system, and align on typographic preferences.


![East-Cree-Syllabics](https://user-images.githubusercontent.com/17300547/198727876-24ec7af1-ab3b-4e4d-8228-088e52e730ce.png)


###### East James Bay Cree Syllabics Subset
`ᐧ ᐁ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐌ ᐎ ᐐ ᐒ ᐔ ᐗ ᐙ ᐯ ᐺ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑆ ᑌ ᑗ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑣ ᑫ ᑴ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᒀ ᒉ ᒒ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒞ ᒣ ᒬ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᒸ ᓀ ᓉ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓍ ᓓ ᓜ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᓨ ᓭ ᓶ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᔂ ᔐ ᔗ ᔑ ᔒ ᔓ ᔔ ᔕ ᔖ ᔣ ᔦ ᔯ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᔳ ᕃ ᣎ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᕎ ᕓ ᐧᕓ ᕕ ᕖ ᕗ ᕘ ᕙ ᕚ ᕛ ᕞ ᐧᕞ ᕠ ᕢ ᕤ ᕥ ᕦ ᕧ ᕨ ᐤ ᑉ ᑦ ᒃ ᒄ ᒡ ᒻ ᒽ ᓐ ᓪ ᔅ ᔥ ᔾ ᕐ ᕝ ᕪ ᣞ ᐦ ᐀ ᙮`


## ᐃᔪᐤ ᐃᔨᒧᐅᓐ / Iyuw Iyimuun (Naskapi)

![Naskapi-Syllabics](https://user-images.githubusercontent.com/17300547/198724399-8a17c2be-e829-4a56-bdf9-f7817620c5f1.png)


###### Naskapi Syllabics Subset
`ᐧ ᐃ ᐅ ᐊ ᐎ ᐛ ᐱ ᐳ ᐸ ᑎ ᑐ ᑕ ᑭ ᑯ ᑲ ᒋ ᒍ ᒐ ᒥ ᒧ ᒪ ᓂ ᓄ ᓇ ᓯ ᓱ ᓴ ᔨ ᔪ ᔭ ᓕ ᓗ ᓚ ᕆ ᕈ ᕋ ᑈ ᑥ ᒂ ᒠ ᒺ ᓏ ᔄ ᔽ ᔋᐸ ᔍ ᔎ ᔏ ᐤ ᑉ ᑦ ᒃ ᒡ ᒻ ᓐ ᔅ ᔾ ᓪ ᕐ ᐦ ᐧ ᒄ ᐀ ᙮`



## ᖃᓂᐅᔮᖅᐸᐃᑦ / Inuktut (Inuktitut)

![Inuktut-Syllabics](https://user-images.githubusercontent.com/17300547/197810250-344ad806-405e-4336-9453-2e1a31cb2363.png)


###### Inuktut Syllabics Subset
`ᐁ ᐂ ᐃ ᐄ ᐅ ᐆ ᐊ ᐋ ᐯ ᐰ ᐱ ᐲ ᐳ ᐴ ᐸ ᐹ ᑌ ᑍ ᑎ ᑏ ᑐ ᑑ ᑕ ᑖ ᑫ ᑬ ᑭ ᑮ ᑯ ᑰ ᑲ ᑳ ᕴ ᕵ ᕶ ᕷ ᕸ ᕹ ᕺ ᒉ ᒊ ᒋ ᒌ ᒍ ᒎ ᒐ ᒑ ᒣ ᒤ ᒥ ᒦ ᒧ ᒨ ᒪ ᒫ ᓀ ᓁ ᓂ ᓃ ᓄ ᓅ ᓇ ᓈ ᓭ ᓮ ᓯ ᓰ ᓱ ᓲ ᓴ ᓵ ᓓ ᓔ ᓕ ᓖ ᓗ ᓘ ᓚ ᓛ ᔦ ᔧ ᔨ ᔩ ᔪ ᔫ ᔭ ᔮ ᖨ ᖩ ᖪ ᖫ ᖬ ᖭ ᕓ ᕔ ᕕ ᕖ ᕗ ᕘ ᕙ ᕚ ᕃ ᕅ ᕆ ᕇ ᕈ ᕉ ᕋ ᕌ ᙯ ᕾ ᕿ ᖀ ᖁ ᖂ ᖃ ᖄ ᙰ ᖎ ᖏ ᖐ ᖑ ᖒ ᖓ ᖔ ᙱ ᙲ ᙳ ᙴ ᙵ ᙶ ᖠ ᖡ ᖢ ᖣ ᖤ ᖥ 𑪰 𑪱 𑪲 𑪳 𑪴 𑪵 ᖨ ᖩ ᖪ ᖫ ᖬ ᖭ 𑪶 𑪷 𑪸 𑪹 𑪺 𑪻 ᕠ ᕢ ᕤ ᕥ ᕦ ᕧ ᑉ ᑦ ᒃ ᕻ ᒡ ᒻ ᓐ ᔅ ᓪ ᔾ ᖮ ᕝ ᕐ ᖅ ᖕ ᖖ ᖦ  ᖮ  ᕪ ᕼ ᖯ ᑊ ’ - .`




## ᑕᓀᖚ ᖚᗀᐥ  (Dane-zaa ZáágeɁ) (Beaver)


![Beaver-Syllabics](https://user-images.githubusercontent.com/17300547/199070859-aab403a2-2937-4200-b20f-1ef4589b778d.png)


###### Dane-zaa ZáágeɁ Syllabics Subset
`ᐊ ᐁ ᐃ ᐅ ᐊ ᐁ ᐃ ᐅ ᐠᐊ ᐠᐁ ᐠᐃ ᐠᐅ ᐊᐧ ᐁᐧ ᐃᐧ ᐅᐧ ᗴ ᗯ ᗰ ᗱ ᑕ ᑌ ᑎ ᑐ ᗃ ᗀ ᗁ ᗂ ᕮ ᕫ ᕬ ᕭ ᑊᕮ ᑊᕫ ᑊᕬ ᑊᕭ ᐠᕮ ᐠᕫ ᐠᕬ ᐠᕭ ᑲ ᑫ ᑭ ᑯ ᖉ ᖆ ᖇ ᖈ ᕍ ᕃ ᕄ ᕊ ᐦᕍ ᐦᕃ ᐦᕄ ᐦᕄ ᒪ ᒣ ᒥ ᒧ ᓇ ᓀ ᓂ ᓄ ᐸ ᐯ ᐱ ᐳ ᓴ ᓭ ᓯ ᓱ ᕦ ᕞ ᕠ ᕤ ᒐ ᒉ ᒋ ᒍ ᘔ ᘛ ᘚ ᘕ ᔭ ᔦ ᔨ ᔪ ᖚ ᖗ ᖘ ᖙ ᐨ ᑊ ᐦ ᐠ ᒼ ᐣ ᑉ ᐢ ᒡ ᒃ - .`




## ᑐᑊᘁᗕᑋᗸ (Dulk wah’ke) (Carrier Syllabics)


![Carrier-Syllabics](https://user-images.githubusercontent.com/17300547/199070885-2a190499-0264-437a-8f0d-b3ed83325eb7.png)


###### Carrier Syllabics Subset
`ᐊ ᐅ ᐈ ᐉ ᐃ ᐁ ᐸ ᐳ ᐶ ᐷ ᐱ ᐯ ᗏ ᗌ ᗍ ᗎ ᗋ ᗊ ᗉ ᗆ ᗇ ᗈ ᗅ ᗄ ᗕ ᗒ ᗓ ᗔ ᗑ ᗐ ᗛ ᗘ ᗙ ᗚ ᗗ ᗖ ᑕ ᑐ ᑓ ᑔ ᑎ ᑌ ᗡ ᗞ ᗟ ᗠ ᗝ ᗜ ᗧ ᗤ ᗥ ᗦ ᗣ ᗢ ᗭ ᗪ ᗫ ᗬ ᗩ ᗨ ᗴ ᗱ ᗲ ᗳ ᗰ ᗯ ᗺ ᗷ ᗸ ᗹ ᗶ ᗵ ᘀ ᗽ ᗾ ᗿ ᗼ ᗻ ᘇ ᘄ ᘅ ᘆ ᘃ ᘂ ᘍ ᘊ ᘋ ᘌ ᘉ ᘈ ᘓ ᘐ ᘑ ᘒ ᘏ ᘎ ᘛ ᘗ ᘘ ᘙ ᘖ ᘔ ᘡ ᘞ ᘟ ᘠ ᘝ ᘜ ᘧ ᘤ ᘥ ᘦ ᘣ ᘢ ᘭ ᘪ ᘫ ᘬ ᘩ ᘨ ᘳ ᘰ ᘱ ᘲ ᘯ ᘮ ᘹ ᘶ ᘷ ᘸ ᘵ ᘴ ᘿ ᘼ ᘽ ᘾ ᘻ ᘺ ᙅ ᙂ ᙃ ᙄ ᙁ ᙀ ᙍ ᙊ ᙋ ᙌ ᙉ ᙈ ᙓ ᙐ ᙑ ᙒ ᙏ ᙎ ᙙ ᙖ ᙗ ᙘ ᙕ ᙔ ᙠ ᙝ ᙞ ᙟ ᙜ ᙛ ᙦ ᙣ ᙤ ᙥ ᙢ ᙡ ᙬ ᙩ ᙪ ᙫ ᙨ ᙧ ᙬ ᙩ ᙪ ᙫ ᙨ ᙧ ᐪ ᗮ ᐟ ᐠ ᘁ ᐣ ᓑ ᒼ ᑊ ᒡ ᙆ ᙇ ᔆ ᣵ ᙚ ᐩ ᶣ ᣟ - .`




## ᓴᔨᓯ ᑌᓀ (Saı́yısı́ dëne) (Sayisi Dene)


![Sayisi-Dene-Syllabics](https://user-images.githubusercontent.com/17300547/198724681-78acb3b8-8f42-4828-a1a6-50258d9f0595.png)


###### Sayisi Dene Syllabics Subset
`ᐊ ᐁ ᐃ ᐅ ᐆ ᐸ ᐯ ᐱ ᐳ ᐴ ᗴ ᗯ ᗰ ᗱ ᣮ ᑕ ᑌ ᑎ ᑐ ᑑ ᗃ ᗀ ᗁ ᗂ ᣬ ᑲ ᑫ ᑭ ᑯ ᑰ ᖉ ᖆ ᖇ ᖈ ᣩ ᕍ ᕃ ᕄ ᕊ ᣡ ᒪ ᒣ ᒥ ᒧ ᒨ ᓇ ᓀ ᓂ ᓄ ᓅ ᓴ ᓭ ᓯ ᓱ ᓲ ᖚ ᖗ ᖘ ᖙ ᣫ ᕦ ᕞ ᕠ ᕤ ᕥ ᒐ ᒉ ᒋ ᒍ ᒎ ᕮ ᕫ ᕬ ᕭ ᣦ ᘔ ᘛ ᘚ ᘕ ᣱ ᔭ ᔦ ᔨ ᔪ ᔮ ᐨ ᑊ ᐠ ᐟ ᒼ ᐣ ᐢ ᒡ ᒢ ᕁ ᐩ ᐡ ᐤ ᐧ - .`




## ᑌᓀ ᓱᒼᕄᓀ ᔭᕠᐁ (Dënësųłinë́) (Chipewyan)

![Chipewyan-Syllabics](https://user-images.githubusercontent.com/17300547/198724696-b3732390-4045-4673-81dd-833f75bae9a8.png)


###### Chipewyan Syllabics Subset
`ᐊ ᐁ ᐃ ᐅ ᐊᐧ ᐁᐧ ᐃᐧ ᐅᐧ ᑲᐧ ᑫᐧ ᑭᐧ ᑯᐧ ᐸ ᐯ ᐱ ᐳ ᑕ ᑌ ᑎ ᑐ ᑲ ᑫ ᑭ ᑯ ᑦᑲ ᑦᑫ ᑦᑭ ᑦᑯ ᕍ ᕃ ᕄ ᕊ ᒪ ᒣ ᒥ ᒧ ᓇ ᓀ ᓂ ᓄ ᖍ ᖊ ᖋ ᖌ ᓴ ᓭ ᓯ ᓱ ᔭ ᔦ ᔨ ᔪ ᘔ ᘚ ᘛ ᘕ ᐟᘔ ᐟᘚ ᐟᘛ ᐟᘕ ᗴ ᗯ ᗰ ᗱ ᒐ ᒉ ᒋ ᒍ ᕮ ᕫ ᕬ ᕭ ᕳ ᕰ ᕱ ᕲ ᑦ ᐤ ᑊ ᐟ ᐠ ᔆ ᑦ ᙆ ᒼ ᐣ ᐢ ᕀ ᑋ - .`



## ᓴᑋᕲᖌᑎᑊᐠᓀᐠ ᔭᕱ (Sahtúgot’įné Yatı̨́) (North Slavey)

![North-Slavey-Syllabics](https://user-images.githubusercontent.com/17300547/198724717-3d0faf0c-3936-48a5-b779-c3b264acd526.png)


###### North Slavey Syllabics Subset
`ᐊ ᐁ ᐃ ᐅ ᐊᐧ ᐁᐧ ᐃᐧ ᐅᐧ ᐸ ᐯ ᐱ ᐳ ᑕ ᑌ ᑎ ᑐ ᑪ ᑧ ᑨ ᑩ ᑲ ᑫ ᑭ ᑯ ᕍ ᕃ ᕄ ᕊ ᒪ ᒣ ᒥ ᒧ ᓇ ᓀ ᓂ ᓄ ᖍ ᖊ ᖋ ᖌ ᓴ ᓭ ᓯ ᓱ ᔭ ᔦ ᔨ ᔪ ᘔ ᘚ ᘛ ᘕ ᗴ ᗯ ᗰ ᗱ ᒐ ᒉ ᒋ ᒍ ᕮ ᕫ ᕬ ᕭ ᕳ ᕰ ᕱ ᕲ ᑋ ᐤ ᑊ ᐟ ᐠ ᔆ ᑦ ᐣ ᙆ ᐢ ᕀ F V - .`


## ᑌᓀ ᒐ (Dene Zhatıé) (South Slavey)

![South-Slavey-Syllabics](https://user-images.githubusercontent.com/17300547/198724725-2bb5675b-8f29-4a3c-9556-7427e5b24f78.png)


###### South Slavey Syllabics Subset
`ᐊ ᐁ ᐃ ᐅ ᐆ ᐸ ᐯ ᐱ ᐳ ᐴ ᗴ ᗯ ᗰ ᗱ ᣮ ᑕ ᑌ ᑎ ᑐ ᑑ ᐣᑕ ᐣᑌ ᐣᑎ ᐣᑐ ᐣᑑ ᗃ ᗀ ᗁ ᗂ ᣬ ᑲ ᑫ ᑭ ᑯ ᑰ ᖉ ᖆ ᖇ ᖈ ᣩ ᕍ ᕃ ᕄ ᕊ ᣡ ᒪ ᒣ ᒥ ᒧ ᒨ ᓇ ᓀ ᓂ ᓄ ᓅ ᓴ ᓭ ᓯ ᓱ ᓲ ᖚ ᖗ ᖘ ᖙ ᣫ ᕦ ᕞ ᕠ ᕤ ᕥ ᒐ ᒉ ᒋ ᒍ ᒎ ᕮ ᕫ ᕬ ᕭ ᣦ ᘔ ᘛ ᘚ ᘕ ᣱ ᐧᐊ ᐧᐁ ᐧᐃ ᐧᐅ ᐧᐆ ᔭ ᔦ ᔨ ᔪ ᔫ ᑉ ᐨ ᑊ ᐠ ᐟ ᒼ ᐣ ᐡ ᐢ ᒡ ᒢ ᕀ ᐦ ʼ - .`




