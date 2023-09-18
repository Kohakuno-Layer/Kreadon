## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[22] Kreadon-Demi.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Demi'. Expected OS/2 usWeightClass is 400, got 600. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Kreadon Light | Kreadon Demi |
| Subfamily Name | Bold | Regular |
| Full Name | Kreadon Demi | Kreadon Demi Regular |
| Poscript Name | Kreadon-Demi | KreadonDemi-Regular |
| Typographic Family Name | Kreadon | N/A |
| Typographic Subfamily Name | Demi | N/A | [code: bad-names]
* ⚠ **WARN** Regular missing from full name [code: lacks-regular]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Kreadon Demi' does not begin with the font family name 'Kreadon Light' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<65.0,0.0>--<64.0,733.0>>

	* Beta (U+0392): L<<65.0,0.0>--<64.0,733.0>>

	* Eng (U+014A): L<<71.0,0.0>--<70.0,733.0>>

	* Eta (U+0397): L<<525.0,431.0>--<524.0,733.0>>

	* Etatonos (U+0389): L<<685.0,431.0>--<684.0,733.0>>

	* H (U+0048): L<<525.0,431.0>--<524.0,733.0>>

	* Hcircumflex (U+0124): L<<525.0,431.0>--<524.0,733.0>>

	* M (U+004D): L<<694.0,0.0>--<693.0,437.0>>

	* M (U+004D): L<<71.0,0.0>--<70.0,733.0>>

	* Mu (U+039C): L<<694.0,0.0>--<693.0,437.0>>

	* Mu (U+039C): L<<71.0,0.0>--<70.0,733.0>>

	* N (U+004E): L<<71.0,0.0>--<70.0,733.0>>

	* Nacute (U+0143): L<<71.0,0.0>--<70.0,733.0>>

	* Ncaron (U+0147): L<<71.0,0.0>--<70.0,733.0>>

	* Ntilde (U+00D1): L<<71.0,0.0>--<70.0,733.0>>

	* Nu (U+039D): L<<71.0,0.0>--<70.0,733.0>>

	* Phi (U+03A6): L<<368.0,99.0>--<367.0,636.0>>

	* Psi (U+03A8): L<<341.0,234.0>--<340.0,733.0>>

	* eng (U+014B): L<<157.0,363.0>--<156.0,0.0>>

	* ij (U+0133): L<<313.0,-40.0>--<312.0,470.0>>

	* ij (U+0133): L<<411.0,470.0>--<410.0,-84.0>>

	* j (U+006A): L<<113.0,-40.0>--<112.0,470.0>>

	* j (U+006A): L<<211.0,470.0>--<210.0,-84.0>>

	* jcircumflex (U+0135): L<<113.0,-40.0>--<112.0,470.0>>

	* jcircumflex (U+0135): L<<211.0,470.0>--<210.0,-84.0>>

	* trademark (U+2122): L<<261.0,470.0>--<260.0,733.0>>

	* uni0145 (U+0145): L<<71.0,0.0>--<70.0,733.0>>

	* uni0237 (U+0237): L<<113.0,-40.0>--<112.0,470.0>>

	* uni0237 (U+0237): L<<211.0,470.0>--<210.0,-84.0>>

	* uni040D (U+040D): L<<643.0,733.0>--<642.0,0.0>>

	* uni0412 (U+0412): L<<65.0,0.0>--<64.0,733.0>>

	* uni0418 (U+0418): L<<643.0,733.0>--<642.0,0.0>>

	* uni0419 (U+0419): L<<643.0,733.0>--<642.0,0.0>>

	* uni041C (U+041C): L<<694.0,0.0>--<693.0,437.0>>

	* uni041C (U+041C): L<<71.0,0.0>--<70.0,733.0>>

	* uni041D (U+041D): L<<525.0,431.0>--<524.0,733.0>>

	* uni0424 (U+0424): L<<368.0,99.0>--<367.0,636.0>>

	* uni0426 (U+0426): L<<174.0,733.0>--<176.0,99.0>>

	* uni0426 (U+0426): L<<65.0,0.0>--<63.0,733.0>>

	* uni0427 (U+0427): L<<469.0,380.0>--<468.0,733.0>>

	* uni043C (U+043C): L<<485.0,0.0>--<484.0,223.0>>

	* uni043C (U+043C): L<<53.0,0.0>--<52.0,470.0>>

	* uni0E3F (U+0E3F): L<<65.0,0.0>--<64.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] Kreadon-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment L<<594.0,484.0>--<594.0,507.0>>

	* G (U+0047) contains a short segment B<<785.0,364.0>-<785.0,360.0>-<785.0,356.0>>

	* G (U+0047) contains a short segment B<<785.0,356.0>-<785.0,352.0>-<785.0,349.0>>

	* a (U+0061) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* b (U+0062) contains a short segment L<<119.0,10.0>--<119.0,0.0>>

	* d (U+0064) contains a short segment L<<461.0,0.0>--<461.0,10.0>>

	* g (U+0067) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* p (U+0070) contains a short segment L<<119.0,470.0>--<119.0,460.0>>

	* q (U+0071) contains a short segment L<<461.0,460.0>--<461.0,470.0>>

	* ordfeminine (U+00AA) contains a short segment L<<232.0,500.0>--<232.0,504.0>>

	* uni00B2 (U+00B2) contains a short segment L<<89.0,501.0>--<98.0,502.0>>

	* onehalf (U+00BD) contains a short segment L<<687.0,34.0>--<696.0,35.0>>

	* agrave (U+00E0) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* aacute (U+00E1) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* acircumflex (U+00E2) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* atilde (U+00E3) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* adieresis (U+00E4) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* aring (U+00E5) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* ae (U+00E6) contains a short segment B<<907.0,243.0>-<907.0,236.0>-<907.0,228.0>>

	* ae (U+00E6) contains a short segment B<<907.0,228.0>-<907.0,220.0>-<906.0,214.0>>

	* amacron (U+0101) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* abreve (U+0103) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* aogonek (U+0105) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* dcaron (U+010F) contains a short segment L<<461.0,0.0>--<461.0,10.0>>

	* dcroat (U+0111) contains a short segment L<<461.0,0.0>--<461.0,10.0>>

	* Gcircumflex (U+011C) contains a short segment B<<785.0,364.0>-<785.0,360.0>-<785.0,356.0>>

	* Gcircumflex (U+011C) contains a short segment B<<785.0,356.0>-<785.0,352.0>-<785.0,349.0>>

	* gcircumflex (U+011D) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* Gbreve (U+011E) contains a short segment B<<785.0,364.0>-<785.0,360.0>-<785.0,356.0>>

	* Gbreve (U+011E) contains a short segment B<<785.0,356.0>-<785.0,352.0>-<785.0,349.0>>

	* gbreve (U+011F) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* Gdotaccent (U+0120) contains a short segment B<<785.0,364.0>-<785.0,360.0>-<785.0,356.0>>

	* Gdotaccent (U+0120) contains a short segment B<<785.0,356.0>-<785.0,352.0>-<785.0,349.0>>

	* gdotaccent (U+0121) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* uni0122 (U+0122) contains a short segment B<<785.0,364.0>-<785.0,360.0>-<785.0,356.0>>

	* uni0122 (U+0122) contains a short segment B<<785.0,356.0>-<785.0,352.0>-<785.0,349.0>>

	* uni0123 (U+0123) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* jcircumflex (U+0135) contains a short segment B<<35.0,-177.5>-<40.0,-178.0>-<44.0,-178.0>>

	* lslash (U+0142) contains a short segment B<<228.0,43.0>-<232.0,43.0>-<238.5,43.5>>

	* Eng (U+014A) contains a short segment B<<410.0,-228.0>-<394.0,-228.0>-<380.5,-226.5>>

	* Eng (U+014A) contains a short segment B<<380.5,-226.5>-<367.0,-225.0>-<359.0,-223.0>>

	* Eng (U+014A) contains a short segment B<<373.0,-169.0>-<383.0,-171.0>-<404.0,-171.0>>

	* eng (U+014B) contains a short segment B<<295.0,-175.0>-<303.0,-177.0>-<308.0,-177.5>>

	* eng (U+014B) contains a short segment B<<308.0,-177.5>-<313.0,-178.0>-<318.0,-178.0>>

	* oe (U+0153) contains a short segment B<<961.0,243.0>-<961.0,236.0>-<961.0,228.5>>

	* oe (U+0153) contains a short segment B<<961.0,228.5>-<961.0,221.0>-<960.0,215.0>>

	* uni018F (U+018F) contains a short segment B<<55.0,349.0>-<55.0,352.0>-<55.0,356.0>>

	* uni018F (U+018F) contains a short segment B<<55.0,356.0>-<55.0,360.0>-<56.0,364.0>>

	* uni018F (U+018F) contains a short segment L<<729.0,364.0>--<730.0,366.0>>

	* uni01CE (U+01CE) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni0237 (U+0237) contains a short segment B<<35.0,-177.5>-<40.0,-178.0>-<44.0,-178.0>>

	* alphatonos (U+03AC) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* alpha (U+03B1) contains a short segment L<<461.0,458.0>--<461.0,470.0>>

	* xi (U+03BE) contains a short segment B<<350.0,417.0>-<359.0,417.0>-<368.5,416.0>>

	* xi (U+03BE) contains a short segment B<<368.5,416.0>-<378.0,415.0>-<388.0,415.0>>

	* xi (U+03BE) contains a short segment B<<388.0,357.0>-<378.0,357.0>-<368.5,356.0>>

	* xi (U+03BE) contains a short segment B<<368.5,356.0>-<359.0,355.0>-<350.0,355.0>>

	* pi (U+03C0) contains a short segment B<<476.0,45.0>-<483.0,45.0>-<493.0,46.0>>

	* uni03D7 (U+03D7) contains a short segment B<<310.0,-175.0>-<318.0,-177.0>-<323.0,-177.5>>

	* uni03D7 (U+03D7) contains a short segment B<<323.0,-177.5>-<328.0,-178.0>-<332.0,-178.0>>

	* uni0411 (U+0411) contains a short segment B<<293.5,380.0>-<285.0,380.0>-<274.0,380.0>>

	* uni0414 (U+0414) contains a short segment L<<43.0,57.0>--<61.0,57.0>>

	* uni042A (U+042A) contains a short segment B<<298.5,412.0>-<290.0,412.0>-<280.0,412.0>>

	* uni042B (U+042B) contains a short segment B<<281.5,412.0>-<273.0,412.0>-<262.0,412.0>>

	* uni042C (U+042C) contains a short segment B<<281.5,412.0>-<273.0,412.0>-<262.0,412.0>>

	* uni0430 (U+0430) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni0440 (U+0440) contains a short segment L<<119.0,470.0>--<119.0,460.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<314.0,356.0>-<304.0,357.0>-<294.0,357.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<294.0,357.5>-<284.0,358.0>-<274.0,358.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<274.0,417.0>-<284.0,417.0>-<294.0,417.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<294.0,417.5>-<304.0,418.0>-<314.0,419.0>>

	* uni1EA1 (U+1EA1) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EA3 (U+1EA3) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EA5 (U+1EA5) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EA7 (U+1EA7) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EA9 (U+1EA9) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EAB (U+1EAB) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EAD (U+1EAD) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EAF (U+1EAF) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EB1 (U+1EB1) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EB3 (U+1EB3) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EB5 (U+1EB5) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni1EB7 (U+1EB7) contains a short segment L<<463.0,0.0>--<463.0,8.0>>

	* uni2082 (U+2082) contains a short segment L<<89.0,-66.0>--<98.0,-65.0>>

	* dong (U+20AB) contains a short segment L<<461.0,0.0>--<461.0,10.0>>

	* uni20B4 (U+20B4) contains a short segment B<<279.0,355.0>-<267.0,351.0>-<256.0,347.0>>

	* uni2154 (U+2154) contains a short segment L<<196.0,396.0>--<205.0,397.0>>

	* uni2156 (U+2156) contains a short segment L<<196.0,399.0>--<205.0,400.0>>

	* integral (U+222B) contains a short segment B<<412.0,695.5>-<407.0,696.0>-<402.0,696.0>>

	* integral (U+222B) contains a short segment B<<77.5,-74.5>-<83.0,-75.0>-<87.0,-75.0>>

	* fl (U+FB02) contains a short segment B<<438.0,43.0>-<442.0,43.0>-<448.5,43.5>> 

	* fl (U+FB02) contains a short segment B<<448.5,43.5>-<455.0,44.0>-<462.0,46.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<71.0,0.0>--<70.0,733.0>>

	* Beta (U+0392): L<<71.0,0.0>--<70.0,733.0>>

	* D (U+0044): L<<128.0,675.0>--<129.0,62.0>>

	* Dcaron (U+010E): L<<128.0,675.0>--<129.0,62.0>>

	* Eng (U+014A): L<<76.0,0.0>--<75.0,733.0>>

	* Eta (U+0397): L<<540.0,411.0>--<539.0,733.0>>

	* Etatonos (U+0389): L<<650.0,411.0>--<649.0,733.0>>

	* H (U+0048): L<<540.0,411.0>--<539.0,733.0>>

	* Hbar (U+0126): L<<545.0,411.0>--<544.0,575.0>>

	* Hcircumflex (U+0124): L<<540.0,411.0>--<539.0,733.0>>

	* M (U+004D): L<<693.0,0.0>--<692.0,545.0>>

	* Mu (U+039C): L<<693.0,0.0>--<692.0,545.0>>

	* N (U+004E): L<<76.0,0.0>--<75.0,733.0>>

	* Nacute (U+0143): L<<76.0,0.0>--<75.0,733.0>>

	* Ncaron (U+0147): L<<76.0,0.0>--<75.0,733.0>>

	* Ntilde (U+00D1): L<<76.0,0.0>--<75.0,733.0>>

	* Nu (U+039D): L<<76.0,0.0>--<75.0,733.0>>

	* Phi (U+03A6): L<<393.0,48.0>--<392.0,687.0>>

	* Psi (U+03A8): L<<362.0,0.0>--<361.0,135.0>>

	* asterisk (U+002A): L<<241.0,577.0>--<242.0,456.0>>

	* asterisk (U+002A): L<<242.0,777.0>--<241.0,656.0>>

	* at (U+0040): L<<645.0,507.0>--<644.0,358.0>>

	* eng (U+014B): L<<116.0,402.0>--<115.0,0.0>>

	* ij (U+0133): L<<264.0,-60.0>--<263.0,470.0>>

	* ij (U+0133): L<<317.0,470.0>--<316.0,-91.0>>

	* j (U+006A): L<<114.0,-60.0>--<113.0,470.0>>

	* j (U+006A): L<<167.0,470.0>--<166.0,-91.0>>

	* jcircumflex (U+0135): L<<116.0,-60.0>--<115.0,470.0>>

	* jcircumflex (U+0135): L<<169.0,470.0>--<168.0,-91.0>>

	* sterling (U+00A3): L<<365.0,350.0>--<192.0,349.0>>

	* trademark (U+2122): L<<261.0,470.0>--<260.0,733.0>>

	* uni0145 (U+0145): L<<76.0,0.0>--<75.0,733.0>>

	* uni0237 (U+0237): L<<116.0,-60.0>--<115.0,470.0>>

	* uni0237 (U+0237): L<<169.0,470.0>--<168.0,-91.0>>

	* uni040D (U+040D): L<<610.0,733.0>--<609.0,0.0>>

	* uni0412 (U+0412): L<<71.0,0.0>--<70.0,733.0>>

	* uni0418 (U+0418): L<<610.0,733.0>--<609.0,0.0>>

	* uni0419 (U+0419): L<<610.0,733.0>--<609.0,0.0>>

	* uni041C (U+041C): L<<693.0,0.0>--<692.0,545.0>>

	* uni041D (U+041D): L<<540.0,411.0>--<539.0,733.0>>

	* uni0424 (U+0424): L<<393.0,48.0>--<392.0,687.0>>

	* uni0426 (U+0426): L<<127.0,733.0>--<129.0,55.0>>

	* uni0426 (U+0426): L<<72.0,0.0>--<70.0,733.0>>

	* uni0427 (U+0427): L<<486.0,360.0>--<485.0,733.0>>

	* uni043C (U+043C): L<<479.0,0.0>--<478.0,310.0>>

	* uni043C (U+043C): L<<60.0,0.0>--<59.0,470.0>>

	* uni0E3F (U+0E3F): L<<71.0,0.0>--<70.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Kreadon-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment L<<608.0,502.0>--<608.0,512.0>>

	* a (U+0061) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* a (U+0061) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* b (U+0062) contains a short segment L<<187.0,8.0>--<187.0,0.0>>

	* d (U+0064) contains a short segment L<<409.0,0.0>--<409.0,8.0>>

	* g (U+0067) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* p (U+0070) contains a short segment L<<187.0,470.0>--<187.0,462.0>>

	* q (U+0071) contains a short segment L<<419.0,462.0>--<419.0,470.0>>

	* ordfeminine (U+00AA) contains a short segment L<<205.0,730.0>--<205.0,735.0>>

	* ordfeminine (U+00AA) contains a short segment L<<207.0,500.0>--<207.0,503.0>>

	* germandbls (U+00DF) contains a short segment B<<328.0,333.0>-<316.0,333.0>-<304.5,334.0>>

	* germandbls (U+00DF) contains a short segment B<<304.5,334.0>-<293.0,335.0>-<282.0,335.0>>

	* germandbls (U+00DF) contains a short segment B<<282.0,452.0>-<293.0,452.0>-<304.5,452.5>>

	* germandbls (U+00DF) contains a short segment B<<304.5,452.5>-<316.0,453.0>-<328.0,454.0>>

	* agrave (U+00E0) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* agrave (U+00E0) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* aacute (U+00E1) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* aacute (U+00E1) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* acircumflex (U+00E2) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* acircumflex (U+00E2) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* atilde (U+00E3) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* atilde (U+00E3) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* adieresis (U+00E4) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* adieresis (U+00E4) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* aring (U+00E5) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* aring (U+00E5) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* ae (U+00E6) contains a short segment B<<903.0,233.0>-<903.0,221.0>-<902.5,212.5>>

	* ae (U+00E6) contains a short segment B<<902.5,212.5>-<902.0,204.0>-<902.0,193.0>>

	* amacron (U+0101) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* amacron (U+0101) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* abreve (U+0103) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* abreve (U+0103) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* aogonek (U+0105) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* aogonek (U+0105) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* dcaron (U+010F) contains a short segment L<<409.0,0.0>--<409.0,8.0>>

	* dcroat (U+0111) contains a short segment L<<409.0,0.0>--<409.0,8.0>>

	* gcircumflex (U+011D) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* gbreve (U+011F) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* gdotaccent (U+0121) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni0123 (U+0123) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni01CE (U+01CE) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni01CE (U+01CE) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* alphatonos (U+03AC) contains a short segment L<<418.0,458.0>--<418.0,470.0>>

	* alpha (U+03B1) contains a short segment L<<418.0,458.0>--<418.0,470.0>>

	* uni0430 (U+0430) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni0430 (U+0430) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni0440 (U+0440) contains a short segment L<<187.0,470.0>--<187.0,462.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<371.0,326.0>-<359.0,327.0>-<347.5,327.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<347.5,327.5>-<336.0,328.0>-<325.0,328.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<325.0,445.0>-<336.0,445.0>-<347.5,445.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<347.5,445.5>-<359.0,446.0>-<371.0,447.0>>

	* uni1EA1 (U+1EA1) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EA1 (U+1EA1) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EA3 (U+1EA3) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EA3 (U+1EA3) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EA5 (U+1EA5) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EA5 (U+1EA5) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EA7 (U+1EA7) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EA7 (U+1EA7) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EA9 (U+1EA9) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EA9 (U+1EA9) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EAB (U+1EAB) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EAB (U+1EAB) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EAD (U+1EAD) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EAD (U+1EAD) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EAF (U+1EAF) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EAF (U+1EAF) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EB1 (U+1EB1) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EB1 (U+1EB1) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EB3 (U+1EB3) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EB3 (U+1EB3) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EB5 (U+1EB5) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EB5 (U+1EB5) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni1EB7 (U+1EB7) contains a short segment L<<409.0,461.0>--<409.0,470.0>>

	* uni1EB7 (U+1EB7) contains a short segment L<<413.0,0.0>--<413.0,5.0>>

	* uni2076 (U+2076) contains a short segment B<<148.0,694.0>-<151.0,694.0>-<154.0,694.0>>

	* uni2079 (U+2079) contains a short segment L<<158.0,604.0>--<155.0,604.0>>

	* uni2086 (U+2086) contains a short segment B<<148.0,127.0>-<151.0,127.0>-<154.0,127.0>>

	* uni2089 (U+2089) contains a short segment L<<158.0,37.0>--<155.0,37.0>>

	* dong (U+20AB) contains a short segment L<<409.0,0.0>--<409.0,8.0>>

	* Euro (U+20AC) contains a short segment B<<76.0,368.0>-<76.0,381.0>-<77.0,393.0>>

	* Euro (U+20AC) contains a short segment B<<225.0,393.0>-<224.0,381.0>-<224.0,368.0>>

	* uni20BD (U+20BD) contains a short segment B<<339.0,260.5>-<330.0,261.0>-<318.0,261.0>>

	* uni2151 (U+2151) contains a short segment L<<753.0,137.0>--<750.0,137.0>>

	* uni2159 (U+2159) contains a short segment B<<742.0,231.0>-<745.0,231.0>-<748.0,231.0>>

	* uni215A (U+215A) contains a short segment B<<735.0,231.0>-<738.0,231.0>-<741.0,231.0>>

	* fl (U+FB02) contains a short segment B<<557.0,104.0>-<566.0,104.0>-<575.0,105.0>> 

	* fl (U+FB02) contains a short segment B<<575.0,105.0>-<584.0,106.0>-<594.0,110.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0432 (U+0432): B<<452.5,281.0>-<435.0,251.0>-<399.0,246.0>>/B<<399.0,246.0>-<437.0,242.0>-<469.0,213.5>> = 13.916168660452962 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<65.0,1.0>--<64.0,733.0>>

	* Beta (U+0392): L<<65.0,1.0>--<64.0,733.0>>

	* Eng (U+014A): L<<71.0,0.0>--<70.0,733.0>>

	* Eta (U+0397): L<<525.0,441.0>--<524.0,733.0>>

	* Etatonos (U+0389): L<<715.0,441.0>--<714.0,733.0>>

	* H (U+0048): L<<525.0,441.0>--<524.0,733.0>>

	* Hcircumflex (U+0124): L<<525.0,441.0>--<524.0,733.0>>

	* M (U+004D): L<<696.0,0.0>--<695.0,333.0>>

	* M (U+004D): L<<71.0,0.0>--<70.0,733.0>>

	* Mu (U+039C): L<<696.0,0.0>--<695.0,333.0>>

	* Mu (U+039C): L<<71.0,0.0>--<70.0,733.0>>

	* N (U+004E): L<<71.0,0.0>--<70.0,733.0>>

	* Nacute (U+0143): L<<71.0,0.0>--<70.0,733.0>>

	* Ncaron (U+0147): L<<71.0,0.0>--<70.0,733.0>>

	* Ntilde (U+00D1): L<<71.0,0.0>--<70.0,733.0>>

	* Nu (U+039D): L<<71.0,0.0>--<70.0,733.0>>

	* Omegatonos (U+038F): L<<475.0,115.0>--<474.0,0.0>>

	* Phi (U+03A6): L<<358.0,127.0>--<357.0,607.0>>

	* ij (U+0133): L<<353.0,-20.0>--<352.0,470.0>>

	* ij (U+0133): L<<477.0,470.0>--<476.0,-68.0>>

	* j (U+006A): L<<123.0,-20.0>--<122.0,470.0>>

	* j (U+006A): L<<247.0,470.0>--<246.0,-68.0>>

	* jcircumflex (U+0135): L<<123.0,-20.0>--<122.0,470.0>>

	* jcircumflex (U+0135): L<<247.0,470.0>--<246.0,-68.0>>

	* trademark (U+2122): L<<266.0,470.0>--<265.0,733.0>>

	* uni0145 (U+0145): L<<71.0,0.0>--<70.0,733.0>>

	* uni0237 (U+0237): L<<123.0,-20.0>--<122.0,470.0>>

	* uni0237 (U+0237): L<<247.0,470.0>--<246.0,-68.0>>

	* uni03A9 (U+03A9): L<<365.0,115.0>--<364.0,0.0>>

	* uni040D (U+040D): L<<677.0,733.0>--<676.0,0.0>>

	* uni0412 (U+0412): L<<65.0,1.0>--<64.0,733.0>>

	* uni0418 (U+0418): L<<677.0,733.0>--<676.0,0.0>>

	* uni0419 (U+0419): L<<677.0,733.0>--<676.0,0.0>>

	* uni041C (U+041C): L<<696.0,0.0>--<695.0,333.0>>

	* uni041C (U+041C): L<<71.0,0.0>--<70.0,733.0>>

	* uni041D (U+041D): L<<525.0,441.0>--<524.0,733.0>>

	* uni0424 (U+0424): L<<358.0,127.0>--<357.0,607.0>>

	* uni0426 (U+0426): L<<208.0,733.0>--<210.0,123.0>>

	* uni0426 (U+0426): L<<65.0,0.0>--<63.0,733.0>>

	* uni0427 (U+0427): L<<469.0,391.0>--<468.0,733.0>>

	* uni043C (U+043C): L<<501.0,0.0>--<500.0,177.0>>

	* uni043C (U+043C): L<<53.0,0.0>--<52.0,470.0>>

	* uni0E3F (U+0E3F): L<<65.0,1.0>--<64.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Kreadon-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Kreadon Extra Light | Kreadon Medium |
