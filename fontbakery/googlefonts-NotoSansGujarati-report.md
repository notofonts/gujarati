## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[2] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Gujarati Black: 896
Noto Sans Gujarati Bold: 896
Noto Sans Gujarati ExtraBold: 896
Noto Sans Gujarati ExtraLight: 896
Noto Sans Gujarati Light: 896
Noto Sans Gujarati Medium: 896
Noto Sans Gujarati: 896
Noto Sans Gujarati SemiBold: 896
Noto Sans Gujarati Thin: 896
Noto Sans Gujarati UI Black: 954
Noto Sans Gujarati UI Bold: 954
Noto Sans Gujarati UI ExtraBold: 954
Noto Sans Gujarati UI ExtraLight: 954
Noto Sans Gujarati UI Light: 954
Noto Sans Gujarati UI Medium: 954
Noto Sans Gujarati UI: 954
Noto Sans Gujarati UI SemiBold: 954
Noto Sans Gujarati UI Thin: 954 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Noto Sans Gujarati Black: 1076
Noto Sans Gujarati Bold: 1076
Noto Sans Gujarati ExtraBold: 1076
Noto Sans Gujarati ExtraLight: 1076
Noto Sans Gujarati Light: 1076
Noto Sans Gujarati Medium: 1076
Noto Sans Gujarati: 1076
Noto Sans Gujarati SemiBold: 1076
Noto Sans Gujarati Thin: 1076
Noto Sans Gujarati UI Black: 954
Noto Sans Gujarati UI Bold: 954
Noto Sans Gujarati UI ExtraBold: 954
Noto Sans Gujarati UI ExtraLight: 954
Noto Sans Gujarati UI Light: 954
Noto Sans Gujarati UI Medium: 954
Noto Sans Gujarati UI: 954
Noto Sans Gujarati UI SemiBold: 954
Noto Sans Gujarati UI Thin: 954 [code: usWinAscent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Noto Sans Gujarati Black: 896
Noto Sans Gujarati Bold: 896
Noto Sans Gujarati ExtraBold: 896
Noto Sans Gujarati ExtraLight: 896
Noto Sans Gujarati Light: 896
Noto Sans Gujarati Medium: 896
Noto Sans Gujarati: 896
Noto Sans Gujarati SemiBold: 896
Noto Sans Gujarati Thin: 896
Noto Sans Gujarati UI Black: 954
Noto Sans Gujarati UI Bold: 954
Noto Sans Gujarati UI ExtraBold: 954
Noto Sans Gujarati UI ExtraLight: 954
Noto Sans Gujarati UI Light: 954
Noto Sans Gujarati UI Medium: 954
Noto Sans Gujarati UI: 954
Noto Sans Gujarati UI SemiBold: 954
Noto Sans Gujarati UI Thin: 954 [code: ascent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Verify that family names in the name table are consistent across all fonts in the family. Checks Typographic Family name (nameID 16) if present, otherwise uses Font Family name (nameID 1) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.adobe.fonts/check/family/consistent_family_name">com.adobe.fonts/check/family/consistent_family_name</a>)</summary><div>


* 🔥 **FAIL** 2 different Font Family names were found:

* 'Noto Sans Gujarati' was found in:
  - NotoSansGujarati-Black.ttf (nameID 16)
  - NotoSansGujarati-Bold.ttf (nameID 1)
  - NotoSansGujarati-ExtraBold.ttf (nameID 16)
  - NotoSansGujarati-ExtraLight.ttf (nameID 16)
  - NotoSansGujarati-Light.ttf (nameID 16)
  - NotoSansGujarati-Medium.ttf (nameID 16)
  - NotoSansGujarati-Regular.ttf (nameID 1)
  - NotoSansGujarati-SemiBold.ttf (nameID 16)
  - NotoSansGujarati-Thin.ttf (nameID 16)

* 'Noto Sans Gujarati UI' was found in:
  - NotoSansGujaratiUI-Black.ttf (nameID 16)
  - NotoSansGujaratiUI-Bold.ttf (nameID 1)
  - NotoSansGujaratiUI-ExtraBold.ttf (nameID 16)
  - NotoSansGujaratiUI-ExtraLight.ttf (nameID 16)
  - NotoSansGujaratiUI-Light.ttf (nameID 16)
  - NotoSansGujaratiUI-Medium.ttf (nameID 16)
  - NotoSansGujaratiUI-Regular.ttf (nameID 1)
  - NotoSansGujaratiUI-SemiBold.ttf (nameID 16)
  - NotoSansGujaratiUI-Thin.ttf (nameID 16) [code: inconsistent-family-name]
</div></details><br></div></details><details><summary><b>[12] NotoSansGujarati-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aagujr
	* agujr
	* aianusvaragujr
	* aigujr
	* aivowelsignrephanusvaragujr
	* aivowelsignrephgujr
	* auanusvaragujr
	* augujr
	* auvowelsignrephanusvaragujr
	* auvowelsignrephgujr
	* badagujr
	* bagujr
	* banuktagujr
	* banuktastemgujr
	* baragujr
	* baranuktagujr
	* baranuktaprehalfgujr
	* baranuktastemgujr
	* baraprehalfgujr
	* barastemgujr
	* bastemgujr
	* bhagujr
	* bhanuktagujr
	* bhanuktaprehalfgujr
	* bhanuktastemgujr
	* bhaprehalfgujr
	* bharagujr
	* bharanuktagujr
	* bharanuktaprehalfgujr
	* bharanuktastemgujr
	* bharaprehalfgujr
	* bharastemgujr
	* bhastemgujr
	* cagujr
	* canuktagujr
	* canuktaprehalfgujr
	* canuktastemgujr
	* caprehalfgujr
	* caragujr
	* caranuktagujr
	* caranuktaprehalfgujr
	* caranuktastemgujr
	* caraprehalfgujr
	* carastemgujr
	* castemgujr
	* chagujr
	* chanuktagujr
	* chanuktaprehalfgujr
	* chanuktasquishgujr
	* chaprehalfgujr
	* charagujr
	* charanuktagujr
	* charanuktaprehalfgujr
	* charaprehalfgujr
	* chasquishgujr
	* chavagujr
	* chayagujr
	* chayastemgujr
	* dabagujr
	* dabhagujr
	* dadagujr
	* dadasquishgujr
	* dadhagujr
	* dadhasquishgujr
	* dagagujr
	* dagasquishgujr
	* daghagujr
	* daghasquishgujr
	* dagujr
	* damagujr
	* damastemgujr
	* danagujr
	* danasquishgujr
	* danuktagujr
	* danuktaprehalfgujr
	* daprehalfgujr
	* daragujr
	* daranuktagujr
	* daranuktaprehalfgujr
	* daranuktasquishgujr
	* daraprehalfgujr
	* darasquishgujr
	* darvocalicvowelgujr
	* darvocalicvowelnuktagujr
	* davagujr
	* dayagujr
	* dayastemgujr
	* ddaddagujr
	* ddaddaugujr
	* ddaddhagujr
	* ddayagujr
	* ddayastemgujr
	* ddhaddhagujr
	* ddharanuktaprehalfgujr
	* ddharaprehalfgujr
	* ddhayagujr
	* ddhayastemgujr
	* dhagujr
	* dhanuktagujr
	* dhanuktaprehalfgujr
	* dhanuktastemgujr
	* dhaprehalfgujr
	* dharagujr
	* dharanuktagujr
	* dharanuktaprehalfgujr
	* dharanuktastemgujr
	* dharaprehalfgujr
	* dharastemgujr
	* dhastemgujr
	* eanusvaragujr
	* ecandraanusvaragujr
	* ecandragujr
	* ecandravowelrephanusvaragujr
	* ecandravowelsignrephgujr
	* egujr
	* evowelsignrephanusvaragujr
	* evowelsignrephgujr
	* ganagujr
	* ghagujr
	* ghanuktagujr
	* ghanuktaprehalfgujr
	* ghanuktastemgujr
	* ghaprehalfgujr
	* gharagujr
	* gharanuktagujr
	* gharanuktaprehalfgujr
	* gharanuktastemgujr
	* gharaprehalfgujr
	* gharastemgujr
	* ghastemgujr
	* halagujr
	* halastemgujr
	* hamagujr
	* hamastemgujr
	* hanagujr
	* hanastemgujr
	* hannagujr
	* hannastemgujr
	* hanuktaprehalfgujr
	* haprehalfgujr
	* haragujr
	* haranuktagujr
	* haranuktaprehalfgujr
	* haranuktastemgujr
	* haraprehalfgujr
	* harastemgujr
	* harvocalicvowelgujr
	* harvocalicvowelnuktagujr
	* havagujr
	* havastemgujr
	* hayagujr
	* hayastemgujr
	* iivowelsignreph1gujr
	* iivowelsignreph2gujr
	* iivowelsignrephanusvara1gujr
	* iivowelsignrephanusvara2gujr
	* iivowelsignrephanusvaragujr
	* iivowelsignrephgujr
	* ivowelsignreph2gujr
	* ivowelsignreph3gujr
	* ivowelsignreph4gujr
	* ivowelsignreph5gujr
	* ivowelsignreph6gujr
	* ivowelsignrephanusvara1gujr
	* ivowelsignrephanusvara2gujr
	* ivowelsignrephanusvara3gujr
	* ivowelsignrephanusvara4gujr
	* ivowelsignrephanusvara5gujr
	* ivowelsignrephanusvara6gujr
	* ivowelsignrephanusvaragujr
	* ivowelsignrephgujr
	* jaaavowelgujr
	* jaaavowelnuktagujr
	* jagujr
	* jaiivowelgujr
	* jaiivowelnuktagujr
	* januktagujr
	* januktaprehalfgujr
	* januktasquishgujr
	* janyagujr
	* janyaprehalfgujr
	* janyaragujr
	* janyaraprehalfgujr
	* janyarastemgujr
	* janyastemgujr
	* japrehalfgujr
	* jaragujr
	* jaranuktagujr
	* jaranuktaprehalfgujr
	* jaraprehalfgujr
	* jasquishgujr
	* jayagujr
	* jayastemgujr
	* jhagujr
	* jhanuktagujr
	* jhanuktaprehalfgujr
	* jhaprehalfgujr
	* jharagujr
	* jharanuktagujr
	* jharanuktaprehalfgujr
	* jharaprehalfgujr
	* kagujr
	* kakagujr
	* kanuktagujr
	* kanuktaprehalfgujr
	* kanuktauuvowelgujr
	* kanuktauvowelgujr
	* kaprehalfgujr
	* karagujr
	* karanuktagujr
	* karanuktaprehalfgujr
	* karanuktauuvowelgujr
	* karanuktauvowelgujr
	* karaprehalfgujr
	* kassagujr
	* kassaprehalfgujr
	* kassaragujr
	* kassaraprehalfgujr
	* kassarastemgujr
	* kassastemgujr
	* kayagujr
	* kayastemgujr
	* khagujr
	* khanuktagujr
	* khanuktaprehalfgujr
	* khanuktastemgujr
	* khaprehalfgujr
	* kharagujr
	* kharanuktagujr
	* kharanuktaprehalfgujr
	* kharanuktastemgujr
	* kharaprehalfgujr
	* kharastemgujr
	* khastemgujr
	* khayagujr
	* khayastemgujr
	* lagujr
	* lanuktagujr
	* lanuktastemgujr
	* laragujr
	* laranuktagujr
	* laranuktastemgujr
	* larastemgujr
	* lastemgujr
	* llaragujr
	* llaranuktagujr
	* llaranuktastemgujr
	* llarastemgujr
	* llayagujr
	* llayastemgujr
	* llvocalicgujr
	* lvocalicgujr
	* magujr
	* manuktagujr
	* manuktaprehalfgujr
	* manuktastemgujr
	* mapreformaltgujr
	* maprehalfgujr
	* maragujr
	* maranuktagujr
	* maranuktaprehalfgujr
	* maranuktastemgujr
	* maraprehalfgujr
	* marastemgujr
	* mastemgujr
	* nagujr
	* nanagujr
	* nanastemgujr
	* nanuktagujr
	* nanuktastemgujr
	* naragujr
	* naranuktagujr
	* naranuktastemgujr
	* narastemgujr
	* nastemgujr
	* ngagagujr
	* ngaghagujr
	* ngakagujr
	* ngamagujr
	* ngayagujr
	* ngayastemgujr
	* nnaragujr
	* nnaranuktagujr
	* nnaranuktastemgujr
	* nnarastemgujr
	* nnarauvowelgujr
	* nnarauvowelnuktagujr
	* nnauvowelgujr
	* nnauvowelnuktagujr
	* nyacagujr
	* nyacastemgujr
	* nyagujr
	* nyajagujr
	* nyajastemgujr
	* nyanuktagujr
	* nyanuktaprehalfgujr
	* nyanuktastemgujr
	* nyaprehalfgujr
	* nyaragujr
	* nyaranuktagujr
	* nyaranuktaprehalfgujr
	* nyaranuktastemgujr
	* nyaraprehalfgujr
	* nyarastemgujr
	* nyastemgujr
	* oanusvaragujr
	* ocandraanusvaragujr
	* ocandragujr
	* ocandravowelrephanusvaragujr
	* ocandravowelsignrephgujr
	* ogujr
	* onegujr
	* ovowelsignrephanusvaragujr
	* ovowelsignrephgujr
	* paragujr
	* paranuktagujr
	* paranuktaprehalfgujr
	* paranuktastemgujr
	* paraprehalfgujr
	* parastemgujr
	* phaaltgujr
	* phagujr
	* phanuktaaltgujr
	* phanuktagujr
	* phanuktaprehalfgujr
	* phanuktasquishgujr
	* phaprehalfgujr
	* pharaaltgujr
	* pharagujr
	* pharanuktaaltgujr
	* pharanuktagujr
	* pharanuktaprehalfgujr
	* pharanuktasquishgujr
	* pharaprehalfgujr
	* pharasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* ragujr
	* ranuktagujr
	* ranuktaprehalfgujr
	* ranuktasquishgujr
	* raprehalfgujr
	* raranuktagujr
	* raranuktaprehalfgujr
	* rasquishgujr
	* rauuvowelgujr
	* rauuvowelnuktagujr
	* rauvowelgujr
	* rauvowelnuktagujr
	* rrvocalicgujr
	* rvocalicgujr
	* sagujr
	* sanuktagujr
	* sanuktaprehalfgujr
	* sanuktastemgujr
	* sapreformaltgujr
	* saprehalfgujr
	* saragujr
	* saranuktagujr
	* saranuktaprehalfgujr
	* saranuktastemgujr
	* saraprehalfgujr
	* sarastemgujr
	* sastemgujr
	* sataragujr
	* satarastemgujr
	* sathagujr
	* sathapreformgujr
	* sathastemgujr
	* shacagujr
	* shacastemgujr
	* shagujr
	* shalagujr
	* shalastemgujr
	* shanagujr
	* shanastemgujr
	* shanuktagujr
	* shanuktaprehalfgujr
	* shanuktastemgujr
	* shapreformaltgujr
	* shaprehalfgujr
	* sharagujr
	* sharanuktagujr
	* sharanuktaprehalfgujr
	* sharanuktastemgujr
	* sharaprehalfgujr
	* sharastemgujr
	* shastemgujr
	* shavagujr
	* shavastemgujr
	* sixgujr
	* ssagujr
	* ssanuktagujr
	* ssanuktastemgujr
	* ssaragujr
	* ssaranuktagujr
	* ssaranuktaprehalfgujr
	* ssaranuktastemgujr
	* ssaraprehalfgujr
	* ssarastemgujr
	* ssastemgujr
	* ssattagujr
	* ssattaragujr
	* ssatthagujr
	* ssattharagujr
	* taragujr
	* taranuktagujr
	* taranuktastemgujr
	* tarastemgujr
	* tatagujr
	* tatastemgujr
	* tharagujr
	* tharanuktagujr
	* tharanuktaprehalfgujr
	* tharanuktastemgujr
	* tharaprehalfgujr
	* tharastemgujr
	* threegujr
	* ttattagujr
	* ttattaugujr
	* ttattauugujr
	* ttatthagujr
	* ttatthauugujr
	* ttavagujr
	* ttavastemgujr
	* ttayagujr
	* ttayastemgujr
	* tthagujr
	* tthanuktagujr
	* tthanuktaprehalfgujr
	* tthanuktasquishgujr
	* tthaprehalfgujr
	* ttharagujr
	* ttharanuktagujr
	* ttharanuktaprehalfgujr
	* ttharaprehalfgujr
	* tthasquishgujr
	* tthatthagujr
	* tthatthaugujr
	* tthayagujr
	* tthayastemgujr
	* twogujr
	* uanusvaragujr
	* ugujr
	* uni0AF1
	* uni20B9.gujr
	* uniA837
	* uuanusvaragujr
	* uugujr
	* vagujr
	* vanuktagujr
	* vanuktastemgujr
	* varagujr
	* varanuktagujr
	* varanuktaprehalfgujr
	* varanuktastemgujr
	* varaprehalfgujr
	* varastemgujr
	* vastemgujr
	* vayagujr
	* vayastemgujr
	* vocalicvattugujr
	* yagujr
	* yanuktagujr
	* yanuktastemgujr
	* yaragujr
	* yaranuktagujr
	* yaranuktaprehalfgujr
	* yaranuktastemgujr
	* yaraprehalfgujr
	* yarastemgujr
	* yastemgujr
	* zhaaavowelgujr
	* zhagujr
	* zhaiivowelgujr
	* zhaprehalfgujr
	* zharagujr
	* zharaprehalfgujr and zhasquishgujr
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* r (U+0072): X=311.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* degree (U+00B0): X=257.5,Y=591.0 (should be at cap-height 592?)

	* degree (U+00B0): X=164.5,Y=591.0 (should be at cap-height 592?)

	* Atilde (U+00C3): X=195.5,Y=894.5 (should be at ascender 896?)

	* Atilde (U+00C3): X=391.5,Y=897.0 (should be at ascender 896?)

	* Ccedilla (U+00C7): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ntilde (U+00D1): X=249.5,Y=894.5 (should be at ascender 896?)

	* Ntilde (U+00D1): X=445.5,Y=897.0 (should be at ascender 896?)

	* Otilde (U+00D5): X=231.5,Y=894.5 (should be at ascender 896?)

	* Otilde (U+00D5): X=427.5,Y=897.0 (should be at ascender 896?)

	* germandbls (U+00DF): X=283.5,Y=592.5 (should be at cap-height 592?)

	* agrave (U+00E0): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=282.0,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=282.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=282.0,Y=-1.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-1.5 (should be at baseline 0?)

	* amacron (U+0101): X=282.0,Y=-1.5 (should be at baseline 0?)

	* Abreve (U+0102): X=299.5,Y=895.0 (should be at ascender 896?)

	* Abreve (U+0102): X=418.0,Y=896.5 (should be at ascender 896?)

	* abreve (U+0103): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=282.0,Y=-1.5 (should be at baseline 0?)

	* Cacute (U+0106): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=317.5,Y=894.0 (should be at ascender 896?)

	* Ccaron (U+010C): X=414.0,Y=894.5 (should be at ascender 896?)

	* Dcaron (U+010E): X=319.5,Y=894.0 (should be at ascender 896?)

	* Dcaron (U+010E): X=416.0,Y=894.5 (should be at ascender 896?)

	* Ecaron (U+011A): X=241.5,Y=894.0 (should be at ascender 896?)

	* Ecaron (U+011A): X=338.0,Y=894.5 (should be at ascender 896?)

	* Gbreve (U+011E): X=545.5,Y=2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=337.5,Y=895.0 (should be at ascender 896?)

	* Gbreve (U+011E): X=456.0,Y=896.5 (should be at ascender 896?)

	* gbreve (U+011F): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=545.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=545.5,Y=2.0 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=386.0,Y=1.0 (should be at baseline 0?)

	* Ncaron (U+0147): X=369.5,Y=894.0 (should be at ascender 896?)

	* Ncaron (U+0147): X=466.0,Y=894.5 (should be at ascender 896?)

	* Rcaron (U+0158): X=291.5,Y=894.0 (should be at ascender 896?)

	* Rcaron (U+0158): X=388.0,Y=894.5 (should be at ascender 896?)

	* Scaron (U+0160): X=241.5,Y=894.0 (should be at ascender 896?)

	* Scaron (U+0160): X=338.0,Y=894.5 (should be at ascender 896?)

	* Tcaron (U+0164): X=248.5,Y=894.0 (should be at ascender 896?)

	* Tcaron (U+0164): X=345.0,Y=894.5 (should be at ascender 896?)

	* tcaron (U+0165): X=363.0,Y=-1.0 (should be at baseline 0?)

	* Ubreve (U+016C): X=315.5,Y=895.0 (should be at ascender 896?)

	* Ubreve (U+016C): X=434.0,Y=896.5 (should be at ascender 896?)

	* Zcaron (U+017D): X=267.5,Y=894.0 (should be at ascender 896?)

	* Zcaron (U+017D): X=364.0,Y=894.5 (should be at ascender 896?)

	* tcommaaccent (U+021B): X=363.0,Y=-1.0 (should be at baseline 0?)

	* igujr (U+0A87): X=330.0,Y=591.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=330.0,Y=591.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=375.5,Y=593.5 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=375.0,Y=593.5 (should be at cap-height 592?)

	* gagujr (U+0A97): X=138.5,Y=591.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=338.0,Y=591.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=352.0,Y=590.0 (should be at cap-height 592?)

	* nyagujr (U+0A9E): X=138.5,Y=591.5 (should be at cap-height 592?)

	* ttagujr (U+0A9F): X=161.0,Y=592.5 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=472.0,Y=590.0 (should be at cap-height 592?)

	* ddhagujr (U+0AA2): X=172.5,Y=594.0 (should be at cap-height 592?)

	* bhagujr (U+0AAD): X=383.5,Y=590.0 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=538.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=19.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=65.0,Y=593.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=577.0,Y=590.0 (should be at cap-height 592?)

	* aavowelsigngujr (U+0ABE): X=241.0,Y=593.0 (should be at cap-height 592?)

	* ivowelsigngujr (U+0ABF): X=241.0,Y=594.0 (should be at cap-height 592?)

	* iivowelsigngujr (U+0AC0): X=64.0,Y=594.0 (should be at cap-height 592?)

	* ocandravowelsigngujr (U+0AC9): X=241.0,Y=593.0 (should be at cap-height 592?)

	* ovowelsigngujr (U+0ACB): X=241.0,Y=593.0 (should be at cap-height 592?)

	* auvowelsigngujr (U+0ACC): X=241.0,Y=593.0 (should be at cap-height 592?)

	* rrvocalicgujr (U+0AE0): X=904.0,Y=-1.0 (should be at baseline 0?)

	* lvocalicvowelsigngujr (U+0AE2): X=-24.0,Y=-407.0 (should be at descender -408?)

	* lvocalicvowelsigngujr (U+0AE2): X=-301.0,Y=-1.0 (should be at baseline 0?)

	* lvocalicvowelsigngujr (U+0AE2): X=-24.0,Y=-407.0 (should be at descender -408?)

	* llvocalicvowelsigngujr (U+0AE3): X=-301.0,Y=-1.0 (should be at baseline 0?)

	* threegujr (U+0AE9): X=207.0,Y=592.5 (should be at cap-height 592?)

	* ninegujr (U+0AEF): X=473.0,Y=-1.5 (should be at baseline 0?)

	* Germandbls (U+1E9E): X=401.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wdieresis (U+1E84): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wdieresis (U+1E84): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wgrave (U+1E80): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wgrave (U+1E80): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wgrave (U+1E80): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSansGujarati-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aagujr
	* agujr
	* aianusvaragujr
	* aigujr
	* auanusvaragujr
	* augujr
	* badagujr
	* bagujr
	* banuktagujr
	* banuktastemgujr
	* baragujr
	* baranuktagujr
	* baranuktastemgujr
	* barastemgujr
	* bastemgujr
	* bharagujr
	* bharanuktagujr
	* bharanuktastemgujr
	* bharastemgujr
	* cagujr
	* canuktagujr
	* canuktaprehalfgujr
	* canuktastemgujr
	* caprehalfgujr
	* caragujr
	* caranuktagujr
	* caranuktaprehalfgujr
	* caranuktastemgujr
	* caraprehalfgujr
	* carastemgujr
	* castemgujr
	* chanuktasquishgujr
	* chasquishgujr
	* chavagujr
	* chayagujr
	* chayastemgujr
	* dabagujr
	* dabhagujr
	* dadagujr
	* dadasquishgujr
	* dadhagujr
	* dadhasquishgujr
	* dagagujr
	* dagasquishgujr
	* daghagujr
	* daghasquishgujr
	* damagujr
	* damastemgujr
	* danagujr
	* danasquishgujr
	* daragujr
	* daranuktagujr
	* daranuktaprehalfgujr
	* daranuktasquishgujr
	* daraprehalfgujr
	* darasquishgujr
	* darvocalicvowelgujr
	* darvocalicvowelnuktagujr
	* davagujr
	* dayagujr
	* dayastemgujr
	* ddaddagujr
	* ddaddaugujr
	* ddaddhagujr
	* ddhaddhagujr
	* ddhayagujr
	* ddhayastemgujr
	* dhagujr
	* dhanuktagujr
	* dhanuktastemgujr
	* dharagujr
	* dharanuktagujr
	* dharanuktaprehalfgujr
	* dharanuktastemgujr
	* dharaprehalfgujr
	* dharastemgujr
	* dhastemgujr
	* eanusvaragujr
	* ecandraanusvaragujr
	* ecandragujr
	* egujr
	* ghagujr
	* ghanuktagujr
	* ghanuktastemgujr
	* gharagujr
	* gharanuktagujr
	* gharanuktaprehalfgujr
	* gharanuktastemgujr
	* gharaprehalfgujr
	* gharastemgujr
	* ghastemgujr
	* halagujr
	* halastemgujr
	* hamagujr
	* hamastemgujr
	* hanagujr
	* hanastemgujr
	* hannagujr
	* hannastemgujr
	* hanuktaprehalfgujr
	* haprehalfgujr
	* haragujr
	* haranuktagujr
	* haranuktaprehalfgujr
	* haranuktastemgujr
	* haraprehalfgujr
	* harastemgujr
	* harvocalicvowelgujr
	* harvocalicvowelnuktagujr
	* havagujr
	* havastemgujr
	* hayagujr
	* hayastemgujr
	* ivowelsignreph1gujr
	* ivowelsignreph2gujr
	* ivowelsignreph3gujr
	* ivowelsignreph4gujr
	* ivowelsignrephanusvara1gujr
	* ivowelsignrephanusvara2gujr
	* ivowelsignrephanusvara3gujr
	* ivowelsignrephanusvara4gujr
	* jaaavowelgujr
	* jaaavowelnuktagujr
	* jagujr
	* jaiivowelgujr
	* jaiivowelnuktagujr
	* januktagujr
	* januktaprehalfgujr
	* januktasquishgujr
	* janyagujr
	* janyaprehalfgujr
	* janyaragujr
	* janyaraprehalfgujr
	* janyarastemgujr
	* janyastemgujr
	* japrehalfgujr
	* jaragujr
	* jaranuktagujr
	* jaranuktaprehalfgujr
	* jaraprehalfgujr
	* jasquishgujr
	* jayagujr
	* jayastemgujr
	* jhagujr
	* jhanuktagujr
	* jhanuktaprehalfgujr
	* jhaprehalfgujr
	* jharagujr
	* jharanuktagujr
	* jharanuktaprehalfgujr
	* jharaprehalfgujr
	* kagujr
	* kakagujr
	* kanuktagujr
	* kanuktaprehalfgujr
	* kanuktauuvowelgujr
	* kanuktauvowelgujr
	* kaprehalfgujr
	* karagujr
	* karanuktagujr
	* karanuktaprehalfgujr
	* karanuktauuvowelgujr
	* karanuktauvowelgujr
	* karaprehalfgujr
	* kassagujr
	* kassaprehalfgujr
	* kassaragujr
	* kassaraprehalfgujr
	* kassarastemgujr
	* kassastemgujr
	* kayagujr
	* kayastemgujr
	* khagujr
	* khanuktagujr
	* khanuktastemgujr
	* kharagujr
	* kharanuktagujr
	* kharanuktastemgujr
	* kharastemgujr
	* khastemgujr
	* khayagujr
	* khayastemgujr
	* laragujr
	* laranuktagujr
	* laranuktastemgujr
	* larastemgujr
	* llaragujr
	* llaranuktagujr
	* llaranuktastemgujr
	* llarastemgujr
	* llvocalicgujr
	* lvocalicgujr
	* manuktastemgujr
	* maragujr
	* maranuktagujr
	* maranuktaprehalfgujr
	* maranuktastemgujr
	* maraprehalfgujr
	* marastemgujr
	* mastemgujr
	* naragujr
	* naranuktagujr
	* naranuktastemgujr
	* narastemgujr
	* ngagagujr
	* ngaghagujr
	* ngakagujr
	* ngamagujr
	* nnaragujr
	* nnaranuktagujr
	* nnaranuktastemgujr
	* nnarastemgujr
	* nnarauvowelgujr
	* nnarauvowelnuktagujr
	* nnauvowelgujr
	* nnauvowelnuktagujr
	* nyacagujr
	* nyacastemgujr
	* nyagujr
	* nyajagujr
	* nyajastemgujr
	* nyanuktagujr
	* nyanuktaprehalfgujr
	* nyanuktastemgujr
	* nyaprehalfgujr
	* nyaragujr
	* nyaranuktagujr
	* nyaranuktaprehalfgujr
	* nyaranuktastemgujr
	* nyaraprehalfgujr
	* nyarastemgujr
	* nyastemgujr
	* oanusvaragujr
	* ocandraanusvaragujr
	* ocandragujr
	* ogujr
	* onegujr
	* paragujr
	* paranuktagujr
	* paranuktaprehalfgujr
	* paranuktastemgujr
	* paraprehalfgujr
	* parastemgujr
	* phaaltgujr
	* phagujr
	* phanuktaaltgujr
	* phanuktagujr
	* phanuktaprehalfgujr
	* phanuktasquishgujr
	* phaprehalfgujr
	* pharaaltgujr
	* pharagujr
	* pharanuktaaltgujr
	* pharanuktagujr
	* pharanuktaprehalfgujr
	* pharanuktasquishgujr
	* pharaprehalfgujr
	* pharasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* ragujr
	* ranuktagujr
	* ranuktaprehalfgujr
	* ranuktasquishgujr
	* raprehalfgujr
	* raranuktagujr
	* raranuktaprehalfgujr
	* rasquishgujr
	* rauuvowelgujr
	* rauuvowelnuktagujr
	* rauvowelgujr
	* rauvowelnuktagujr
	* rrvocalicgujr
	* rvocalicgujr
	* sagujr
	* sanuktagujr
	* sanuktaprehalfgujr
	* sanuktastemgujr
	* sapreformaltgujr
	* saprehalfgujr
	* saragujr
	* saranuktagujr
	* saranuktaprehalfgujr
	* saranuktastemgujr
	* saraprehalfgujr
	* sarastemgujr
	* sastemgujr
	* sataragujr
	* satarastemgujr
	* sathagujr
	* sathapreformgujr
	* sathastemgujr
	* shacagujr
	* shacastemgujr
	* shagujr
	* shalagujr
	* shalastemgujr
	* shanagujr
	* shanastemgujr
	* shanuktagujr
	* shanuktaprehalfgujr
	* shanuktastemgujr
	* shapreformaltgujr
	* shaprehalfgujr
	* sharagujr
	* sharanuktagujr
	* sharanuktaprehalfgujr
	* sharanuktastemgujr
	* sharaprehalfgujr
	* sharastemgujr
	* shastemgujr
	* shavagujr
	* shavastemgujr
	* ssaragujr
	* ssaranuktagujr
	* ssaranuktaprehalfgujr
	* ssaranuktastemgujr
	* ssaraprehalfgujr
	* ssarastemgujr
	* ssattagujr
	* ssattaragujr
	* ssatthagujr
	* ssattharagujr
	* tharagujr
	* tharanuktagujr
	* tharanuktaprehalfgujr
	* tharanuktastemgujr
	* tharaprehalfgujr
	* tharastemgujr
	* threegujr
	* ttattagujr
	* ttattaugujr
	* ttattauugujr
	* ttatthagujr
	* ttatthauugujr
	* ttayagujr
	* ttayastemgujr
	* tthagujr
	* tthanuktagujr
	* tthanuktaprehalfgujr
	* tthanuktasquishgujr
	* tthaprehalfgujr
	* ttharagujr
	* ttharanuktagujr
	* ttharanuktaprehalfgujr
	* ttharaprehalfgujr
	* tthasquishgujr
	* tthatthagujr
	* tthatthaugujr
	* tthayagujr
	* tthayastemgujr
	* twogujr
	* uanusvaragujr
	* ugujr
	* uni0AF1
	* uni20B9.gujr
	* uniA837
	* uuanusvaragujr
	* uugujr
	* varagujr
	* varanuktagujr
	* varanuktaprehalfgujr
	* varanuktastemgujr
	* varaprehalfgujr
	* varastemgujr
	* yaragujr
	* yaranuktagujr
	* yaranuktaprehalfgujr
	* yaranuktastemgujr
	* yaraprehalfgujr
	* yarastemgujr
	* zhaaavowelgujr
	* zhagujr
	* zhaiivowelgujr
	* zhaprehalfgujr
	* zharagujr
	* zharaprehalfgujr and zhasquishgujr
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wdieresis (U+1E84): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wgrave (U+1E80): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansGujarati-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aagujr
	* agujr
	* aianusvaragujr
	* aigujr
	* aivowelsignrephanusvaragujr
	* aivowelsignrephgujr
	* auanusvaragujr
	* augujr
	* auvowelsignrephanusvaragujr
	* auvowelsignrephgujr
	* badagujr
	* bagujr
	* banuktagujr
	* banuktastemgujr
	* baragujr
	* baranuktagujr
	* baranuktastemgujr
	* barastemgujr
	* bastemgujr
	* bhagujr
	* bhanuktagujr
	* bhanuktastemgujr
	* bharagujr
	* bharanuktagujr
	* bharanuktastemgujr
	* bharastemgujr
	* bhastemgujr
	* cagujr
	* canuktagujr
	* canuktaprehalfgujr
	* canuktastemgujr
	* caprehalfgujr
	* caragujr
	* caranuktagujr
	* caranuktaprehalfgujr
	* caranuktastemgujr
	* caraprehalfgujr
	* carastemgujr
	* castemgujr
	* chanuktasquishgujr
	* chasquishgujr
	* chavagujr
	* chayagujr
	* chayastemgujr
	* dabagujr
	* dabhagujr
	* dadagujr
	* dadasquishgujr
	* dadhagujr
	* dadhasquishgujr
	* dagagujr
	* dagasquishgujr
	* daghagujr
	* daghasquishgujr
	* dagujr
	* damagujr
	* damastemgujr
	* danagujr
	* danasquishgujr
	* danuktagujr
	* danuktaprehalfgujr
	* daprehalfgujr
	* daragujr
	* daranuktagujr
	* daranuktaprehalfgujr
	* daranuktasquishgujr
	* daraprehalfgujr
	* darasquishgujr
	* darvocalicvowelgujr
	* darvocalicvowelnuktagujr
	* davagujr
	* dayagujr
	* dayastemgujr
	* ddaddagujr
	* ddaddaugujr
	* ddaddhagujr
	* ddhaddhagujr
	* ddhayagujr
	* ddhayastemgujr
	* dhagujr
	* dhanuktagujr
	* dhanuktaprehalfgujr
	* dhanuktastemgujr
	* dhaprehalfgujr
	* dharagujr
	* dharanuktagujr
	* dharanuktaprehalfgujr
	* dharanuktastemgujr
	* dharaprehalfgujr
	* dharastemgujr
	* dhastemgujr
	* eanusvaragujr
	* ecandraanusvaragujr
	* ecandragujr
	* egujr
	* ganagujr
	* ghagujr
	* ghanuktagujr
	* ghanuktaprehalfgujr
	* ghanuktastemgujr
	* ghaprehalfgujr
	* gharagujr
	* gharanuktagujr
	* gharanuktaprehalfgujr
	* gharanuktastemgujr
	* gharaprehalfgujr
	* gharastemgujr
	* ghastemgujr
	* halagujr
	* halastemgujr
	* hamagujr
	* hamastemgujr
	* hanagujr
	* hanastemgujr
	* hannagujr
	* hannastemgujr
	* hanuktaprehalfgujr
	* haprehalfgujr
	* haragujr
	* haranuktagujr
	* haranuktaprehalfgujr
	* haranuktastemgujr
	* haraprehalfgujr
	* harastemgujr
	* harvocalicvowelgujr
	* harvocalicvowelnuktagujr
	* havagujr
	* havastemgujr
	* hayagujr
	* hayastemgujr
	* iivowelsignrephanusvara1gujr
	* iivowelsignrephanusvara2gujr
	* iivowelsignrephanusvaragujr
	* ivowelsignreph2gujr
	* ivowelsignreph3gujr
	* ivowelsignreph4gujr
	* ivowelsignreph5gujr
	* ivowelsignreph6gujr
	* ivowelsignrephanusvara1gujr
	* ivowelsignrephanusvara2gujr
	* ivowelsignrephanusvara3gujr
	* ivowelsignrephanusvara4gujr
	* ivowelsignrephanusvara5gujr
	* ivowelsignrephanusvara6gujr
	* ivowelsignrephanusvaragujr
	* ivowelsignrephgujr
	* jaaavowelgujr
	* jaaavowelnuktagujr
	* jagujr
	* jaiivowelgujr
	* jaiivowelnuktagujr
	* januktagujr
	* januktaprehalfgujr
	* januktasquishgujr
	* janyagujr
	* janyaprehalfgujr
	* janyaragujr
	* janyaraprehalfgujr
	* janyarastemgujr
	* janyastemgujr
	* japrehalfgujr
	* jaragujr
	* jaranuktagujr
	* jaranuktaprehalfgujr
	* jaraprehalfgujr
	* jasquishgujr
	* jayagujr
	* jayastemgujr
	* jhagujr
	* jhanuktagujr
	* jhanuktaprehalfgujr
	* jhaprehalfgujr
	* jharagujr
	* jharanuktagujr
	* jharanuktaprehalfgujr
	* jharaprehalfgujr
	* kagujr
	* kakagujr
	* kanuktagujr
	* kanuktaprehalfgujr
	* kanuktauuvowelgujr
	* kanuktauvowelgujr
	* kaprehalfgujr
	* karagujr
	* karanuktagujr
	* karanuktaprehalfgujr
	* karanuktauuvowelgujr
	* karanuktauvowelgujr
	* karaprehalfgujr
	* kassagujr
	* kassaprehalfgujr
	* kassaragujr
	* kassaraprehalfgujr
	* kassarastemgujr
	* kassastemgujr
	* kayagujr
	* kayastemgujr
	* khagujr
	* khanuktagujr
	* khanuktaprehalfgujr
	* khanuktastemgujr
	* khaprehalfgujr
	* kharagujr
	* kharanuktagujr
	* kharanuktaprehalfgujr
	* kharanuktastemgujr
	* kharaprehalfgujr
	* kharastemgujr
	* khastemgujr
	* khayagujr
	* khayastemgujr
	* laragujr
	* laranuktagujr
	* laranuktastemgujr
	* larastemgujr
	* llaragujr
	* llaranuktagujr
	* llaranuktastemgujr
	* llarastemgujr
	* llvocalicgujr
	* lvocalicgujr
	* magujr
	* manuktagujr
	* manuktastemgujr
	* maragujr
	* maranuktagujr
	* maranuktaprehalfgujr
	* maranuktastemgujr
	* maraprehalfgujr
	* marastemgujr
	* mastemgujr
	* naragujr
	* naranuktagujr
	* naranuktastemgujr
	* narastemgujr
	* ngagagujr
	* ngaghagujr
	* ngakagujr
	* ngamagujr
	* nnaragujr
	* nnaranuktagujr
	* nnaranuktastemgujr
	* nnarastemgujr
	* nnarauvowelgujr
	* nnarauvowelnuktagujr
	* nnauvowelgujr
	* nnauvowelnuktagujr
	* nyacagujr
	* nyacastemgujr
	* nyagujr
	* nyajagujr
	* nyajastemgujr
	* nyanuktagujr
	* nyanuktaprehalfgujr
	* nyanuktastemgujr
	* nyaprehalfgujr
	* nyaragujr
	* nyaranuktagujr
	* nyaranuktaprehalfgujr
	* nyaranuktastemgujr
	* nyaraprehalfgujr
	* nyarastemgujr
	* nyastemgujr
	* oanusvaragujr
	* ocandraanusvaragujr
	* ocandragujr
	* ogujr
	* onegujr
	* paragujr
	* paranuktagujr
	* paranuktaprehalfgujr
	* paranuktastemgujr
	* paraprehalfgujr
	* parastemgujr
	* phaaltgujr
	* phagujr
	* phanuktaaltgujr
	* phanuktagujr
	* phanuktaprehalfgujr
	* phanuktasquishgujr
	* phaprehalfgujr
	* pharaaltgujr
	* pharagujr
	* pharanuktaaltgujr
	* pharanuktagujr
	* pharanuktaprehalfgujr
	* pharanuktasquishgujr
	* pharaprehalfgujr
	* pharasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* ragujr
	* ranuktagujr
	* ranuktaprehalfgujr
	* ranuktasquishgujr
	* raprehalfgujr
	* raranuktagujr
	* raranuktaprehalfgujr
	* rasquishgujr
	* rauuvowelgujr
	* rauuvowelnuktagujr
	* rauvowelgujr
	* rauvowelnuktagujr
	* rrvocalicgujr
	* rvocalicgujr
	* sagujr
	* sanuktagujr
	* sanuktaprehalfgujr
	* sanuktastemgujr
	* sapreformaltgujr
	* saprehalfgujr
	* saragujr
	* saranuktagujr
	* saranuktaprehalfgujr
	* saranuktastemgujr
	* saraprehalfgujr
	* sarastemgujr
	* sastemgujr
	* sataragujr
	* satarastemgujr
	* sathagujr
	* sathapreformgujr
	* sathastemgujr
	* shacagujr
	* shacastemgujr
	* shagujr
	* shalagujr
	* shalastemgujr
	* shanagujr
	* shanastemgujr
	* shanuktagujr
	* shanuktaprehalfgujr
	* shanuktastemgujr
	* shapreformaltgujr
	* shaprehalfgujr
	* sharagujr
	* sharanuktagujr
	* sharanuktaprehalfgujr
	* sharanuktastemgujr
	* sharaprehalfgujr
	* sharastemgujr
	* shastemgujr
	* shavagujr
	* shavastemgujr
	* sixgujr
	* ssagujr
	* ssanuktagujr
	* ssanuktastemgujr
	* ssaragujr
	* ssaranuktagujr
	* ssaranuktaprehalfgujr
	* ssaranuktastemgujr
	* ssaraprehalfgujr
	* ssarastemgujr
	* ssastemgujr
	* ssattagujr
	* ssattaragujr
	* ssatthagujr
	* ssattharagujr
	* taragujr
	* taranuktagujr
	* taranuktastemgujr
	* tarastemgujr
	* tharagujr
	* tharanuktagujr
	* tharanuktaprehalfgujr
	* tharanuktastemgujr
	* tharaprehalfgujr
	* tharastemgujr
	* threegujr
	* ttattagujr
	* ttattaugujr
	* ttattauugujr
	* ttatthagujr
	* ttatthauugujr
	* ttayagujr
	* ttayastemgujr
	* tthagujr
	* tthanuktagujr
	* tthanuktaprehalfgujr
	* tthanuktasquishgujr
	* tthaprehalfgujr
	* ttharagujr
	* ttharanuktagujr
	* ttharanuktaprehalfgujr
	* ttharaprehalfgujr
	* tthasquishgujr
	* tthatthagujr
	* tthatthaugujr
	* tthayagujr
	* tthayastemgujr
	* twogujr
	* uanusvaragujr
	* ugujr
	* uni0AF1
	* uni20B9.gujr
	* uniA837
	* uuanusvaragujr
	* uugujr
	* varagujr
	* varanuktagujr
	* varanuktaprehalfgujr
	* varanuktastemgujr
	* varaprehalfgujr
	* varastemgujr
	* yaragujr
	* yaranuktagujr
	* yaranuktaprehalfgujr
	* yaranuktastemgujr
	* yaraprehalfgujr
	* yarastemgujr
	* zhaaavowelgujr
	* zhagujr
	* zhaiivowelgujr
	* zhaprehalfgujr
	* zharagujr
	* zharaprehalfgujr and zhasquishgujr
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 578 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=275.5,Y=591.5 (should be at cap-height 592?)

	* comma (U+002C): X=57.5,Y=2.0 (should be at baseline 0?)

	* six (U+0036): X=403.0,Y=590.0 (should be at cap-height 592?)

	* semicolon (U+003B): X=57.5,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=231.0,Y=590.0 (should be at cap-height 592?)

	* C (U+0043): X=485.5,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=535.5,Y=1.5 (should be at baseline 0?)

	* S (U+0053): X=142.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=298.0,Y=535.5 (should be at x-height 536?)

	* c (U+0063): X=405.0,Y=1.5 (should be at baseline 0?)

	* e (U+0065): X=441.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=341.0,Y=538.0 (should be at x-height 536?)

	* g (U+0067): X=565.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=238.0,Y=537.5 (should be at x-height 536?)

	* h (U+0068): X=498.5,Y=538.0 (should be at x-height 536?)

	* p (U+0070): X=298.0,Y=535.0 (should be at x-height 536?)

	* q (U+0071): X=344.5,Y=536.5 (should be at x-height 536?)

	* t (U+0074): X=352.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=131.0,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=485.5,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=630.0,Y=594.0 (should be at cap-height 592?)

	* germandbls (U+00DF): X=630.0,Y=594.0 (should be at cap-height 592?)

	* ae (U+00E6): X=764.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=405.0,Y=1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=441.5,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=441.5,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=441.5,Y=-0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=441.5,Y=-0.5 (should be at baseline 0?)

	* divide (U+00F7): X=238.0,Y=593.0 (should be at cap-height 592?)

	* divide (U+00F7): X=338.5,Y=593.0 (should be at cap-height 592?)

	* Cacute (U+0106): X=485.5,Y=-1.0 (should be at baseline 0?)

	* cacute (U+0107): X=405.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=485.5,Y=-1.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=405.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=485.5,Y=-1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=318.5,Y=895.5 (should be at ascender 896?)

	* ccaron (U+010D): X=405.0,Y=1.5 (should be at baseline 0?)

	* Dcaron (U+010E): X=315.5,Y=895.5 (should be at ascender 896?)

	* emacron (U+0113): X=441.5,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=441.5,Y=-0.5 (should be at baseline 0?)

	* Ecaron (U+011A): X=242.5,Y=895.5 (should be at ascender 896?)

	* ecaron (U+011B): X=441.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=535.5,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=565.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=535.5,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=565.0,Y=-1.0 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=535.5,Y=1.5 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=565.0,Y=-1.0 (should be at baseline 0?)

	* Ncaron (U+0147): X=358.5,Y=895.5 (should be at ascender 896?)

	* Eng (U+014A): X=593.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=739.0,Y=-2.0 (should be at baseline 0?)

	* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

	* Rcaron (U+0158): X=285.5,Y=895.5 (should be at ascender 896?)

	* Sacute (U+015A): X=142.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=142.0,Y=1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=142.0,Y=1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=233.5,Y=895.5 (should be at ascender 896?)

	* Tcaron (U+0164): X=240.5,Y=895.5 (should be at ascender 896?)

	* tcaron (U+0165): X=352.0,Y=-2.0 (should be at baseline 0?)

	* Zcaron (U+017D): X=251.5,Y=895.5 (should be at ascender 896?)

	* Scommaaccent (U+0218): X=142.0,Y=1.0 (should be at baseline 0?)

	* tcommaaccent (U+021B): X=352.0,Y=-2.0 (should be at baseline 0?)

	* igujr (U+0A87): X=329.0,Y=591.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=329.0,Y=591.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=358.0,Y=594.0 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=357.5,Y=594.0 (should be at cap-height 592?)

	* gagujr (U+0A97): X=130.5,Y=592.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=333.0,Y=591.0 (should be at cap-height 592?)

	* ngagujr (U+0A99): X=435.0,Y=590.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=340.0,Y=591.0 (should be at cap-height 592?)

	* nyagujr (U+0A9E): X=130.5,Y=592.5 (should be at cap-height 592?)

	* ttagujr (U+0A9F): X=161.0,Y=593.0 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=460.0,Y=591.0 (should be at cap-height 592?)

	* ddagujr (U+0AA1): X=435.0,Y=590.0 (should be at cap-height 592?)

	* ddhagujr (U+0AA2): X=172.5,Y=594.0 (should be at cap-height 592?)

	* nnagujr (U+0AA3): X=368.0,Y=594.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=133.0,Y=1.0 (should be at baseline 0?)

	* ragujr (U+0AB0): X=113.0,Y=593.0 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=532.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=17.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=48.0,Y=593.0 (should be at cap-height 592?)

	* sagujr (U+0AB8): X=112.0,Y=593.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=570.0,Y=591.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=554.0,Y=1.5 (should be at baseline 0?)

	* omgujr (U+0AD0): X=187.5,Y=593.0 (should be at cap-height 592?)

	* lvocalicvowelsigngujr (U+0AE2): X=-302.5,Y=-1.0 (should be at baseline 0?)

	* llvocalicvowelsigngujr (U+0AE3): X=-302.5,Y=-1.0 (should be at baseline 0?)

	* onegujr (U+0AE7): X=352.5,Y=590.0 (should be at cap-height 592?)

	* twogujr (U+0AE8): X=159.0,Y=593.0 (should be at cap-height 592?)

	* threegujr (U+0AE9): X=200.0,Y=593.5 (should be at cap-height 592?)

	* ninegujr (U+0AEF): X=469.0,Y=-0.5 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=128.0,Y=593.5 (should be at cap-height 592?)

	* uni0AFD (U+0AFD): X=-254.0,Y=895.0 (should be at ascender 896?)

	* quotesinglbase (U+201A): X=57.5,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=295.5,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=57.5,Y=1.5 (should be at baseline 0?)

	* trademark (U+2122): X=637.0,Y=590.5 (should be at cap-height 592?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansGujarati-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* ttatthauugujr and tthatthaugujr
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-216.0,707.5>-<-189.0,715.0>-<-162.0,728.0>>/B<<-162.0,728.0>-<-174.0,724.0>-<-184.0,723.0>> = 7.2750049578891804 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansGujarati-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* ddaddaugujr
	* hannagujr
	* hannastemgujr
	* kakagujr
	* ngaghagujr
	* phanuktasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* ttattaugujr
	* ttattauugujr
	* ttatthauugujr
	* tthatthagujr and tthatthaugujr
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-236.0,709.0>-<-214.0,714.0>-<-192.0,723.0>>/B<<-192.0,723.0>-<-199.0,722.0>-<-205.0,721.5>> = 14.118921303056355 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[10] NotoSansGujarati-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aagujr
	* agujr
	* aianusvaragujr
	* aigujr
	* auanusvaragujr
	* augujr
	* badagujr
	* bagujr
	* banuktagujr
	* banuktastemgujr
	* baragujr
	* baranuktagujr
	* baranuktastemgujr
	* barastemgujr
	* bastemgujr
	* bharagujr
	* bharanuktagujr
	* bharanuktastemgujr
	* bharastemgujr
	* cagujr
	* canuktagujr
	* canuktastemgujr
	* caragujr
	* caranuktagujr
	* caranuktaprehalfgujr
	* caranuktastemgujr
	* caraprehalfgujr
	* carastemgujr
	* castemgujr
	* chavagujr
	* dabagujr
	* dabhagujr
	* dadagujr
	* dadasquishgujr
	* dadhagujr
	* dadhasquishgujr
	* dagasquishgujr
	* daghagujr
	* daghasquishgujr
	* danagujr
	* danasquishgujr
	* daragujr
	* daranuktagujr
	* daranuktaprehalfgujr
	* daranuktasquishgujr
	* daraprehalfgujr
	* darasquishgujr
	* darvocalicvowelgujr
	* darvocalicvowelnuktagujr
	* ddaddagujr
	* ddaddaugujr
	* ddhaddhagujr
	* ddhayagujr
	* ddhayastemgujr
	* dharagujr
	* dharanuktagujr
	* dharanuktaprehalfgujr
	* dharanuktastemgujr
	* dharaprehalfgujr
	* dharastemgujr
	* eanusvaragujr
	* ecandraanusvaragujr
	* ecandragujr
	* egujr
	* gharagujr
	* gharanuktagujr
	* gharanuktaprehalfgujr
	* gharanuktastemgujr
	* gharaprehalfgujr
	* gharastemgujr
	* halagujr
	* halastemgujr
	* hamagujr
	* hamastemgujr
	* hanagujr
	* hanastemgujr
	* hannagujr
	* hannastemgujr
	* haragujr
	* haranuktagujr
	* haranuktaprehalfgujr
	* haranuktastemgujr
	* haraprehalfgujr
	* harastemgujr
	* havagujr
	* havastemgujr
	* hayagujr
	* hayastemgujr
	* jaaavowelgujr
	* jaaavowelnuktagujr
	* jagujr
	* jaiivowelgujr
	* jaiivowelnuktagujr
	* januktagujr
	* januktaprehalfgujr
	* januktasquishgujr
	* janyagujr
	* janyaragujr
	* janyarastemgujr
	* janyastemgujr
	* japrehalfgujr
	* jaragujr
	* jaranuktagujr
	* jaranuktaprehalfgujr
	* jaraprehalfgujr
	* jasquishgujr
	* jayagujr
	* jayastemgujr
	* jhagujr
	* jhanuktagujr
	* jhanuktaprehalfgujr
	* jhaprehalfgujr
	* jharagujr
	* jharanuktagujr
	* jharanuktaprehalfgujr
	* jharaprehalfgujr
	* kagujr
	* kakagujr
	* kanuktagujr
	* kanuktaprehalfgujr
	* kanuktauuvowelgujr
	* kanuktauvowelgujr
	* kaprehalfgujr
	* karagujr
	* karanuktagujr
	* karanuktaprehalfgujr
	* karanuktauuvowelgujr
	* karanuktauvowelgujr
	* karaprehalfgujr
	* kassagujr
	* kassaragujr
	* kassarastemgujr
	* kassastemgujr
	* kayagujr
	* kayastemgujr
	* khagujr
	* khanuktagujr
	* khanuktastemgujr
	* kharagujr
	* kharanuktagujr
	* kharanuktastemgujr
	* kharastemgujr
	* khastemgujr
	* khayagujr
	* khayastemgujr
	* llvocalicgujr
	* lvocalicgujr
	* maragujr
	* maranuktagujr
	* maranuktastemgujr
	* marastemgujr
	* ngagagujr
	* ngaghagujr
	* ngakagujr
	* ngamagujr
	* nnarauvowelgujr
	* nnarauvowelnuktagujr
	* nyacagujr
	* nyacastemgujr
	* nyagujr
	* nyajagujr
	* nyajastemgujr
	* nyanuktagujr
	* nyanuktastemgujr
	* nyaragujr
	* nyaranuktagujr
	* nyaranuktastemgujr
	* nyarastemgujr
	* nyastemgujr
	* oanusvaragujr
	* ocandraanusvaragujr
	* ocandragujr
	* ogujr
	* paragujr
	* paranuktagujr
	* paranuktaprehalfgujr
	* paranuktastemgujr
	* paraprehalfgujr
	* parastemgujr
	* phaaltgujr
	* phagujr
	* phanuktaaltgujr
	* phanuktagujr
	* phanuktaprehalfgujr
	* phanuktasquishgujr
	* phaprehalfgujr
	* pharaaltgujr
	* pharagujr
	* pharanuktaaltgujr
	* pharanuktagujr
	* pharanuktaprehalfgujr
	* pharanuktasquishgujr
	* pharaprehalfgujr
	* pharasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* ragujr
	* ranuktagujr
	* ranuktaprehalfgujr
	* ranuktasquishgujr
	* raprehalfgujr
	* raranuktagujr
	* raranuktaprehalfgujr
	* rasquishgujr
	* rauuvowelgujr
	* rauuvowelnuktagujr
	* rauvowelgujr
	* rauvowelnuktagujr
	* rrvocalicgujr
	* rvocalicgujr
	* sagujr
	* sanuktagujr
	* sanuktaprehalfgujr
	* sanuktastemgujr
	* sapreformaltgujr
	* saprehalfgujr
	* saragujr
	* saranuktagujr
	* saranuktaprehalfgujr
	* saranuktastemgujr
	* saraprehalfgujr
	* sarastemgujr
	* sastemgujr
	* sataragujr
	* satarastemgujr
	* sathagujr
	* sathapreformgujr
	* sathastemgujr
	* shacagujr
	* shacastemgujr
	* shagujr
	* shalagujr
	* shalastemgujr
	* shanagujr
	* shanastemgujr
	* shanuktagujr
	* shanuktaprehalfgujr
	* shanuktastemgujr
	* shapreformaltgujr
	* shaprehalfgujr
	* sharagujr
	* sharanuktagujr
	* sharanuktaprehalfgujr
	* sharanuktastemgujr
	* sharaprehalfgujr
	* sharastemgujr
	* shastemgujr
	* shavagujr
	* shavastemgujr
	* ssaragujr
	* ssaranuktagujr
	* ssaranuktaprehalfgujr
	* ssaranuktastemgujr
	* ssaraprehalfgujr
	* ssarastemgujr
	* ssattagujr
	* ssattaragujr
	* ssatthagujr
	* ssattharagujr
	* tharagujr
	* tharanuktagujr
	* tharanuktaprehalfgujr
	* tharanuktastemgujr
	* tharaprehalfgujr
	* tharastemgujr
	* ttattagujr
	* ttattaugujr
	* ttattauugujr
	* ttatthagujr
	* ttatthauugujr
	* tthagujr
	* tthanuktagujr
	* tthanuktaprehalfgujr
	* tthanuktasquishgujr
	* tthaprehalfgujr
	* ttharagujr
	* ttharanuktagujr
	* ttharanuktaprehalfgujr
	* ttharaprehalfgujr
	* tthasquishgujr
	* tthatthagujr
	* tthatthaugujr
	* tthayagujr
	* tthayastemgujr
	* twogujr
	* uni0AF1
	* uni20B9.gujr
	* varagujr
	* varanuktagujr
	* varanuktaprehalfgujr
	* varanuktastemgujr
	* varaprehalfgujr
	* varastemgujr
	* yaranuktaprehalfgujr
	* yaraprehalfgujr
	* zhaaavowelgujr
	* zhagujr
	* zhaiivowelgujr
	* zhaprehalfgujr
	* zharagujr
	* zharaprehalfgujr and zhasquishgujr
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[9] NotoSansGujarati-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aagujr
	* agujr
	* aianusvaragujr
	* aigujr
	* auanusvaragujr
	* augujr
	* bagujr
	* banuktagujr
	* banuktastemgujr
	* baragujr
	* baranuktagujr
	* baranuktastemgujr
	* barastemgujr
	* bastemgujr
	* bharagujr
	* bharanuktagujr
	* bharanuktastemgujr
	* bharastemgujr
	* caragujr
	* caranuktagujr
	* caranuktaprehalfgujr
	* caranuktastemgujr
	* caraprehalfgujr
	* carastemgujr
	* dabagujr
	* dadasquishgujr
	* dadhagujr
	* dadhasquishgujr
	* daghagujr
	* daghasquishgujr
	* danasquishgujr
	* daragujr
	* daranuktagujr
	* daranuktaprehalfgujr
	* daranuktasquishgujr
	* daraprehalfgujr
	* darasquishgujr
	* darvocalicvowelgujr
	* darvocalicvowelnuktagujr
	* ddaddagujr
	* ddaddaugujr
	* ddhaddhagujr
	* dharagujr
	* dharanuktagujr
	* dharanuktaprehalfgujr
	* dharanuktastemgujr
	* dharaprehalfgujr
	* dharastemgujr
	* eanusvaragujr
	* ecandraanusvaragujr
	* ecandragujr
	* egujr
	* gharagujr
	* gharanuktagujr
	* gharanuktaprehalfgujr
	* gharanuktastemgujr
	* gharaprehalfgujr
	* gharastemgujr
	* halagujr
	* halastemgujr
	* hamagujr
	* hamastemgujr
	* hannagujr
	* hannastemgujr
	* jaaavowelgujr
	* jaaavowelnuktagujr
	* jaiivowelgujr
	* jaiivowelnuktagujr
	* janyagujr
	* janyaragujr
	* janyarastemgujr
	* janyastemgujr
	* jayagujr
	* jayastemgujr
	* jharagujr
	* jharanuktagujr
	* kakagujr
	* karagujr
	* karanuktagujr
	* karanuktaprehalfgujr
	* karanuktauuvowelgujr
	* karanuktauvowelgujr
	* karaprehalfgujr
	* kassaragujr
	* kassarastemgujr
	* kayagujr
	* kayastemgujr
	* khagujr
	* khanuktagujr
	* khanuktastemgujr
	* kharagujr
	* kharanuktagujr
	* kharanuktastemgujr
	* kharastemgujr
	* khastemgujr
	* khayagujr
	* khayastemgujr
	* lvocalicgujr
	* ngagagujr
	* ngaghagujr
	* ngakagujr
	* nyacagujr
	* nyacastemgujr
	* nyagujr
	* nyajagujr
	* nyajastemgujr
	* nyanuktagujr
	* nyanuktastemgujr
	* nyaragujr
	* nyaranuktagujr
	* nyaranuktastemgujr
	* nyarastemgujr
	* nyastemgujr
	* oanusvaragujr
	* ocandraanusvaragujr
	* ocandragujr
	* ogujr
	* phaaltgujr
	* phagujr
	* phanuktaaltgujr
	* phanuktagujr
	* phanuktaprehalfgujr
	* phanuktasquishgujr
	* phaprehalfgujr
	* pharaaltgujr
	* pharagujr
	* pharanuktaaltgujr
	* pharanuktagujr
	* pharanuktaprehalfgujr
	* pharanuktasquishgujr
	* pharaprehalfgujr
	* pharasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* rauuvowelgujr
	* rauuvowelnuktagujr
	* rauvowelgujr
	* rauvowelnuktagujr
	* rrvocalicgujr
	* rvocalicgujr
	* sagujr
	* sanuktagujr
	* sanuktaprehalfgujr
	* sanuktastemgujr
	* sapreformaltgujr
	* saprehalfgujr
	* saragujr
	* saranuktagujr
	* saranuktaprehalfgujr
	* saranuktastemgujr
	* saraprehalfgujr
	* sarastemgujr
	* sastemgujr
	* sataragujr
	* satarastemgujr
	* sathagujr
	* sathapreformgujr
	* sathastemgujr
	* shacagujr
	* shacastemgujr
	* shalagujr
	* shalastemgujr
	* shanagujr
	* shanastemgujr
	* sharagujr
	* sharanuktagujr
	* sharanuktastemgujr
	* sharastemgujr
	* shavagujr
	* shavastemgujr
	* ssaragujr
	* ssaranuktagujr
	* ssaranuktastemgujr
	* ssarastemgujr
	* ssattagujr
	* ssattaragujr
	* ssatthagujr
	* ssattharagujr
	* tharanuktaprehalfgujr
	* tharaprehalfgujr
	* ttattaugujr
	* ttattauugujr
	* ttatthagujr
	* ttatthauugujr
	* tthatthagujr
	* tthatthaugujr
	* uni0AF1
	* varagujr
	* varanuktagujr
	* varanuktaprehalfgujr
	* varanuktastemgujr
	* varaprehalfgujr
	* varastemgujr
	* zhaaavowelgujr and zhaiivowelgujr
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[12] NotoSansGujarati-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* aagujr
	* agujr
	* aianusvaragujr
	* aigujr
	* auanusvaragujr
	* augujr
	* badagujr
	* bagujr
	* banuktagujr
	* banuktastemgujr
	* baragujr
	* baranuktagujr
	* baranuktastemgujr
	* barastemgujr
	* bastemgujr
	* bharagujr
	* bharanuktagujr
	* bharanuktastemgujr
	* bharastemgujr
	* cagujr
	* canuktagujr
	* canuktaprehalfgujr
	* canuktastemgujr
	* caprehalfgujr
	* caragujr
	* caranuktagujr
	* caranuktaprehalfgujr
	* caranuktastemgujr
	* caraprehalfgujr
	* carastemgujr
	* castemgujr
	* chavagujr
	* chayagujr
	* chayastemgujr
	* dabagujr
	* dabhagujr
	* dadagujr
	* dadasquishgujr
	* dadhagujr
	* dadhasquishgujr
	* dagagujr
	* dagasquishgujr
	* daghagujr
	* daghasquishgujr
	* danagujr
	* danasquishgujr
	* daragujr
	* daranuktagujr
	* daranuktaprehalfgujr
	* daranuktasquishgujr
	* daraprehalfgujr
	* darasquishgujr
	* darvocalicvowelgujr
	* darvocalicvowelnuktagujr
	* davagujr
	* dayagujr
	* dayastemgujr
	* ddaddagujr
	* ddaddaugujr
	* ddaddhagujr
	* ddhaddhagujr
	* ddhayagujr
	* ddhayastemgujr
	* dharagujr
	* dharanuktagujr
	* dharanuktaprehalfgujr
	* dharanuktastemgujr
	* dharaprehalfgujr
	* dharastemgujr
	* eanusvaragujr
	* ecandraanusvaragujr
	* ecandragujr
	* egujr
	* gharagujr
	* gharanuktagujr
	* gharanuktaprehalfgujr
	* gharanuktastemgujr
	* gharaprehalfgujr
	* gharastemgujr
	* halagujr
	* halastemgujr
	* hamagujr
	* hamastemgujr
	* hanagujr
	* hanastemgujr
	* hannagujr
	* hannastemgujr
	* haragujr
	* haranuktagujr
	* haranuktaprehalfgujr
	* haranuktastemgujr
	* haraprehalfgujr
	* harastemgujr
	* harvocalicvowelgujr
	* harvocalicvowelnuktagujr
	* havagujr
	* havastemgujr
	* hayagujr
	* hayastemgujr
	* ivowelsignreph2gujr
	* ivowelsignrephanusvara2gujr
	* jaaavowelgujr
	* jaaavowelnuktagujr
	* jagujr
	* jaiivowelgujr
	* jaiivowelnuktagujr
	* januktagujr
	* januktaprehalfgujr
	* januktasquishgujr
	* janyagujr
	* janyaprehalfgujr
	* janyaragujr
	* janyaraprehalfgujr
	* janyarastemgujr
	* janyastemgujr
	* japrehalfgujr
	* jaragujr
	* jaranuktagujr
	* jaranuktaprehalfgujr
	* jaraprehalfgujr
	* jasquishgujr
	* jayagujr
	* jayastemgujr
	* jhagujr
	* jhanuktagujr
	* jhanuktaprehalfgujr
	* jhaprehalfgujr
	* jharagujr
	* jharanuktagujr
	* jharanuktaprehalfgujr
	* jharaprehalfgujr
	* kagujr
	* kakagujr
	* kanuktagujr
	* kanuktaprehalfgujr
	* kanuktauuvowelgujr
	* kanuktauvowelgujr
	* kaprehalfgujr
	* karagujr
	* karanuktagujr
	* karanuktaprehalfgujr
	* karanuktauuvowelgujr
	* karanuktauvowelgujr
	* karaprehalfgujr
	* kassagujr
	* kassaprehalfgujr
	* kassaragujr
	* kassaraprehalfgujr
	* kassarastemgujr
	* kassastemgujr
	* kayagujr
	* kayastemgujr
	* khagujr
	* khanuktagujr
	* khanuktastemgujr
	* kharagujr
	* kharanuktagujr
	* kharanuktastemgujr
	* kharastemgujr
	* khastemgujr
	* khayagujr
	* khayastemgujr
	* laragujr
	* laranuktagujr
	* laranuktastemgujr
	* larastemgujr
	* llvocalicgujr
	* lvocalicgujr
	* maragujr
	* maranuktagujr
	* maranuktastemgujr
	* marastemgujr
	* naragujr
	* naranuktagujr
	* naranuktastemgujr
	* narastemgujr
	* ngagagujr
	* ngaghagujr
	* ngakagujr
	* ngamagujr
	* nnarauvowelgujr
	* nnarauvowelnuktagujr
	* nyacagujr
	* nyacastemgujr
	* nyagujr
	* nyajagujr
	* nyajastemgujr
	* nyanuktagujr
	* nyanuktaprehalfgujr
	* nyanuktastemgujr
	* nyaprehalfgujr
	* nyaragujr
	* nyaranuktagujr
	* nyaranuktaprehalfgujr
	* nyaranuktastemgujr
	* nyaraprehalfgujr
	* nyarastemgujr
	* nyastemgujr
	* oanusvaragujr
	* ocandraanusvaragujr
	* ocandragujr
	* ogujr
	* paragujr
	* paranuktagujr
	* paranuktaprehalfgujr
	* paranuktastemgujr
	* paraprehalfgujr
	* parastemgujr
	* phaaltgujr
	* phagujr
	* phanuktaaltgujr
	* phanuktagujr
	* phanuktaprehalfgujr
	* phanuktasquishgujr
	* phaprehalfgujr
	* pharaaltgujr
	* pharagujr
	* pharanuktaaltgujr
	* pharanuktagujr
	* pharanuktaprehalfgujr
	* pharanuktasquishgujr
	* pharaprehalfgujr
	* pharasquishgujr
	* phasquishgujr
	* phayagujr
	* phayastemgujr
	* ragujr
	* ranuktagujr
	* ranuktaprehalfgujr
	* ranuktasquishgujr
	* raprehalfgujr
	* raranuktagujr
	* raranuktaprehalfgujr
	* rasquishgujr
	* rauuvowelgujr
	* rauuvowelnuktagujr
	* rauvowelgujr
	* rauvowelnuktagujr
	* rrvocalicgujr
	* rvocalicgujr
	* sagujr
	* sanuktagujr
	* sanuktaprehalfgujr
	* sanuktastemgujr
	* sapreformaltgujr
	* saprehalfgujr
	* saragujr
	* saranuktagujr
	* saranuktaprehalfgujr
	* saranuktastemgujr
	* saraprehalfgujr
	* sarastemgujr
	* sastemgujr
	* sataragujr
	* satarastemgujr
	* sathagujr
	* sathapreformgujr
	* sathastemgujr
	* shacagujr
	* shacastemgujr
	* shagujr
	* shalagujr
	* shalastemgujr
	* shanagujr
	* shanastemgujr
	* shanuktagujr
	* shanuktaprehalfgujr
	* shanuktastemgujr
	* shapreformaltgujr
	* shaprehalfgujr
	* sharagujr
	* sharanuktagujr
	* sharanuktaprehalfgujr
	* sharanuktastemgujr
	* sharaprehalfgujr
	* sharastemgujr
	* shastemgujr
	* shavagujr
	* shavastemgujr
	* ssaragujr
	* ssaranuktagujr
	* ssaranuktaprehalfgujr
	* ssaranuktastemgujr
	* ssaraprehalfgujr
	* ssarastemgujr
	* ssattagujr
	* ssattaragujr
	* ssatthagujr
	* ssattharagujr
	* tharagujr
	* tharanuktagujr
	* tharanuktaprehalfgujr
	* tharanuktastemgujr
	* tharaprehalfgujr
	* tharastemgujr
	* ttattagujr
	* ttattaugujr
	* ttattauugujr
	* ttatthagujr
	* ttatthauugujr
	* ttayagujr
	* ttayastemgujr
	* tthagujr
	* tthanuktagujr
	* tthanuktaprehalfgujr
	* tthanuktasquishgujr
	* tthaprehalfgujr
	* ttharagujr
	* ttharanuktagujr
	* ttharanuktaprehalfgujr
	* ttharaprehalfgujr
	* tthasquishgujr
	* tthatthagujr
	* tthatthaugujr
	* tthayagujr
	* tthayastemgujr
	* twogujr
	* uni0AF1
	* uni20B9.gujr
	* uniA837
	* varagujr
	* varanuktagujr
	* varanuktaprehalfgujr
	* varanuktastemgujr
	* varaprehalfgujr
	* varastemgujr
	* yaragujr
	* yaranuktagujr
	* yaranuktaprehalfgujr
	* yaranuktastemgujr
	* yaraprehalfgujr
	* yarastemgujr
	* zhaaavowelgujr
	* zhagujr
	* zhaiivowelgujr
	* zhaprehalfgujr
	* zharagujr
	* zharaprehalfgujr and zhasquishgujr
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=353.0,Y=592.5 (should be at cap-height 592?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=168.0,Y=590.5 (should be at cap-height 592?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=531.0,Y=0.5 (should be at baseline 0?)

	* S (U+0053): X=210.0,Y=592.5 (should be at cap-height 592?)

	* asciicircum (U+005E): X=275.0,Y=590.0 (should be at cap-height 592?)

	* c (U+0063): X=388.5,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=423.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=126.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=2.0 (should be at baseline 0?)

	* section (U+00A7): X=129.0,Y=1.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=485.5,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=503.0,Y=590.0 (should be at cap-height 592?)

	* ae (U+00E6): X=740.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=308.5,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=388.5,Y=-1.0 (should be at baseline 0?)

	* egrave (U+00E8): X=423.0,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=423.0,Y=-1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=217.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cacute (U+0107): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=485.5,Y=-2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=388.5,Y=-1.0 (should be at baseline 0?)

	* emacron (U+0113): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecaron (U+011B): X=423.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=531.0,Y=0.5 (should be at baseline 0?)

	* Eng (U+014A): X=586.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=700.0,Y=2.0 (should be at baseline 0?)

	* Ohungarumlaut (U+0150): X=573.5,Y=895.0 (should be at ascender 896?)

	* Ohungarumlaut (U+0150): X=386.0,Y=895.0 (should be at ascender 896?)

	* oe (U+0153): X=807.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=210.0,Y=592.5 (should be at cap-height 592?)

	* sacute (U+015B): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=210.0,Y=592.5 (should be at cap-height 592?)

	* scedilla (U+015F): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=210.0,Y=592.5 (should be at cap-height 592?)

	* scaron (U+0161): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Uhungarumlaut (U+0170): X=551.5,Y=895.0 (should be at ascender 896?)

	* Uhungarumlaut (U+0170): X=364.0,Y=895.0 (should be at ascender 896?)

	* ycircumflex (U+0177): X=217.0,Y=2.0 (should be at baseline 0?)

	* Scommaaccent (U+0218): X=210.0,Y=592.5 (should be at cap-height 592?)

	* scommaaccent (U+0219): X=126.5,Y=-2.0 (should be at baseline 0?)

	* igujr (U+0A87): X=320.0,Y=591.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=320.0,Y=591.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=333.0,Y=593.5 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=333.0,Y=593.5 (should be at cap-height 592?)

	* gagujr (U+0A97): X=123.5,Y=593.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=320.0,Y=591.0 (should be at cap-height 592?)

	* ngagujr (U+0A99): X=411.0,Y=591.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=320.0,Y=591.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=607.0,Y=591.5 (should be at cap-height 592?)

	* jhagujr (U+0A9D): X=303.0,Y=0.5 (should be at baseline 0?)

	* nyagujr (U+0A9E): X=123.5,Y=593.5 (should be at cap-height 592?)

	* ttagujr (U+0A9F): X=160.5,Y=594.0 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=436.0,Y=591.0 (should be at cap-height 592?)

	* ddagujr (U+0AA1): X=411.0,Y=591.0 (should be at cap-height 592?)

	* ddhagujr (U+0AA2): X=171.5,Y=594.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=410.0,Y=590.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=140.0,Y=-2.0 (should be at baseline 0?)

	* bhagujr (U+0AAD): X=353.5,Y=590.0 (should be at cap-height 592?)

	* yagujr (U+0AAF): X=14.0,Y=590.0 (should be at cap-height 592?)

	* ragujr (U+0AB0): X=108.0,Y=593.5 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=518.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=15.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=28.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=83.5,Y=590.5 (should be at cap-height 592?)

	* sagujr (U+0AB8): X=105.5,Y=593.5 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=550.0,Y=591.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=533.0,Y=1.5 (should be at baseline 0?)

	* omgujr (U+0AD0): X=174.5,Y=593.5 (should be at cap-height 592?)

	* llvocalicgujr (U+0AE1): X=758.0,Y=1.0 (should be at baseline 0?)

	* llvocalicgujr (U+0AE1): X=502.0,Y=-2.0 (should be at baseline 0?)

	* onegujr (U+0AE7): X=327.5,Y=593.5 (should be at cap-height 592?)

	* twogujr (U+0AE8): X=154.0,Y=593.5 (should be at cap-height 592?)

	* threegujr (U+0AE9): X=192.0,Y=593.5 (should be at cap-height 592?)

	* sixgujr (U+0AEC): X=335.0,Y=1.0 (should be at baseline 0?)

	* ninegujr (U+0AEF): X=456.5,Y=-0.5 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=122.5,Y=593.5 (should be at cap-height 592?)

	* Germandbls (U+1E9E): X=354.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=2.0 (should be at baseline 0?)

	* euro (U+20AC): X=471.5,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansGujarati-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsignlowgujr

	- lvocalicvowelsignlowgujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsignlowgujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-202.5,707.0>-<-172.0,716.0>-<-141.0,731.0>>/B<<-141.0,731.0>-<-156.0,726.0>-<-169.0,724.5>> = 7.386043151267186 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansGujaratiUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 586 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 318:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three (U+0033): X=129.0,Y=0.5 (should be at baseline 0?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* r (U+0072): X=311.5,Y=534.5 (should be at x-height 536?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* degree (U+00B0): X=257.5,Y=591.0 (should be at cap-height 592?)

	* degree (U+00B0): X=164.5,Y=591.0 (should be at cap-height 592?)

	* Ccedilla (U+00C7): X=490.5,Y=-0.5 (should be at baseline 0?)

	* germandbls (U+00DF): X=283.5,Y=592.5 (should be at cap-height 592?)

	* agrave (U+00E0): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aacute (U+00E1): X=282.0,Y=-1.5 (should be at baseline 0?)

	* acircumflex (U+00E2): X=282.0,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=282.0,Y=-1.5 (should be at baseline 0?)

	* adieresis (U+00E4): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aring (U+00E5): X=282.0,Y=-1.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-1.5 (should be at baseline 0?)

	* amacron (U+0101): X=282.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=282.0,Y=-1.5 (should be at baseline 0?)

	* aogonek (U+0105): X=282.0,Y=-1.5 (should be at baseline 0?)

	* Cacute (U+0106): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=490.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=545.5,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gbreve (U+011F): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=545.5,Y=2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=386.0,Y=1.0 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=545.5,Y=2.0 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=577.0,Y=-1.0 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=386.0,Y=1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=363.0,Y=-1.0 (should be at baseline 0?)

	* tcommaaccent (U+021B): X=363.0,Y=-1.0 (should be at baseline 0?)

	* igujr (U+0A87): X=330.0,Y=591.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=330.0,Y=591.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=375.5,Y=593.5 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=375.0,Y=593.5 (should be at cap-height 592?)

	* gagujr (U+0A97): X=138.5,Y=591.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=338.0,Y=591.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=352.0,Y=590.0 (should be at cap-height 592?)

	* nyagujr (U+0A9E): X=138.5,Y=591.5 (should be at cap-height 592?)

	* ttagujr (U+0A9F): X=161.0,Y=592.5 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=472.0,Y=590.0 (should be at cap-height 592?)

	* ddhagujr (U+0AA2): X=172.5,Y=594.0 (should be at cap-height 592?)

	* bhagujr (U+0AAD): X=383.5,Y=590.0 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=538.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=19.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=65.0,Y=593.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=577.0,Y=590.0 (should be at cap-height 592?)

	* aavowelsigngujr (U+0ABE): X=241.0,Y=593.0 (should be at cap-height 592?)

	* ivowelsigngujr (U+0ABF): X=241.0,Y=594.0 (should be at cap-height 592?)

	* iivowelsigngujr (U+0AC0): X=64.0,Y=594.0 (should be at cap-height 592?)

	* ocandravowelsigngujr (U+0AC9): X=241.0,Y=593.0 (should be at cap-height 592?)

	* ovowelsigngujr (U+0ACB): X=241.0,Y=593.0 (should be at cap-height 592?)

	* auvowelsigngujr (U+0ACC): X=241.0,Y=593.0 (should be at cap-height 592?)

	* rrvocalicgujr (U+0AE0): X=904.0,Y=-1.0 (should be at baseline 0?)

	* threegujr (U+0AE9): X=207.0,Y=592.5 (should be at cap-height 592?)

	* ninegujr (U+0AEF): X=473.0,Y=-1.5 (should be at baseline 0?)

	* Germandbls (U+1E9E): X=401.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wdieresis (U+1E84): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wdieresis (U+1E84): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wdieresis (U+1E84): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wgrave (U+1E80): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wgrave (U+1E80): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wgrave (U+1E80): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansGujaratiUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wdieresis (U+1E84): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wgrave (U+1E80): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wgrave (U+1E80): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansGujaratiUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 578 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 320:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=275.5,Y=591.5 (should be at cap-height 592?)

	* comma (U+002C): X=57.5,Y=2.0 (should be at baseline 0?)

	* six (U+0036): X=403.0,Y=590.0 (should be at cap-height 592?)

	* semicolon (U+003B): X=57.5,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=231.0,Y=590.0 (should be at cap-height 592?)

	* C (U+0043): X=485.5,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=535.5,Y=1.5 (should be at baseline 0?)

	* S (U+0053): X=142.0,Y=1.0 (should be at baseline 0?)

	* b (U+0062): X=298.0,Y=535.5 (should be at x-height 536?)

	* c (U+0063): X=405.0,Y=1.5 (should be at baseline 0?)

	* e (U+0065): X=441.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=341.0,Y=538.0 (should be at x-height 536?)

	* g (U+0067): X=565.0,Y=-1.0 (should be at baseline 0?)

	* h (U+0068): X=238.0,Y=537.5 (should be at x-height 536?)

	* h (U+0068): X=498.5,Y=538.0 (should be at x-height 536?)

	* p (U+0070): X=298.0,Y=535.0 (should be at x-height 536?)

	* q (U+0071): X=344.5,Y=536.5 (should be at x-height 536?)

	* t (U+0074): X=352.0,Y=-2.0 (should be at baseline 0?)

	* section (U+00A7): X=131.0,Y=-0.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=485.5,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=630.0,Y=594.0 (should be at cap-height 592?)

	* germandbls (U+00DF): X=630.0,Y=594.0 (should be at cap-height 592?)

	* ae (U+00E6): X=764.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=311.0,Y=-0.5 (should be at baseline 0?)

	* ccedilla (U+00E7): X=405.0,Y=1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=441.5,Y=-0.5 (should be at baseline 0?)

	* eacute (U+00E9): X=441.5,Y=-0.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=441.5,Y=-0.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=441.5,Y=-0.5 (should be at baseline 0?)

	* divide (U+00F7): X=238.0,Y=593.0 (should be at cap-height 592?)

	* divide (U+00F7): X=338.5,Y=593.0 (should be at cap-height 592?)

	* Cacute (U+0106): X=485.5,Y=-1.0 (should be at baseline 0?)

	* cacute (U+0107): X=405.0,Y=1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=485.5,Y=-1.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=405.0,Y=1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=485.5,Y=-1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=405.0,Y=1.5 (should be at baseline 0?)

	* emacron (U+0113): X=441.5,Y=-0.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=441.5,Y=-0.5 (should be at baseline 0?)

	* ecaron (U+011B): X=441.5,Y=-0.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=535.5,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=565.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=535.5,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=565.0,Y=-1.0 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=535.5,Y=1.5 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=565.0,Y=-1.0 (should be at baseline 0?)

	* Eng (U+014A): X=593.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=739.0,Y=-2.0 (should be at baseline 0?)

	* oe (U+0153): X=816.5,Y=-0.5 (should be at baseline 0?)

	* Sacute (U+015A): X=142.0,Y=1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=142.0,Y=1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=142.0,Y=1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=352.0,Y=-2.0 (should be at baseline 0?)

	* Scommaaccent (U+0218): X=142.0,Y=1.0 (should be at baseline 0?)

	* tcommaaccent (U+021B): X=352.0,Y=-2.0 (should be at baseline 0?)

	* igujr (U+0A87): X=329.0,Y=591.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=329.0,Y=591.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=358.0,Y=594.0 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=357.5,Y=594.0 (should be at cap-height 592?)

	* gagujr (U+0A97): X=130.5,Y=592.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=333.0,Y=591.0 (should be at cap-height 592?)

	* ngagujr (U+0A99): X=435.0,Y=590.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=340.0,Y=591.0 (should be at cap-height 592?)

	* nyagujr (U+0A9E): X=130.5,Y=592.5 (should be at cap-height 592?)

	* ttagujr (U+0A9F): X=161.0,Y=593.0 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=460.0,Y=591.0 (should be at cap-height 592?)

	* ddagujr (U+0AA1): X=435.0,Y=590.0 (should be at cap-height 592?)

	* ddhagujr (U+0AA2): X=172.5,Y=594.0 (should be at cap-height 592?)

	* nnagujr (U+0AA3): X=368.0,Y=594.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=133.0,Y=1.0 (should be at baseline 0?)

	* ragujr (U+0AB0): X=113.0,Y=593.0 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=532.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=17.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=48.0,Y=593.0 (should be at cap-height 592?)

	* sagujr (U+0AB8): X=112.0,Y=593.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=570.0,Y=591.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=554.0,Y=1.5 (should be at baseline 0?)

	* omgujr (U+0AD0): X=187.5,Y=593.0 (should be at cap-height 592?)

	* onegujr (U+0AE7): X=352.5,Y=590.0 (should be at cap-height 592?)

	* twogujr (U+0AE8): X=159.0,Y=593.0 (should be at cap-height 592?)

	* threegujr (U+0AE9): X=200.0,Y=593.5 (should be at cap-height 592?)

	* ninegujr (U+0AEF): X=469.0,Y=-0.5 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=128.0,Y=593.5 (should be at cap-height 592?)

	* quotesinglbase (U+201A): X=57.5,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=295.5,Y=1.5 (should be at baseline 0?)

	* quotedblbase (U+201E): X=57.5,Y=1.5 (should be at baseline 0?)

	* trademark (U+2122): X=637.0,Y=590.5 (should be at cap-height 592?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wgrave (U+1E80): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansGujaratiUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=141.5,Y=1.5 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=1.5 (should be at baseline 0?)

	* comma (U+002C): X=72.0,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=141.5,Y=1.5 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=1.5 (should be at baseline 0?)

	* three (U+0033): X=136.5,Y=1.5 (should be at baseline 0?)

	* five (U+0035): X=149.5,Y=1.5 (should be at baseline 0?)

	* nine (U+0039): X=95.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=141.5,Y=1.5 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=1.5 (should be at baseline 0?)

	* less (U+003C): X=515.0,Y=590.0 (should be at cap-height 592?)

	* greater (U+003E): X=55.0,Y=590.0 (should be at cap-height 592?)

	* question (U+003F): X=189.0,Y=1.5 (should be at baseline 0?)

	* question (U+003F): X=137.5,Y=1.5 (should be at baseline 0?)

	* C (U+0043): X=491.0,Y=-1.5 (should be at baseline 0?)

	* G (U+0047): X=534.5,Y=1.0 (should be at baseline 0?)

	* Q (U+0051): X=457.0,Y=-2.0 (should be at baseline 0?)

	* S (U+0053): X=136.5,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=127.0,Y=535.0 (should be at x-height 536?)

	* e (U+0065): X=387.5,Y=-2.0 (should be at baseline 0?)

	* r (U+0072): X=290.0,Y=538.0 (should be at x-height 536?)

	* r (U+0072): X=331.0,Y=535.5 (should be at x-height 536?)

	* r (U+0072): X=290.0,Y=538.0 (should be at x-height 536?)

	* w (U+0077): X=205.0,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=167.0,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=548.0,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=509.0,Y=-1.0 (should be at baseline 0?)

	* section (U+00A7): X=232.0,Y=-2.0 (should be at baseline 0?)

	* copyright (U+00A9): X=655.0,Y=592.5 (should be at cap-height 592?)

	* registered (U+00AE): X=655.0,Y=592.5 (should be at cap-height 592?)

	* Ccedilla (U+00C7): X=491.0,Y=-1.5 (should be at baseline 0?)

	* germandbls (U+00DF): X=271.5,Y=-1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=387.5,Y=-2.0 (should be at baseline 0?)

	* eacute (U+00E9): X=387.5,Y=-2.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=387.5,Y=-2.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=387.5,Y=-2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=491.0,Y=-1.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=491.0,Y=-1.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=491.0,Y=-1.5 (should be at baseline 0?)

	* emacron (U+0113): X=387.5,Y=-2.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=387.5,Y=-2.0 (should be at baseline 0?)

	* ecaron (U+011B): X=387.5,Y=-2.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=534.5,Y=1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=534.5,Y=1.0 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=534.5,Y=1.0 (should be at baseline 0?)

	* oe (U+0153): X=805.5,Y=-2.0 (should be at baseline 0?)

	* Sacute (U+015A): X=136.5,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=136.5,Y=-1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=136.5,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=205.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=167.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=548.0,Y=-1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=509.0,Y=-1.0 (should be at baseline 0?)

	* Scommaaccent (U+0218): X=136.5,Y=-1.0 (should be at baseline 0?)

	* igujr (U+0A87): X=290.0,Y=593.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=290.0,Y=593.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=385.5,Y=594.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=302.0,Y=592.5 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=302.0,Y=592.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=288.0,Y=591.0 (should be at cap-height 592?)

	* ngagujr (U+0A99): X=357.0,Y=593.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=295.0,Y=593.0 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=387.0,Y=591.0 (should be at cap-height 592?)

	* ddagujr (U+0AA1): X=357.0,Y=593.0 (should be at cap-height 592?)

	* dagujr (U+0AA6): X=329.0,Y=591.0 (should be at cap-height 592?)

	* ragujr (U+0AB0): X=103.0,Y=594.0 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=489.0,Y=593.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=497.0,Y=591.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=493.5,Y=-1.0 (should be at baseline 0?)

	* omgujr (U+0AD0): X=172.0,Y=591.5 (should be at cap-height 592?)

	* lvocalicvowelsignlowgujr (U+0AE2): X=-339.0,Y=2.0 (should be at baseline 0?)

	* lvocalicvowelsignlowgujr (U+0AE2): X=-111.0,Y=2.0 (should be at baseline 0?)

	* llvocalicvowelsignlowgujr (U+0AE3): X=-339.0,Y=2.0 (should be at baseline 0?)

	* llvocalicvowelsignlowgujr (U+0AE3): X=-111.0,Y=2.0 (should be at baseline 0?)

	* threegujr (U+0AE9): X=195.0,Y=592.5 (should be at cap-height 592?)

	* ninegujr (U+0AEF): X=433.0,Y=-2.0 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=122.5,Y=592.5 (should be at cap-height 592?)

	* zhagujr (U+0AF9): X=110.0,Y=-2.0 (should be at baseline 0?)

	* zhagujr (U+0AF9): X=110.0,Y=-2.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=205.0,Y=-1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=167.0,Y=-1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=548.0,Y=-1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=509.0,Y=-1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=205.0,Y=-1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=167.0,Y=-1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=548.0,Y=-1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=509.0,Y=-1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=205.0,Y=-1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=167.0,Y=-1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=548.0,Y=-1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=509.0,Y=-1.0 (should be at baseline 0?)

	* Germandbls (U+1E9E): X=305.0,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=141.5,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=90.0,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=374.5,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=323.0,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=607.5,Y=1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=556.0,Y=1.5 (should be at baseline 0?)

	* euro (U+20AC): X=471.5,Y=-1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-216.0,707.5>-<-189.0,715.0>-<-162.0,728.0>>/B<<-162.0,728.0>-<-174.0,724.0>-<-184.0,723.0>> = 7.2750049578891804 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansGujaratiUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 571 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five (U+0035): X=147.5,Y=1.0 (should be at baseline 0?)

	* six (U+0036): X=185.0,Y=590.0 (should be at cap-height 592?)

	* nine (U+0039): X=98.0,Y=1.0 (should be at baseline 0?)

	* semicolon (U+003B): X=66.5,Y=-1.5 (should be at baseline 0?)

	* C (U+0043): X=491.0,Y=-2.0 (should be at baseline 0?)

	* O (U+004F): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Q (U+0051): X=478.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=579.5,Y=590.0 (should be at cap-height 592?)

	* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=458.0,Y=591.5 (should be at cap-height 592?)

	* c (U+0063): X=385.0,Y=535.0 (should be at x-height 536?)

	* e (U+0065): X=395.0,Y=-2.0 (should be at baseline 0?)

	* f (U+0066): X=111.0,Y=534.0 (should be at x-height 536?)

	* s (U+0073): X=118.0,Y=-0.5 (should be at baseline 0?)

	* t (U+0074): X=92.0,Y=537.0 (should be at x-height 536?)

	* y (U+0079): X=209.0,Y=2.0 (should be at baseline 0?)

	* cent (U+00A2): X=343.0,Y=591.0 (should be at cap-height 592?)

	* copyright (U+00A9): X=183.5,Y=590.5 (should be at cap-height 592?)

	* registered (U+00AE): X=183.5,Y=590.5 (should be at cap-height 592?)

	* Ccedilla (U+00C7): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Ograve (U+00D2): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Oacute (U+00D3): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Ocircumflex (U+00D4): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Otilde (U+00D5): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Odieresis (U+00D6): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Oslash (U+00D8): X=91.0,Y=-1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=578.0,Y=590.0 (should be at cap-height 592?)

	* germandbls (U+00DF): X=288.0,Y=-1.5 (should be at baseline 0?)

	* ae (U+00E6): X=702.0,Y=-2.0 (should be at baseline 0?)

	* egrave (U+00E8): X=395.0,Y=-2.0 (should be at baseline 0?)

	* eacute (U+00E9): X=395.0,Y=-2.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=395.0,Y=-2.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=395.0,Y=-2.0 (should be at baseline 0?)

	* eth (U+00F0): X=167.0,Y=593.0 (should be at cap-height 592?)

	* oslash (U+00F8): X=59.0,Y=-2.0 (should be at baseline 0?)

	* yacute (U+00FD): X=209.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=209.0,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=491.0,Y=-2.0 (should be at baseline 0?)

	* emacron (U+0113): X=395.0,Y=-2.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=395.0,Y=-2.0 (should be at baseline 0?)

	* eogonek (U+0119): X=392.0,Y=-2.0 (should be at baseline 0?)

	* ecaron (U+011B): X=395.0,Y=-2.0 (should be at baseline 0?)

	* Omacron (U+014C): X=579.5,Y=590.0 (should be at cap-height 592?)

	* Ohungarumlaut (U+0150): X=579.5,Y=590.0 (should be at cap-height 592?)

	* oe (U+0153): X=800.5,Y=-2.0 (should be at baseline 0?)

	* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

	* sacute (U+015B): X=118.0,Y=-0.5 (should be at baseline 0?)

	* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=118.0,Y=-0.5 (should be at baseline 0?)

	* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scaron (U+0161): X=118.0,Y=-0.5 (should be at baseline 0?)

	* Wcircumflex (U+0174): X=458.0,Y=591.5 (should be at cap-height 592?)

	* ycircumflex (U+0177): X=209.0,Y=2.0 (should be at baseline 0?)

	* Scommaaccent (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scommaaccent (U+0219): X=118.0,Y=-0.5 (should be at baseline 0?)

	* igujr (U+0A87): X=296.0,Y=593.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=296.0,Y=593.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=384.5,Y=591.5 (should be at cap-height 592?)

	* ugujr (U+0A89): X=308.0,Y=593.0 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=308.0,Y=593.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=299.0,Y=593.0 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=397.0,Y=591.0 (should be at cap-height 592?)

	* dagujr (U+0AA6): X=335.0,Y=590.0 (should be at cap-height 592?)

	* dagujr (U+0AA6): X=378.5,Y=2.0 (should be at baseline 0?)

	* dhagujr (U+0AA7): X=225.0,Y=594.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=135.0,Y=-1.0 (should be at baseline 0?)

	* ragujr (U+0AB0): X=104.5,Y=594.0 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=494.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=15.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=21.0,Y=593.0 (should be at cap-height 592?)

	* sagujr (U+0AB8): X=103.5,Y=594.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=508.0,Y=591.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=502.5,Y=-0.5 (should be at baseline 0?)

	* omgujr (U+0AD0): X=168.0,Y=592.5 (should be at cap-height 592?)

	* onegujr (U+0AE7): X=313.0,Y=591.5 (should be at cap-height 592?)

	* twogujr (U+0AE8): X=166.0,Y=594.0 (should be at cap-height 592?)

	* threegujr (U+0AE9): X=192.5,Y=593.0 (should be at cap-height 592?)

	* ninegujr (U+0AEF): X=436.5,Y=-2.0 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=123.0,Y=593.0 (should be at cap-height 592?)

	* Wgrave (U+1E80): X=458.0,Y=591.5 (should be at cap-height 592?)

	* Wacute (U+1E82): X=458.0,Y=591.5 (should be at cap-height 592?)

	* Wdieresis (U+1E84): X=458.0,Y=591.5 (should be at cap-height 592?)

	* Germandbls (U+1E9E): X=313.0,Y=0.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=209.0,Y=2.0 (should be at baseline 0?)

	* euro (U+20AC): X=470.5,Y=-1.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-236.0,709.0>-<-214.0,714.0>-<-192.0,723.0>>/B<<-192.0,723.0>-<-199.0,722.0>-<-205.0,721.5>> = 14.118921303056355 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansGujaratiUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[11] NotoSansGujaratiUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansGujaratiUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* two (U+0032): X=353.0,Y=592.5 (should be at cap-height 592?)

	* three (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* nine (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=168.0,Y=590.5 (should be at cap-height 592?)

	* C (U+0043): X=485.5,Y=-2.0 (should be at baseline 0?)

	* G (U+0047): X=531.0,Y=0.5 (should be at baseline 0?)

	* S (U+0053): X=210.0,Y=592.5 (should be at cap-height 592?)

	* asciicircum (U+005E): X=275.0,Y=590.0 (should be at cap-height 592?)

	* c (U+0063): X=388.5,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=423.0,Y=-1.0 (should be at baseline 0?)

	* s (U+0073): X=126.5,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=2.0 (should be at baseline 0?)

	* section (U+00A7): X=129.0,Y=1.5 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=485.5,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=503.0,Y=590.0 (should be at cap-height 592?)

	* ae (U+00E6): X=740.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=308.5,Y=2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=388.5,Y=-1.0 (should be at baseline 0?)

	* egrave (U+00E8): X=423.0,Y=-1.0 (should be at baseline 0?)

	* eacute (U+00E9): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edieresis (U+00EB): X=423.0,Y=-1.0 (should be at baseline 0?)

	* yacute (U+00FD): X=217.0,Y=2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=2.0 (should be at baseline 0?)

	* Cacute (U+0106): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cacute (U+0107): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=485.5,Y=-2.0 (should be at baseline 0?)

	* cdotaccent (U+010B): X=388.5,Y=-1.0 (should be at baseline 0?)

	* Ccaron (U+010C): X=485.5,Y=-2.0 (should be at baseline 0?)

	* ccaron (U+010D): X=388.5,Y=-1.0 (should be at baseline 0?)

	* emacron (U+0113): X=423.0,Y=-1.0 (should be at baseline 0?)

	* edotaccent (U+0117): X=423.0,Y=-1.0 (should be at baseline 0?)

	* ecaron (U+011B): X=423.0,Y=-1.0 (should be at baseline 0?)

	* Gbreve (U+011E): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=531.0,Y=0.5 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=531.0,Y=0.5 (should be at baseline 0?)

	* Eng (U+014A): X=586.0,Y=1.0 (should be at baseline 0?)

	* Eng (U+014A): X=700.0,Y=2.0 (should be at baseline 0?)

	* oe (U+0153): X=807.0,Y=-1.0 (should be at baseline 0?)

	* Sacute (U+015A): X=210.0,Y=592.5 (should be at cap-height 592?)

	* sacute (U+015B): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=210.0,Y=592.5 (should be at cap-height 592?)

	* scedilla (U+015F): X=126.5,Y=-2.0 (should be at baseline 0?)

	* Scaron (U+0160): X=210.0,Y=592.5 (should be at cap-height 592?)

	* scaron (U+0161): X=126.5,Y=-2.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=2.0 (should be at baseline 0?)

	* Scommaaccent (U+0218): X=210.0,Y=592.5 (should be at cap-height 592?)

	* scommaaccent (U+0219): X=126.5,Y=-2.0 (should be at baseline 0?)

	* igujr (U+0A87): X=320.0,Y=591.0 (should be at cap-height 592?)

	* iigujr (U+0A88): X=320.0,Y=591.0 (should be at cap-height 592?)

	* ugujr (U+0A89): X=333.0,Y=593.5 (should be at cap-height 592?)

	* uugujr (U+0A8A): X=333.0,Y=593.5 (should be at cap-height 592?)

	* gagujr (U+0A97): X=123.5,Y=593.5 (should be at cap-height 592?)

	* ghagujr (U+0A98): X=320.0,Y=591.0 (should be at cap-height 592?)

	* ngagujr (U+0A99): X=411.0,Y=591.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=320.0,Y=591.0 (should be at cap-height 592?)

	* chagujr (U+0A9B): X=607.0,Y=591.5 (should be at cap-height 592?)

	* jhagujr (U+0A9D): X=303.0,Y=0.5 (should be at baseline 0?)

	* nyagujr (U+0A9E): X=123.5,Y=593.5 (should be at cap-height 592?)

	* ttagujr (U+0A9F): X=160.5,Y=594.0 (should be at cap-height 592?)

	* tthagujr (U+0AA0): X=436.0,Y=591.0 (should be at cap-height 592?)

	* ddagujr (U+0AA1): X=411.0,Y=591.0 (should be at cap-height 592?)

	* ddhagujr (U+0AA2): X=171.5,Y=594.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=410.0,Y=590.0 (should be at cap-height 592?)

	* phagujr (U+0AAB): X=140.0,Y=-2.0 (should be at baseline 0?)

	* bhagujr (U+0AAD): X=353.5,Y=590.0 (should be at cap-height 592?)

	* yagujr (U+0AAF): X=14.0,Y=590.0 (should be at cap-height 592?)

	* ragujr (U+0AB0): X=108.0,Y=593.5 (should be at cap-height 592?)

	* llagujr (U+0AB3): X=518.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=15.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=28.0,Y=593.0 (should be at cap-height 592?)

	* ssagujr (U+0AB7): X=83.5,Y=590.5 (should be at cap-height 592?)

	* sagujr (U+0AB8): X=105.5,Y=593.5 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=550.0,Y=591.0 (should be at cap-height 592?)

	* hagujr (U+0AB9): X=533.0,Y=1.5 (should be at baseline 0?)

	* omgujr (U+0AD0): X=174.5,Y=593.5 (should be at cap-height 592?)

	* llvocalicgujr (U+0AE1): X=758.0,Y=1.0 (should be at baseline 0?)

	* llvocalicgujr (U+0AE1): X=502.0,Y=-2.0 (should be at baseline 0?)

	* lvocalicvowelsignlowgujr (U+0AE2): X=-32.0,Y=0.5 (should be at baseline 0?)

	* onegujr (U+0AE7): X=327.5,Y=593.5 (should be at cap-height 592?)

	* twogujr (U+0AE8): X=154.0,Y=593.5 (should be at cap-height 592?)

	* threegujr (U+0AE9): X=192.0,Y=593.5 (should be at cap-height 592?)

	* sixgujr (U+0AEC): X=335.0,Y=1.0 (should be at baseline 0?)

	* ninegujr (U+0AEF): X=456.5,Y=-0.5 (should be at baseline 0?)

	* uni0AF1 (U+0AF1): X=122.5,Y=593.5 (should be at cap-height 592?)

	* Germandbls (U+1E9E): X=354.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=2.0 (should be at baseline 0?)

	* euro (U+20AC): X=471.5,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSansGujaratiUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1076, but got 954 instead [code: ascent]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, malayalam, old-permic, tifinagh, math, tai-le, canadian-aboriginal, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, devanagari, sharada, tirhuta, telugu
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: devanagari, telugu, tirhuta, grantha
 * U+2010 HYPHEN: try adding one of: yi, kaithi, kayah-li, cham, lisu, sora-sompeng, kharoshthi, coptic, syloti-nagri, sundanese

Or you can add the above codepoints to one of the subsets supported by the font: `gujarati`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Gujarati UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* ⚠ **WARN** Glyph 0x00A0 is called "nbspace": Change to "uni00A0" [code: not-recommended-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- charanuktaprehalfUIgujr

	- charaprehalfUIgujr

	- daraprehalfUIgujr

	- ddaranuktaprehalfUIgujr

	- ddaraprehalfUIgujr

	- ddharanuktaprehalfUIgujr

	- ddharaprehalfUIgujr

	- llvocalicvowelsigngujr

	- lvocalicvowelsigngujr

	- ngaranuktaprehalfUIgujr

	- ngaraprehalfUIgujr

	- phanuktasquishaltgujr

	- phanuktauuvowelgujr

	- phanuktauvowelgujr

	- pharanuktassquishaltgujr

	- pharanuktauuvowelgujr

	- pharanuktauvowelgujr

	- raragujr

	- raranuktaprehalfUIgujr

	- raraprehalfUIgujr

	- raraprehalfgujr

	- rrvocalicvowelsigngujr

	- rvocalicvattugujr

	- ttaranuktaprehalfUIgujr

	- ttaraprehalfUIgujr

	- ttharanuktaprehalfUIgujr

	- ttharaprehalfUIgujr

	- uuvattugujr

	- uuvowelsigngujr.alt

	- uvattugujr

	- uvowelsigngujr.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 570 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignlowgujr (U+0AE3), lvocalicvowelsignlowgujr (U+0AE2) and rrvocalicvowelsignlowgujr (U+0AC4) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0AFC (U+0AFC): B<<-202.5,707.0>-<-172.0,716.0>-<-141.0,731.0>>/B<<-141.0,731.0>-<-156.0,726.0>-<-169.0,724.5>> = 7.386043151267186 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Navajo (Latn, 166,319 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 29 | 182 | 2117 | 110 | 1755 | 0 |
| 0% | 1% | 4% | 50% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
