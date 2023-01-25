## Fontbakery report

Fontbakery version: 0.8.11a9

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifGujarati/googlefonts/ttf', 'fonts/NotoSerifGujarati/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Serif Gujarati' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[9] NotoSerifGujarati-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* b_rgujarati
	* bh_ragujarati
	* bh_rgujarati
	* c_rgujarati
	* ch_vagujarati
	* ch_yagujarati
	* dd_yagujarati
	* ddh_ddhagujarati
	* ddh_yagujarati and 158 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 82 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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
</div></details><br></div></details><details><summary><b>[7] NotoSerifGujarati-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* bh_ragujarati
	* ch_vagujarati
	* ch_yagujarati
	* ddh_yagujarati
	* dh_nagujarati
	* dh_ragujarati
	* gh_nagujarati
	* gh_ragujarati
	* j_ny_ragujarati and 105 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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
</div></details><br></div></details><details><summary><b>[9] NotoSerifGujarati-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* b_rgujarati
	* bh_ragujarati
	* bh_rgujarati
	* ch_vagujarati
	* ch_yagujarati
	* ddh_yagujarati
	* dh_nagujarati
	* dh_ragujarati
	* dh_rgujarati and 132 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 80 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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
</div></details><br></div></details><details><summary><b>[7] NotoSerifGujarati-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648

	* uni0AA0 (U+0AA0): B<<249.0,338.0>-<263.0,338.0>-<277.0,335.0>>/B<<277.0,335.0>-<242.0,350.0>-<211.0,369.5>> = 11.103833436636071 

	* uni0AFC (U+0AFC): B<<-210.5,708.5>-<-182.0,716.0>-<-155.0,729.0>>/B<<-155.0,729.0>-<-168.0,725.0>-<-180.5,724.0>> = 8.607224811758856 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[8] NotoSerifGujarati-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* dh_nagujarati and uni006A0A9C
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-223.0,710.5>-<-197.0,716.0>-<-173.0,727.0>>/B<<-173.0,727.0>-<-186.0,724.0>-<-197.5,723.0>> = 11.6289479942471 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[9] NotoSerifGujarati-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* bh_ragujarati
	* ch_vagujarati
	* ddh_yagujarati
	* dh_nagujarati
	* gh_nagujarati
	* j_ny_ragujarati
	* j_ra_aaMatragujarati
	* j_ra_iiMatragujarati
	* j_rgujarati and 50 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 64 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-290.0,709.0>-<-238.0,709.0>-<-200.0,724.0>>/B<<-200.0,724.0>-<-212.0,722.0>-<-222.0,721.5>> = 12.078653710512796 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<408.0,339.0>--<251.0,340.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[7] NotoSerifGujarati-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/issues.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifGujarati/googlefonts/ttf/NotoSerifGujarati-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/issues.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">શૣ શ્રૣ શ્રૈ</span> (Issue #3)</li>


<pre>Expected: None</pre>



