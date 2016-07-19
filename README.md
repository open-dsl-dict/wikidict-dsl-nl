# wikidict-dsl-nl - Wikidata Bilingual DSL Dictionaries (Dutch)

This repository makes available a collection of bilingual Dutch dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-nl/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-nl_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-nl` | Afrikaans => Dutch
`am-nl` | Amharic => Dutch
`ang-nl` | Anglo-Saxon => Dutch
`ar-nl` | Arabic => Dutch
`arc-nl` | Aramaic => Dutch
`bg-nl` | Bulgarian => Dutch
`bi-nl` | Bislama => Dutch
`bn-nl` | Bengali => Dutch
`bo-nl` | Tibetan => Dutch
`br-nl` | Breton => Dutch
`bs-nl` | Bosnian => Dutch
`ca-nl` | Catalan => Dutch
`cdo-nl` | Min Dong => Dutch
`chr-nl` | Cherokee => Dutch
`chy-nl` | Cheyenne => Dutch
`cr-nl` | Cree => Dutch
`cs-nl` | Czech => Dutch
`cy-nl` | Welsh => Dutch
`da-nl` | Danish => Dutch
`de-nl` | German => Dutch
`el-nl` | Greek => Dutch
`en-nl` | English => Dutch
`eo-nl` | Esperanto => Dutch
`es-nl` | Spanish => Dutch
`et-nl` | Estonian => Dutch
`eu-nl` | Basque => Dutch
`fa-nl` | Persian => Dutch
`ff-nl` | Fula => Dutch
`fi-nl` | Finnish => Dutch
`fr-nl` | French => Dutch
`ga-nl` | Irish => Dutch
`gan-nl` | Gan => Dutch
`gd-nl` | Scottish Gaelic => Dutch
`gu-nl` | Gujarati => Dutch
`gv-nl` | Manx => Dutch
`ha-nl` | Hausa => Dutch
`hak-nl` | Hakka => Dutch
`haw-nl` | Hawaiian => Dutch
`he-nl` | Hebrew => Dutch
`hi-nl` | Hindi => Dutch
`hr-nl` | Croatian => Dutch
`ht-nl` | Haitian => Dutch
`hu-nl` | Hungarian => Dutch
`hy-nl` | Armenian => Dutch
`id-nl` | Indonesian => Dutch
`ig-nl` | Igbo => Dutch
`is-nl` | Icelandic => Dutch
`it-nl` | Italian => Dutch
`iu-nl` | Inuktitut => Dutch
`ja-nl` | Japanese => Dutch
`jbo-nl` | Lojban => Dutch
`jv-nl` | Javanese => Dutch
`ka-nl` | Georgian => Dutch
`kg-nl` | Kongo => Dutch
`ki-nl` | Kikuyu => Dutch
`kl-nl` | Greenlandic => Dutch
`km-nl` | Khmer => Dutch
`ko-nl` | Korean => Dutch
`la-nl` | Latin => Dutch
`lg-nl` | Luganda => Dutch
`lo-nl` | Lao => Dutch
`lt-nl` | Lithuanian => Dutch
`lv-nl` | Latvian => Dutch
`mg-nl` | Malagasy => Dutch
`mi-nl` | Maori => Dutch
`mn-nl` | Mongolian => Dutch
`ms-nl` | Malay => Dutch
`mt-nl` | Maltese => Dutch
`nah-nl` | Nahuatl => Dutch
`ne-nl` | Nepali => Dutch
`nn-nl` | Norwegian (Nynorsk) => Dutch
`no-nl` | Norwegian => Dutch
`nv-nl` | Navajo => Dutch
`ny-nl` | Chichewa => Dutch
`oc-nl` | Occitan => Dutch
`pa-nl` | Punjabi => Dutch
`pi-nl` | Pali => Dutch
`pl-nl` | Polish => Dutch
`ps-nl` | Pashto => Dutch
`pt-nl` | Portuguese => Dutch
`qu-nl` | Quechua => Dutch
`ro-nl` | Romanian => Dutch
`ru-nl` | Russian => Dutch
`sa-nl` | Sanskrit => Dutch
`se-nl` | Northern Sami => Dutch
`sh-nl` | Serbo-Croatian => Dutch
`sk-nl` | Slovak => Dutch
`sl-nl` | Slovenian => Dutch
`sn-nl` | Shona => Dutch
`so-nl` | Somali => Dutch
`sq-nl` | Albanian => Dutch
`sr-nl` | Serbian => Dutch
`sv-nl` | Swedish => Dutch
`sw-nl` | Kiswahili => Dutch
`ta-nl` | Tamil => Dutch
`te-nl` | Telugu => Dutch
`th-nl` | Thai => Dutch
`tl-nl` | Tagalog => Dutch
`tpi-nl` | Tok Pisin => Dutch
`tr-nl` | Turkish => Dutch
`ug-nl` | Uyghur => Dutch
`uk-nl` | Ukrainian => Dutch
`ur-nl` | Urdu => Dutch
`vi-nl` | Vietnamese => Dutch
`wo-nl` | Wolof => Dutch
`wuu-nl` | Wu => Dutch
`xh-nl` | Xhosa => Dutch
`yi-nl` | Yiddish => Dutch
`yo-nl` | Yoruba => Dutch
`za-nl` | Zhuang => Dutch
`zh-nl` | Chinese (Mandarin) => Dutch
`zh_classical-nl` | Classical Chinese => Dutch
`zh_min_nan-nl` | Min Nan => Dutch
`zh_yue-nl` | Cantonese => Dutch
`zu-nl` | Zulu => Dutch

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-nl` | 25303
`am-nl` | 5440
`ang-nl` | 2318
`ar-nl` | 117652
`arc-nl` | 1283
`bg-nl` | 99767
`bi-nl` | 434
`bn-nl` | 18777
`bo-nl` | 2541
`br-nl` | 35216
`bs-nl` | 35847
`ca-nl` | 240461
`cdo-nl` | 1878
`chr-nl` | 461
`chy-nl` | 542
`cr-nl` | 91
`cs-nl` | 137181
`cy-nl` | 30223
`da-nl` | 95503
`de-nl` | 407130
`el-nl` | 47767
`en-nl` | 715204
`eo-nl` | 122918
`es-nl` | 408318
`et-nl` | 56977
`eu-nl` | 144472
`fa-nl` | 146000
`ff-nl` | 188
`fi-nl` | 150664
`fr-nl` | 468524
`ga-nl` | 20544
`gan-nl` | 4476
`gd-nl` | 10830
`gu-nl` | 3405
`gv-nl` | 3995
`ha-nl` | 378
`hak-nl` | 2385
`haw-nl` | 1441
`he-nl` | 81024
`hi-nl` | 22115
`hr-nl` | 72567
`ht-nl` | 24184
`hu-nl` | 123483
`hy-nl` | 38710
`id-nl` | 190382
`ig-nl` | 700
`is-nl` | 21215
`it-nl` | 397321
`iu-nl` | 343
`ja-nl` | 187948
`jbo-nl` | 1133
`jv-nl` | 24133
`ka-nl` | 50408
`kg-nl` | 772
`ki-nl` | 294
`kl-nl` | 1526
`km-nl` | 1359
`ko-nl` | 108503
`la-nl` | 79260
`lg-nl` | 150
`lo-nl` | 1029
`lt-nl` | 64290
`lv-nl` | 34184
`mg-nl` | 50234
`mi-nl` | 2128
`mn-nl` | 9243
`ms-nl` | 134194
`mt-nl` | 2277
`nah-nl` | 6604
`ne-nl` | 6496
`nn-nl` | 49425
`no-nl` | 157001
`nv-nl` | 1682
`ny-nl` | 123
`oc-nl` | 73059
`pa-nl` | 7275
`pi-nl` | 2312
`pl-nl` | 368630
`ps-nl` | 2394
`pt-nl` | 347953
`qu-nl` | 10932
`ro-nl` | 143772
`ru-nl` | 315215
`sa-nl` | 4436
`se-nl` | 5529
`sh-nl` | 132260
`sk-nl` | 126745
`sl-nl` | 62456
`sn-nl` | 1440
`so-nl` | 2255
`sq-nl` | 26902
`sr-nl` | 150206
`sv-nl` | 754072
`sw-nl` | 16661
`ta-nl` | 20368
`te-nl` | 7135
`th-nl` | 43592
`tl-nl` | 30896
`tpi-nl` | 1162
`tr-nl` | 101379
`ug-nl` | 2049
`uk-nl` | 206160
`ur-nl` | 32267
`vi-nl` | 509742
`wo-nl` | 862
`wuu-nl` | 1900
`xh-nl` | 253
`yi-nl` | 6727
`yo-nl` | 11561
`za-nl` | 543
`zh-nl` | 252143
`zh_classical-nl` | 1992
`zh_min_nan-nl` | 9936
`zh_yue-nl` | 16102
`zu-nl` | 553

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`sv-nl` | 754072
`en-nl` | 715204
`vi-nl` | 509742
`fr-nl` | 468524
`es-nl` | 408318
`de-nl` | 407130
`it-nl` | 397321
`pl-nl` | 368630
`pt-nl` | 347953
`ru-nl` | 315215

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