| Subfamily Name | Bold | Regular |
| Full Name | Kreadon Medium | Kreadon Medium |
| Poscript Name | Kreadon-Medium | Kreadon-Medium |
| Typographic Family Name | Kreadon | Kreadon |
| Typographic Subfamily Name | Medium | Medium | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle BOLD bit should be unset. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be set. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be unset. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Kreadon Medium' does not begin with the font family name 'Kreadon Extra Light' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment L<<581.0,502.0>--<581.0,512.0>>

	* G (U+0047) contains a short segment B<<779.0,374.0>-<780.0,368.0>-<780.0,361.5>>

	* G (U+0047) contains a short segment B<<780.0,361.5>-<780.0,355.0>-<780.0,349.0>>

	* N (U+004E) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* N (U+004E) contains a short segment L<<149.0,617.0>--<149.0,592.0>>

	* a (U+0061) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* b (U+0062) contains a short segment L<<134.0,11.0>--<134.0,0.0>>

	* d (U+0064) contains a short segment L<<436.0,0.0>--<436.0,11.0>>

	* g (U+0067) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* p (U+0070) contains a short segment L<<134.0,470.0>--<134.0,458.0>>

	* q (U+0071) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* ordfeminine (U+00AA) contains a short segment L<<220.0,500.0>--<220.0,504.0>>

	* uni00B2 (U+00B2) contains a short segment L<<103.0,512.0>--<109.0,512.0>>

	* onehalf (U+00BD) contains a short segment L<<699.0,45.0>--<705.0,45.0>>

	* Ntilde (U+00D1) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* Ntilde (U+00D1) contains a short segment L<<149.0,617.0>--<149.0,592.0>>

	* germandbls (U+00DF) contains a short segment B<<310.0,346.0>-<298.0,347.0>-<286.0,347.5>>

	* germandbls (U+00DF) contains a short segment B<<286.0,347.5>-<274.0,348.0>-<262.0,348.0>>

	* germandbls (U+00DF) contains a short segment B<<262.0,425.0>-<274.0,425.0>-<286.0,425.5>>

	* germandbls (U+00DF) contains a short segment B<<286.0,425.5>-<298.0,426.0>-<310.0,427.0>>

	* agrave (U+00E0) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* aacute (U+00E1) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* acircumflex (U+00E2) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* atilde (U+00E3) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* adieresis (U+00E4) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* aring (U+00E5) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* ae (U+00E6) contains a short segment B<<896.0,233.0>-<896.0,226.0>-<896.0,219.0>>

	* ae (U+00E6) contains a short segment B<<896.0,219.0>-<896.0,212.0>-<895.0,205.0>>

	* amacron (U+0101) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* abreve (U+0103) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* aogonek (U+0105) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* dcaron (U+010F) contains a short segment L<<436.0,0.0>--<436.0,11.0>>

	* dcroat (U+0111) contains a short segment L<<436.0,0.0>--<436.0,11.0>>

	* Gcircumflex (U+011C) contains a short segment B<<779.0,374.0>-<780.0,368.0>-<780.0,361.5>>

	* Gcircumflex (U+011C) contains a short segment B<<780.0,361.5>-<780.0,355.0>-<780.0,349.0>>

	* gcircumflex (U+011D) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* Gbreve (U+011E) contains a short segment B<<779.0,374.0>-<780.0,368.0>-<780.0,361.5>>

	* Gbreve (U+011E) contains a short segment B<<780.0,361.5>-<780.0,355.0>-<780.0,349.0>>

	* gbreve (U+011F) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* Gdotaccent (U+0120) contains a short segment B<<779.0,374.0>-<780.0,368.0>-<780.0,361.5>>

	* Gdotaccent (U+0120) contains a short segment B<<780.0,361.5>-<780.0,355.0>-<780.0,349.0>>

	* gdotaccent (U+0121) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* uni0122 (U+0122) contains a short segment B<<779.0,374.0>-<780.0,368.0>-<780.0,361.5>>

	* uni0122 (U+0122) contains a short segment B<<780.0,361.5>-<780.0,355.0>-<780.0,349.0>>

	* uni0123 (U+0123) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* Nacute (U+0143) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* Nacute (U+0143) contains a short segment L<<149.0,617.0>--<149.0,592.0>>

	* uni0145 (U+0145) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* uni0145 (U+0145) contains a short segment L<<149.0,617.0>--<149.0,592.0>>

	* Ncaron (U+0147) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* Ncaron (U+0147) contains a short segment L<<149.0,617.0>--<149.0,592.0>>

	* Eng (U+014A) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* Eng (U+014A) contains a short segment B<<369.0,-230.5>-<352.0,-228.0>-<344.0,-225.0>>

	* eng (U+014B) contains a short segment B<<307.0,-157.0>-<314.0,-158.0>-<319.0,-158.0>>

	* oe (U+0153) contains a short segment B<<936.0,233.0>-<936.0,226.0>-<936.0,219.0>>

	* oe (U+0153) contains a short segment B<<936.0,219.0>-<936.0,212.0>-<935.0,205.0>>

	* uni018F (U+018F) contains a short segment B<<50.0,349.0>-<50.0,355.0>-<50.0,361.5>>

	* uni018F (U+018F) contains a short segment B<<50.0,361.5>-<50.0,368.0>-<51.0,374.0>>

	* uni01CE (U+01CE) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* Nu (U+039D) contains a short segment L<<533.0,115.0>--<532.0,141.0>>

	* Nu (U+039D) contains a short segment L<<149.0,617.0>--<149.0,592.0>>

	* alphatonos (U+03AC) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* alpha (U+03B1) contains a short segment L<<436.0,458.0>--<436.0,470.0>>

	* pi (U+03C0) contains a short segment B<<471.0,66.0>-<476.0,66.0>-<484.5,67.0>>

	* uni03D7 (U+03D7) contains a short segment B<<301.0,-153.0>-<314.0,-156.0>-<321.0,-157.0>>

	* uni03D7 (U+03D7) contains a short segment B<<321.0,-157.0>-<328.0,-158.0>-<333.0,-158.0>>

	* uni040D (U+040D) contains a short segment L<<531.0,592.0>--<531.0,617.0>>

	* uni040D (U+040D) contains a short segment L<<148.0,141.0>--<147.0,115.0>>

	* uni0411 (U+0411) contains a short segment B<<289.0,367.0>-<281.0,367.0>-<267.0,366.0>>

	* uni0418 (U+0418) contains a short segment L<<531.0,592.0>--<531.0,617.0>>

	* uni0418 (U+0418) contains a short segment L<<148.0,141.0>--<147.0,115.0>>

	* uni0419 (U+0419) contains a short segment L<<531.0,592.0>--<531.0,617.0>>

	* uni0419 (U+0419) contains a short segment L<<148.0,141.0>--<147.0,115.0>>

	* uni0430 (U+0430) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni0440 (U+0440) contains a short segment L<<134.0,470.0>--<134.0,458.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<320.0,346.0>-<308.0,347.0>-<296.0,347.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<296.0,347.5>-<284.0,348.0>-<272.0,348.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<272.0,425.0>-<284.0,425.0>-<296.0,425.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<296.0,425.5>-<308.0,426.0>-<320.0,427.0>>

	* uni1EA1 (U+1EA1) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EA3 (U+1EA3) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EA5 (U+1EA5) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EA7 (U+1EA7) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EA9 (U+1EA9) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EAB (U+1EAB) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EAD (U+1EAD) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EAF (U+1EAF) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EB1 (U+1EB1) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EB3 (U+1EB3) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EB5 (U+1EB5) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni1EB7 (U+1EB7) contains a short segment L<<440.0,0.0>--<440.0,8.0>>

	* uni2082 (U+2082) contains a short segment L<<103.0,-55.0>--<109.0,-55.0>>

	* dong (U+20AB) contains a short segment L<<436.0,0.0>--<436.0,11.0>>

	* uni2154 (U+2154) contains a short segment L<<208.0,407.0>--<214.0,407.0>>

	* uni2156 (U+2156) contains a short segment L<<208.0,412.0>--<214.0,412.0>> 

	* fl (U+FB02) contains a short segment B<<462.5,-12.5>-<452.0,-14.0>-<442.0,-14.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<65.0,0.0>--<64.0,733.0>>

	* Beta (U+0392): L<<65.0,0.0>--<64.0,733.0>>

	* Eng (U+014A): L<<71.0,0.0>--<70.0,733.0>>

	* Eta (U+0397): L<<525.0,421.0>--<524.0,733.0>>

	* Etatonos (U+0389): L<<655.0,421.0>--<654.0,733.0>>

	* H (U+0048): L<<525.0,421.0>--<524.0,733.0>>

	* Hcircumflex (U+0124): L<<525.0,421.0>--<524.0,733.0>>

	* M (U+004D): L<<692.0,0.0>--<691.0,540.0>>

	* M (U+004D): L<<71.0,0.0>--<70.0,733.0>>

	* Mu (U+039C): L<<692.0,0.0>--<691.0,540.0>>

	* Mu (U+039C): L<<71.0,0.0>--<70.0,733.0>>

	* N (U+004E): L<<71.0,0.0>--<70.0,733.0>>

	* Nacute (U+0143): L<<71.0,0.0>--<70.0,733.0>>

	* Ncaron (U+0147): L<<71.0,0.0>--<70.0,733.0>>

	* Ntilde (U+00D1): L<<71.0,0.0>--<70.0,733.0>>

	* Nu (U+039D): L<<71.0,0.0>--<70.0,733.0>>

	* Phi (U+03A6): L<<378.0,71.0>--<377.0,664.0>>

	* Psi (U+03A8): L<<346.0,212.0>--<345.0,733.0>>

	* asterisk (U+002A): L<<257.0,566.0>--<258.0,450.0>>

	* asterisk (U+002A): L<<258.0,783.0>--<257.0,667.0>>

	* eng (U+014B): L<<131.0,380.0>--<130.0,0.0>>

	* ij (U+0133): L<<273.0,-60.0>--<272.0,470.0>>

	* ij (U+0133): L<<344.0,470.0>--<343.0,-101.0>>

	* j (U+006A): L<<103.0,-60.0>--<102.0,470.0>>

	* j (U+006A): L<<174.0,470.0>--<173.0,-101.0>>

	* jcircumflex (U+0135): L<<103.0,-60.0>--<102.0,470.0>>

	* jcircumflex (U+0135): L<<174.0,470.0>--<173.0,-101.0>>

	* trademark (U+2122): L<<255.0,470.0>--<254.0,733.0>>

	* uni0145 (U+0145): L<<71.0,0.0>--<70.0,733.0>>

	* uni0237 (U+0237): L<<103.0,-60.0>--<102.0,470.0>>

	* uni0237 (U+0237): L<<174.0,470.0>--<173.0,-101.0>>

	* uni040D (U+040D): L<<610.0,733.0>--<609.0,0.0>>

	* uni0412 (U+0412): L<<65.0,0.0>--<64.0,733.0>>

	* uni0418 (U+0418): L<<610.0,733.0>--<609.0,0.0>>

	* uni0419 (U+0419): L<<610.0,733.0>--<609.0,0.0>>

	* uni041C (U+041C): L<<692.0,0.0>--<691.0,540.0>>

	* uni041C (U+041C): L<<71.0,0.0>--<70.0,733.0>>

	* uni041D (U+041D): L<<525.0,421.0>--<524.0,733.0>>

	* uni0424 (U+0424): L<<378.0,71.0>--<377.0,664.0>>

	* uni0426 (U+0426): L<<141.0,733.0>--<143.0,76.0>>

	* uni0426 (U+0426): L<<65.0,0.0>--<63.0,733.0>>

	* uni0427 (U+0427): L<<469.0,368.0>--<468.0,733.0>>

	* uni043C (U+043C): L<<468.0,0.0>--<467.0,270.0>>

	* uni043C (U+043C): L<<53.0,0.0>--<52.0,470.0>>

	* uni0E3F (U+0E3F): L<<65.0,0.0>--<64.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] Kreadon-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment L<<587.0,493.0>--<587.0,509.0>>

	* G (U+0047) contains a short segment B<<782.0,369.0>-<782.0,364.0>-<782.0,359.0>>

	* G (U+0047) contains a short segment B<<782.0,359.0>-<782.0,354.0>-<782.0,349.0>>

	* a (U+0061) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* b (U+0062) contains a short segment L<<127.0,10.0>--<127.0,0.0>>

	* d (U+0064) contains a short segment L<<448.0,0.0>--<448.0,10.0>>

	* g (U+0067) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* p (U+0070) contains a short segment L<<127.0,470.0>--<127.0,459.0>>

	* q (U+0071) contains a short segment L<<448.0,459.0>--<448.0,470.0>>

	* ordfeminine (U+00AA) contains a short segment L<<225.0,500.0>--<225.0,504.0>>

	* uni00B2 (U+00B2) contains a short segment L<<96.0,507.0>--<104.0,507.0>>

	* onehalf (U+00BD) contains a short segment L<<693.0,40.0>--<701.0,40.0>>

	* agrave (U+00E0) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* aacute (U+00E1) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* acircumflex (U+00E2) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* atilde (U+00E3) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* adieresis (U+00E4) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* aring (U+00E5) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* ae (U+00E6) contains a short segment B<<901.0,238.0>-<901.0,231.0>-<901.0,223.5>>

	* ae (U+00E6) contains a short segment B<<901.0,223.5>-<901.0,216.0>-<900.0,209.0>>

	* amacron (U+0101) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* abreve (U+0103) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* aogonek (U+0105) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* dcaron (U+010F) contains a short segment L<<448.0,0.0>--<448.0,10.0>>

	* dcroat (U+0111) contains a short segment L<<448.0,0.0>--<448.0,10.0>>

	* Gcircumflex (U+011C) contains a short segment B<<782.0,369.0>-<782.0,364.0>-<782.0,359.0>>

	* Gcircumflex (U+011C) contains a short segment B<<782.0,359.0>-<782.0,354.0>-<782.0,349.0>>

	* gcircumflex (U+011D) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* Gbreve (U+011E) contains a short segment B<<782.0,369.0>-<782.0,364.0>-<782.0,359.0>>

	* Gbreve (U+011E) contains a short segment B<<782.0,359.0>-<782.0,354.0>-<782.0,349.0>>

	* gbreve (U+011F) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* Gdotaccent (U+0120) contains a short segment B<<782.0,369.0>-<782.0,364.0>-<782.0,359.0>>

	* Gdotaccent (U+0120) contains a short segment B<<782.0,359.0>-<782.0,354.0>-<782.0,349.0>>

	* gdotaccent (U+0121) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* uni0122 (U+0122) contains a short segment B<<782.0,369.0>-<782.0,364.0>-<782.0,359.0>>

	* uni0122 (U+0122) contains a short segment B<<782.0,359.0>-<782.0,354.0>-<782.0,349.0>>

	* uni0123 (U+0123) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* Eng (U+014A) contains a short segment B<<374.5,-229.0>-<359.0,-227.0>-<351.0,-224.0>>

	* eng (U+014B) contains a short segment B<<291.0,-163.0>-<301.0,-166.0>-<307.5,-166.5>>

	* eng (U+014B) contains a short segment B<<307.5,-166.5>-<314.0,-167.0>-<318.0,-167.0>>

	* oe (U+0153) contains a short segment B<<948.0,238.0>-<948.0,231.0>-<947.5,223.5>>

	* oe (U+0153) contains a short segment B<<947.5,223.5>-<947.0,216.0>-<947.0,210.0>>

	* uni018F (U+018F) contains a short segment B<<52.0,349.0>-<52.0,354.0>-<52.5,359.0>>

	* uni018F (U+018F) contains a short segment B<<52.5,359.0>-<53.0,364.0>-<53.0,369.0>>

	* uni01CE (U+01CE) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* alphatonos (U+03AC) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* alpha (U+03B1) contains a short segment L<<448.0,458.0>--<448.0,470.0>>

	* pi (U+03C0) contains a short segment B<<473.0,56.0>-<479.0,56.0>-<488.5,57.0>>

	* uni03D7 (U+03D7) contains a short segment B<<305.0,-163.0>-<316.0,-166.0>-<322.0,-166.5>>

	* uni03D7 (U+03D7) contains a short segment B<<322.0,-166.5>-<328.0,-167.0>-<333.0,-167.0>>

	* uni0411 (U+0411) contains a short segment B<<291.0,373.0>-<283.0,373.0>-<270.0,373.0>>

	* uni0414 (U+0414) contains a short segment L<<40.0,67.0>--<59.0,67.0>>

	* uni042A (U+042A) contains a short segment B<<298.5,406.0>-<290.0,406.0>-<278.0,406.0>>

	* uni0430 (U+0430) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni0440 (U+0440) contains a short segment L<<127.0,470.0>--<127.0,459.0>>

	* uni0E3F (U+0E3F) contains a short segment B<<325.0,0.0>-<319.0,0.0>-<312.0,0.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<317.0,351.0>-<306.0,351.0>-<295.0,351.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<295.0,351.5>-<284.0,352.0>-<273.0,353.0>>

	* uni1E9E (U+1E9E) contains a short segment B<<273.0,421.0>-<284.0,421.0>-<295.0,421.5>>

	* uni1E9E (U+1E9E) contains a short segment B<<295.0,421.5>-<306.0,422.0>-<317.0,423.0>>

	* uni1EA1 (U+1EA1) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EA3 (U+1EA3) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EA5 (U+1EA5) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EA7 (U+1EA7) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EA9 (U+1EA9) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EAB (U+1EAB) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EAD (U+1EAD) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EAF (U+1EAF) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EB1 (U+1EB1) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EB3 (U+1EB3) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EB5 (U+1EB5) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni1EB7 (U+1EB7) contains a short segment L<<451.0,0.0>--<451.0,8.0>>

	* uni2082 (U+2082) contains a short segment L<<96.0,-60.0>--<104.0,-60.0>>

	* dong (U+20AB) contains a short segment L<<448.0,0.0>--<448.0,10.0>>

	* uni2154 (U+2154) contains a short segment L<<202.0,402.0>--<210.0,402.0>>

	* uni2156 (U+2156) contains a short segment L<<202.0,406.0>--<210.0,406.0>>

	* fi (U+FB01) contains a short segment B<<239.0,747.0>-<248.0,747.0>-<257.5,745.5>> 

	* fl (U+FB02) contains a short segment B<<457.5,-12.5>-<448.0,-14.0>-<440.0,-14.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<68.0,0.0>--<67.0,733.0>>

	* Beta (U+0392): L<<68.0,0.0>--<67.0,733.0>>

	* Eng (U+014A): L<<73.0,0.0>--<72.0,733.0>>

	* Eta (U+0397): L<<532.0,416.0>--<531.0,733.0>>

	* Etatonos (U+0389): L<<653.0,416.0>--<652.0,733.0>>

	* H (U+0048): L<<532.0,416.0>--<531.0,733.0>>

	* Hcircumflex (U+0124): L<<532.0,416.0>--<531.0,733.0>>

	* M (U+004D): L<<692.0,0.0>--<691.0,542.0>>

	* Mu (U+039C): L<<692.0,0.0>--<691.0,542.0>>

	* N (U+004E): L<<73.0,0.0>--<72.0,733.0>>

	* Nacute (U+0143): L<<73.0,0.0>--<72.0,733.0>>

	* Ncaron (U+0147): L<<73.0,0.0>--<72.0,733.0>>

	* Ntilde (U+00D1): L<<73.0,0.0>--<72.0,733.0>>

	* Nu (U+039D): L<<73.0,0.0>--<72.0,733.0>>

	* Phi (U+03A6): L<<385.0,60.0>--<384.0,675.0>>

	* Psi (U+03A8): L<<353.0,204.0>--<352.0,733.0>>

	* asterisk (U+002A): L<<249.0,571.0>--<250.0,453.0>>

	* asterisk (U+002A): L<<250.0,780.0>--<249.0,662.0>>

	* eng (U+014B): L<<124.0,390.0>--<123.0,0.0>>

	* ij (U+0133): L<<269.0,-60.0>--<268.0,470.0>>

	* ij (U+0133): L<<332.0,470.0>--<331.0,-96.0>>

	* j (U+006A): L<<108.0,-60.0>--<107.0,470.0>>

	* j (U+006A): L<<171.0,470.0>--<170.0,-96.0>>

	* jcircumflex (U+0135): L<<109.0,-60.0>--<108.0,470.0>>

	* jcircumflex (U+0135): L<<172.0,470.0>--<171.0,-96.0>>

	* trademark (U+2122): L<<258.0,470.0>--<257.0,733.0>>

	* uni0145 (U+0145): L<<73.0,0.0>--<72.0,733.0>>

	* uni0237 (U+0237): L<<109.0,-60.0>--<108.0,470.0>>

	* uni0237 (U+0237): L<<172.0,470.0>--<171.0,-96.0>>

	* uni040D (U+040D): L<<610.0,733.0>--<609.0,0.0>>

	* uni0412 (U+0412): L<<68.0,0.0>--<67.0,733.0>>

	* uni0418 (U+0418): L<<610.0,733.0>--<609.0,0.0>>

	* uni0419 (U+0419): L<<610.0,733.0>--<609.0,0.0>>

	* uni041C (U+041C): L<<692.0,0.0>--<691.0,542.0>>

	* uni041D (U+041D): L<<532.0,416.0>--<531.0,733.0>>

	* uni0424 (U+0424): L<<385.0,60.0>--<384.0,675.0>>

	* uni0426 (U+0426): L<<134.0,733.0>--<136.0,66.0>>

	* uni0426 (U+0426): L<<68.0,0.0>--<66.0,733.0>>

	* uni0427 (U+0427): L<<477.0,364.0>--<476.0,733.0>>

	* uni043C (U+043C): L<<473.0,0.0>--<472.0,289.0>>

	* uni043C (U+043C): L<<56.0,0.0>--<55.0,470.0>>

	* uni0E3F (U+0E3F): L<<68.0,0.0>--<67.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[25] Kreadon-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Extra Bold'. Expected OS/2 usWeightClass is 700, got 800. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Kreadon Medium | Kreadon Extra |
