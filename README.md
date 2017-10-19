[Powered by Yandex.Translate](https://translate.yandex.com/)

# Time and Date Translations

This repository contains `.json`, `.php` and `.txt` files for the translations of the following words:

```
millisecond, second, minute, hour, day, week, month, year, decade, century, Millennium, millisecond, seconds, minutes, hours, days, weeks, months, years, decades, centuries, millennia, January, February, March, April, May, June, July, August, September, October, November, December, Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
```

Also there is a `all.csv` and a `all.json` containing every language.
The CSV-file contains the languages in the first row.

The translation was automated and used the Yandex.Translate-API so **the results may be not perfect**. Of course it can be used and it should be understandable but with the machine-translation-drawbacks if not checked.

You can check below for languages which should not contain any mistakes.

These files are meant to be easy convertable for your needs.
For PHP also a laravel-localization-folder structure is given in the subdirectory `php/laravel` for easy copy-and-paste.

## Problems

You should especially pay attention on the following problems if the language was not checked already:

|    | wrong (originally) | right       | Problem                                                                                       |
|----|--------------------|-------------|--------------------------------------------------------------------------------------------------|
| de | sekunde            | Sekunde       | capitalization as it may vary depending on the language (in german every noun is capitalized) |
| fr | des millénaires    | millénaires   | the translator put an article before the translation                                    |

## Languages

(Adopted from the [Yandex.Translate API & Documentation](https://tech.yandex.com/translate/doc/dg/concepts/api-overview-docpage/))

| Language         | Code | Checked for mistakes |
|------------------|------|----------------------|
| ﻿Afrikaans        | af   | ✕                    |
| Albanian         | sq   | ✕                    |
| Amharic          | am   | ✕                    |
| Arabic           | ar   | ✕                    |
| Armenian         | hy   | ✕                    |
| Azerbaijan       | az   | ✕                    |
| Bashkir          | ba   | ✕                    |
| Basque           | eu   | ✕                    |
| Belarusian       | be   | ✕                    |
| Bengali          | bn   | ✕                    |
| Bosnian          | bs   | ✕                    |
| Bulgarian        | bg   | ✕                    |
| Burmese          | my   | ✕                    |
| Catalan          | ca   | ✕                    |
| Cebuano          | ceb  | ✕                    |
| Chinese          | zh   | ✕                    |
| Croatian         | hr   | ✕                    |
| Czech            | cs   | ✕                    |
| Danish           | da   | ✕                    |
| Dutch            | nl   | ✕                    |
| English          | en   | &nbsp;&nbsp;&nbsp;&nbsp;✓ |
| Esperanto        | eo   | ✕                    |
| Estonian         | et   | ✕                    |
| Finnish          | fi   | ✕                    |
| French           | fr   | &nbsp;&nbsp;&nbsp;&nbsp;✓ |
| Galician         | gl   | ✕                    |
| Georgian         | ka   | ✕                    |
| German           | de   | &nbsp;&nbsp;&nbsp;&nbsp;✓ |
| Greek            | el   | ✕                    |
| Gujarati         | gu   | ✕                    |
| Haitian (Creole) | ht   | ✕                    |
| Hebrew           | he   | ✕                    |
| Hill Mari        | mrj  | ✕                    |
| Hindi            | hi   | ✕                    |
| Hungarian        | hu   | ✕                    |
| Icelandic        | is   | ✕                    |
| Indonesian       | id   | ✕                    |
| Irish            | ga   | ✕                    |
| Italian          | it   | ✕                    |
| Japanese         | ja   | ✕                    |
| Javanese         | jv   | ✕                    |
| Kannada          | kn   | ✕                    |
| Kazakh           | kk   | ✕                    |
| Khmer            | km   | ✕                    |
| Korean           | ko   | ✕                    |
| Kyrgyz           | ky   | ✕                    |
| Laotian          | lo   | ✕                    |
| Latin            | la   | ✕                    |
| Latvian          | lv   | ✕                    |
| Lithuanian       | lt   | ✕                    |
| Luxembourgish    | lb   | ✕                    |
| Macedonian       | mk   | ✕                    |
| Malagasy         | mg   | ✕                    |
| Malay            | ms   | ✕                    |
| Malayalam        | ml   | ✕                    |
| Maltese          | mt   | ✕                    |
| Maori            | mi   | ✕                    |
| Marathi          | mr   | ✕                    |
| Mari             | mhr  | ✕                    |
| Mongolian        | mn   | ✕                    |
| Nepali           | ne   | ✕                    |
| Norwegian        | no   | ✕                    |
| Papiamento       | pap  | ✕                    |
| Persian          | fa   | ✕                    |
| Polish           | pl   | ✕                    |
| Portuguese       | pt   | ✕                    |
| Punjabi          | pa   | ✕                    |
| Romanian         | ro   | ✕                    |
| Russian          | ru   | ✕                    |
| Scottish         | gd   | ✕                    |
| Serbian          | sr   | ✕                    |
| Sinhala          | si   | ✕                    |
| Slovakian        | sk   | ✕                    |
| Slovenian        | sl   | ✕                    |
| Spanish          | es   | &nbsp;&nbsp;&nbsp;&nbsp;✓ |
| Sundanese        | su   | ✕                    |
| Swahili          | sw   | ✕                    |
| Swedish          | sv   | ✕                    |
| Tagalog          | tl   | ✕                    |
| Tajik            | tg   | ✕                    |
| Tamil            | ta   | ✕                    |
| Tatar            | tt   | ✕                    |
| Telugu           | te   | ✕                    |
| Thai             | th   | ✕                    |
| Turkish          | tr   | ✕                    |
| Udmurt           | udm  | ✕                    |
| Ukrainian        | uk   | ✕                    |
| Urdu             | ur   | ✕                    |
| Uzbek            | uz   | ✕                    |
| Vietnamese       | vi   | ✕                    |
| Welsh            | cy   | ✕                    |
| Xhosa            | xh   | ✕                    |
| Yiddish          | yi   | ✕                    |

## Method

Every of the words was put into the translator in german and saved in the files.
German was used because none of the german words has a second meaning, but "second" for example has.

[The (nodejs-)script can be found here.](https://gist.github.com/movabo/eb8bd8e2651322366084975f394568f4)

## License

The [script](https://gist.github.com/movabo/eb8bd8e2651322366084975f394568f4) and files are licensed on CC-0 1.0.
