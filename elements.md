### UMKC DIgital Projects Still Image Metadata Elements

Image class objects include photographs, graphics, and posters. Where variation exists, the instructions shall be qualified.

| **titleInfo**                         |                                                                                                                                                                                                                                                                              |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Label**                                | photographs = Caption  <br>graphics and posters = Title                                                                                                                                                                                                                      |
| **Defined by**                           | [http://www.loc.gov/standards/mods/userguide/titleinfo.html](http://www.loc.gov/standards/mods/userguide/titleinfo.html)                                                                                                                                                     |
| **Source Definition**                    | A word, phrase, character, or group of characters, normally appearing in a resource, that names it or the work contained in it.                                                                                                                                              |
| **DC Mapping**                           | dc:title                                                                                                                                                                                                                                                                     |
| **Type of Term**                         | Container element                                                                                                                                                                                                                                                            |
| **Obligation**                           | R                                                                                                                                                                                                                                                                            |
| **Occurrence**                           | Repeatable                                                                                                                                                                                                                                                                   |
| **Guidelines - Best Practices**          | Contains nonSort, title, subTitle, alternativeTitle subelements.                                                                                                                                                                                                             |
| ### nonSort                              |                                                                                                                                                                                                                                                                              |
| **Element.Subelement  <br>[@attribute]** | titleInfo.nonSort                                                                                                                                                                                                                                                            |
| **Islandora Mapping  <br>**              | field_title_non_sort                                                                                                                                                                                                                                                         |
| **Defined by**                           | [http://www.loc.gov/standards/mods/userguide/titleinfo.html#nonsort](http://www.loc.gov/standards/mods/userguide/titleinfo.html#nonsort)                                                                                                                                     |
| **Source Definition**                    | Characters, including initial articles, punctuation, and spaces that appear at the beginning of a title that should be ignored for indexing of titles.                                                                                                                       |
| **Type of Term**                         | Element                                                                                                                                                                                                                                                                      |
| **Obligation**                           | O                                                                                                                                                                                                                                                                            |
| **Occurrence**                           | Not Repeatable                                                                                                                                                                                                                                                               |
| **Guidelines - Best Practices**          | - Record non-sorting characters that appear at the beginning of the title, such as initial articles.<br>    <br>- Be careful to omit any trailing whitespaces.<br>    <br>- RDA, Appendix C: Initial Articles provides a list of initial articles by language and by word(s) |
| **Examples**                             | The  <br>An  <br>L’                                                                                                                                                                                                                                                          |
| ### title                                |                                                                                                                                                                                                                                                                              |
| **Element.Subelement  <br>[@attribute]** | titleInfo.title                                                                                                                                                                                                                                                              |
| **Islandora Mapping  <br>**              | title                                                                                                                                                                                                                                                                        |
| **Defined by**                           | [http://www.loc.gov/standards/mods/userguide/titleinfo.html#title](http://www.loc.gov/standards/mods/userguide/titleinfo.html#title)                                                                                                                                         |
| **Source Definition**                    | A word, phrase, character, or group of characters that constitutes the chief title of a resource, i.e., the title normally used when citing the resource.                                                                                                                    |
| **Type of Term**                         | Element                                                                                                                                                                                                                                                                      |
| **Obligation**                           | R                                                                                                                                                                                                                                                                            |
| **Occurrence**                           | Repeatable                                                                                                                                                                                                                                                                   |
| **Guidelines - Best Practices**          | - Use most prominent text on resource. Use judgment when selecting a title.<br>    <br>- Use caption on resource; otherwise, provide a title that identifies the people or subjects pictured.                                                                                |
| **Examples**                             | ACME stained glass at the KC Mace Conference  <br>Freedom now!  <br>Parkview Pharmacies matchbook cover                                                                                                                                                                      |
| ### subTitle                             |                                                                                                                                                                                                                                                                              |
| **Element.Subelement[@attribute]**       | titleInfo.subTitle                                                                                                                                                                                                                                                           |
| **Islandora Mapping  <br>**              | field_subtitle                                                                                                                                                                                                                                                               |
| **Defined by**                           | [http://www.loc.gov/standards/mods/userguide/titleinfo.html#subtitle](http://www.loc.gov/standards/mods/userguide/titleinfo.html#subtitle)                                                                                                                                   |
| **Source Definition**                    | A word, phrase, character, or group of characters that contains the remainder of the title information after the title proper.                                                                                                                                               |
| **Type of Term**                         | Element                                                                                                                                                                                                                                                                      |
| **Obligation**                           | REA                                                                                                                                                                                                                                                                          |
| **Occurrence**                           | Non-Repeatable                                                                                                                                                                                                                                                               |
| **Guidelines - Best Practices**          | If subtitle is present on the item, please record. Do not supply a subtitle.                                                                                                                                                                                                 |
| **Examples**                             | Elect Bruce R. Watkins, Committeeman, 2nd Ward  <br>Elect Catherine Mitchell, Committeewoman, 2nd Ward                                                                                                                                                                       |
| ### alternativeTitle                     |                                                                                                                                                                                                                                                                              |
| **Element.Subelement[@attribute]**       | titleInfo[@type="alternative"].title                                                                                                                                                                                                                                         |
| **Islandora Mapping  <br>**              | field_alt_title                                                                                                                                                                                                                                                              |
| **Defined by**                           | [http://www.loc.gov/standards/mods/userguide/titleinfo.html](http://www.loc.gov/standards/mods/userguide/titleinfo.html)                                                                                                                                                     |
| **Source Definition**                    | Varying form of the title if it contributes to the further identification of the item.                                                                                                                                                                                       |
| **Type of Term**                         | Element                                                                                                                                                                                                                                                                      |
| **Obligation**                           | O                                                                                                                                                                                                                                                                            |
| **Occurrence**                           | Repeatable                                                                                                                                                                                                                                                                   |
| **Guidelines - Best Practices**          | Use judgment in recording an alternative title.                                                                                                                                                                                                                              |
| **Examples**                             | Vote Freedom Inc. democratic ballot                                                                                                                                                                                                                                          |
  
|**name**|   |
|---|---|
|**Label**|photographs = Photographer  <br>graphics = Contributor<br><br>posters = Participating Organization|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html](http://www.loc.gov/standards/mods/userguide/name.html)|
|**Source Definition**|The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource.|
|**DC Mapping**|dc:contributor|
|**Type of Term**|Container element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices  <br>**|Contains namePart, nameDate, nameToA, role, nameDisplay.|
|### namePart|   |
|**Element.Subelement[@attribute]**|name[@authority="naf"][@type].namePart|
|**Islandora Mapping  <br>**|field_mods_name_personal_namepar|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|The individual parsed parts that together make up the full name.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single namePart element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File. When used, this element requires the use of the attribute, @type set to personal, corporate, conference, or family.|
|**Examples**|Randolph, William  <br>Freedom, Inc.|
|### nameDate|   |
|**Element.Subelement[@attribute]**|name[@authority="naf"][@type="personal"].namePart[@type="date"]|
|**Islandora Mapping  <br>**|field_lcsh_date_name_part|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|Used to parse dates that are not integral parts of a name. Dates that are part of a name, e.g. dates within a conference name, do not use this attribute to separate the date, since it is an integral part of the name string. The birthdate associated with a personal name, however, is not an integral part of the name but added to distinguish the name from others, so it does include a separate <namePart> with type="date". This attribute is not used when parsing the components of a corporate name.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element-attribute|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The date(s) are entered as one string in a single namePart[@type="date"] element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File. When used, this element requires the use of the attribute, @type set to personal, corporate, conference, or family.|
|**Examples**|1920-1978  <br>approximately 1918-2001|
|### nameToA|   |
|**Element.Subelement[@attribute]**|name[@authority="naf"][@type="personal"].namePart[@type="termsOfAddress"]|
|**Islandora Mapping  <br>**|field_terms_of_address|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|Used to record titles and enumeration associated with a name, such as Jr., II, etc.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element-attribute|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The term of address is entered as one string in a single namePart[@type="termsOfAddress"] element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File. When used, this element requires the use of the attribute, @type set to personal.|
|**Examples**|Mrs.  <br>Jr.  <br>Sir|
|### nameRole|   |
|**Element.Subelement[@attribute]**|name[@authority="naf"][@type].role[@type="text"][@authority="marcrelator"].roleTerm|
|**Islandora Mapping  <br>**|field_personal_name_role|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#roleterm](http://www.loc.gov/standards/mods/userguide/name.html#roleterm)|
|**Source Definition**|Designates the relationship (role) of the entity recorded in the name to the resource described in the record.|
|**Encoding Scheme / Controlled Vocab**|[http://www.loc.gov/marc/relators/relaterm.html](http://www.loc.gov/marc/relators/relaterm.html) - MARC Code List for Relators|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|When a MARC relator term is used, it is required to use the term and not the code for the term. When used, this element requires the use of the attributes, @type=”text” and @authority=”marcrelator”.|
|**Examples**|Photographer  <br>Donor  <br>Sponsor|
|### nameDisplay|   |
|**Element.Subelement[@attribute]**|name[@authority="naf"][@type].displayForm|
|**Islandora Mapping  <br>**|field_subject_personal_name_disp|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#displayform](http://www.loc.gov/standards/mods/userguide/name.html#displayform)|
|**Source Definition**|The unstructured form of the name as given on the resource.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single displayForm element. When possible, names should come from a controlled vocabulary. Highly recommends the use of LC Name Authority File. When used, this element requires the use of the attribute, @type set to personal, corporate, conference, or family.|
|**Examples**|Randolph, William, 1920-1978  <br>Jewell, Keith (Photographer)  <br>Freedom, Inc.|

  

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|   |   |
|---|---|
|## **typeOfResource**|   |
|**Element.Subelement[@attribute]**|typeOfResource|
|**Islandora Mapping  <br>**|field_resource_type|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/typeofresource.html](http://www.loc.gov/standards/mods/userguide/typeofresource.html)|
|**Source Definition**|A term that specifies the characteristics and general type of content of the resource.|
|**DC Mapping**|dc:type|
|**Encoding Scheme / Controlled Vocab**|[http://www.loc.gov/standards/mods/userguide/typeofresource.html](http://www.loc.gov/standards/mods/userguide/typeofresource.html)|
|**Type of Term**|Element|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|For still images, the term will be: still image|
|**Examples**|still image|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|## **genre**|   |
|---|---|
|**Label**|Genres|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/genre.html](http://www.loc.gov/standards/mods/userguide/genre.html)|
|**Source Definition**|A term or terms that designate a category characterizing a particular style, form, or content, such as artistic, musical, literary composition, etc.|
|**DC Mapping**|dc:type [not@authority="local"]|
|**Type of Term**|Element|
|**Obligation**|RE|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|For still images, use LCTGM and Local Types list.|
|### genreLctgm|   |
|**Element.Subelement[@attribute]**|genre[@authority="lcgtm"]|
|**Islandora Mapping  <br>**|field_genre_authority_lctgm|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/genre.html](http://www.loc.gov/standards/mods/userguide/genre.html)|
|**Source Definition**|A term or terms that designate a category characterizing a particular style, form, or content, such as artistic, musical, literary composition, etc.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/vocabulary/graphicMaterials.html](http://id.loc.gov/vocabulary/graphicMaterials.html) - Library of Congress' Thesaurus for Graphic Materials|
|**Type of Term**|Element-attribute|
|**Obligation**|RE|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**||
|**Examples**|Black & white photographs  <br>Gelatin silver prints  <br>Architectural drawings  <br>Photographic postcards|
|### genreLocal|   |
|**Label**|Type|
|**Element.Subelement[@attribute]**|genre[@authority="local"]|
|**Islandora Mapping  <br>**|field_genre_authority_local|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/genre.html](http://www.loc.gov/standards/mods/userguide/genre.html)|
|**Source Definition**|A term or terms that designate a category characterizing a particular style, form, or content, such as artistic, musical, literary composition, etc.|
|**Encoding Scheme / Controlled Vocab**|[http://library.umkc.edu/ulwiki/umkculibs/spec-coll-home/dlmetadata/topicstypes](http://library.umkc.edu/ulwiki/umkculibs/spec-coll-home/dlmetadata/topicstypes) - UMKC Local Types|
|**Type of Term**|Element-attribute|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|In some cases, double indexing is necessary, e.g., if a graphic belongs to a photographic collection, double index as graphics and photographs.|
|**Examples**|photographs  <br>graphics  <br>posters|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

  

|## **originInfo**|   |
|---|---|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html](http://www.loc.gov/standards/mods/userguide/origininfo.html)|
|**Source Definition**|Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.|
|**Type of Term**|Container element|
|**Obligation**|R|
|**Occurrence**|Non-Repeatable|
|**Guidelines - Best Practices**|Contains publisher, date, dateStart, dateEnd, dateOther, dateCopyright.|
|### publisher|   |
|**Label**|photographs = Image Credit  <br>graphics, posters = Publisher|
|**Element.Subelement[@attribute]**|originInfo.publisher|
|**Islandora Mapping  <br>**|field_publisher|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html#publisher](http://www.loc.gov/standards/mods/userguide/origininfo.html#publisher)|
|**Source Definition**|The name of the entity that published, printed, distributed, released, issued, or produced the resource.|
|**DC Mapping**|dc:publisher|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Rarely known for posters. Transcribe, when applicable.|
|**Examples**|America's Best Attractions|
|### date|   |
|**Element.Subelement[@attribute]**|originInfo.dateIssued[@encoding="w3cdtf"][@keyDate="yes"]|
|**Islandora Mapping  <br>**|field_edtf_date_issued|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued](http://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued)|
|**Source Definition**|The date that the resource was published, released, or issued.|
|**DC Mapping**|dc:date|
|**Type of Term**|Element-attribute|
|**Encoding Scheme / Controlled Vocab**|[https://www.w3.org/TR/NOTE-datetime](https://www.w3.org/TR/NOTE-datetime) - W3C-DTF|
|**Obligation**|RA|
|**Occurrence**|Non-Repeatable|
|**Guidelines - Best Practices**|Use this for single dates only (containing a known, year, month, day). It is preferred (but not required) that single dates where only a year or a year and month are known be entered under dateStart and dateEnd as a range (ie. 1981 = 1981-01-01 to 1981-12-31 or 1994-04 = 1994-04-01 to 1994-04-30)|
|**Examples**|1923 (allowed but preferred as a range in dateStart/dateEnd)  <br>1952-06-21|
|### dateStart||
|**Element.Subelement[@attribute]**|originInfo.dateIssued[@encoding="w3cdtf"][@keyDate="yes"][@qualifier="approximate"][@point="start"]|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued](http://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued)|
|**Source Definition**|The date that the resource was published, released, or issued.|
|**DC Mapping**|dc:date|
|**Type of Term**|Element-attribute|
|**Encoding Scheme / Controlled Vocab**|[https://www.w3.org/TR/NOTE-datetime](https://www.w3.org/TR/NOTE-datetime) - W3C-DTF|
|**Obligation**|RA|
|**Occurrence**|Non-Repeatable|
|**Guidelines - Best Practices**|Use this for date ranges, indicating the start date in the range. May include varying levels of specificity.|
|**Examples**|1923  <br>1945-05  <br>1952-06-21|
|### dateEnd|   |
|**Element.Subelement[@attribute]**|originInfo.dateIssued[@encoding="w3cdtf"][@qualifier="approximate"][@point="end"]|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued](http://www.loc.gov/standards/mods/userguide/origininfo.html#dateissued)|
|**Source Definition**|The date that the resource was published, released, or issued.|
|**DC Mapping**|dc:date|
|**Type of Term**|Element-attribute|
|**Encoding Scheme / Controlled Vocab**|[https://www.w3.org/TR/NOTE-datetime](https://www.w3.org/TR/NOTE-datetime) - W3C-DTF|
|**Obligation**|RA|
|**Occurrence**|Non-Repeatable|
|**Guidelines - Best Practices**|Use this for date ranges, indicating the end date in the range. May include varying levels of specificity.|
|**Examples**|1929  <br>1945-05  <br>1952-06-25|
|### copyrightDate|   |
|**Element.Subelement[@attribute]**|originInfo.dateIssued[@encoding="w3cdtf"]|
|**Islandora Mapping  <br>**|field_copyright_date|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html#copyrightdate](http://www.loc.gov/standards/mods/userguide/origininfo.html#copyrightdate)|
|**Source Definition**|A date in which a resource is copyrighted.|
|**DC Mapping**|dc:date|
|**Type of Term**|Element-attribute|
|**Encoding Scheme / Controlled Vocab**|[https://www.w3.org/TR/NOTE-datetime](https://www.w3.org/TR/NOTE-datetime) - W3C-DTF|
|**Obligation**|REA|
|**Occurrence**|Non-Repeatable|
|**Guidelines - Best Practices**|Record copyright date; usually just a year.|
|**Examples**|1948|
|### dateOther||
|**Label**|Date of Event|
|**Element.Subelement[@attribute]**|originInfo.dateOther[@encoding="w3cdtf"]|
|**Islandora Mapping  <br>**|field_edtf_date|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/origininfo.html#dateother](http://www.loc.gov/standards/mods/userguide/origininfo.html#dateother)|
|**Source Definition**|A date that does not fall into another category but is important to record.|
|**DC Mapping**|dc:date|
|**Type of Term**|Element-attribute|
|**Encoding Scheme / Controlled Vocab**|[https://www.w3.org/TR/NOTE-datetime](https://www.w3.org/TR/NOTE-datetime) - W3C-DTF|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Use this for posters to indicate date of event.|
|**Examples**|1962-06-04|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|## **language**|   |
|---|---|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/language.html](http://www.loc.gov/standards/mods/userguide/language.html)|
|**Source Definition**|A designation of the language in which the content of a resource is expressed.|
|**DC Mapping**|dc:language|
|**Encoding Scheme / Controlled Vocab**|[https://www.loc.gov/standards/iso639-2/php/code_list.php](https://www.loc.gov/standards/iso639-2/php/code_list.php) - ISO 639-2b|
|**Type of Term**|Container element|
|**Obligation**|O|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Contains languageTerm, languageCode|
|### languageTerm|   |
|**Element.Subelement[@attribute]**|language.languageTerm[@type="text"]|
|**Islandora Mapping  <br>**|field_language|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/language.html#languageterm](http://www.loc.gov/standards/mods/userguide/language.html#languageterm)|
|**Source Definition**|Contains the textual form for the language of the content of the resource.|
|**Type of Term**|Element-attribute|
|**Obligation**|O|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Mostly used for posters or graphics containing text.|
|**Examples**|English|
|### languageCode|   |
|**Element.Subelement[@attribute]**|language.languageTerm[@type="code"]|
|**Islandora Mapping  <br>**|field_language|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/language.html#languageterm](http://www.loc.gov/standards/mods/userguide/language.html#languageterm)|
|**Source Definition**|Contains the coded form for the language of the content of the resource.|
|**Type of Term**|Element-attribute|
|**Obligation**|O|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Mostly used for posters or graphics containing text.|
|**Examples**|eng|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

  

|## **physicalDescription**|   |
|---|---|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/physicaldescription.html](http://www.loc.gov/standards/mods/userguide/physicaldescription.html)|
|**Source Definition**|Describes the physical attributes of the information resource.|
|**DC Mapping**|dc:format|
|**Type of Term**|Container element|
|**Obligation**|R|
|**Occurrence**|Not Repeatable|
|**Guidelines - Best Practices**|Contains internetMediaType, extent, digitalOrigin|
|### extent|   |
|**Label**|Extent of Original|
|**Element.Subelement[@attribute]**|physicalDescription.extent|
|**Islandora  <br>**|field_extent|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/physicaldescription.html#extent](http://www.loc.gov/standards/mods/userguide/physicaldescription.html#extent)|
|**Source Definition**|A statement of the number and specific material of the units of the resource that express physical extent.|
|**Type of Term**|Element|
|**Obligation**|RE|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Measurement in centimeters. Format: [number] [type] : [color] ; [height] x [width] cm|
|**Examples**|1 photograph : black and white print ; 26 x 21 cm  <br>1 photograph : color ; 9 x 6 cm (slide format)  <br>1 print (poster) : screen, color ; 28 x 36 cm  <br>1 matchbook : color ; 4.5 x 4 cm (folded)|
|### internetMediaType|   |
|**Element.Subelement[@attribute]**|physicalDescription.internetMediaType|
|**Islandora Mapping  <br>**|field_internet_media_types|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/physicaldescription.html#internetmediatype](http://www.loc.gov/standards/mods/userguide/physicaldescription.html#internetmediatype)|
|**Source Definition**|An identification of the electronic format type, or the data representation of the resource.|
|**Type of Term**|Element|
|**Encoding Scheme / Controlled Vocab**|[http://www.iana.org/assignments/media-types/media-types.xhtml](http://www.iana.org/assignments/media-types/media-types.xhtml) - IANA Media Types|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**||
|**Examples**|image/tiff  <br>image/jpeg  <br>image/jp2|
|### digitalOrigin|   |
|**Element.Subelement[@attribute]**|physicalDescription.digitalOrigin|
|**Islandroa Mapping  <br>**|field_physical_description_digit|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/physicaldescription.html#digitalorigin](http://www.loc.gov/standards/mods/userguide/physicaldescription.html#digitalorigin)|
|**Source Definition**|The method by which a resource achieved digital form.|
|**Type of Term**|Element|
|**Encoding Scheme / Controlled Vocab**|The following values may be used:<br><br>- **born digital** – A resource was created and is intended to remain in digital form.<br>- **reformatted digital** – A resource was created by digitization of the original which was in a non-digital form (except original microforms).<br>- **digitized microfilm** – A resource was created by digitizing a microform.<br>- **digitized other analog** – A resource was created by digitizing an intermediate form of the original resource (but not microform) such as photocopy, transparency, slide, 2nd generation analog tapes, etc.|
|**Obligation**|R|
|**Occurrence**|Not Repeatable|
|**Guidelines - Best Practices**||
|**Examples**|reformatted digital|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

  

|## **abstract  <br>**|   |
|---|---|
|**Label**|Description|
|**Element.Subelement[@attribute]**|abstract|
|**Islandora Mapping  <br>**|field_abstract|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/abstract.html](http://www.loc.gov/standards/mods/userguide/abstract.html)|
|**Source Definition**|A summary of the content of the resource.|
|**DC Mapping**|dc:description|
|**Type of Term**|Element|
|**Obligation**|RE|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|A description of what the image depicts. Consider the subjects. If a person, are they seated or standing? Does it show only their upper body? What are they wearing? Which direction are they facing? Where was the image captured? Why was it captured? Is it an aerial shot? Etc. Your description should enable someone to visualize the image.|
|**Examples**|An unidentified man (background) holds up a circular stained glass at the KC Mace Conference. The stained glass depicts two small children holding hands in front of a heart, center image of a 5-pointed star, and the word ACME in front of two interlacing circles at the top.  <br>  <br>Election campaign poster for Freedom Inc. candidates representing the 2nd Ward, Kansas City: Bruce R. Watkins and Catherine Mitchell. Includes a black and white photograph of each of the candidates.|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

  

|## **note  <br>**|   |
|---|---|
|**Label**|Notes|
|**Element.Subelement[@attribute]**|note|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/note.html](http://www.loc.gov/standards/mods/userguide/note.html)|
|**Source Definition**|General textual information relating to a resource.|
|**DC Mapping**|dc:description|
|**Type of Term**|Element|
|**Obligation**|O|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Additional notes pertaining to the image. Add a note indicating source of title.|
|**Examples**|Caption title.  <br>Original publisher: America's Best Attractions, Suite 201, 1800 Burlington Street, North Kansas City, Missouri 64116.|
|### noteDate|   |
|**Label**|Date Published|
|**Element.Subelement[@attribute]**|note[@type="date"]|
|**Islandora Mapping  <br>**|field_note|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/note.html](http://www.loc.gov/standards/mods/userguide/note.html)|
|**Type of Term**|Element-attribute|
|**Obligation**|R|
|**Occurrence**|Not Repeatable|
|**Guidelines - Best Practices**|Note textual form of date(s) for display purposes. If unknown date, note approximation by proceeding with: No date; likely between YYYY and YYYY OR Approximately YYYY-YYYY.|
|**Examples**|No date; likely between 1961 and 1976  <br>October 1978  <br>Approximately 1952-1955|
|### noteAgency||
|**Label**|Notes|
|**Element.Subelement[@attribute]**|note|
|**Islandora Mapping  <br>**|field_note|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/note.html](http://www.loc.gov/standards/mods/userguide/note.html)|
|**Type of Term**|Element|
|**Obligation**|R|
|**Occurrence**|Not Repeatable|
|**Guidelines - Best Practices**|Digitizing agency: [Take the form of the name as found in LCNAF].|
|**Examples**|Digitizing agency: University of Missouri--Kansas City. Library. Dr. Kenneth J. LaBudde Special Collections.|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|## **subject  <br>**|   |
|---|---|
|**Label**|Subjects|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html](http://www.loc.gov/standards/mods/userguide/subject.html)|
|**Source Definition**|A term or phrase representing the primary topic(s) on which a work is focused.|
|**DC Mapping**|dc:subject|
|**Type of Term**|Container element|
|**Obligation**|RE|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Contains topic, geographic, temporal, titleInfo, name|
|### subjectTopic|   |
|**Islandora Mapping  <br>**|?|
|**Element.Subelement[@attribute]**|subject[@authority="fast"].topic|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html#topic](http://www.loc.gov/standards/mods/userguide/subject.html#topic)|
|**Source Definition**|Used as the tag for any topical subjects that are not appropriate in the <geographic>, <temporal>, <titleInfo>, <name>, <genre>, <hierarchicalGeographic>, or <occupation> subelements.|
|**Type of Term**|Element|
|**Encoding Scheme / Controlled Vocab**|[http://fast.oclc.org/searchfast/](http://fast.oclc.org/searchfast/) - FAST (Faceted Application of Subject Terminology)|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Subjects that are topical in nature.|
|**Examples**|African-American jazz musicians  <br>Jazz musicians  <br>City council members  <br>Women politicians  <br>Flowers|
|### subjectName|   |
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html#name](http://www.loc.gov/standards/mods/userguide/subject.html#name)|
|**Source Definition**|A name used as a subject.|
|**Type of Term**|Container element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices  <br>**|Contains subjectPersonalName, subjectPersonalNameDate, subjectPersonalNameToA, subjectPersonalNameRole, subjectPersonalNameDisplay, subjectCorporateName.|
|#### **subjectPersonalName**|   |
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type="personal"].namePart|
|**Islandora Mapping  <br>**|field_subjects_name|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|The individual parsed parts that together make up the full name.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single namePart element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File.|
|**Examples**|Starr, Martha Jane  <br>Cookingham, L. Perry (Laurie Perry)|
|#### **subjectPersonalNameDate**|   |
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type="personal"].namePart[@type="date"]|
|**Islandora Mapping  <br>**|?|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|Used to parse dates that are not integral parts of a name. Dates that are part of a name, e.g. dates within a conference name, do not use this attribute to separate the date, since it is an integral part of the name string. The birthdate associated with a personal name, however, is not an integral part of the name but added to distinguish the name from others, so it does include a separate <namePart> with type="date". This attribute is not used when parsing the components of a corporate name.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element-attribute|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The date(s) are entered as one string in a single namePart[@type="date"] element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File.|
|**Examples**|1906-2011  <br>approximately 1918-2001|
|#### **subjectPersonalNameToA**|   |
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type="personal"].namePart[@type="termsOfAddress"]|
|**Islandora Mapping  <br>**|?|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|Used to record titles and enumeration associated with a name, such as Jr., II, etc.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element-attribute|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The term of address is entered as one string in a single namePart[@type="termsOfAddress"] element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File.|
|**Examples**|Mrs.  <br>Jr.  <br>Baron|
|#### **subjectPersonalNameRole**|   |
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type].role[@type="text"][@authority="marcrelator"].roleTerm|
|**Islandora Mapping  <br>**|field_personal_name_role|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#roleterm](http://www.loc.gov/standards/mods/userguide/name.html#roleterm)|
|**Source Definition**|Designates the relationship (role) of the entity recorded in the name to the resource described in the record.|
|**Encoding Scheme / Controlled Vocab**|[http://www.loc.gov/marc/relators/relaterm.html](http://www.loc.gov/marc/relators/relaterm.html) - MARC Code List for Relators|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|When a MARC relator term is used, it is required to use the term and not the code for the term. When used, this element requires the use of the attributes, @type=”text” and @authority=”marcrelator”.|
|**Examples**|Saxophonist  <br>Publisher|
|#### **subjectPersonalNameDisplay**|   |
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type].displayForm|
|**Islandora Mapping  <br>**|field_subject_personal_name_disp|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#displayform](http://www.loc.gov/standards/mods/userguide/name.html#displayform)|
|**Source Definition**|The unstructured form of the name as given on the resource.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single displayForm element. When possible, names should come from a controlled vocabulary. Highly recommends the use of LC Name Authority File.|
|**Examples**|Sherfield, Roger Mellor Makins, Baron, 1904-1996  <br><br>Starr, Martha Jane, 1906-2011|
|#### **subjectCorporateName**|   |
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type="corporate"].namePart|
|**Islandora Mapping  <br>**|field_corporate_name_name_part|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|The individual parsed parts that together make up the full name.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single namePart element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File.|
|**Examples**|ACE and his Spades  <br>Freedom, Inc.|
|#### **subjectConferenceName**||
|**Element.Subelement[@attribute]**|[subject.name](http://subject.name)[@authority="naf"][@type="conference"].namePart|
|**Islandora Mapping  <br>**|field_conference_name_namepart_|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/name.html#namepart](http://www.loc.gov/standards/mods/userguide/name.html#namepart)|
|**Source Definition**|The individual parsed parts that together make up the full name.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single namePart element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File.|
|**Examples**|Newport Jazz Festival (1956)  <br>Kool Jazz Festival (1979 : New York, N.Y.)|
|### subjectTitle|   |
|**Element.Subelement[@attribute]**|subject.titleInfo[@type="uniform"][@authority="naf"].title|
|**Islandora Mapping  <br>**|field_subject_uniform_title|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html#titleinfo](http://www.loc.gov/standards/mods/userguide/subject.html#titleinfo)|
|**Source Definition**|A title used as a subject.|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The name is entered as one string in a single namePart element. When possible, names should come from a controlled vocabulary. Highly recommend the use of LC Name Authority File.|
|**Examples**|New York post  <br>Art Ford show (Television program)|
|### subjectTemporal|   |
|**Label**|Time Period|
|**Element.Subelement[@attribute]**|subject[@authority="local"].temporal|
|**Islandora Mapping  <br>**|field_temporal_subject|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html#temporal](http://www.loc.gov/standards/mods/userguide/subject.html#temporal)|
|**Source Definition**|Used for chronological subject terms or temporal coverage.|
|**Type of Term**|Element|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Note the date coverage of the resource. Use the LCSH decade format, e.g., 1951-1960.|
|**Examples**|1951-1960  <br>1891-1900|
|### subjectGeographicLocal|   |
|**Label**|Geographic Area (Local)|
|**Element.Subelement[@attribute]**|subject[@authority="local"].geographic|
|**Islandora Mapping  <br>**|field_geographic_subject|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html#geographic](http://www.loc.gov/standards/mods/userguide/subject.html#geographic)|
|**Source Definition**|Used for geographic subject terms that are not appropriate for the <[hierarchicalGeographic](http://www.loc.gov/standards/mods/userguide/subject.html#hierarchicalgeographic)> element.|
|**Encoding Scheme / Controlled Vocab**|[](http://id.loc.gov/authorities/names.html)[http://www.kchistory.org/cdm4/local-subjects-2.php?db=Local&nicks=local&title=Local%20History -](http://www.kchistory.org/cdm4/local-subjects-2.php?db=Local&nicks=local&title=Local%20History) KC Public Library Local History Index|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|If outside the KCMO, then add qualifier: (Kansas City, Kan.), (Olathe, Kan.), etc. for context.|
|**Examples**|Kansas City Metropolitan Area  <br>Troost Avenue|
|### subjectGeographicLCSH|   |
|**Label**|Geographic Area (Other)|
|**Element.Subelement[@attribute]**|subject[@authority="lcsh"].geographic|
|**Islandora Mapping  <br>**|field_geographic_subject_lcsh|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/subject.html#geographic](http://www.loc.gov/standards/mods/userguide/subject.html#geographic)|
|**Source Definition**|Used for geographic subject terms that are not appropriate for the <[hierarchicalGeographic](http://www.loc.gov/standards/mods/userguide/subject.html#hierarchicalgeographic)> element.|
|**DC Mapping**|dc:coverage|
|**Encoding Scheme / Controlled Vocab**|[http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html) - Library of Congress Name Authority File|
|**Type of Term**|Element|
|**Obligation**|REA|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**||
|**Examples**|Kansas City (Mo.)  <br>Washington (D.C.)|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|   |   |
|---|---|
|## host|   |
|**Label**|Digital Collection|
|**Element.Subelement[@attribute]**|relatedItem[@type="host"].note|
|**Islandora Mapping  <br>**|field_collection_name|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/relateditem.html](http://www.loc.gov/standards/mods/userguide/relateditem.html)|
|**Source Definition**|Information that identifies other resources related to the one being described.|
|**DC Mapping**|dc:relation|
|**Type of Term**|Element|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Use the official form of collection name as provided in the Collections_migration.xlsx.|
|**Examples**|Kansas City Sheet Music Collection  <br>Martha Jane Starr Collection|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

  

|   |   |
|---|---|
|## identifier|   |
|**Label**|Filename|
|**Element.Subelement[@attribute]**|identifier[@type="local"]|
|**Islandora Mapping  <br>**|field_identifier|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/identifier.html](http://www.loc.gov/standards/mods/userguide/identifier.html)|
|**Source Definition**|Contains a unique standard number or code that distinctively identifies a resource.|
|**DC Mapping**|dc:identifier|
|**Type of Term**|Element-attribute|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Repository's original filename. This will be used as a match-point for running a batch script for ingest.|
|**Examples**|umkc_lsc_starr_photo-04.tif  <br>umkc_lsc_glama_wilson_photo-101.tif|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

  

|   |   |
|---|---|
|## location|   |
|**Element.Subelement[@attribute]**|location|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/location.html](http://www.loc.gov/standards/mods/userguide/location.html)|
|**Source Definition**|Identifies the institution or repository holding the resource, or the electronic location in the form of a URL where it is available.|
|**Type of Term**|Container element|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Contains collectionURL for digital location and repository for physicalLocation.|
|### collectionURL|   |
|**Element.Subelement[@attribute]**|location.url[@usage="primary display"][@access="object in context"]|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/location.html#url](http://www.loc.gov/standards/mods/userguide/location.html#url)|
|**Source Definition**|Contains the Uniform Resource Location of the resource.|
|**DC Mapping**|dc:identifier|
|**Type of Term**|Element-attribute|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|The URL for the parent collection. Use colon instead of %3A in PID.|
|**Examples**|[http://dl.mospace.umsystem.edu/umkc/islandora/object/umkc:starr](http://dl.mospace.umsystem.edu/umkc/islandora/object/umkc%3Astarr)|
|### repository|   |
|**Label**|Repository|
|**Element.Subelement[@attribute]**|location.physicalLocation|
|**Islandora Mapping  <br>**|field_physical_location|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/location.html#physicallocation](http://www.loc.gov/standards/mods/userguide/location.html#physicallocation)|
|**Source Definition**|The institution or repository that holds the resource or where it is available.|
|**DC Mapping**|dc:coverage|
|**Type of Term**|Element|
|**Obligation**|R|
|**Occurrence**|Repeatable|
|**Guidelines - Best Practices**|Note the repository that holds the analog items. When the name is distinctive use short-form name; when not, include "UMKC".|
|**Examples**|LaBudde Special Collections  <br>UMKC School of Law|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|   |   |
|---|---|
|## rights|   |
|**Label**|Rights|
|**Element.Subelement[@attribute]**|accessCondition[@type="useAndReproduction"]|
|**Islandora Mapping  <br>**|field_rights|
|**Defined by**|[http://www.loc.gov/standards/mods/userguide/accesscondition.html](http://www.loc.gov/standards/mods/userguide/accesscondition.html)|
|**Source Definition**|Information about restrictions imposed on access to a resource.|
|**DC Mapping**|dc:rights|
|**Type of Term**|Element-attribute|
|**Obligation**|R|
|**Occurrence**|Not Repeatable|
|**Guidelines - Best Practices**|Rights statement for each object.|
|**Examples**|All collection images may be freely searched and displayed. Permission must be received for subsequent use and/or distribution in print or electronically. Please contact LaBudde Special Collections for more information.|

[Back to Contents](https://confluence.library.umkc.edu/display/DSC/Still+Images+MAP#StillImagesMAP-Contents)

|                                        |                                                                                                                                                                      |
| -------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ## recordInfo                          |                                                                                                                                                                      |
| **Element.Subelement[@attribute]**     | recordInfo                                                                                                                                                           |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/recordinfo.html](http://www.loc.gov/standards/mods/userguide/recordinfo.html)                                           |
| **Source Definition**                  | Information about the metadata record.                                                                                                                               |
| **Type of Term**                       | Container element                                                                                                                                                    |
| **Obligation**                         | RE                                                                                                                                                                   |
| **Occurrence**                         | Not Repeatable                                                                                                                                                       |
| **Guidelines - Best Practices**        |                                                                                                                                                                      |
| ### recordCreationDate                 |                                                                                                                                                                      |
| **Element.Subelement[@attribute]**     | recordInfo.recordCreationDate[@encoding="w3cdtf"]                                                                                                                    |
| **Islandora Mapping  <br>**            | field_date_created_wc3_dtf                                                                                                                                           |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/recordinfo.html#recordcreationdate](http://www.loc.gov/standards/mods/userguide/recordinfo.html#recordcreationdate)     |
| **Source Definition**                  | The date or date and time on which the original MODS record was first created.                                                                                       |
| **Encoding Scheme / Controlled Vocab** | [](http://id.loc.gov/authorities/names.html)[https://www.w3.org/TR/NOTE-datetime](https://www.w3.org/TR/NOTE-datetime) - W3C-DTF                                     |
| **Type of Term**                       | Element-attribute                                                                                                                                                    |
| **Obligation**                         | RE                                                                                                                                                                   |
| **Occurrence**                         | Not Repeatable                                                                                                                                                       |
| **Guidelines - Best Practices**        | Record date the record was created. Use w3cdtf. Format: YYYY-MM-DD.                                                                                                  |
| **Examples**                           | 2016-01-15                                                                                                                                                           |
| ### recordOrigin                       |                                                                                                                                                                      |
| **Element.Subelement[@attribute]**     | recordInfo.recordOrigin                                                                                                                                              |
| **Islandora Mapping  <br>**            | field_record_origin                                                                                                                                                  |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/recordinfo.html#recordorigin](http://www.loc.gov/standards/mods/userguide/recordinfo.html#recordorigin)                 |
| **Source Definition**                  | Shows the origin or provenance of the MODS record.                                                                                                                   |
| **Type of Term**                       | Element                                                                                                                                                              |
| **Obligation**                         | RE                                                                                                                                                                   |
| **Occurrence**                         | Not Repeatable                                                                                                                                                       |
| **Guidelines - Best Practices**        | Record information about the origin, or provenance of the MODS record including how it was generated and what transformations have been applied.                     |
| **Examples**                           | Record created manually using Microsoft Excel, tab-delimited data, and a parsing script to generate MODS records.                                                    |
| ### languageOfCataloging               |                                                                                                                                                                      |
| **Element.Subelement[@attribute]**     | recordInfo.languageOfCataloging.languageTerm[@authority="iso639-2b"]                                                                                                 |
| **Islandora Mapping  <br>**            | ?                                                                                                                                                                    |
| **Defined by**                         | [http://www.loc.gov/standards/mods/userguide/recordinfo.html#languageofcataloging](http://www.loc.gov/standards/mods/userguide/recordinfo.html#languageofcataloging) |
| **Source Definition**                  | The language of the text of the cataloging in the MODS record.                                                                                                       |
| **Encoding Scheme / Controlled Vocab** | [https://www.loc.gov/standards/iso639-2/php/code_list.php](https://www.loc.gov/standards/iso639-2/php/code_list.php) - ISO 639-2b                                    |
| **Type of Term**                       | Element-attribute                                                                                                                                                    |
| **Obligation**                         | RE                                                                                                                                                                   |
| **Occurrence**                         | Not Repeatable                                                                                                                                                       |
| **Guidelines - Best Practices**        |                                                                                                                                                                      |
| **Examples**                           | eng                                                                                                                                                                  |
|                                        |                                                                                                                                                                      |
