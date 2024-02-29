| ## **language**                        |                                                                                                                                                  |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/language.html](http://www.loc.gov/standards/mods/userguide/language.html)                           |
| **Source Definition**                  | A designation of the language in which the content of a resource is expressed.                                                                   |
| **DC Mapping**                         | dc:language                                                                                                                                      |
| **Encoding Scheme / Controlled Vocab** | [https://www.loc.gov/standards/iso639-2/php/code_list.php](https://www.loc.gov/standards/iso639-2/php/code_list.php) - ISO 639-2b                |
| **Type of Term**                       | Container element                                                                                                                                |
| **Obligation**                         | O                                                                                                                                                |
| **Occurrence**                         | Repeatable                                                                                                                                       |
| **Guidelines - Best Practices**        | Contains languageTerm, languageCode                                                                                                              |
| ### languageTerm                       |                                                                                                                                                  |
| **Element.Subelement[@attribute]**     | language.languageTerm[@type="text"]                                                                                                              |
| **Islandora Mapping  <br>**            | field_language                                                                                                                                   |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/language.html#languageterm](http://www.loc.gov/standards/mods/userguide/language.html#languageterm) |
| **Source Definition**                  | Contains the textual form for the language of the content of the resource.                                                                       |
| **Type of Term**                       | Element-attribute                                                                                                                                |
| **Obligation**                         | O                                                                                                                                                |
| **Occurrence**                         | Repeatable                                                                                                                                       |
| **Guidelines - Best Practices**        | Mostly used for posters or graphics containing text.                                                                                             |
| **Examples**                           | English                                                                                                                                          |
| ### languageCode                       |                                                                                                                                                  |
| **Element.Subelement[@attribute]**     | language.languageTerm[@type="code"]                                                                                                              |
| **Islandora Mapping  <br>**            | field_language                                                                                                                                   |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/language.html#languageterm](http://www.loc.gov/standards/mods/userguide/language.html#languageterm) |
| **Source Definition**                  | Contains the coded form for the language of the content of the resource.                                                                         |
| **Type of Term**                       | Element-attribute                                                                                                                                |
| **Obligation**                         | O                                                                                                                                                |
| **Occurrence**                         | Repeatable                                                                                                                                       |
| **Guidelines - Best Practices**        | Mostly used for posters or graphics containing text.                                                                                             |
| **Examples**                           | eng                                                                                                                                              |