<pre>Got     : uni0AB6=0+709|uni0AE3=0@-126,0+0|space=2+299|sh_ragujarati=3+646|uni0AE3=3@-126,0+0|space=7+299|sh_ragujarati=8+646|uni0AC8=8@-125,0+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2599 2447" transform="matrix(1 0 0 -1 0 0)">
<path d="M678.0,-5.0Q655.0,-5.0 636.5,4.5Q618.0,14.0 595.0,31.0Q564.0,54.0 553.5,74.5Q543.0,95.0 543.0,125.0L543.0,612.0L624.0,579.0L624.0,61.0Q624.0,51.0 633.0,51.0Q651.0,51.0 672.5,62.5Q694.0,74.0 710.0,93.0L751.0,25.0Q739.0,15.0 720.5,5.0Q702.0,-5.0 678.0,-5.0ZM409.0,-3.0Q340.0,-3.0 291.0,23.0Q242.0,49.0 209.5,92.5Q177.0,136.0 155.0,188.0Q127.0,188.0 101.5,197.0Q76.0,206.0 60.0,224.0Q44.0,242.0 44.0,268.0Q44.0,288.0 58.5,303.5Q73.0,319.0 99.0,319.0Q143.0,319.0 176.0,273.0Q233.0,286.0 275.0,310.0Q248.0,325.0 218.0,349.0Q188.0,373.0 167.0,407.5Q146.0,442.0 146.0,488.0Q146.0,535.0 176.5,565.5Q207.0,596.0 253.0,596.0Q308.0,596.0 364.0,540.0Q433.0,471.0 433.0,396.0Q433.0,355.0 407.5,313.5Q382.0,272.0 331.0,240.0Q280.0,208.0 201.0,194.0Q233.0,131.0 283.0,107.5Q333.0,84.0 383.0,84.0Q398.0,84.0 412.5,85.5Q427.0,87.0 440.0,88.0L409.0,-3.0ZM221.0,456.0Q221.0,417.0 249.5,387.5Q278.0,358.0 315.0,338.0Q337.0,359.0 349.5,384.0Q362.0,409.0 362.0,438.0Q362.0,476.0 341.0,500.0Q320.0,524.0 289.0,524.0Q261.0,524.0 241.0,505.5Q221.0,487.0 221.0,456.0Z"  transform="translate(0, 950)"/>
<path d="M-35.0,-347.0Q-64.0,-327.0 -93.5,-296.5Q-123.0,-266.0 -142.0,-228.5Q-161.0,-191.0 -161.0,-151.0Q-161.0,-102.0 -129.5,-73.0Q-98.0,-44.0 -52.0,-44.0Q-25.0,-44.0 2.0,-59.0Q29.0,-74.0 50.0,-100.0Q66.0,-74.0 90.5,-61.0Q115.0,-48.0 144.0,-48.0Q167.0,-48.0 190.5,-55.5Q214.0,-63.0 241.0,-86.0Q272.0,-112.0 281.5,-134.0Q291.0,-156.0 291.0,-179.0Q291.0,-200.0 278.5,-216.0Q266.0,-232.0 253.5,-245.0Q241.0,-258.0 241.0,-271.0Q241.0,-291.0 270.0,-291.0Q287.0,-291.0 303.5,-288.5Q320.0,-286.0 340.0,-280.0L375.0,-332.0Q361.0,-335.0 339.0,-340.5Q317.0,-346.0 300.5,-355.0Q284.0,-364.0 284.0,-378.0Q284.0,-387.0 291.5,-393.5Q299.0,-400.0 318.0,-400.0Q344.0,-400.0 373.5,-391.5Q403.0,-383.0 426.0,-368.0L466.0,-415.0Q437.0,-435.0 405.5,-444.0Q374.0,-453.0 343.0,-453.0Q316.0,-453.0 293.5,-442.0Q271.0,-431.0 256.0,-415.0Q242.0,-400.0 234.0,-385.0Q226.0,-370.0 226.0,-353.0Q226.0,-337.0 237.0,-324.0Q220.0,-316.0 208.0,-304.0Q195.0,-290.0 186.5,-275.5Q178.0,-261.0 178.0,-243.0Q178.0,-222.0 190.0,-207.0Q202.0,-192.0 214.0,-177.0Q226.0,-162.0 226.0,-143.0Q226.0,-126.0 212.5,-115.0Q199.0,-104.0 177.0,-104.0Q145.0,-104.0 121.0,-127.5Q97.0,-151.0 97.0,-198.0Q97.0,-206.0 97.0,-213.0Q97.0,-220.0 98.0,-228.0L32.0,-209.0Q31.0,-203.0 30.5,-196.0Q30.0,-189.0 30.0,-184.0Q30.0,-153.0 38.0,-128.0Q22.0,-119.0 7.0,-115.0Q-8.0,-111.0 -23.0,-111.0Q-53.0,-111.0 -74.0,-130.0Q-95.0,-149.0 -95.0,-183.0Q-95.0,-221.0 -70.5,-254.5Q-46.0,-288.0 -12.0,-317.0L-35.0,-347.0Z"  transform="translate(583, 950)"/>
<path d=""  transform="translate(709, 950)"/>
<path d="M209.0,11.0L155.0,80.0L427.0,224.0Q393.0,235.0 349.0,252.5Q305.0,270.0 262.0,293.0Q222.0,266.0 173.0,245.0Q124.0,224.0 73.0,210.0L16.0,285.0Q60.0,296.0 101.5,310.5Q143.0,325.0 178.0,344.0Q133.0,378.0 103.0,419.0Q73.0,460.0 73.0,508.0Q73.0,558.0 106.5,587.5Q140.0,617.0 191.0,617.0Q216.0,617.0 241.0,608.0Q266.0,599.0 291.0,579.0Q321.0,555.0 345.0,521.0Q369.0,487.0 369.0,448.0Q369.0,413.0 350.5,381.5Q332.0,350.0 301.0,323.0Q338.0,305.0 382.5,287.5Q427.0,270.0 480.0,253.0L480.0,612.0L561.0,579.0L561.0,61.0Q561.0,51.0 570.0,51.0Q587.0,51.0 609.0,62.5Q631.0,74.0 647.0,93.0L688.0,25.0Q675.0,15.0 657.0,5.0Q639.0,-5.0 615.0,-5.0Q592.0,-5.0 573.0,4.5Q554.0,14.0 531.0,31.0Q500.0,55.0 490.0,75.0Q480.0,95.0 480.0,125.0L480.0,172.0L209.0,11.0ZM155.0,480.0Q155.0,421.0 221.0,371.0Q252.0,394.0 270.5,422.5Q289.0,451.0 289.0,485.0Q289.0,514.0 271.5,535.0Q254.0,556.0 225.0,556.0Q194.0,556.0 174.5,534.0Q155.0,512.0 155.0,480.0Z"  transform="translate(1008, 950)"/>
<path d="M-35.0,-347.0Q-64.0,-327.0 -93.5,-296.5Q-123.0,-266.0 -142.0,-228.5Q-161.0,-191.0 -161.0,-151.0Q-161.0,-102.0 -129.5,-73.0Q-98.0,-44.0 -52.0,-44.0Q-25.0,-44.0 2.0,-59.0Q29.0,-74.0 50.0,-100.0Q66.0,-74.0 90.5,-61.0Q115.0,-48.0 144.0,-48.0Q167.0,-48.0 190.5,-55.5Q214.0,-63.0 241.0,-86.0Q272.0,-112.0 281.5,-134.0Q291.0,-156.0 291.0,-179.0Q291.0,-200.0 278.5,-216.0Q266.0,-232.0 253.5,-245.0Q241.0,-258.0 241.0,-271.0Q241.0,-291.0 270.0,-291.0Q287.0,-291.0 303.5,-288.5Q320.0,-286.0 340.0,-280.0L375.0,-332.0Q361.0,-335.0 339.0,-340.5Q317.0,-346.0 300.5,-355.0Q284.0,-364.0 284.0,-378.0Q284.0,-387.0 291.5,-393.5Q299.0,-400.0 318.0,-400.0Q344.0,-400.0 373.5,-391.5Q403.0,-383.0 426.0,-368.0L466.0,-415.0Q437.0,-435.0 405.5,-444.0Q374.0,-453.0 343.0,-453.0Q316.0,-453.0 293.5,-442.0Q271.0,-431.0 256.0,-415.0Q242.0,-400.0 234.0,-385.0Q226.0,-370.0 226.0,-353.0Q226.0,-337.0 237.0,-324.0Q220.0,-316.0 208.0,-304.0Q195.0,-290.0 186.5,-275.5Q178.0,-261.0 178.0,-243.0Q178.0,-222.0 190.0,-207.0Q202.0,-192.0 214.0,-177.0Q226.0,-162.0 226.0,-143.0Q226.0,-126.0 212.5,-115.0Q199.0,-104.0 177.0,-104.0Q145.0,-104.0 121.0,-127.5Q97.0,-151.0 97.0,-198.0Q97.0,-206.0 97.0,-213.0Q97.0,-220.0 98.0,-228.0L32.0,-209.0Q31.0,-203.0 30.5,-196.0Q30.0,-189.0 30.0,-184.0Q30.0,-153.0 38.0,-128.0Q22.0,-119.0 7.0,-115.0Q-8.0,-111.0 -23.0,-111.0Q-53.0,-111.0 -74.0,-130.0Q-95.0,-149.0 -95.0,-183.0Q-95.0,-221.0 -70.5,-254.5Q-46.0,-288.0 -12.0,-317.0L-35.0,-347.0Z"  transform="translate(1528, 950)"/>
<path d=""  transform="translate(1654, 950)"/>
<path d="M209.0,11.0L155.0,80.0L427.0,224.0Q393.0,235.0 349.0,252.5Q305.0,270.0 262.0,293.0Q222.0,266.0 173.0,245.0Q124.0,224.0 73.0,210.0L16.0,285.0Q60.0,296.0 101.5,310.5Q143.0,325.0 178.0,344.0Q133.0,378.0 103.0,419.0Q73.0,460.0 73.0,508.0Q73.0,558.0 106.5,587.5Q140.0,617.0 191.0,617.0Q216.0,617.0 241.0,608.0Q266.0,599.0 291.0,579.0Q321.0,555.0 345.0,521.0Q369.0,487.0 369.0,448.0Q369.0,413.0 350.5,381.5Q332.0,350.0 301.0,323.0Q338.0,305.0 382.5,287.5Q427.0,270.0 480.0,253.0L480.0,612.0L561.0,579.0L561.0,61.0Q561.0,51.0 570.0,51.0Q587.0,51.0 609.0,62.5Q631.0,74.0 647.0,93.0L688.0,25.0Q675.0,15.0 657.0,5.0Q639.0,-5.0 615.0,-5.0Q592.0,-5.0 573.0,4.5Q554.0,14.0 531.0,31.0Q500.0,55.0 490.0,75.0Q480.0,95.0 480.0,125.0L480.0,172.0L209.0,11.0ZM155.0,480.0Q155.0,421.0 221.0,371.0Q252.0,394.0 270.5,422.5Q289.0,451.0 289.0,485.0Q289.0,514.0 271.5,535.0Q254.0,556.0 225.0,556.0Q194.0,556.0 174.5,534.0Q155.0,512.0 155.0,480.0Z"  transform="translate(1953, 950)"/>
<path d="M-13.0,645.0L-37.0,712.0Q-55.0,762.0 -77.0,791.5Q-99.0,821.0 -141.0,821.0Q-170.0,821.0 -197.0,813.0L-221.0,890.0Q-206.0,895.0 -189.0,897.0Q-172.0,899.0 -157.0,899.0Q-101.0,899.0 -63.0,861.5Q-25.0,824.0 1.0,730.0L25.0,645.0L-13.0,645.0ZM-107.0,643.0L-124.0,659.0Q-164.0,697.0 -193.5,714.5Q-223.0,732.0 -261.0,732.0Q-280.0,732.0 -296.5,728.0Q-313.0,724.0 -326.0,718.0L-368.0,792.0Q-332.0,811.0 -289.0,811.0Q-234.0,811.0 -196.5,782.5Q-159.0,754.0 -115.0,701.0L-84.0,664.0L-107.0,643.0Z"  transform="translate(2474, 950)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">કૂ઼</span> (Issue #13)</li>


<pre>Expected: None</pre>



<pre>Got     : uni0A95=0+506|uni0AC2.alt=0@-244,0+0|uni0ABC=0@-244,-370+0</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 506 2447" transform="matrix(1 0 0 -1 0 0)">
<path d="M112.0,216.0L68.0,288.0L220.0,324.0Q183.0,345.0 154.0,381.0Q125.0,417.0 125.0,464.0Q125.0,509.0 149.5,540.0Q174.0,571.0 216.0,587.0Q258.0,603.0 309.0,603.0Q325.0,603.0 341.0,601.5Q357.0,600.0 371.0,598.0L389.0,521.0Q377.0,523.0 362.5,524.0Q348.0,525.0 333.0,525.0Q277.0,525.0 241.5,504.0Q206.0,483.0 206.0,438.0Q206.0,407.0 223.5,381.5Q241.0,356.0 267.0,336.0L445.0,382.0L488.0,311.0L340.0,276.0Q366.0,265.0 392.0,246.0Q418.0,227.0 435.5,198.0Q453.0,169.0 453.0,129.0Q453.0,68.0 408.5,31.0Q364.0,-6.0 284.0,-6.0Q217.0,-6.0 162.5,21.5Q108.0,49.0 70.0,82.0L95.0,119.0Q128.0,91.0 166.0,73.0Q204.0,55.0 248.0,55.0Q306.0,55.0 335.0,81.5Q364.0,108.0 364.0,148.0Q364.0,183.0 342.0,213.0Q320.0,243.0 289.0,263.0L112.0,216.0Z"  transform="translate(0, 950)"/>
<path d="M210.0,-286.0Q165.0,-224.0 132.5,-185.0Q100.0,-146.0 74.0,-127.5Q48.0,-109.0 20.0,-109.0Q-23.0,-109.0 -45.5,-130.0Q-68.0,-151.0 -68.0,-180.0Q-68.0,-218.0 -25.0,-218.0Q-7.0,-218.0 13.5,-214.0Q34.0,-210.0 63.0,-192.0L85.0,-259.0Q64.0,-268.0 48.0,-272.5Q32.0,-277.0 11.0,-277.0Q-17.0,-277.0 -44.0,-261.5Q-71.0,-246.0 -93.0,-225.0Q-111.0,-208.0 -122.0,-190.0Q-133.0,-172.0 -133.0,-149.0Q-133.0,-123.0 -119.0,-99.0Q-105.0,-75.0 -77.0,-59.5Q-49.0,-44.0 -9.0,-44.0Q27.0,-44.0 55.0,-57.5Q83.0,-71.0 110.0,-98.0Q137.0,-125.0 171.0,-164.5Q205.0,-204.0 253.0,-256.0L210.0,-286.0Z"  transform="translate(262, 950)"/>
<path d="M0.0,-57.0Q-22.0,-57.0 -37.5,-44.5Q-53.0,-32.0 -53.0,0.0Q-53.0,32.0 -37.5,44.5Q-22.0,57.0 0.0,57.0Q22.0,57.0 37.5,44.5Q53.0,32.0 53.0,0.0Q53.0,-32.0 37.5,-44.5Q22.0,-57.0 0.0,-57.0Z"  transform="translate(262, 580)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* dh_nagujarati
	* gh_nagujarati
	* j_ra_aaMatragujarati
	* j_ra_iiMatragujarati
	* ja_aaMatragujarati
	* jh_ragujarati
	* k_ss_ragujarati
	* ng_ghagujarati
	* ng_magujarati and 25 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 54 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[9] NotoSerifGujarati-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* bh_ragujarati
	* ch_vagujarati
	* ch_yagujarati
	* ddh_yagujarati
	* dh_nagujarati
	* dh_ragujarati
	* gh_nagujarati
	* gh_ragujarati
	* j_ny_ragujarati and 87 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-245.5,712.0>-<-224.0,715.0>-<-202.0,723.0>>/B<<-202.0,723.0>-<-213.0,721.0>-<-223.5,720.5>> = 9.678260053133936 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* h (U+0068): L<<104.0,119.0>--<103.0,648.0>> 

	* h (U+0068): L<<233.0,313.0>--<234.0,115.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSerifGujarati-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Gujarati Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
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

	* 89 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
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
</div></details><br></div></details><details><summary><b>[8] NotoSerifGujarati[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 682, but got 450 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font: 	- Contour 1 start point differs in glyph 'k_ss_rgujarati' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f7118753c10> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f7118753d10>

	- Contour 1 start point differs in glyph 'k_ss_rgujarati' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f7118753c10> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f7118753d50> 

	- Contour 1 start point differs in glyph 'k_ss_rgujarati' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f7118753c10> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f711872a110> [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=72.0,Y=590.0 (should be at cap-height 592?)

	* three (U+0033): X=70.0,Y=590.0 (should be at cap-height 592?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=408.0,Y=593.0 (should be at cap-height 592?)

	* five (U+0035): X=328.0,Y=0.5 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* V (U+0056): X=580.0,Y=594.0 (should be at cap-height 592?)

	* W (U+0057): X=943.0,Y=594.0 (should be at cap-height 592?) 

	* 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 23 | 57 | 1102 | 62 | 948 | 0 |
| 0% | 1% | 3% | 50% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