| Subfamily Name | Bold | Bold |
| Full Name | Kreadon Extra Bold | Kreadon Extra Bold |
| Poscript Name | Kreadon-ExtraBold | KreadonExtra-Bold |
| Typographic Family Name | Kreadon | N/A |
| Typographic Subfamily Name | Extra Bold | N/A | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking head.macStyle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/mac_style">com.google.fonts/check/mac_style</a>)</summary><div>


* 🔥 **FAIL** head macStyle BOLD bit should be unset. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsSelection value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/fsselection">com.google.fonts/check/fsselection</a>)</summary><div>


* 🔥 **FAIL** OS/2 fsSelection REGULAR bit should be set. [code: bad-REGULAR]
* 🔥 **FAIL** OS/2 fsSelection BOLD bit should be unset. [code: bad-BOLD]
</div></details><details><summary>🔥 <b>FAIL:</b> Does full font name begin with the font family name? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/match_familyname_fullfont">com.google.fonts/check/name/match_familyname_fullfont</a>)</summary><div>


* 🔥 **FAIL** On the 'name' table, the full font name 'Kreadon Extra Bold' does not begin with the font family name 'Kreadon Medium' in platformID 3, encodingID 1, languageID 1033(0409), and nameID 1. [code: mismatch-font-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* trademark (U+2122): L<<529.0,591.0>--<532.0,659.0>>/L<<532.0,659.0>--<476.0,470.0>> = 13.978244470135463 

	* uni0432 (U+0432): B<<478.0,279.5>-<459.0,249.0>-<423.0,244.0>>/B<<423.0,244.0>-<447.0,243.0>-<471.0,229.5>> = 10.293106733347221 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<65.0,1.0>--<64.0,733.0>>

	* Beta (U+0392): L<<65.0,1.0>--<64.0,733.0>>

	* Eng (U+014A): L<<71.0,0.0>--<70.0,733.0>>

	* Eta (U+0397): L<<525.0,451.0>--<524.0,733.0>>

	* Etatonos (U+0389): L<<745.0,451.0>--<744.0,733.0>>

	* H (U+0048): L<<525.0,451.0>--<524.0,733.0>>

	* Hcircumflex (U+0124): L<<525.0,451.0>--<524.0,733.0>>

	* M (U+004D): L<<698.0,0.0>--<697.0,230.0>>

	* M (U+004D): L<<71.0,0.0>--<70.0,733.0>>

	* Mu (U+039C): L<<698.0,0.0>--<697.0,230.0>>

	* Mu (U+039C): L<<71.0,0.0>--<70.0,733.0>>

	* N (U+004E): L<<71.0,0.0>--<70.0,733.0>>

	* Nacute (U+0143): L<<71.0,0.0>--<70.0,733.0>>

	* Ncaron (U+0147): L<<71.0,0.0>--<70.0,733.0>>

	* Ntilde (U+00D1): L<<71.0,0.0>--<70.0,733.0>>

	* Nu (U+039D): L<<71.0,0.0>--<70.0,733.0>>

	* Omegatonos (U+038F): L<<518.0,135.0>--<517.0,0.0>>

	* Phi (U+03A6): L<<348.0,155.0>--<347.0,579.0>>

	* Psi (U+03A8): L<<332.0,282.0>--<331.0,733.0>>

	* fl (U+FB02): L<<258.0,470.0>--<257.0,338.0>>

	* ij (U+0133): L<<393.0,0.0>--<392.0,470.0>>

	* ij (U+0133): L<<544.0,470.0>--<543.0,-51.0>>

	* j (U+006A): L<<133.0,0.0>--<132.0,470.0>>

	* j (U+006A): L<<284.0,470.0>--<283.0,-51.0>>

	* jcircumflex (U+0135): L<<133.0,0.0>--<132.0,470.0>>

	* jcircumflex (U+0135): L<<284.0,470.0>--<283.0,-51.0>>

	* trademark (U+2122): L<<272.0,470.0>--<271.0,733.0>>

	* uni0145 (U+0145): L<<71.0,0.0>--<70.0,733.0>>

	* uni0237 (U+0237): L<<133.0,0.0>--<132.0,470.0>>

	* uni0237 (U+0237): L<<284.0,470.0>--<283.0,-51.0>>

	* uni03A9 (U+03A9): L<<378.0,135.0>--<377.0,0.0>>

	* uni040D (U+040D): L<<710.0,733.0>--<709.0,0.0>>

	* uni0412 (U+0412): L<<65.0,1.0>--<64.0,733.0>>

	* uni0418 (U+0418): L<<710.0,733.0>--<709.0,0.0>>

	* uni0419 (U+0419): L<<710.0,733.0>--<709.0,0.0>>

	* uni041C (U+041C): L<<698.0,0.0>--<697.0,230.0>>

	* uni041C (U+041C): L<<71.0,0.0>--<70.0,733.0>>

	* uni041D (U+041D): L<<525.0,451.0>--<524.0,733.0>>

	* uni0424 (U+0424): L<<348.0,155.0>--<347.0,579.0>>

	* uni0426 (U+0426): L<<241.0,733.0>--<243.0,146.0>>

	* uni0426 (U+0426): L<<65.0,0.0>--<63.0,733.0>>

	* uni0427 (U+0427): L<<469.0,403.0>--<468.0,733.0>>

	* uni043C (U+043C): L<<518.0,0.0>--<517.0,130.0>>

	* uni043C (U+043C): L<<53.0,0.0>--<52.0,470.0>>

	* uni0E3F (U+0E3F): L<<65.0,1.0>--<64.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[22] Kreadon-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** Best SubFamily name is 'Extra Light'. Expected OS/2 usWeightClass is 300, got 200. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Kreadon Extra Light | Kreadon Extra Light |
| Subfamily Name | Regular | Regular |
| Full Name | Kreadon Extra Light | Kreadon Extra Light |
| Poscript Name | Kreadon-ExtraLight | KreadonExtra-Light |
| Typographic Family Name | Kreadon | Kreadon Extra |
| Typographic Subfamily Name | Extra Light | Light | [code: bad-names]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Kreadon-Demi.ttf', 'fonts/ttf/Kreadon-Light.ttf', 'fonts/ttf/Kreadon-Bold.ttf', 'fonts/ttf/Kreadon-Medium.ttf', 'fonts/ttf/Kreadon-Regular.ttf', 'fonts/ttf/Kreadon-ExtraBold.ttf', 'fonts/ttf/Kreadon-ExtraLight.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current Font Bakery version is 0.8.13, while a newer 0.9.0 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking with fontTools.ttx (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/ttx_roundtrip">com.google.fonts/check/ttx_roundtrip</a>)</summary><div>


* 🔥 **FAIL** name id 256 missing from name table
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ і́ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters should disappear in other cases, for example: ĭ̦ i̦̇ i̦̊ i̦̋ i̦̒ i⃝̀ i⃝́ i⃝̂ i⃝̃ i⃝̄ i⃝̆ i⃝̇ i⃝̈ i⃝̉ i⃝̊ i⃝̋ i⃝̌ i⃝̒ j̦̀ j̦́ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=13] [code: http-in-description]
* ⚠ **WARN** For now we're still accepting http URLs, but you should consider using https instead.
 [code: http]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss03 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss04 lacks a description string on the 'name' table. [code: missing-description]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: Yucy	Contours detected: 3	Expected: 2

	- Glyph name: Yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: yacy	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2

	- Glyph name: arrowupdn	Contours detected: 2	Expected: 1

	- Glyph name: Kappa	Contours detected: 2	Expected: 1

	- Glyph name: Racute	Contours detected: 2	Expected: 3

	- Glyph name: Rcaron	Contours detected: 2	Expected: 3

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowupdn	Contours detected: 2	Expected: 1

	- Glyph name: delta	Contours detected: 1	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: kappa	Contours detected: 2	Expected: 1

	- Glyph name: m	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0156	Contours detected: 2	Expected: 3

	- Glyph name: uni03CF	Contours detected: 2	Expected: 1

	- Glyph name: uni0411	Contours detected: 1	Expected: 2

	- Glyph name: uni0416	Contours detected: 3	Expected: 1

	- Glyph name: uni041A	Contours detected: 2	Expected: 1

	- Glyph name: uni042A	Contours detected: 1	Expected: 2

	- Glyph name: uni042B	Contours detected: 2	Expected: 3

	- Glyph name: uni042C	Contours detected: 1	Expected: 2

	- Glyph name: uni0436	Contours detected: 3	Expected: 1

	- Glyph name: uni043A	Contours detected: 2	Expected: 1

	- Glyph name: uni044A	Contours detected: 1	Expected: 2

	- Glyph name: uni044B	Contours detected: 2	Expected: 3

	- Glyph name: uni044C	Contours detected: 1	Expected: 2

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni20BD	Contours detected: 1	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20DD (U+20DD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* alpha (U+03B1): B<<509.0,23.0>-<489.0,60.0>-<489.0,124.0>>/B<<489.0,124.0>-<481.0,89.0>-<451.0,58.0>> = 12.875001559612462

	* alphatonos (U+03AC): B<<509.0,23.0>-<489.0,60.0>-<489.0,124.0>>/B<<489.0,124.0>-<481.0,89.0>-<451.0,58.0>> = 12.875001559612462

	* at (U+0040): B<<572.5,463.0>-<599.0,439.0>-<609.0,406.0>>/L<<609.0,406.0>--<606.0,465.0>> = 13.947560941570508 

	* uni0431 (U+0431): L<<101.0,382.0>--<95.0,326.0>>/B<<95.0,326.0>-<107.0,368.0>-<134.5,403.5>> = 9.829892334637428 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<77.0,0.0>--<76.0,733.0>>

	* Beta (U+0392): L<<77.0,0.0>--<76.0,733.0>>

	* D (U+0044): L<<111.0,696.0>--<112.0,41.0>>

	* Dcaron (U+010E): L<<111.0,696.0>--<112.0,41.0>>

	* Eng (U+014A): L<<81.0,0.0>--<80.0,733.0>>

	* Eta (U+0397): L<<554.0,400.0>--<553.0,733.0>>

	* Etatonos (U+0389): L<<644.0,400.0>--<643.0,733.0>>

	* H (U+0048): L<<554.0,400.0>--<553.0,733.0>>

	* Hbar (U+0126): L<<564.0,400.0>--<563.0,584.0>>

	* Hcircumflex (U+0124): L<<554.0,400.0>--<553.0,733.0>>

	* M (U+004D): L<<694.0,0.0>--<693.0,550.0>>

	* Mu (U+039C): L<<694.0,0.0>--<693.0,550.0>>

	* N (U+004E): L<<81.0,0.0>--<80.0,733.0>>

	* Nacute (U+0143): L<<81.0,0.0>--<80.0,733.0>>

	* Ncaron (U+0147): L<<81.0,0.0>--<80.0,733.0>>

	* Ntilde (U+00D1): L<<81.0,0.0>--<80.0,733.0>>

	* Nu (U+039D): L<<81.0,0.0>--<80.0,733.0>>

	* Phi (U+03A6): L<<407.0,25.0>--<406.0,710.0>>

	* Psi (U+03A8): L<<377.0,176.0>--<376.0,733.0>>

	* asterisk (U+002A): L<<224.0,588.0>--<225.0,462.0>>

	* asterisk (U+002A): L<<225.0,771.0>--<224.0,645.0>>

	* ij (U+0133): L<<254.0,-60.0>--<253.0,470.0>>

	* ij (U+0133): L<<289.0,470.0>--<288.0,-81.0>>

	* j (U+006A): L<<124.0,-60.0>--<123.0,470.0>>

	* j (U+006A): L<<159.0,470.0>--<158.0,-81.0>>

	* jcircumflex (U+0135): L<<129.0,-60.0>--<128.0,470.0>>

	* jcircumflex (U+0135): L<<164.0,470.0>--<163.0,-81.0>>

	* thorn (U+00FE): L<<104.0,675.0>--<102.0,360.0>>

	* uni0145 (U+0145): L<<81.0,0.0>--<80.0,733.0>>

	* uni0237 (U+0237): L<<129.0,-60.0>--<128.0,470.0>>

	* uni0237 (U+0237): L<<164.0,470.0>--<163.0,-81.0>>

	* uni040D (U+040D): L<<610.0,733.0>--<609.0,0.0>>

	* uni0412 (U+0412): L<<77.0,0.0>--<76.0,733.0>>

	* uni0418 (U+0418): L<<610.0,733.0>--<609.0,0.0>>

	* uni0419 (U+0419): L<<610.0,733.0>--<609.0,0.0>>

	* uni041C (U+041C): L<<694.0,0.0>--<693.0,550.0>>

	* uni041D (U+041D): L<<554.0,400.0>--<553.0,733.0>>

	* uni0424 (U+0424): L<<407.0,25.0>--<406.0,710.0>>

	* uni0426 (U+0426): L<<112.0,733.0>--<114.0,34.0>>

	* uni0426 (U+0426): L<<78.0,0.0>--<76.0,733.0>>

	* uni0427 (U+0427): L<<503.0,351.0>--<502.0,733.0>>

	* uni043C (U+043C): L<<490.0,0.0>--<489.0,350.0>>

	* uni043C (U+043C): L<<66.0,0.0>--<65.0,470.0>>

	* uni0E3F (U+0E3F): L<<77.0,0.0>--<76.0,733.0>> 

	* uni2116 (U+2116): L<<71.0,0.0>--<70.0,733.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 56 | 98 | 826 | 43 | 597 | 0 |
| 0% | 3% | 6% | 51% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
