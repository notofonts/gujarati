## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[12] NotoSerifGujarati-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0A85
	* uni0A86
	* uni0A8B
	* uni0A8C
	* uni0A8D
	* uni0A8F
	* uni0A90
	* uni0A91
	* uni0A93
	* uni0A94
	* uni0A96
	* uni0A960ACD
	* uni0A98
	* uni0A9A
	* uni0A9B
	* uni0A9C
	* uni0A9C0ACD
	* uni0A9D
	* uni0A9D0ACD
	* uni0A9E
	* uni0AA5
	* uni0AA7
	* uni0AAA
	* uni0AAB
	* uni0AAB0ACD
	* uni0AAC
	* uni0AAC0ACD
	* uni0AAD
	* uni0AAE
	* uni0AAE0ACD
	* uni0AAF
	* uni0AB5
	* uni0AB7
	* uni0AB8
	* uni0AB80ACD
	* uni0AE0
	* uni0AE1
	* uni0AEA
	* uni0AEB
	* uni0AED
	* uni0AF9
	* zh_ra_aaMatragujarati
	* zh_ra_iiMatragujarati
	* zh_ragujarati and zhgujarati
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=328.5,Y=603.5 (should be at cap-height 602?)

	* parenright (U+0029): X=216.0,Y=603.5 (should be at cap-height 602?)

	* one (U+0031): X=222.0,Y=604.0 (should be at cap-height 602?)

	* four (U+0034): X=277.0,Y=601.0 (should be at cap-height 602?)

	* at (U+0040): X=765.0,Y=-2.0 (should be at baseline 0?)

	* F (U+0046): X=113.0,Y=603.0 (should be at cap-height 602?)

	* H (U+0048): X=113.0,Y=600.0 (should be at cap-height 602?)

	* I (U+0049): X=113.0,Y=600.0 (should be at cap-height 602?)

	* J (U+004A): X=117.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=317.0,Y=601.0 (should be at cap-height 602?)

	* J (U+004A): X=317.0,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=314.0,Y=604.0 (should be at cap-height 602?)

	* Q (U+0051): X=317.0,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=78.0,Y=600.0 (should be at cap-height 602?)

	* X (U+0058): X=137.0,Y=600.0 (should be at cap-height 602?)

	* Y (U+0059): X=88.0,Y=600.0 (should be at cap-height 602?)

	* Y (U+0059): X=555.0,Y=600.0 (should be at cap-height 602?)

	* c (U+0063): X=431.0,Y=535.0 (should be at x-height 536?)

	* p (U+0070): X=337.5,Y=1.5 (should be at baseline 0?)

	* q (U+0071): X=386.0,Y=1.0 (should be at baseline 0?)

	* s (U+0073): X=376.5,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=93.0,Y=535.5 (should be at x-height 536?)

	* t (U+0074): X=367.0,Y=1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=329.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=526.0,Y=601.0 (should be at cap-height 602?)

	* sterling (U+00A3): X=469.0,Y=2.0 (should be at baseline 0?)

	* yen (U+00A5): X=67.0,Y=600.0 (should be at cap-height 602?)

	* Igrave (U+00CC): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Iacute (U+00CD): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Icircumflex (U+00CE): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Idieresis (U+00CF): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Yacute (U+00DD): X=88.0,Y=600.0 (should be at cap-height 602?)

	* Yacute (U+00DD): X=555.0,Y=600.0 (should be at cap-height 602?)

	* Thorn (U+00DE): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Thorn (U+00DE): X=313.0,Y=604.0 (should be at cap-height 602?)

	* thorn (U+00FE): X=281.0,Y=-1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=712.0,Y=600.0 (should be at cap-height 602?)

	* dcaron (U+010F): X=633.0,Y=600.0 (should be at cap-height 602?)

	* Hbar (U+0126): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Imacron (U+012A): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Iogonek (U+012E): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Idotaccent (U+0130): X=113.0,Y=600.0 (should be at cap-height 602?)

	* Lacute (U+0139): X=314.0,Y=604.0 (should be at cap-height 602?)

	* uni013B (U+013B): X=314.0,Y=604.0 (should be at cap-height 602?)

	* Lcaron (U+013D): X=314.0,Y=604.0 (should be at cap-height 602?)

	* Lcaron (U+013D): X=590.5,Y=603.0 (should be at cap-height 602?)

	* lcaron (U+013E): X=422.0,Y=600.0 (should be at cap-height 602?)

	* lcaron (U+013E): X=343.0,Y=600.0 (should be at cap-height 602?)

	* Lslash (U+0141): X=314.0,Y=604.0 (should be at cap-height 602?)

	* tcaron (U+0165): X=371.0,Y=1.5 (should be at baseline 0?)

	* tcaron (U+0165): X=424.0,Y=600.0 (should be at cap-height 602?)

	* tcaron (U+0165): X=345.0,Y=600.0 (should be at cap-height 602?)

	* Wcircumflex (U+0174): X=78.0,Y=600.0 (should be at cap-height 602?)

	* Ycircumflex (U+0176): X=88.0,Y=600.0 (should be at cap-height 602?)

	* Ycircumflex (U+0176): X=555.0,Y=600.0 (should be at cap-height 602?)

	* Ydieresis (U+0178): X=88.0,Y=600.0 (should be at cap-height 602?)

	* Ydieresis (U+0178): X=555.0,Y=600.0 (should be at cap-height 602?)

	* uni021B (U+021B): X=367.0,Y=1.5 (should be at baseline 0?)

	* uni0A87 (U+0A87): X=292.0,Y=600.0 (should be at cap-height 602?)

	* uni0A88 (U+0A88): X=292.0,Y=600.0 (should be at cap-height 602?)

	* uni0A95 (U+0A95): X=433.0,Y=600.0 (should be at cap-height 602?)

	* uni0A96 (U+0A96): X=68.0,Y=603.0 (should be at cap-height 602?)

	* uni0A97 (U+0A97): X=476.0,Y=603.0 (should be at cap-height 602?)

	* uni0A9B (U+0A9B): X=256.0,Y=601.0 (should be at cap-height 602?)

	* uni0AA0 (U+0AA0): X=401.0,Y=600.0 (should be at cap-height 602?)

	* uni0AA3 (U+0AA3): X=352.0,Y=601.5 (should be at cap-height 602?)

	* uni0AAA (U+0AAA): X=68.0,Y=603.0 (should be at cap-height 602?)

	* uni0AAB (U+0AAB): X=410.0,Y=600.0 (should be at cap-height 602?)

	* uni0AAE (U+0AAE): X=86.0,Y=603.0 (should be at cap-height 602?)

	* uni0AB7 (U+0AB7): X=80.0,Y=603.0 (should be at cap-height 602?)

	* uni0AD0 (U+0AD0): X=598.0,Y=600.0 (should be at cap-height 602?)

	* uni0AD0 (U+0AD0): X=598.0,Y=600.0 (should be at cap-height 602?)

	* uni0AE1 (U+0AE1): X=725.5,Y=1.0 (should be at baseline 0?)

	* uni0AE1 (U+0AE1): X=859.0,Y=-1.0 (should be at baseline 0?)

	* uni0AE7 (U+0AE7): X=148.0,Y=603.0 (should be at cap-height 602?)

	* uni0AE8 (U+0AE8): X=213.0,Y=603.0 (should be at cap-height 602?)

	* uni0AE9 (U+0AE9): X=220.0,Y=603.0 (should be at cap-height 602?)

	* uni0AEA (U+0AEA): X=80.0,Y=603.0 (should be at cap-height 602?)

	* uni0AEB (U+0AEB): X=99.0,Y=603.0 (should be at cap-height 602?)

	* uni0AED (U+0AED): X=250.0,Y=603.0 (should be at cap-height 602?)

	* uni0AEF (U+0AEF): X=275.0,Y=603.0 (should be at cap-height 602?)

	* uni0AF1 (U+0AF1): X=212.0,Y=603.0 (should be at cap-height 602?)

	* uni0AF1 (U+0AF1): X=159.0,Y=-1.0 (should be at baseline 0?)

	* Wgrave (U+1E80): X=78.0,Y=600.0 (should be at cap-height 602?)

	* Wacute (U+1E82): X=78.0,Y=600.0 (should be at cap-height 602?)

	* Wdieresis (U+1E84): X=78.0,Y=600.0 (should be at cap-height 602?)

	* Ygrave (U+1EF2): X=88.0,Y=600.0 (should be at cap-height 602?)

	* Ygrave (U+1EF2): X=555.0,Y=600.0 (should be at cap-height 602?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* uni0AFC (U+0AFC): B<<-255.0,710.0>-<-234.0,713.0>-<-208.0,721.0>>/B<<-208.0,721.0>-<-231.0,717.0>-<-251.0,717.0>> = 7.236922025967975

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSerifGujarati-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0A85
	* uni0A86
	* uni0A8C
	* uni0A8D
	* uni0A8F
	* uni0A90
	* uni0A91
	* uni0A93
	* uni0A94
	* uni0A96
	* uni0A98
	* uni0A9A
	* uni0A9C
	* uni0A9C0ACD
	* uni0A9D
	* uni0A9D0ACD
	* uni0AA5
	* uni0AAC
	* uni0AAD
	* uni0AAE
	* uni0AAE0ACD
	* uni0AB7
	* uni0AE0
	* uni0AE1
	* uni0AEA
	* uni0AF9
	* zh_ra_aaMatragujarati
	* zh_ra_iiMatragujarati
	* zh_ragujarati and zhgujarati
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-248.5,711.0>-<-227.0,714.0>-<-204.0,723.0>>/B<<-204.0,723.0>-<-225.0,719.0>-<-246.0,719.0>> = 10.586324401780564

	* y (U+0079): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* yacute (U+00FD): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ycircumflex (U+0177): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ydieresis (U+00FF): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127

	* ygrave (U+1EF3): B<<321.0,162.0>-<327.0,138.0>-<329.0,118.0>>/B<<329.0,118.0>-<331.0,139.0>-<339.5,165.0>> = 11.150925168505127 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<101.0,122.0>--<100.0,646.0>>

	* h (U+0068): L<<252.0,309.0>--<253.0,118.0>>

	* sterling (U+00A3): L<<428.0,346.0>--<270.0,347.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifGujarati-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0A85
	* uni0A86
	* uni0A8B
	* uni0A8C
	* uni0A8D
	* uni0A8F
	* uni0A90
	* uni0A91
	* uni0A93
	* uni0A94
	* uni0A96
	* uni0A960ACD
	* uni0A98
	* uni0A9A
	* uni0A9C
	* uni0A9C0ACD
	* uni0A9D
	* uni0A9D0ACD
	* uni0AA5
	* uni0AA7
	* uni0AAB
	* uni0AAB0ACD
	* uni0AAC
	* uni0AAC0ACD
	* uni0AAD
	* uni0AAE
	* uni0AAE0ACD
	* uni0AB5
	* uni0AB7
	* uni0AE0
	* uni0AE1
	* uni0AEA
	* uni0AED
	* uni0AF9
	* zh_ra_aaMatragujarati
	* zh_ra_iiMatragujarati
	* zh_ragujarati and zhgujarati
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=351.5,Y=1.0 (should be at baseline 0?)

	* H (U+0048): X=117.0,Y=600.0 (should be at cap-height 602?)

	* H (U+0048): X=298.0,Y=601.0 (should be at cap-height 602?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* J (U+004A): X=120.0,Y=601.0 (should be at cap-height 602?)

	* K (U+004B): X=117.0,Y=603.0 (should be at cap-height 602?)

	* K (U+004B): X=298.0,Y=601.0 (should be at cap-height 602?)

	* M (U+004D): X=842.0,Y=601.0 (should be at cap-height 602?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?)

	* S (U+0053): X=529.0,Y=603.0 (should be at cap-height 602?)

	* W (U+0057): X=81.0,Y=604.0 (should be at cap-height 602?)

	* X (U+0058): X=134.0,Y=604.0 (should be at cap-height 602?)

	* Y (U+0059): X=86.0,Y=604.0 (should be at cap-height 602?)

	* bracketleft (U+005B): X=246.0,Y=1.0 (should be at baseline 0?)

	* bracketright (U+005D): X=247.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=269.5,Y=534.5 (should be at x-height 536?)

	* c (U+0063): X=417.0,Y=535.0 (should be at x-height 536?)

	* p (U+0070): X=265.0,Y=-1.5 (should be at baseline 0?)

	* s (U+0073): X=367.0,Y=535.0 (should be at x-height 536?)

	* t (U+0074): X=86.5,Y=534.0 (should be at x-height 536?)

	* t (U+0074): X=154.0,Y=604.0 (should be at cap-height 602?)

	* t (U+0074): X=351.0,Y=0.5 (should be at baseline 0?)

	* y (U+0079): X=353.0,Y=2.0 (should be at baseline 0?)

	* cent (U+00A2): X=489.5,Y=603.5 (should be at cap-height 602?)

	* sterling (U+00A3): X=517.0,Y=604.0 (should be at cap-height 602?)

	* yen (U+00A5): X=71.0,Y=604.0 (should be at cap-height 602?)

	* questiondown (U+00BF): X=476.0,Y=-1.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=86.0,Y=604.0 (should be at cap-height 602?)

	* Thorn (U+00DE): X=298.0,Y=603.0 (should be at cap-height 602?)

	* yacute (U+00FD): X=353.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=353.0,Y=2.0 (should be at baseline 0?)

	* dcaron (U+010F): X=690.0,Y=600.0 (should be at cap-height 602?)

	* dcaron (U+010F): X=620.0,Y=600.0 (should be at cap-height 602?)

	* Hbar (U+0126): X=117.0,Y=600.0 (should be at cap-height 602?)

	* Hbar (U+0126): X=298.0,Y=601.0 (should be at cap-height 602?)

	* uni0136 (U+0136): X=117.0,Y=603.0 (should be at cap-height 602?)

	* uni0136 (U+0136): X=298.0,Y=601.0 (should be at cap-height 602?)

	* Lcaron (U+013D): X=570.5,Y=603.0 (should be at cap-height 602?)

	* lcaron (U+013E): X=397.0,Y=600.0 (should be at cap-height 602?)

	* lcaron (U+013E): X=327.0,Y=600.0 (should be at cap-height 602?)

	* Sacute (U+015A): X=529.0,Y=603.0 (should be at cap-height 602?)

	* Scedilla (U+015E): X=529.0,Y=603.0 (should be at cap-height 602?)

	* Scaron (U+0160): X=529.0,Y=603.0 (should be at cap-height 602?)

	* tcaron (U+0165): X=156.0,Y=604.0 (should be at cap-height 602?)

	* tcaron (U+0165): X=353.0,Y=0.5 (should be at baseline 0?)

	* tcaron (U+0165): X=398.0,Y=600.0 (should be at cap-height 602?)

	* tcaron (U+0165): X=328.0,Y=600.0 (should be at cap-height 602?)

	* Wcircumflex (U+0174): X=81.0,Y=604.0 (should be at cap-height 602?)

	* Ycircumflex (U+0176): X=86.0,Y=604.0 (should be at cap-height 602?)

	* ycircumflex (U+0177): X=353.0,Y=2.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=86.0,Y=604.0 (should be at cap-height 602?)

	* uni0218 (U+0218): X=529.0,Y=603.0 (should be at cap-height 602?)

	* uni021B (U+021B): X=154.0,Y=604.0 (should be at cap-height 602?)

	* uni021B (U+021B): X=351.0,Y=0.5 (should be at baseline 0?)

	* uni0A87 (U+0A87): X=289.0,Y=600.0 (should be at cap-height 602?)

	* uni0A88 (U+0A88): X=289.0,Y=600.0 (should be at cap-height 602?)

	* uni0A95 (U+0A95): X=421.0,Y=600.0 (should be at cap-height 602?)

	* uni0A96 (U+0A96): X=65.0,Y=603.0 (should be at cap-height 602?)

	* uni0A97 (U+0A97): X=470.0,Y=604.0 (should be at cap-height 602?)

	* uni0A99 (U+0A99): X=371.5,Y=604.0 (should be at cap-height 602?)

	* uni0A9B (U+0A9B): X=254.0,Y=601.0 (should be at cap-height 602?)

	* uni0AA0 (U+0AA0): X=396.0,Y=600.0 (should be at cap-height 602?)

	* uni0AA1 (U+0AA1): X=371.5,Y=604.0 (should be at cap-height 602?)

	* uni0AA3 (U+0AA3): X=343.5,Y=600.0 (should be at cap-height 602?)

	* uni0AA6 (U+0AA6): X=293.0,Y=603.5 (should be at cap-height 602?)

	* uni0AAA (U+0AAA): X=65.0,Y=603.0 (should be at cap-height 602?)

	* uni0AAB (U+0AAB): X=399.0,Y=600.0 (should be at cap-height 602?)

	* uni0AAE (U+0AAE): X=88.0,Y=603.0 (should be at cap-height 602?)

	* uni0AB7 (U+0AB7): X=75.0,Y=603.0 (should be at cap-height 602?)

	* uni0AD0 (U+0AD0): X=593.0,Y=603.0 (should be at cap-height 602?)

	* uni0AD0 (U+0AD0): X=593.0,Y=603.0 (should be at cap-height 602?)

	* uni0AE1 (U+0AE1): X=532.0,Y=-1.0 (should be at baseline 0?)

	* uni0AE3 (U+0AE3): X=338.0,Y=-452.0 (should be at descender -450?)

	* uni0AE7 (U+0AE7): X=149.0,Y=601.0 (should be at cap-height 602?)

	* uni0AE8 (U+0AE8): X=166.0,Y=600.0 (should be at cap-height 602?)

	* uni0AEA (U+0AEA): X=76.0,Y=601.0 (should be at cap-height 602?)

	* uni0AED (U+0AED): X=246.0,Y=601.0 (should be at cap-height 602?)

	* uni0AEF (U+0AEF): X=271.0,Y=600.0 (should be at cap-height 602?)

	* uni0AF1 (U+0AF1): X=157.0,Y=2.0 (should be at baseline 0?)

	* Wgrave (U+1E80): X=81.0,Y=604.0 (should be at cap-height 602?)

	* Wacute (U+1E82): X=81.0,Y=604.0 (should be at cap-height 602?)

	* Wdieresis (U+1E84): X=81.0,Y=604.0 (should be at cap-height 602?)

	* Ygrave (U+1EF2): X=86.0,Y=604.0 (should be at cap-height 602?)

	* ygrave (U+1EF3): X=353.0,Y=2.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=423.0,Y=1.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=409.5,Y=600.0 (should be at cap-height 602?)

	* uni20B9 (U+20B9): X=505.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eogonek (U+0119): B<<270.5,-58.5>-<297.0,-26.0>-<333.0,-9.0>>/B<<333.0,-9.0>-<329.0,-10.0>-<324.0,-10.0>> = 11.24147876762648

	* uni0AFC (U+0AFC): B<<-252.0,710.0>-<-231.0,713.0>-<-206.0,722.0>>/B<<-206.0,722.0>-<-229.0,718.0>-<-249.0,718.0>> = 9.933069411440542

	* y (U+0079): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* yacute (U+00FD): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ycircumflex (U+0177): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ydieresis (U+00FF): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296

	* ygrave (U+1EF3): B<<329.0,175.5>-<335.0,150.0>-<337.0,131.0>>/B<<337.0,131.0>-<339.0,153.0>-<345.0,173.0>> = 11.203434865229296 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<442.0,340.0>--<284.0,341.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSerifGujarati-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* six (U+0036): X=458.5,Y=593.5 (should be at cap-height 592?)

	* nine (U+0039): X=126.5,Y=594.0 (should be at cap-height 592?)

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=166.0,Y=593.0 (should be at cap-height 592?)

	* W (U+0057): X=865.0,Y=590.0 (should be at cap-height 592?)

	* w (U+0077): X=411.0,Y=535.0 (should be at x-height 536?)

	* w (U+0077): X=452.0,Y=535.0 (should be at x-height 536?)

	* sterling (U+00A3): X=359.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=91.0,Y=2.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=173.0,Y=593.0 (should be at cap-height 592?)

	* Gbreve (U+011E): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=486.5,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=486.5,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=569.0,Y=1.0 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=166.0,Y=593.0 (should be at cap-height 592?)

	* Wcircumflex (U+0174): X=865.0,Y=590.0 (should be at cap-height 592?)

	* uni0A85 (U+0A85): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A86 (U+0A86): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A86 (U+0A86): X=943.0,Y=591.0 (should be at cap-height 592?)

	* uni0A89 (U+0A89): X=314.0,Y=590.5 (should be at cap-height 592?)

	* uni0A8A (U+0A8A): X=314.0,Y=590.5 (should be at cap-height 592?)

	* uni0A8B (U+0A8B): X=455.0,Y=591.0 (should be at cap-height 592?)

	* uni0A8D (U+0A8D): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A8F (U+0A8F): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A90 (U+0A90): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A91 (U+0A91): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A91 (U+0A91): X=943.0,Y=591.0 (should be at cap-height 592?)

	* uni0A93 (U+0A93): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A93 (U+0A93): X=943.0,Y=591.0 (should be at cap-height 592?)

	* uni0A94 (U+0A94): X=717.0,Y=591.0 (should be at cap-height 592?)

	* uni0A94 (U+0A94): X=943.0,Y=591.0 (should be at cap-height 592?)

	* uni0A96 (U+0A96): X=657.0,Y=591.0 (should be at cap-height 592?)

	* uni0A97 (U+0A97): X=505.0,Y=591.0 (should be at cap-height 592?)

	* uni0A98 (U+0A98): X=482.0,Y=591.0 (should be at cap-height 592?)

	* uni0A9A (U+0A9A): X=512.0,Y=591.0 (should be at cap-height 592?)

	* uni0A9A (U+0A9A): X=522.5,Y=-0.5 (should be at baseline 0?)

	* uni0A9D (U+0A9D): X=547.0,Y=591.0 (should be at cap-height 592?)

	* uni0A9E (U+0A9E): X=573.0,Y=591.0 (should be at cap-height 592?)

	* uni0A9F (U+0A9F): X=268.0,Y=-2.0 (should be at baseline 0?)

	* uni0A9F (U+0A9F): X=268.0,Y=-2.0 (should be at baseline 0?)

	* uni0AA3 (U+0AA3): X=128.0,Y=594.0 (should be at cap-height 592?)

	* uni0AA3 (U+0AA3): X=679.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA3 (U+0AA3): X=342.0,Y=593.0 (should be at cap-height 592?)

	* uni0AA4 (U+0AA4): X=439.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA5 (U+0AA5): X=460.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA6 (U+0AA6): X=337.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA7 (U+0AA7): X=470.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA8 (U+0AA8): X=417.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA8 (U+0AA8): X=428.5,Y=-0.5 (should be at baseline 0?)

	* uni0AAA (U+0AAA): X=445.0,Y=591.0 (should be at cap-height 592?)

	* uni0AAC (U+0AAC): X=603.0,Y=591.0 (should be at cap-height 592?)

	* uni0AAD (U+0AAD): X=644.0,Y=591.0 (should be at cap-height 592?)

	* uni0AAE (U+0AAE): X=476.0,Y=591.0 (should be at cap-height 592?)

	* uni0AAF (U+0AAF): X=177.5,Y=590.0 (should be at cap-height 592?)

	* uni0AAF (U+0AAF): X=476.0,Y=591.0 (should be at cap-height 592?)

	* uni0AB2 (U+0AB2): X=524.0,Y=591.0 (should be at cap-height 592?)

	* uni0AB3 (U+0AB3): X=208.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB5 (U+0AB5): X=468.0,Y=591.0 (should be at cap-height 592?)

	* uni0AB6 (U+0AB6): X=585.5,Y=-0.5 (should be at baseline 0?)

	* uni0AB6 (U+0AB6): X=574.0,Y=591.0 (should be at cap-height 592?)

	* uni0AB6 (U+0AB6): X=401.0,Y=-2.0 (should be at baseline 0?)

	* uni0AB7 (U+0AB7): X=475.0,Y=591.0 (should be at cap-height 592?)

	* uni0AB7 (U+0AB7): X=486.5,Y=-0.5 (should be at baseline 0?)

	* uni0AB8 (U+0AB8): X=567.0,Y=591.0 (should be at cap-height 592?)

	* uni0ABE (U+0ABE): X=146.0,Y=591.0 (should be at cap-height 592?)

	* uni0AC9 (U+0AC9): X=146.0,Y=591.0 (should be at cap-height 592?)

	* uni0ACB (U+0ACB): X=146.0,Y=591.0 (should be at cap-height 592?)

	* uni0ACC (U+0ACC): X=146.0,Y=591.0 (should be at cap-height 592?)

	* uni0AD0 (U+0AD0): X=172.0,Y=590.0 (should be at cap-height 592?)

	* uni0AE0 (U+0AE0): X=464.0,Y=591.0 (should be at cap-height 592?)

	* uni0AE1 (U+0AE1): X=577.0,Y=-1.0 (should be at baseline 0?)

	* uni0AE7 (U+0AE7): X=178.0,Y=593.0 (should be at cap-height 592?)

	* uni0AE8 (U+0AE8): X=128.0,Y=590.0 (should be at cap-height 592?)

	* uni0AE8 (U+0AE8): X=158.5,Y=594.0 (should be at cap-height 592?)

	* uni0AE9 (U+0AE9): X=216.0,Y=593.0 (should be at cap-height 592?)

	* uni0AEA (U+0AEA): X=36.5,Y=590.5 (should be at cap-height 592?)

	* uni0AEB (U+0AEB): X=112.5,Y=593.0 (should be at cap-height 592?)

	* uni0AEB (U+0AEB): X=429.0,Y=591.0 (should be at cap-height 592?)

	* uni0AED (U+0AED): X=252.0,Y=593.0 (should be at cap-height 592?)

	* Wgrave (U+1E80): X=166.0,Y=593.0 (should be at cap-height 592?)

	* Wgrave (U+1E80): X=865.0,Y=590.0 (should be at cap-height 592?)

	* Wacute (U+1E82): X=166.0,Y=593.0 (should be at cap-height 592?)

	* Wacute (U+1E82): X=865.0,Y=590.0 (should be at cap-height 592?)

	* Wdieresis (U+1E84): X=166.0,Y=593.0 (should be at cap-height 592?)

	* Wdieresis (U+1E84): X=865.0,Y=590.0 (should be at cap-height 592?)

	* Euro (U+20AC): X=417.0,Y=1.5 (should be at baseline 0?)

	* fractionOneQuartercinf (U+A830): X=105.0,Y=2.0 (should be at baseline 0?)

	* fractionOneQuartercinf (U+A830): X=144.0,Y=591.0 (should be at cap-height 592?)

	* fractionOneHalfcinf (U+A831): X=306.0,Y=2.0 (should be at baseline 0?)

	* fractionOneHalfcinf (U+A831): X=344.0,Y=591.0 (should be at cap-height 592?)

	* fractionOneHalfcinf (U+A831): X=105.0,Y=2.0 (should be at baseline 0?)

	* fractionOneHalfcinf (U+A831): X=144.0,Y=591.0 (should be at cap-height 592?)

	* fractionThreeQuarterscinf (U+A832): X=506.0,Y=2.0 (should be at baseline 0?)

	* fractionThreeQuarterscinf (U+A832): X=544.0,Y=591.0 (should be at cap-height 592?)

	* fractionThreeQuarterscinf (U+A832): X=105.0,Y=2.0 (should be at baseline 0?)

	* fractionThreeQuarterscinf (U+A832): X=144.0,Y=591.0 (should be at cap-height 592?)

	* fractionThreeQuarterscinf (U+A832): X=306.0,Y=2.0 (should be at baseline 0?)

	* fractionThreeQuarterscinf (U+A832): X=344.0,Y=591.0 (should be at cap-height 592?)

	* rupeeMarkcinf (U+A838): X=142.0,Y=593.0 (should be at cap-height 592?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648

	* uni0AA0 (U+0AA0): B<<249.0,338.0>-<263.0,338.0>-<277.0,335.0>>/B<<277.0,335.0>-<242.0,350.0>-<211.0,369.5>> = 11.103833436636071

	* uni0AFC (U+0AFC): B<<-210.5,708.5>-<-182.0,716.0>-<-155.0,729.0>>/B<<-155.0,729.0>-<-168.0,725.0>-<-180.5,724.0>> = 8.607224811758856 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSerifGujarati-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk (U+002A): X=215.0,Y=593.0 (should be at cap-height 592?)

	* asterisk (U+002A): X=239.0,Y=593.0 (should be at cap-height 592?)

	* four (U+0034): X=349.0,Y=591.5 (should be at cap-height 592?)

	* nine (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* K (U+004B): X=519.0,Y=590.0 (should be at cap-height 592?)

	* W (U+0057): X=184.0,Y=591.0 (should be at cap-height 592?)

	* X (U+0058): X=420.0,Y=593.0 (should be at cap-height 592?)

	* t (U+0074): X=112.0,Y=590.0 (should be at cap-height 592?)

	* t (U+0074): X=297.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=412.0,Y=534.0 (should be at x-height 536?)

	* w (U+0077): X=462.0,Y=534.0 (should be at x-height 536?)

	* y (U+0079): X=269.0,Y=-1.0 (should be at baseline 0?)

	* cent (U+00A2): X=460.0,Y=590.0 (should be at cap-height 592?)

	* sterling (U+00A3): X=354.5,Y=-2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=79.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=460.5,Y=1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=269.0,Y=-1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=269.0,Y=-1.0 (should be at baseline 0?)

	* uni0136 (U+0136): X=519.0,Y=590.0 (should be at cap-height 592?)

	* tcaron (U+0165): X=112.0,Y=590.0 (should be at cap-height 592?)

	* tcaron (U+0165): X=297.0,Y=1.0 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=184.0,Y=591.0 (should be at cap-height 592?)

	* ycircumflex (U+0177): X=269.0,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=112.0,Y=590.0 (should be at cap-height 592?)

	* uni021B (U+021B): X=297.0,Y=1.0 (should be at baseline 0?)

	* uni0A85 (U+0A85): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A86 (U+0A86): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A86 (U+0A86): X=966.0,Y=2.0 (should be at baseline 0?)

	* uni0A87 (U+0A87): X=383.0,Y=590.0 (should be at cap-height 592?)

	* uni0A89 (U+0A89): X=308.5,Y=590.0 (should be at cap-height 592?)

	* uni0A8A (U+0A8A): X=729.0,Y=2.0 (should be at baseline 0?)

	* uni0A8A (U+0A8A): X=308.5,Y=590.0 (should be at cap-height 592?)

	* uni0A8D (U+0A8D): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A8F (U+0A8F): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A90 (U+0A90): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A91 (U+0A91): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A91 (U+0A91): X=966.0,Y=2.0 (should be at baseline 0?)

	* uni0A93 (U+0A93): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A93 (U+0A93): X=966.0,Y=2.0 (should be at baseline 0?)

	* uni0A94 (U+0A94): X=730.0,Y=1.5 (should be at baseline 0?)

	* uni0A94 (U+0A94): X=966.0,Y=2.0 (should be at baseline 0?)

	* uni0A96 (U+0A96): X=675.5,Y=2.0 (should be at baseline 0?)

	* uni0A97 (U+0A97): X=524.0,Y=1.5 (should be at baseline 0?)

	* uni0A98 (U+0A98): X=502.0,Y=2.0 (should be at baseline 0?)

	* uni0A9A (U+0A9A): X=531.5,Y=1.5 (should be at baseline 0?)

	* uni0A9E (U+0A9E): X=116.0,Y=593.0 (should be at cap-height 592?)

	* uni0A9E (U+0A9E): X=593.0,Y=1.5 (should be at baseline 0?)

	* uni0A9F (U+0A9F): X=274.0,Y=-2.0 (should be at baseline 0?)

	* uni0A9F (U+0A9F): X=274.0,Y=-2.0 (should be at baseline 0?)

	* uni0AA3 (U+0AA3): X=708.0,Y=2.0 (should be at baseline 0?)

	* uni0AA3 (U+0AA3): X=305.5,Y=590.0 (should be at cap-height 592?)

	* uni0AA3 (U+0AA3): X=341.0,Y=593.0 (should be at cap-height 592?)

	* uni0AA4 (U+0AA4): X=458.0,Y=2.0 (should be at baseline 0?)

	* uni0AA5 (U+0AA5): X=253.0,Y=590.0 (should be at cap-height 592?)

	* uni0AA5 (U+0AA5): X=484.5,Y=1.5 (should be at baseline 0?)

	* uni0AA6 (U+0AA6): X=334.0,Y=590.0 (should be at cap-height 592?)

	* uni0AA7 (U+0AA7): X=488.0,Y=2.0 (should be at baseline 0?)

	* uni0AA8 (U+0AA8): X=440.0,Y=1.5 (should be at baseline 0?)

	* uni0AAA (U+0AAA): X=461.0,Y=2.0 (should be at baseline 0?)

	* uni0AAC (U+0AAC): X=620.5,Y=1.5 (should be at baseline 0?)

	* uni0AAD (U+0AAD): X=332.0,Y=591.0 (should be at cap-height 592?)

	* uni0AAD (U+0AAD): X=663.0,Y=1.5 (should be at baseline 0?)

	* uni0AAE (U+0AAE): X=495.0,Y=2.0 (should be at baseline 0?)

	* uni0AAF (U+0AAF): X=490.5,Y=1.5 (should be at baseline 0?)

	* uni0AB2 (U+0AB2): X=547.0,Y=2.0 (should be at baseline 0?)

	* uni0AB3 (U+0AB3): X=629.0,Y=1.5 (should be at baseline 0?)

	* uni0AB5 (U+0AB5): X=479.0,Y=2.0 (should be at baseline 0?)

	* uni0AB6 (U+0AB6): X=607.5,Y=1.5 (should be at baseline 0?)

	* uni0AB7 (U+0AB7): X=488.0,Y=1.5 (should be at baseline 0?)

	* uni0AB8 (U+0AB8): X=584.0,Y=1.5 (should be at baseline 0?)

	* uni0AB9 (U+0AB9): X=513.0,Y=-0.5 (should be at baseline 0?)

	* uni0ABE (U+0ABE): X=165.0,Y=2.0 (should be at baseline 0?)

	* uni0ABF (U+0ABF): X=165.5,Y=1.5 (should be at baseline 0?)

	* uni0AC0 (U+0AC0): X=174.0,Y=1.5 (should be at baseline 0?)

	* uni0AC9 (U+0AC9): X=165.0,Y=2.0 (should be at baseline 0?)

	* uni0ACB (U+0ACB): X=165.0,Y=2.0 (should be at baseline 0?)

	* uni0ACC (U+0ACC): X=165.0,Y=2.0 (should be at baseline 0?)

	* uni0AD0 (U+0AD0): X=171.0,Y=590.0 (should be at cap-height 592?)

	* uni0AE0 (U+0AE0): X=484.0,Y=1.5 (should be at baseline 0?)

	* uni0AE3 (U+0AE3): X=343.0,Y=-449.0 (should be at descender -450?)

	* uni0AE7 (U+0AE7): X=341.0,Y=1.5 (should be at baseline 0?)

	* uni0AE7 (U+0AE7): X=163.0,Y=594.0 (should be at cap-height 592?)

	* uni0AE8 (U+0AE8): X=126.0,Y=591.0 (should be at cap-height 592?)

	* uni0AEB (U+0AEB): X=456.5,Y=1.5 (should be at baseline 0?)

	* uni0AED (U+0AED): X=242.0,Y=594.0 (should be at cap-height 592?)

	* uni0AF9 (U+0AF9): X=225.5,Y=1.5 (should be at baseline 0?)

	* uni0AF9 (U+0AF9): X=286.5,Y=1.5 (should be at baseline 0?)

	* uni0AF9 (U+0AF9): X=66.5,Y=1.5 (should be at baseline 0?)

	* uni0AF9 (U+0AF9): X=127.0,Y=1.5 (should be at baseline 0?)

	* Wgrave (U+1E80): X=184.0,Y=591.0 (should be at cap-height 592?)

	* Wacute (U+1E82): X=184.0,Y=591.0 (should be at cap-height 592?)

	* Wdieresis (U+1E84): X=184.0,Y=591.0 (should be at cap-height 592?)

	* ygrave (U+1EF3): X=269.0,Y=-1.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=393.0,Y=2.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=416.0,Y=2.0 (should be at baseline 0?)

	* quantityMarkcinf (U+A839): X=259.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-223.0,710.5>-<-197.0,716.0>-<-173.0,727.0>>/B<<-173.0,727.0>-<-186.0,724.0>-<-197.5,723.0>> = 11.6289479942471 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifGujarati-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0A9A
	* uni0A9C0ACD
	* uni0AE1
	* zh_ra_aaMatragujarati
	* zh_ra_iiMatragujarati
	* zh_ragujarati and zhgujarati
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three (U+0033): X=167.0,Y=594.0 (should be at cap-height 595?)

	* three (U+0033): X=337.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=2.0 (should be at baseline 0?)

	* W (U+0057): X=882.0,Y=596.0 (should be at cap-height 595?)

	* X (U+0058): X=539.0,Y=597.0 (should be at cap-height 595?)

	* a (U+0061): X=183.5,Y=537.0 (should be at x-height 536?)

	* a (U+0061): X=271.0,Y=1.5 (should be at baseline 0?)

	* b (U+0062): X=215.0,Y=537.5 (should be at x-height 536?)

	* c (U+0063): X=371.0,Y=535.0 (should be at x-height 536?)

	* f (U+0066): X=229.0,Y=594.0 (should be at cap-height 595?)

	* g (U+0067): X=324.5,Y=537.0 (should be at x-height 536?)

	* g (U+0067): X=316.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=213.0,Y=-1.0 (should be at baseline 0?)

	* q (U+0071): X=408.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=259.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=78.0,Y=2.0 (should be at baseline 0?)

	* yen (U+00A5): X=406.5,Y=596.5 (should be at cap-height 595?)

	* agrave (U+00E0): X=271.0,Y=1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=271.0,Y=1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=271.0,Y=1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=271.0,Y=1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=271.0,Y=1.5 (should be at baseline 0?)

	* aring (U+00E5): X=271.0,Y=1.5 (should be at baseline 0?)

	* aring (U+00E5): X=286.0,Y=596.0 (should be at cap-height 595?)

	* aring (U+00E5): X=286.0,Y=596.0 (should be at cap-height 595?)

	* yacute (U+00FD): X=259.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=259.0,Y=2.0 (should be at baseline 0?)

	* amacron (U+0101): X=271.0,Y=1.5 (should be at baseline 0?)

	* abreve (U+0103): X=271.0,Y=1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=271.0,Y=1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=527.5,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=316.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=213.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=527.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=316.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=213.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=527.5,Y=2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=316.0,Y=-1.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=213.0,Y=-1.0 (should be at baseline 0?)

	* uring (U+016F): X=308.0,Y=596.0 (should be at cap-height 595?)

	* uring (U+016F): X=308.0,Y=596.0 (should be at cap-height 595?)

	* Wcircumflex (U+0174): X=882.0,Y=596.0 (should be at cap-height 595?)

	* ycircumflex (U+0177): X=259.0,Y=2.0 (should be at baseline 0?)

	* ring (U+02DA): X=166.0,Y=596.0 (should be at cap-height 595?)

	* ring (U+02DA): X=166.0,Y=596.0 (should be at cap-height 595?)

	* uni030A (U+030A): X=0.0,Y=596.0 (should be at cap-height 595?)

	* uni030A (U+030A): X=0.0,Y=596.0 (should be at cap-height 595?)

	* uni0AAB (U+0AAB): X=205.0,Y=1.0 (should be at baseline 0?)

	* uni0AAE (U+0AAE): X=44.5,Y=596.5 (should be at cap-height 595?)

	* uni0AB0 (U+0AB0): X=113.0,Y=593.5 (should be at cap-height 595?)

	* uni0AB3 (U+0AB3): X=166.0,Y=597.0 (should be at cap-height 595?)

	* uni0AB7 (U+0AB7): X=101.5,Y=597.0 (should be at cap-height 595?)

	* uni0AB8 (U+0AB8): X=95.5,Y=594.5 (should be at cap-height 595?)

	* uni0ABD (U+0ABD): X=264.0,Y=593.0 (should be at cap-height 595?)

	* uni0ABD (U+0ABD): X=396.0,Y=593.0 (should be at cap-height 595?)

	* uni0AD0 (U+0AD0): X=337.0,Y=-1.0 (should be at baseline 0?)

	* uni0AD0 (U+0AD0): X=337.0,Y=-1.0 (should be at baseline 0?)

	* uni0AE7 (U+0AE7): X=145.0,Y=596.0 (should be at cap-height 595?)

	* uni0AE8 (U+0AE8): X=124.0,Y=593.0 (should be at cap-height 595?)

	* uni0AE8 (U+0AE8): X=152.5,Y=595.5 (should be at cap-height 595?)

	* uni0AE8 (U+0AE8): X=182.0,Y=597.0 (should be at cap-height 595?)

	* uni0AEA (U+0AEA): X=62.0,Y=596.0 (should be at cap-height 595?)

	* uni0AEB (U+0AEB): X=32.0,Y=595.5 (should be at cap-height 595?)

	* uni0AEC (U+0AEC): X=29.0,Y=1.0 (should be at baseline 0?)

	* uni0AEF (U+0AEF): X=439.5,Y=2.0 (should be at baseline 0?)

	* Wgrave (U+1E80): X=882.0,Y=596.0 (should be at cap-height 595?)

	* Wacute (U+1E82): X=882.0,Y=596.0 (should be at cap-height 595?)

	* Wdieresis (U+1E84): X=882.0,Y=596.0 (should be at cap-height 595?)

	* ygrave (U+1EF3): X=259.0,Y=2.0 (should be at baseline 0?)

	* quoteright (U+2019): X=89.5,Y=596.5 (should be at cap-height 595?)

	* quotedblright (U+201D): X=289.5,Y=596.5 (should be at cap-height 595?)

	* quotedblright (U+201D): X=89.5,Y=596.5 (should be at cap-height 595?)

	* uni20B9 (U+20B9): X=400.0,Y=1.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=438.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-290.0,709.0>-<-238.0,709.0>-<-200.0,724.0>>/B<<-200.0,724.0>-<-212.0,722.0>-<-222.0,721.5>> = 12.078653710512796 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<408.0,339.0>--<251.0,340.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSerifGujarati-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: 'sha-gujarati'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* zh_ra_aaMatragujarati and zh_ra_iiMatragujarati
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=72.0,Y=590.0 (should be at cap-height 592?)

	* three (U+0033): X=70.0,Y=590.0 (should be at cap-height 592?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=408.0,Y=593.0 (should be at cap-height 592?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* V (U+0056): X=580.0,Y=594.0 (should be at cap-height 592?)

	* W (U+0057): X=943.0,Y=594.0 (should be at cap-height 592?)

	* Y (U+0059): X=533.0,Y=594.0 (should be at cap-height 592?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* cent (U+00A2): X=472.0,Y=593.0 (should be at cap-height 592?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* yen (U+00A5): X=469.0,Y=594.0 (should be at cap-height 592?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* Yacute (U+00DD): X=533.0,Y=594.0 (should be at cap-height 592?)

	* dcroat (U+0111): X=412.0,Y=593.0 (should be at cap-height 592?)

	* dcroat (U+0111): X=241.0,Y=593.0 (should be at cap-height 592?)

	* dcroat (U+0111): X=597.0,Y=593.0 (should be at cap-height 592?)

	* dcroat (U+0111): X=506.0,Y=593.0 (should be at cap-height 592?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* hbar (U+0127): X=108.0,Y=593.0 (should be at cap-height 592?)

	* hbar (U+0127): X=17.0,Y=593.0 (should be at cap-height 592?)

	* hbar (U+0127): X=373.0,Y=593.0 (should be at cap-height 592?)

	* hbar (U+0127): X=202.0,Y=593.0 (should be at cap-height 592?)

	* Wcircumflex (U+0174): X=943.0,Y=594.0 (should be at cap-height 592?)

	* Ycircumflex (U+0176): X=533.0,Y=594.0 (should be at cap-height 592?)

	* Ydieresis (U+0178): X=533.0,Y=594.0 (should be at cap-height 592?)

	* uni0A89 (U+0A89): X=83.0,Y=591.5 (should be at cap-height 592?)

	* uni0A8A (U+0A8A): X=83.0,Y=591.5 (should be at cap-height 592?)

	* uni0A8A (U+0A8A): X=655.0,Y=592.5 (should be at cap-height 592?)

	* uni0A9F (U+0A9F): X=281.0,Y=-2.0 (should be at baseline 0?)

	* uni0A9F (U+0A9F): X=281.0,Y=-2.0 (should be at baseline 0?)

	* uni0AA3 (U+0AA3): X=307.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA3 (U+0AA3): X=340.0,Y=593.0 (should be at cap-height 592?)

	* uni0AA6 (U+0AA6): X=330.0,Y=590.0 (should be at cap-height 592?)

	* uni0AAB (U+0AAB): X=202.0,Y=1.0 (should be at baseline 0?)

	* uni0AB0 (U+0AB0): X=112.0,Y=592.5 (should be at cap-height 592?)

	* uni0AB8 (U+0AB8): X=92.5,Y=593.0 (should be at cap-height 592?)

	* uni0AB9 (U+0AB9): X=513.0,Y=-1.0 (should be at baseline 0?)

	* uni0AD0 (U+0AD0): X=170.0,Y=590.0 (should be at cap-height 592?)

	* uni0AEA (U+0AEA): X=29.0,Y=591.5 (should be at cap-height 592?)

	* uni0AEB (U+0AEB): X=6.0,Y=590.0 (should be at cap-height 592?)

	* uni0AED (U+0AED): X=263.0,Y=-2.0 (should be at baseline 0?)

	* uni0AED (U+0AED): X=229.0,Y=594.0 (should be at cap-height 592?)

	* uni0AED (U+0AED): X=263.0,Y=-2.0 (should be at baseline 0?)

	* uni0AEF (U+0AEF): X=435.0,Y=2.0 (should be at baseline 0?)

	* Wgrave (U+1E80): X=943.0,Y=594.0 (should be at cap-height 592?)

	* Wacute (U+1E82): X=943.0,Y=594.0 (should be at cap-height 592?)

	* Wdieresis (U+1E84): X=943.0,Y=594.0 (should be at cap-height 592?)

	* Ygrave (U+1EF2): X=533.0,Y=594.0 (should be at cap-height 592?)

	* quoteright (U+2019): X=114.0,Y=590.0 (should be at cap-height 592?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=310.0,Y=590.0 (should be at cap-height 592?)

	* quotedblright (U+201D): X=114.0,Y=590.0 (should be at cap-height 592?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSerifGujarati-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* uni0A85
	* uni0A86
	* uni0A8C
	* uni0A8D
	* uni0A8F
	* uni0A90
	* uni0A91
	* uni0A93
	* uni0A94
	* uni0A96
	* uni0A9A
	* uni0A9C
	* uni0A9C0ACD
	* uni0A9D
	* uni0A9D0ACD
	* uni0AAE
	* uni0AE1
	* uni0AF9
	* zh_ra_aaMatragujarati
	* zh_ra_iiMatragujarati
	* zh_ragujarati and zhgujarati
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk (U+002A): X=269.0,Y=599.0 (should be at cap-height 598?)

	* comma (U+002C): X=179.0,Y=-1.0 (should be at baseline 0?)

	* three (U+0033): X=340.0,Y=1.0 (should be at baseline 0?)

	* four (U+0034): X=294.5,Y=597.0 (should be at cap-height 598?)

	* semicolon (U+003B): X=179.0,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=126.0,Y=600.0 (should be at cap-height 598?)

	* K (U+004B): X=481.0,Y=598.5 (should be at cap-height 598?)

	* Q (U+0051): X=470.0,Y=-2.0 (should be at baseline 0?)

	* Y (U+0059): X=237.0,Y=597.5 (should be at cap-height 598?)

	* a (U+0061): X=186.5,Y=538.0 (should be at x-height 536?)

	* y (U+0079): X=254.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=343.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=92.0,Y=600.0 (should be at cap-height 598?)

	* section (U+00A7): X=434.5,Y=597.0 (should be at cap-height 598?)

	* Yacute (U+00DD): X=237.0,Y=597.5 (should be at cap-height 598?)

	* aring (U+00E5): X=294.0,Y=596.0 (should be at cap-height 598?)

	* aring (U+00E5): X=294.0,Y=596.0 (should be at cap-height 598?)

	* yacute (U+00FD): X=254.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=343.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=343.0,Y=-2.0 (should be at baseline 0?)

	* dcaron (U+010F): X=638.0,Y=600.0 (should be at cap-height 598?)

	* dcaron (U+010F): X=587.0,Y=600.0 (should be at cap-height 598?)

	* uni0136 (U+0136): X=481.0,Y=598.5 (should be at cap-height 598?)

	* lcaron (U+013E): X=339.0,Y=600.0 (should be at cap-height 598?)

	* lcaron (U+013E): X=288.0,Y=600.0 (should be at cap-height 598?)

	* tcaron (U+0165): X=340.0,Y=600.0 (should be at cap-height 598?)

	* tcaron (U+0165): X=289.0,Y=600.0 (should be at cap-height 598?)

	* uring (U+016F): X=313.0,Y=596.0 (should be at cap-height 598?)

	* uring (U+016F): X=313.0,Y=596.0 (should be at cap-height 598?)

	* Ycircumflex (U+0176): X=237.0,Y=597.5 (should be at cap-height 598?)

	* ycircumflex (U+0177): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=343.0,Y=-2.0 (should be at baseline 0?)

	* Ydieresis (U+0178): X=237.0,Y=597.5 (should be at cap-height 598?)

	* ring (U+02DA): X=166.0,Y=596.0 (should be at cap-height 598?)

	* ring (U+02DA): X=166.0,Y=596.0 (should be at cap-height 598?)

	* uni030A (U+030A): X=0.0,Y=596.0 (should be at cap-height 598?)

	* uni030A (U+030A): X=0.0,Y=596.0 (should be at cap-height 598?)

	* uni0A87 (U+0A87): X=282.0,Y=600.0 (should be at cap-height 598?)

	* uni0A88 (U+0A88): X=282.0,Y=600.0 (should be at cap-height 598?)

	* uni0A89 (U+0A89): X=370.0,Y=600.0 (should be at cap-height 598?)

	* uni0A89 (U+0A89): X=204.0,Y=600.0 (should be at cap-height 598?)

	* uni0A8A (U+0A8A): X=370.0,Y=600.0 (should be at cap-height 598?)

	* uni0A95 (U+0A95): X=393.0,Y=599.0 (should be at cap-height 598?)

	* uni0A96 (U+0A96): X=9.0,Y=597.5 (should be at cap-height 598?)

	* uni0A98 (U+0A98): X=270.0,Y=599.0 (should be at cap-height 598?)

	* uni0A99 (U+0A99): X=393.0,Y=599.0 (should be at cap-height 598?)

	* uni0AA0 (U+0AA0): X=385.0,Y=599.0 (should be at cap-height 598?)

	* uni0AA1 (U+0AA1): X=393.0,Y=599.0 (should be at cap-height 598?)

	* uni0AA3 (U+0AA3): X=362.0,Y=599.0 (should be at cap-height 598?)

	* uni0AAA (U+0AAA): X=9.0,Y=597.5 (should be at cap-height 598?)

	* uni0AAB (U+0AAB): X=373.0,Y=599.0 (should be at cap-height 598?)

	* uni0AAB (U+0AAB): X=209.0,Y=2.0 (should be at baseline 0?)

	* uni0AAE (U+0AAE): X=40.5,Y=596.5 (should be at cap-height 598?)

	* uni0AB3 (U+0AB3): X=163.0,Y=600.0 (should be at cap-height 598?)

	* uni0AB6 (U+0AB6): X=251.0,Y=600.0 (should be at cap-height 598?)

	* uni0AB7 (U+0AB7): X=21.5,Y=598.5 (should be at cap-height 598?)

	* uni0ABF (U+0ABF): X=84.0,Y=600.0 (should be at cap-height 598?)

	* uni0AD0 (U+0AD0): X=344.0,Y=-2.0 (should be at baseline 0?)

	* uni0AD0 (U+0AD0): X=344.0,Y=-2.0 (should be at baseline 0?)

	* uni0AE1 (U+0AE1): X=811.0,Y=2.0 (should be at baseline 0?)

	* uni0AE3 (U+0AE3): X=425.5,Y=-448.0 (should be at descender -450?)

	* uni0AE7 (U+0AE7): X=148.0,Y=597.0 (should be at cap-height 598?)

	* uni0AE8 (U+0AE8): X=157.0,Y=596.5 (should be at cap-height 598?)

	* uni0AE9 (U+0AE9): X=216.0,Y=599.0 (should be at cap-height 598?)

	* uni0AEA (U+0AEA): X=66.0,Y=597.0 (should be at cap-height 598?)

	* uni0AEB (U+0AEB): X=34.0,Y=596.0 (should be at cap-height 598?)

	* uni0AEB (U+0AEB): X=73.0,Y=600.0 (should be at cap-height 598?)

	* uni0AEC (U+0AEC): X=35.0,Y=2.0 (should be at baseline 0?)

	* uni0AED (U+0AED): X=237.0,Y=597.0 (should be at cap-height 598?)

	* uni0AEF (U+0AEF): X=445.5,Y=2.0 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=199.0,Y=599.0 (should be at cap-height 598?)

	* Ygrave (U+1EF2): X=237.0,Y=597.5 (should be at cap-height 598?)

	* ygrave (U+1EF3): X=254.0,Y=-2.0 (should be at baseline 0?)

	* ygrave (U+1EF3): X=343.0,Y=-2.0 (should be at baseline 0?)

	* quotesinglbase (U+201A): X=119.0,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=324.5,Y=-1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=119.0,Y=-1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=419.5,Y=596.5 (should be at cap-height 598?)

	* uni20B9 (U+20B9): X=409.0,Y=2.0 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=465.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-245.5,712.0>-<-224.0,715.0>-<-202.0,723.0>>/B<<-202.0,723.0>-<-213.0,721.0>-<-223.5,720.5>> = 9.678260053133936 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<104.0,119.0>--<103.0,648.0>>

	* h (U+0068): L<<233.0,313.0>--<234.0,115.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSerifGujarati-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 997 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, tifinagh, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, coptic, math, tai-le, tifinagh, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: sharada, tirhuta, devanagari, telugu, grantha
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, grantha, tirhuta, devanagari
 * U+2010 HYPHEN: try adding one of: kayah-li, kharoshthi, sora-sompeng, lisu, yi, coptic, cham, sundanese, kaithi, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=147.5,Y=-1.5 (should be at baseline 0?)

	* semicolon (U+003B): X=147.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=407.0,Y=1.5 (should be at baseline 0?)

	* G (U+0047): X=477.5,Y=-1.5 (should be at baseline 0?)

	* K (U+004B): X=457.0,Y=593.0 (should be at cap-height 592?)

	* g (U+0067): X=394.0,Y=537.5 (should be at x-height 536?)

	* t (U+0074): X=53.5,Y=536.5 (should be at x-height 536?)

	* sterling (U+00A3): X=362.5,Y=-1.5 (should be at baseline 0?)

	* sterling (U+00A3): X=464.5,Y=-0.5 (should be at baseline 0?)

	* copyright (U+00A9): X=422.0,Y=591.0 (should be at cap-height 592?)

	* Ccedilla (U+00C7): X=407.0,Y=1.5 (should be at baseline 0?)

	* Cacute (U+0106): X=407.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=407.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=407.0,Y=1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=477.5,Y=-1.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=477.5,Y=-1.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=477.5,Y=-1.5 (should be at baseline 0?)

	* uni0136 (U+0136): X=457.0,Y=593.0 (should be at cap-height 592?)

	* Eng (U+014A): X=566.0,Y=1.0 (should be at baseline 0?)

	* uni0A85 (U+0A85): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A86 (U+0A86): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A86 (U+0A86): X=934.0,Y=594.0 (should be at cap-height 592?)

	* uni0A89 (U+0A89): X=318.0,Y=591.0 (should be at cap-height 592?)

	* uni0A8A (U+0A8A): X=318.0,Y=591.0 (should be at cap-height 592?)

	* uni0A8B (U+0A8B): X=448.0,Y=594.0 (should be at cap-height 592?)

	* uni0A8B (U+0A8B): X=460.0,Y=-1.5 (should be at baseline 0?)

	* uni0A8C (U+0A8C): X=641.5,Y=1.5 (should be at baseline 0?)

	* uni0A8D (U+0A8D): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A8F (U+0A8F): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A90 (U+0A90): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A91 (U+0A91): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A91 (U+0A91): X=934.0,Y=594.0 (should be at cap-height 592?)

	* uni0A93 (U+0A93): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A93 (U+0A93): X=934.0,Y=594.0 (should be at cap-height 592?)

	* uni0A94 (U+0A94): X=716.0,Y=594.0 (should be at cap-height 592?)

	* uni0A94 (U+0A94): X=934.0,Y=594.0 (should be at cap-height 592?)

	* uni0A96 (U+0A96): X=148.0,Y=593.0 (should be at cap-height 592?)

	* uni0A96 (U+0A96): X=652.0,Y=594.0 (should be at cap-height 592?)

	* uni0A97 (U+0A97): X=500.0,Y=594.0 (should be at cap-height 592?)

	* uni0A98 (U+0A98): X=477.0,Y=594.0 (should be at cap-height 592?)

	* uni0A9A (U+0A9A): X=55.0,Y=590.0 (should be at cap-height 592?)

	* uni0A9A (U+0A9A): X=506.0,Y=594.0 (should be at cap-height 592?)

	* uni0A9C (U+0A9C): X=697.0,Y=591.0 (should be at cap-height 592?)

	* uni0A9D (U+0A9D): X=545.0,Y=594.0 (should be at cap-height 592?)

	* uni0A9E (U+0A9E): X=181.0,Y=593.0 (should be at cap-height 592?)

	* uni0A9E (U+0A9E): X=567.0,Y=594.0 (should be at cap-height 592?)

	* uni0A9F (U+0A9F): X=265.0,Y=-2.0 (should be at baseline 0?)

	* uni0A9F (U+0A9F): X=265.0,Y=-2.0 (should be at baseline 0?)

	* uni0AA3 (U+0AA3): X=668.0,Y=594.0 (should be at cap-height 592?)

	* uni0AA3 (U+0AA3): X=342.0,Y=593.0 (should be at cap-height 592?)

	* uni0AA4 (U+0AA4): X=434.0,Y=594.0 (should be at cap-height 592?)

	* uni0AA5 (U+0AA5): X=451.0,Y=594.0 (should be at cap-height 592?)

	* uni0AA6 (U+0AA6): X=339.0,Y=591.0 (should be at cap-height 592?)

	* uni0AA7 (U+0AA7): X=466.0,Y=594.0 (should be at cap-height 592?)

	* uni0AA8 (U+0AA8): X=410.0,Y=594.0 (should be at cap-height 592?)

	* uni0AAA (U+0AAA): X=148.0,Y=593.0 (should be at cap-height 592?)

	* uni0AAA (U+0AAA): X=441.0,Y=594.0 (should be at cap-height 592?)

	* uni0AAC (U+0AAC): X=599.0,Y=594.0 (should be at cap-height 592?)

	* uni0AAD (U+0AAD): X=640.0,Y=594.0 (should be at cap-height 592?)

	* uni0AAE (U+0AAE): X=178.0,Y=593.0 (should be at cap-height 592?)

	* uni0AAE (U+0AAE): X=471.0,Y=594.0 (should be at cap-height 592?)

	* uni0AAF (U+0AAF): X=180.0,Y=590.5 (should be at cap-height 592?)

	* uni0AAF (U+0AAF): X=474.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB2 (U+0AB2): X=516.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB3 (U+0AB3): X=219.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB5 (U+0AB5): X=468.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB6 (U+0AB6): X=561.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB6 (U+0AB6): X=399.0,Y=-2.0 (should be at baseline 0?)

	* uni0AB7 (U+0AB7): X=475.0,Y=594.0 (should be at cap-height 592?)

	* uni0AB8 (U+0AB8): X=564.0,Y=594.0 (should be at cap-height 592?)

	* uni0ABE (U+0ABE): X=140.0,Y=594.0 (should be at cap-height 592?)

	* uni0AC9 (U+0AC9): X=140.0,Y=594.0 (should be at cap-height 592?)

	* uni0ACB (U+0ACB): X=140.0,Y=594.0 (should be at cap-height 592?)

	* uni0ACC (U+0ACC): X=140.0,Y=594.0 (should be at cap-height 592?)

	* uni0AD0 (U+0AD0): X=248.5,Y=592.5 (should be at cap-height 592?)

	* uni0AD0 (U+0AD0): X=172.0,Y=590.0 (should be at cap-height 592?)

	* uni0AE0 (U+0AE0): X=459.0,Y=594.0 (should be at cap-height 592?)

	* uni0AE1 (U+0AE1): X=572.0,Y=1.0 (should be at baseline 0?)

	* uni0AE8 (U+0AE8): X=161.0,Y=594.0 (should be at cap-height 592?)

	* uni0AEA (U+0AEA): X=38.5,Y=590.5 (should be at cap-height 592?)

	* uni0AEB (U+0AEB): X=419.0,Y=594.0 (should be at cap-height 592?)

	* uni0AED (U+0AED): X=258.0,Y=593.0 (should be at cap-height 592?)

	* uni0AF9 (U+0AF9): X=697.0,Y=591.0 (should be at cap-height 592?)

	* uni0AF9 (U+0AF9): X=259.0,Y=-1.0 (should be at baseline 0?)

	* uni0AF9 (U+0AF9): X=99.0,Y=-1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=406.0,Y=0.5 (should be at baseline 0?)

	* uni20B9 (U+20B9): X=357.0,Y=590.0 (should be at cap-height 592?)

	* fractionOneQuartercinf (U+A830): X=112.0,Y=-1.0 (should be at baseline 0?)

	* fractionOneQuartercinf (U+A830): X=140.0,Y=594.0 (should be at cap-height 592?)

	* fractionOneHalfcinf (U+A831): X=313.0,Y=-1.0 (should be at baseline 0?)

	* fractionOneHalfcinf (U+A831): X=340.0,Y=594.0 (should be at cap-height 592?)

	* fractionOneHalfcinf (U+A831): X=112.0,Y=-1.0 (should be at baseline 0?)

	* fractionOneHalfcinf (U+A831): X=140.0,Y=594.0 (should be at cap-height 592?)

	* fractionThreeQuarterscinf (U+A832): X=513.0,Y=-1.0 (should be at baseline 0?)

	* fractionThreeQuarterscinf (U+A832): X=540.0,Y=594.0 (should be at cap-height 592?)

	* fractionThreeQuarterscinf (U+A832): X=112.0,Y=-1.0 (should be at baseline 0?)

	* fractionThreeQuarterscinf (U+A832): X=140.0,Y=594.0 (should be at cap-height 592?)

	* fractionThreeQuarterscinf (U+A832): X=313.0,Y=-1.0 (should be at baseline 0?)

	* fractionThreeQuarterscinf (U+A832): X=340.0,Y=594.0 (should be at cap-height 592?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526

	* uni0AA0 (U+0AA0): B<<274.0,336.5>-<282.0,336.0>-<289.0,334.0>>/B<<289.0,334.0>-<252.0,349.0>-<219.5,368.5>> = 6.122503661487386

	* uni0AFC (U+0AFC): B<<-202.5,707.0>-<-172.0,716.0>-<-141.0,731.0>>/B<<-141.0,731.0>-<-156.0,726.0>-<-169.0,724.5>> = 7.386043151267186 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<161.0,714.0>--<158.0,167.0>>

	* exclamdown (U+00A1): L<<111.0,-177.0>--<114.0,370.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 1 | 18 | 80 | 1054 | 55 | 897 | 0 |
| 0% | 1% | 4% | 50% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
