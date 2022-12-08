## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[12] GolosTextVF-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 230, but got 220 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (774) and hhea ascent (980) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.tab

	- approxequal.tab

	- asciitilde.tab

	- cent.tab

	- currency.tab

	- divide.tab

	- division.tab

	- dollar.tab

	- equal.tab

	- greater.tab

	- greaterequal.tab

	- less.tab

	- lessequal.tab

	- logicalnot.tab

	- minus.tab

	- multiply.tab

	- numbersign.tab

	- plus.tab

	- plusminus.tab

	- radical.tab

	- uni0394.tab

	- uni2060

	- uni20B4.tab

	- uni20B8.tab

	- uni20BD.tab 

	- And yen.tab
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=109.5,Y=1.0 (should be at baseline 0?)

	* exclam (U+0021): X=231.0,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=109.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=231.0,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=109.5,Y=1.0 (should be at baseline 0?)

	* colon (U+003A): X=231.0,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=219.5,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=341.0,Y=1.0 (should be at baseline 0?)

	* C (U+0043): X=500.5,Y=699.0 (should be at cap-height 700?)

	* s (U+0073): X=156.5,Y=1.0 (should be at baseline 0?)

	* uni00B9 (U+00B9): X=10.0,Y=702.0 (should be at cap-height 700?)

	* onequarter (U+00BC): X=10.0,Y=702.0 (should be at cap-height 700?)

	* onehalf (U+00BD): X=10.0,Y=702.0 (should be at cap-height 700?)

	* Atilde (U+00C3): X=297.0,Y=775.0 (should be at ascender 774?)

	* Ccedilla (U+00C7): X=500.5,Y=699.0 (should be at cap-height 700?)

	* Ntilde (U+00D1): X=295.0,Y=775.0 (should be at ascender 774?)

	* Otilde (U+00D5): X=295.0,Y=775.0 (should be at ascender 774?)

	* Cacute (U+0106): X=500.5,Y=699.0 (should be at cap-height 700?)

	* Cdotaccent (U+010A): X=500.5,Y=699.0 (should be at cap-height 700?)

	* Ccaron (U+010C): X=500.5,Y=699.0 (should be at cap-height 700?)

	* lslash (U+0142): X=217.0,Y=-2.0 (should be at baseline 0?)

	* oe (U+0153): X=408.5,Y=1.5 (should be at baseline 0?)

	* sacute (U+015B): X=156.5,Y=1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=156.5,Y=1.0 (should be at baseline 0?)

	* scaron (U+0161): X=156.5,Y=1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=156.5,Y=1.0 (should be at baseline 0?)

	* uni0404 (U+0404): X=500.5,Y=699.0 (should be at cap-height 700?)

	* uni0421 (U+0421): X=500.5,Y=699.0 (should be at cap-height 700?)

	* uni042D (U+042D): X=224.5,Y=699.0 (should be at cap-height 700?)

	* uni0431 (U+0431): X=314.0,Y=702.0 (should be at cap-height 700?)

	* uni0455 (U+0455): X=156.5,Y=1.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=258.0,Y=-2.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=246.5,Y=1.5 (should be at baseline 0?)

	* uni04AA (U+04AA): X=500.5,Y=699.0 (should be at cap-height 700?)

	* uni04AA (U+04AA): X=492.0,Y=-2.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=195.5,Y=-0.5 (should be at baseline 0?)

	* uni04AB (U+04AB): X=418.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=65.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=255.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=325.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=515.0,Y=701.0 (should be at cap-height 700?)

	* ellipsis (U+2026): X=109.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=231.0,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=469.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=591.0,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=829.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=951.0,Y=1.0 (should be at baseline 0?)

	* Euro (U+20AC): X=517.5,Y=699.0 (should be at cap-height 700?) 

	* And cyrEstail.alt02 (U+F50C): X=500.5,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* dollar (U+0024) contains a short segment B<<396.0,200.0>-<396.0,212.0>-<386.0,219.5>>

	* at (U+0040) contains a short segment B<<460.0,505.5>-<481.0,499.0>-<492.5,487.5>>

	* at (U+0040) contains a short segment B<<492.5,487.5>-<504.0,476.0>-<513.0,460.0>>

	* at (U+0040) contains a short segment B<<705.5,181.0>-<712.0,165.0>-<737.0,165.0>>

	* at (U+0040) contains a short segment B<<737.0,165.0>-<752.0,165.0>-<764.0,174.5>>

	* R (U+0052) contains a short segment L<<309.0,206.0>--<304.0,206.0>>

	* a (U+0061) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* s (U+0073) contains a short segment B<<330.0,166.0>-<330.0,172.0>-<323.0,176.5>>

	* s (U+0073) contains a short segment B<<251.5,382.0>-<245.0,377.0>-<245.0,370.0>>

	* section (U+00A7) contains a short segment B<<311.0,-53.0>-<317.0,-61.0>-<330.0,-61.0>>

	* section (U+00A7) contains a short segment B<<349.0,552.5>-<343.0,561.0>-<330.0,561.0>>

	* ordfeminine (U+00AA) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* germandbls (U+00DF) contains a short segment L<<305.0,453.0>--<320.0,453.0>>

	* agrave (U+00E0) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* aacute (U+00E1) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* acircumflex (U+00E2) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* atilde (U+00E3) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* adieresis (U+00E4) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* aring (U+00E5) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* ae (U+00E6) contains a short segment L<<330.0,326.0>--<330.0,338.0>>

	* ae (U+00E6) contains a short segment B<<262.5,381.5>-<254.0,376.0>-<250.0,365.0>>

	* amacron (U+0101) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* abreve (U+0103) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* aogonek (U+0105) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* Eng (U+014A) contains a short segment B<<484.0,-215.0>-<473.0,-215.0>-<459.5,-214.5>>

	* OE (U+0152) contains a short segment L<<500.0,0.0>--<500.0,13.0>>

	* Racute (U+0154) contains a short segment L<<309.0,206.0>--<304.0,206.0>>

	* uni0156 (U+0156) contains a short segment L<<309.0,206.0>--<304.0,206.0>>

	* Rcaron (U+0158) contains a short segment L<<309.0,206.0>--<304.0,206.0>>

	* sacute (U+015B) contains a short segment B<<330.0,166.0>-<330.0,172.0>-<323.0,176.5>>

	* sacute (U+015B) contains a short segment B<<251.5,382.0>-<245.0,377.0>-<245.0,370.0>>

	* scedilla (U+015F) contains a short segment B<<330.0,166.0>-<330.0,172.0>-<323.0,176.5>>

	* scedilla (U+015F) contains a short segment B<<251.5,382.0>-<245.0,377.0>-<245.0,370.0>>

	* scaron (U+0161) contains a short segment B<<330.0,166.0>-<330.0,172.0>-<323.0,176.5>>

	* scaron (U+0161) contains a short segment B<<251.5,382.0>-<245.0,377.0>-<245.0,370.0>>

	* florin (U+0192) contains a short segment B<<0.0,-74.0>-<9.0,-76.0>-<14.5,-76.5>>

	* florin (U+0192) contains a short segment B<<14.5,-76.5>-<20.0,-77.0>-<27.0,-77.0>>

	* uni0219 (U+0219) contains a short segment B<<330.0,166.0>-<330.0,172.0>-<323.0,176.5>>

	* uni0219 (U+0219) contains a short segment B<<251.5,382.0>-<245.0,377.0>-<245.0,370.0>>

	* uni0409 (U+0409) contains a short segment B<<10.0,200.0>-<13.0,199.0>-<25.0,199.0>>

	* uni0416 (U+0416) contains a short segment L<<393.0,443.0>--<413.0,443.0>>

	* uni0416 (U+0416) contains a short segment L<<677.0,443.0>--<697.0,443.0>>

	* uni0416 (U+0416) contains a short segment L<<697.0,267.0>--<677.0,267.0>>

	* uni0416 (U+0416) contains a short segment L<<413.0,267.0>--<393.0,267.0>>

	* uni041B (U+041B) contains a short segment B<<10.0,200.0>-<13.0,199.0>-<25.0,199.0>>

	* uni0430 (U+0430) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* uni0436 (U+0436) contains a short segment L<<305.0,350.0>--<315.0,350.0>>

	* uni0436 (U+0436) contains a short segment L<<535.0,350.0>--<545.0,350.0>>

	* uni0436 (U+0436) contains a short segment L<<545.0,190.0>--<535.0,190.0>>

	* uni0436 (U+0436) contains a short segment L<<315.0,190.0>--<305.0,190.0>>

	* uni043B (U+043B) contains a short segment B<<10.0,164.0>-<13.0,163.0>-<25.0,163.0>>

	* uni0455 (U+0455) contains a short segment B<<330.0,166.0>-<330.0,172.0>-<323.0,176.5>>

	* uni0455 (U+0455) contains a short segment B<<251.5,382.0>-<245.0,377.0>-<245.0,370.0>>

	* uni0459 (U+0459) contains a short segment B<<10.0,164.0>-<13.0,163.0>-<25.0,163.0>>

	* gemiddlehookcy (U+0495) contains a short segment B<<270.5,113.0>-<260.0,109.0>-<255.0,104.0>>

	* uni0496 (U+0496) contains a short segment L<<697.0,267.0>--<677.0,267.0>>

	* uni0496 (U+0496) contains a short segment L<<413.0,267.0>--<393.0,267.0>>

	* uni0496 (U+0496) contains a short segment L<<393.0,443.0>--<413.0,443.0>>

	* uni0496 (U+0496) contains a short segment L<<677.0,443.0>--<697.0,443.0>>

	* uni0497 (U+0497) contains a short segment L<<545.0,190.0>--<535.0,190.0>>

	* uni0497 (U+0497) contains a short segment L<<315.0,190.0>--<305.0,190.0>>

	* uni0497 (U+0497) contains a short segment L<<305.0,350.0>--<315.0,350.0>>

	* uni0497 (U+0497) contains a short segment L<<535.0,350.0>--<545.0,350.0>>

	* uni049C (U+049C) contains a short segment L<<304.0,443.0>--<330.0,443.0>>

	* uni049C (U+049C) contains a short segment L<<488.0,443.0>--<506.0,443.0>>

	* uni049C (U+049C) contains a short segment L<<506.0,267.0>--<488.0,267.0>>

	* uni049C (U+049C) contains a short segment L<<330.0,267.0>--<304.0,267.0>>

	* uni04AA (U+04AA) contains a short segment B<<258.0,-2.0>-<251.0,0.0>-<246.5,1.5>>

	* uni04AA (U+04AA) contains a short segment B<<246.5,1.5>-<242.0,3.0>-<235.0,4.0>>

	* uni04AA (U+04AA) contains a short segment B<<502.0,0.0>-<496.0,-1.0>-<492.0,-2.0>>

	* uni04AA (U+04AA) contains a short segment B<<492.0,-2.0>-<488.0,-3.0>-<482.0,-5.0>>

	* uni04B9 (U+04B9) contains a short segment B<<440.0,353.0>-<448.0,355.0>-<455.0,357.0>>

	* uni04D1 (U+04D1) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* uni04D3 (U+04D3) contains a short segment L<<330.0,326.0>--<330.0,340.0>>

	* uni04D5 (U+04D5) contains a short segment L<<330.0,326.0>--<330.0,338.0>>

	* uni04D5 (U+04D5) contains a short segment B<<262.5,381.5>-<254.0,376.0>-<250.0,365.0>>

	* uni04DC (U+04DC) contains a short segment L<<393.0,443.0>--<413.0,443.0>>

	* uni04DC (U+04DC) contains a short segment L<<677.0,443.0>--<697.0,443.0>>

	* uni04DC (U+04DC) contains a short segment L<<697.0,267.0>--<677.0,267.0>>

	* uni04DC (U+04DC) contains a short segment L<<413.0,267.0>--<393.0,267.0>>

	* uni04DD (U+04DD) contains a short segment L<<305.0,350.0>--<315.0,350.0>>

	* uni04DD (U+04DD) contains a short segment L<<535.0,350.0>--<545.0,350.0>>

	* uni04DD (U+04DD) contains a short segment L<<545.0,190.0>--<535.0,190.0>>

	* uni04DD (U+04DD) contains a short segment L<<315.0,190.0>--<305.0,190.0>>

	* uni0512 (U+0512) contains a short segment B<<10.0,200.0>-<12.0,199.0>-<25.0,199.0>>

	* uni0513 (U+0513) contains a short segment B<<10.0,164.0>-<12.0,163.0>-<25.0,163.0>> 

	* And uni20B4 (U+20B4) contains a short segment B<<353.5,522.0>-<355.0,530.0>-<355.0,535.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<404.0,432.0>--<416.0,571.0>> -> L<<416.0,571.0>--<416.0,700.0>>

	* dcaron (U+010F): L<<635.0,432.0>--<647.0,571.0>> -> L<<647.0,571.0>--<647.0,700.0>>

	* lcaron (U+013E): L<<305.0,432.0>--<317.0,571.0>> -> L<<317.0,571.0>--<317.0,700.0>> 

	* And tcaron (U+0165): L<<345.0,606.0>--<357.0,745.0>> -> L<<357.0,745.0>--<357.0,874.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] GolosTextVF-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 230, but got 220 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (774) and hhea ascent (980) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Golos Text VF SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.tab

	- approxequal.tab

	- asciitilde.tab

	- cent.tab

	- currency.tab

	- divide.tab

	- division.tab

	- dollar.tab

	- equal.tab

	- greater.tab

	- greaterequal.tab

	- less.tab

	- lessequal.tab

	- logicalnot.tab

	- minus.tab

	- multiply.tab

	- numbersign.tab

	- plus.tab

	- plusminus.tab

	- radical.tab

	- uni0394.tab

	- uni2060

	- uni20B4.tab

	- uni20B8.tab

	- uni20BD.tab 

	- And yen.tab
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* Q (U+0051): X=475.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=260.0,Y=-2.0 (should be at baseline 0?)

	* t (U+0074): X=365.0,Y=-1.0 (should be at baseline 0?)

	* uni00B9 (U+00B9): X=15.0,Y=702.0 (should be at cap-height 700?)

	* onequarter (U+00BC): X=15.0,Y=702.0 (should be at cap-height 700?)

	* onehalf (U+00BD): X=15.0,Y=702.0 (should be at cap-height 700?)

	* Atilde (U+00C3): X=237.0,Y=775.0 (should be at ascender 774?)

	* Ntilde (U+00D1): X=272.0,Y=775.0 (should be at ascender 774?)

	* Otilde (U+00D5): X=272.0,Y=775.0 (should be at ascender 774?)

	* Oslash (U+00D8): X=275.5,Y=1.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=484.0,Y=699.0 (should be at cap-height 700?)

	* eth (U+00F0): X=325.0,Y=698.0 (should be at cap-height 700?)

	* gbreve (U+011F): X=260.0,Y=-2.0 (should be at baseline 0?)

	* gdotaccent (U+0121): X=260.0,Y=-2.0 (should be at baseline 0?)

	* uni0123 (U+0123): X=260.0,Y=-2.0 (should be at baseline 0?)

	* OE (U+0152): X=475.5,Y=698.0 (should be at cap-height 700?)

	* OE (U+0152): X=475.5,Y=2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=365.0,Y=-1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=365.0,Y=-1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=139.5,Y=-1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=139.5,Y=-1.0 (should be at baseline 0?)

	* uni0431 (U+0431): X=314.0,Y=701.0 (should be at cap-height 700?)

	* uni04AA (U+04AA): X=477.0,Y=1.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=214.5,Y=-1.5 (should be at baseline 0?)

	* uni04AB (U+04AB): X=386.0,Y=1.0 (should be at baseline 0?)

	* uni04AF (U+04AF): X=371.0,Y=-227.0 (should be at descender -226?)

	* uni04AF (U+04AF): X=239.0,Y=-227.0 (should be at descender -226?)

	* uni04AF (U+04AF): X=371.0,Y=2.0 (should be at baseline 0?)

	* uni04B1 (U+04B1): X=367.0,Y=-227.0 (should be at descender -226?)

	* uni04B1 (U+04B1): X=235.0,Y=-227.0 (should be at descender -226?) 

	* And uni0512 (U+0512): X=139.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* germandbls (U+00DF) contains a short segment L<<275.0,430.0>--<290.0,430.0>>

	* Eng (U+014A) contains a short segment B<<500.0,-212.0>-<489.0,-212.0>-<475.0,-211.5>>

	* Eng (U+014A) contains a short segment B<<475.0,-211.5>-<461.0,-211.0>-<450.0,-209.0>>

	* Eng (U+014A) contains a short segment B<<450.0,-97.0>-<458.0,-99.0>-<467.5,-99.5>>

	* Eng (U+014A) contains a short segment B<<467.5,-99.5>-<477.0,-100.0>-<485.0,-100.0>>

	* eng (U+014B) contains a short segment B<<320.0,-97.0>-<328.0,-99.0>-<337.5,-99.5>>

	* eng (U+014B) contains a short segment B<<337.5,-99.5>-<347.0,-100.0>-<355.0,-100.0>>

	* uni0402 (U+0402) contains a short segment B<<490.0,123.0>-<498.0,121.0>-<510.0,120.5>>

	* uni0402 (U+0402) contains a short segment B<<510.0,120.5>-<522.0,120.0>-<530.0,120.0>>

	* uni0409 (U+0409) contains a short segment B<<65.0,-12.0>-<57.0,-12.0>-<45.0,-11.5>>

	* uni0409 (U+0409) contains a short segment B<<45.0,-11.5>-<33.0,-11.0>-<25.0,-9.0>>

	* uni0409 (U+0409) contains a short segment B<<25.0,125.0>-<28.0,124.0>-<40.0,124.0>>

	* uni041B (U+041B) contains a short segment B<<65.0,-12.0>-<57.0,-12.0>-<45.0,-11.5>>

	* uni041B (U+041B) contains a short segment B<<45.0,-11.5>-<33.0,-11.0>-<25.0,-9.0>>

	* uni041B (U+041B) contains a short segment B<<25.0,125.0>-<28.0,124.0>-<40.0,124.0>>

	* uni043B (U+043B) contains a short segment B<<25.0,110.0>-<28.0,109.0>-<40.0,109.0>>

	* uni0452 (U+0452) contains a short segment B<<360.0,-97.0>-<368.0,-99.0>-<377.5,-99.5>>

	* uni0452 (U+0452) contains a short segment B<<377.5,-99.5>-<387.0,-100.0>-<395.0,-100.0>>

	* uni0459 (U+0459) contains a short segment B<<25.0,110.0>-<28.0,109.0>-<40.0,109.0>>

	* gemiddlehookcy (U+0495) contains a short segment B<<290.0,-97.0>-<298.0,-99.0>-<307.5,-99.5>>

	* gemiddlehookcy (U+0495) contains a short segment B<<307.5,-99.5>-<317.0,-100.0>-<325.0,-100.0>>

	* uni049C (U+049C) contains a short segment L<<397.0,414.0>--<419.0,414.0>>

	* uni049C (U+049C) contains a short segment L<<419.0,303.0>--<397.0,303.0>>

	* uni049D (U+049D) contains a short segment L<<347.0,322.0>--<367.0,322.0>>

	* uni04AA (U+04AA) contains a short segment B<<477.0,1.0>-<467.0,-1.0>-<456.5,-3.0>>

	* uni04C4 (U+04C4) contains a short segment B<<292.0,-94.0>-<301.0,-96.0>-<309.5,-96.5>>

	* uni04C4 (U+04C4) contains a short segment B<<309.5,-96.5>-<318.0,-97.0>-<326.0,-97.0>>

	* uni04C8 (U+04C8) contains a short segment B<<329.0,-94.0>-<337.0,-96.0>-<346.0,-96.5>>

	* uni04C8 (U+04C8) contains a short segment B<<346.0,-96.5>-<355.0,-97.0>-<363.0,-97.0>>

	* uni0512 (U+0512) contains a short segment B<<65.0,-12.0>-<57.0,-12.0>-<45.0,-11.5>>

	* uni0512 (U+0512) contains a short segment B<<45.0,-11.5>-<33.0,-11.0>-<25.0,-9.0>>

	* uni0512 (U+0512) contains a short segment B<<25.0,127.0>-<27.0,126.0>-<40.0,126.0>>

	* uni0513 (U+0513) contains a short segment B<<311.0,-94.0>-<319.0,-96.0>-<328.0,-96.5>>

	* uni0513 (U+0513) contains a short segment B<<328.0,-96.5>-<337.0,-97.0>-<345.0,-97.0>> 

	* And uni0513 (U+0513) contains a short segment B<<22.0,110.0>-<24.0,109.0>-<37.0,109.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<447.0,486.0>--<458.0,613.0>> -> L<<458.0,613.0>--<458.0,700.0>>

	* dcaron (U+010F): L<<626.0,486.0>--<637.0,613.0>> -> L<<637.0,613.0>--<637.0,700.0>>

	* lcaron (U+013E): L<<268.0,486.0>--<279.0,613.0>> -> L<<279.0,613.0>--<279.0,700.0>> 

	* And tcaron (U+0165): L<<285.0,595.0>--<296.0,722.0>> -> L<<296.0,722.0>--<296.0,809.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[13] GolosTextVF-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 230, but got 220 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (774) and hhea ascent (980) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Golos Text VF ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.tab

	- approxequal.tab

	- asciitilde.tab

	- cent.tab

	- currency.tab

	- divide.tab

	- division.tab

	- dollar.tab

	- equal.tab

	- greater.tab

	- greaterequal.tab

	- less.tab

	- lessequal.tab

	- logicalnot.tab

	- minus.tab

	- multiply.tab

	- numbersign.tab

	- plus.tab

	- plusminus.tab

	- radical.tab

	- uni0394.tab

	- uni2060

	- uni20B4.tab

	- uni20B8.tab

	- uni20BD.tab 

	- And yen.tab
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=699.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=385.0,Y=2.0 (should be at baseline 0?)

	* uni00B9 (U+00B9): X=10.0,Y=702.0 (should be at cap-height 700?)

	* onequarter (U+00BC): X=10.0,Y=702.0 (should be at cap-height 700?)

	* onehalf (U+00BD): X=10.0,Y=702.0 (should be at cap-height 700?)

	* Oslash (U+00D8): X=279.0,Y=-2.0 (should be at baseline 0?)

	* Oslash (U+00D8): X=487.0,Y=701.5 (should be at cap-height 700?)

	* atilde (U+00E3): X=390.5,Y=701.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=396.5,Y=701.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=395.5,Y=701.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=385.0,Y=2.0 (should be at baseline 0?)

	* uni021B (U+021B): X=385.0,Y=2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=302.5,Y=701.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=302.5,Y=701.0 (should be at cap-height 700?)

	* uni0431 (U+0431): X=317.0,Y=702.0 (should be at cap-height 700?)

	* uni043B (U+043B): X=148.5,Y=-2.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=148.5,Y=-2.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=256.5,Y=-0.5 (should be at baseline 0?)

	* uni04AB (U+04AB): X=203.5,Y=-1.5 (should be at baseline 0?)

	* uni04AB (U+04AB): X=409.0,Y=1.0 (should be at baseline 0?)

	* uni0513 (U+0513): X=148.5,Y=-2.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=73.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=243.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=318.0,Y=701.0 (should be at cap-height 700?) 

	* And quotedblright (U+201D): X=488.0,Y=701.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* at (U+0040) contains a short segment B<<733.0,147.0>-<753.0,147.0>-<768.0,158.5>>

	* uni03BC (U+00B5) contains a short segment B<<249.0,-12.0>-<239.0,-12.0>-<230.0,-10.0>>

	* germandbls (U+00DF) contains a short segment L<<290.0,446.0>--<305.0,446.0>>

	* ae (U+00E6) contains a short segment L<<356.0,322.0>--<356.0,339.0>>

	* lslash (U+0142) contains a short segment B<<360.5,146.5>-<366.0,147.0>-<373.0,148.0>>

	* Eng (U+014A) contains a short segment B<<492.0,-214.0>-<481.0,-214.0>-<467.5,-213.5>>

	* Eng (U+014A) contains a short segment B<<467.5,-213.5>-<454.0,-213.0>-<443.0,-211.0>>

	* Eng (U+014A) contains a short segment B<<443.0,-58.0>-<452.0,-60.0>-<459.0,-60.5>>

	* Eng (U+014A) contains a short segment B<<459.0,-60.5>-<466.0,-61.0>-<472.0,-61.0>>

	* eng (U+014B) contains a short segment B<<305.0,-58.0>-<313.0,-60.0>-<321.5,-60.5>>

	* eng (U+014B) contains a short segment B<<321.5,-60.5>-<330.0,-61.0>-<337.0,-61.0>>

	* OE (U+0152) contains a short segment L<<523.0,0.0>--<523.0,25.0>>

	* uni0402 (U+0402) contains a short segment B<<495.0,164.0>-<502.0,162.0>-<511.0,161.5>>

	* uni0402 (U+0402) contains a short segment B<<511.0,161.5>-<520.0,161.0>-<528.0,161.0>>

	* uni0409 (U+0409) contains a short segment B<<42.5,-13.5>-<26.0,-13.0>-<18.0,-11.0>>

	* uni0409 (U+0409) contains a short segment B<<18.0,174.0>-<21.0,173.0>-<33.0,173.0>>

	* uni0416 (U+0416) contains a short segment L<<387.0,433.0>--<417.0,433.0>>

	* uni0416 (U+0416) contains a short segment L<<639.0,433.0>--<669.0,433.0>>

	* uni0416 (U+0416) contains a short segment L<<669.0,282.0>--<639.0,282.0>>

	* uni0416 (U+0416) contains a short segment L<<417.0,282.0>--<387.0,282.0>>

	* uni041B (U+041B) contains a short segment B<<18.0,174.0>-<21.0,173.0>-<33.0,173.0>>

	* uni0436 (U+0436) contains a short segment L<<304.0,339.0>--<324.0,339.0>>

	* uni0436 (U+0436) contains a short segment L<<511.0,339.0>--<531.0,339.0>>

	* uni0436 (U+0436) contains a short segment L<<531.0,202.0>--<511.0,202.0>>

	* uni0436 (U+0436) contains a short segment L<<324.0,202.0>--<304.0,202.0>>

	* uni043B (U+043B) contains a short segment B<<15.0,144.0>-<18.0,143.0>-<30.0,143.0>>

	* uni0452 (U+0452) contains a short segment B<<353.0,-58.0>-<360.0,-60.0>-<368.5,-60.5>>

	* uni0452 (U+0452) contains a short segment B<<368.5,-60.5>-<377.0,-61.0>-<385.0,-61.0>>

	* uni0459 (U+0459) contains a short segment B<<15.0,144.0>-<18.0,143.0>-<30.0,143.0>>

	* gemiddlehookcy (U+0495) contains a short segment B<<280.0,-58.0>-<288.0,-60.0>-<296.5,-60.5>>

	* gemiddlehookcy (U+0495) contains a short segment B<<296.5,-60.5>-<305.0,-61.0>-<312.0,-61.0>>

	* uni0496 (U+0496) contains a short segment L<<669.0,282.0>--<639.0,282.0>>

	* uni0496 (U+0496) contains a short segment L<<417.0,282.0>--<387.0,282.0>>

	* uni0496 (U+0496) contains a short segment L<<387.0,433.0>--<417.0,433.0>>

	* uni0496 (U+0496) contains a short segment L<<639.0,433.0>--<669.0,433.0>>

	* uni0497 (U+0497) contains a short segment L<<531.0,202.0>--<511.0,202.0>>

	* uni0497 (U+0497) contains a short segment L<<324.0,202.0>--<304.0,202.0>>

	* uni0497 (U+0497) contains a short segment L<<304.0,339.0>--<324.0,339.0>>

	* uni0497 (U+0497) contains a short segment L<<511.0,339.0>--<531.0,339.0>>

	* uni049C (U+049C) contains a short segment L<<459.0,433.0>--<480.0,433.0>>

	* uni049C (U+049C) contains a short segment L<<480.0,282.0>--<459.0,282.0>>

	* uni04AA (U+04AA) contains a short segment B<<276.0,-4.0>-<266.0,-3.0>-<256.5,-0.5>>

	* uni04AA (U+04AA) contains a short segment B<<256.5,-0.5>-<247.0,2.0>-<237.0,5.0>>

	* uni04AA (U+04AA) contains a short segment B<<495.0,0.0>-<487.0,-2.0>-<480.5,-3.0>>

	* uni04AA (U+04AA) contains a short segment B<<480.5,-3.0>-<474.0,-4.0>-<466.0,-6.0>>

	* uni04C4 (U+04C4) contains a short segment B<<300.0,-58.0>-<308.0,-60.0>-<316.5,-60.5>>

	* uni04C4 (U+04C4) contains a short segment B<<316.5,-60.5>-<325.0,-61.0>-<332.0,-61.0>>

	* uni04C8 (U+04C8) contains a short segment B<<310.0,-58.0>-<318.0,-60.0>-<326.5,-60.5>>

	* uni04C8 (U+04C8) contains a short segment B<<326.5,-60.5>-<335.0,-61.0>-<342.0,-61.0>>

	* uni04D5 (U+04D5) contains a short segment L<<356.0,322.0>--<356.0,339.0>>

	* uni04DC (U+04DC) contains a short segment L<<387.0,433.0>--<417.0,433.0>>

	* uni04DC (U+04DC) contains a short segment L<<639.0,433.0>--<669.0,433.0>>

	* uni04DC (U+04DC) contains a short segment L<<669.0,282.0>--<639.0,282.0>>

	* uni04DC (U+04DC) contains a short segment L<<417.0,282.0>--<387.0,282.0>>

	* uni04DD (U+04DD) contains a short segment L<<304.0,339.0>--<324.0,339.0>>

	* uni04DD (U+04DD) contains a short segment L<<511.0,339.0>--<531.0,339.0>>

	* uni04DD (U+04DD) contains a short segment L<<531.0,202.0>--<511.0,202.0>>

	* uni04DD (U+04DD) contains a short segment L<<324.0,202.0>--<304.0,202.0>>

	* uni0512 (U+0512) contains a short segment B<<42.5,-13.5>-<25.0,-13.0>-<18.0,-11.0>>

	* uni0512 (U+0512) contains a short segment B<<18.0,174.0>-<20.0,173.0>-<33.0,173.0>>

	* uni0513 (U+0513) contains a short segment B<<293.0,-58.0>-<300.0,-60.0>-<308.5,-60.5>>

	* uni0513 (U+0513) contains a short segment B<<308.5,-60.5>-<317.0,-61.0>-<325.0,-61.0>> 

	* And uni0513 (U+0513) contains a short segment B<<15.0,144.0>-<17.0,143.0>-<30.0,143.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<425.0,452.0>--<437.0,587.0>> -> L<<437.0,587.0>--<437.0,700.0>>

	* dcaron (U+010F): L<<639.0,452.0>--<651.0,587.0>> -> L<<651.0,587.0>--<651.0,700.0>>

	* lcaron (U+013E): L<<296.0,452.0>--<308.0,587.0>> -> L<<308.0,587.0>--<308.0,700.0>> 

	* And tcaron (U+0165): L<<320.0,605.0>--<332.0,740.0>> -> L<<332.0,740.0>--<332.0,853.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[12] GolosTextVF-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 230, but got 220 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (774) and hhea ascent (980) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.tab

	- approxequal.tab

	- asciitilde.tab

	- cent.tab

	- currency.tab

	- divide.tab

	- division.tab

	- dollar.tab

	- equal.tab

	- greater.tab

	- greaterequal.tab

	- less.tab

	- lessequal.tab

	- logicalnot.tab

	- minus.tab

	- multiply.tab

	- numbersign.tab

	- plus.tab

	- plusminus.tab

	- radical.tab

	- uni0394.tab

	- uni2060

	- uni20B4.tab

	- uni20B8.tab

	- uni20BD.tab 

	- And yen.tab
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* germandbls (U+00DF) contains a short segment L<<275.0,422.0>--<290.0,422.0>>

	* Eng (U+014A) contains a short segment B<<500.0,-211.0>-<489.0,-211.0>-<475.0,-210.5>>

	* Eng (U+014A) contains a short segment B<<475.0,-210.5>-<461.0,-210.0>-<450.0,-208.0>>

	* Eng (U+014A) contains a short segment B<<450.0,-112.0>-<458.0,-114.0>-<467.5,-114.5>>

	* Eng (U+014A) contains a short segment B<<467.5,-114.5>-<477.0,-115.0>-<485.0,-115.0>>

	* eng (U+014B) contains a short segment B<<320.0,-112.0>-<328.0,-114.0>-<337.5,-114.5>>

	* eng (U+014B) contains a short segment B<<337.5,-114.5>-<347.0,-115.0>-<355.0,-115.0>>

	* florin (U+0192) contains a short segment L<<100.0,530.0>--<100.0,545.0>>

	* uni0402 (U+0402) contains a short segment B<<540.0,-5.0>-<532.0,-5.0>-<515.0,-4.5>>

	* uni0402 (U+0402) contains a short segment B<<490.0,104.0>-<498.0,102.0>-<510.0,101.5>>

	* uni0402 (U+0402) contains a short segment B<<510.0,101.5>-<522.0,101.0>-<530.0,101.0>>

	* uni0409 (U+0409) contains a short segment B<<60.0,-11.0>-<52.0,-11.0>-<42.5,-10.5>>

	* uni0409 (U+0409) contains a short segment B<<42.5,-10.5>-<33.0,-10.0>-<25.0,-8.0>>

	* uni0409 (U+0409) contains a short segment B<<25.0,106.0>-<28.0,105.0>-<40.0,105.0>>

	* uni041B (U+041B) contains a short segment B<<60.0,-11.0>-<52.0,-11.0>-<42.5,-10.5>>

	* uni041B (U+041B) contains a short segment B<<42.5,-10.5>-<33.0,-10.0>-<25.0,-8.0>>

	* uni041B (U+041B) contains a short segment B<<25.0,106.0>-<28.0,105.0>-<40.0,105.0>>

	* uni043B (U+043B) contains a short segment B<<25.0,96.0>-<28.0,95.0>-<40.0,95.0>>

	* uni0452 (U+0452) contains a short segment B<<350.0,-112.0>-<358.0,-114.0>-<367.5,-114.5>>

	* uni0452 (U+0452) contains a short segment B<<367.5,-114.5>-<377.0,-115.0>-<385.0,-115.0>>

	* uni0459 (U+0459) contains a short segment B<<60.0,-11.0>-<52.0,-11.0>-<42.5,-10.5>>

	* uni0459 (U+0459) contains a short segment B<<42.5,-10.5>-<33.0,-10.0>-<25.0,-8.0>>

	* uni0459 (U+0459) contains a short segment B<<25.0,96.0>-<28.0,95.0>-<40.0,95.0>>

	* gemiddlehookcy (U+0495) contains a short segment B<<289.0,-112.0>-<297.0,-114.0>-<306.5,-114.5>>

	* gemiddlehookcy (U+0495) contains a short segment B<<306.5,-114.5>-<316.0,-115.0>-<324.0,-115.0>>

	* uni049C (U+049C) contains a short segment L<<365.0,404.0>--<385.0,404.0>>

	* uni049C (U+049C) contains a short segment L<<385.0,308.0>--<365.0,308.0>>

	* uni049D (U+049D) contains a short segment L<<313.0,315.0>--<328.0,315.0>>

	* uni049D (U+049D) contains a short segment L<<328.0,225.0>--<313.0,225.0>>

	* uni04C7 (U+04C7) contains a short segment L<<448.0,-109.0>--<465.0,-109.0>>

	* uni04C8 (U+04C8) contains a short segment B<<338.0,-106.0>-<347.0,-108.0>-<355.0,-109.0>>

	* uni04C8 (U+04C8) contains a short segment B<<355.0,-109.0>-<363.0,-110.0>-<370.0,-110.0>>

	* uni0512 (U+0512) contains a short segment L<<408.0,-109.0>--<425.0,-109.0>>

	* uni0512 (U+0512) contains a short segment B<<60.0,-11.0>-<52.0,-11.0>-<42.5,-10.5>>

	* uni0512 (U+0512) contains a short segment B<<42.5,-10.5>-<33.0,-10.0>-<25.0,-8.0>>

	* uni0512 (U+0512) contains a short segment B<<25.0,106.0>-<27.0,105.0>-<40.0,105.0>>

	* uni0513 (U+0513) contains a short segment B<<316.0,-106.0>-<325.0,-108.0>-<333.0,-109.0>>

	* uni0513 (U+0513) contains a short segment B<<333.0,-109.0>-<341.0,-110.0>-<348.0,-110.0>>

	* uni0513 (U+0513) contains a short segment B<<58.0,-11.0>-<50.0,-11.0>-<40.5,-10.5>>

	* uni0513 (U+0513) contains a short segment B<<40.5,-10.5>-<31.0,-10.0>-<23.0,-8.0>> 

	* And uni0513 (U+0513) contains a short segment B<<23.0,95.0>-<25.0,94.0>-<38.0,94.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<449.0,492.0>--<460.0,615.0>> -> L<<460.0,615.0>--<460.0,700.0>>

	* dcaron (U+010F): L<<630.0,492.0>--<641.0,615.0>> -> L<<641.0,615.0>--<641.0,700.0>>

	* lcaron (U+013E): L<<270.0,492.0>--<281.0,615.0>> -> L<<281.0,615.0>--<281.0,700.0>> 

	* And tcaron (U+0165): L<<271.0,595.0>--<282.0,718.0>> -> L<<282.0,718.0>--<282.0,803.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Aogonek (U+0104): L<<604.0,0.0>--<665.0,0.0>>/B<<665.0,0.0>-<657.0,-2.0>-<641.5,-17.0>> = 14.036243467926484

	* Eogonek (U+0118): L<<499.0,0.0>--<560.0,0.0>>/B<<560.0,0.0>-<552.0,-2.0>-<536.5,-17.0>> = 14.036243467926484

	* Iogonek (U+012E): L<<159.0,0.0>--<220.0,0.0>>/B<<220.0,0.0>-<212.0,-2.0>-<196.5,-17.0>> = 14.036243467926484

	* Uogonek (U+0172): L<<400.0,0.0>--<461.0,0.0>>/B<<461.0,0.0>-<453.0,-2.0>-<437.5,-17.0>> = 14.036243467926484

	* aogonek (U+0105): L<<450.0,0.0>--<511.0,0.0>>/B<<511.0,0.0>-<503.0,-2.0>-<487.5,-17.0>> = 14.036243467926484

	* eogonek (U+0119): L<<325.0,0.0>--<386.0,0.0>>/B<<386.0,0.0>-<378.0,-2.0>-<362.5,-17.0>> = 14.036243467926484

	* iogonek (U+012F): L<<129.0,0.0>--<190.0,0.0>>/B<<190.0,0.0>-<182.0,-2.0>-<166.5,-17.0>> = 14.036243467926484

	* ogonek (U+02DB): L<<129.0,0.0>--<190.0,0.0>>/B<<190.0,0.0>-<182.0,-2.0>-<166.5,-17.0>> = 14.036243467926484

	* uni0328 (U+0328): L<<129.0,0.0>--<190.0,0.0>>/B<<190.0,0.0>-<182.0,-2.0>-<166.5,-17.0>> = 14.036243467926484 

	* And uogonek (U+0173): L<<464.0,0.0>--<525.0,0.0>>/B<<525.0,0.0>-<517.0,-2.0>-<501.5,-17.0>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] GolosTextVF-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 230, but got 220 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (774) and hhea ascent (980) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.tab

	- approxequal.tab

	- asciitilde.tab

	- cent.tab

	- currency.tab

	- divide.tab

	- division.tab

	- dollar.tab

	- equal.tab

	- greater.tab

	- greaterequal.tab

	- less.tab

	- lessequal.tab

	- logicalnot.tab

	- minus.tab

	- multiply.tab

	- numbersign.tab

	- plus.tab

	- plusminus.tab

	- radical.tab

	- uni0394.tab

	- uni2060

	- uni20B4.tab

	- uni20B8.tab

	- uni20BD.tab 

	- And yen.tab
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: greaterequal	Contours detected: 1	Expected: 2

	- Glyph name: lessequal	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* at (U+0040): X=102.5,Y=1.0 (should be at baseline 0?)

	* r (U+0072): X=265.0,Y=529.5 (should be at x-height 530?)

	* t (U+0074): X=370.0,Y=-1.0 (should be at baseline 0?)

	* y (U+0079): X=234.0,Y=1.0 (should be at baseline 0?)

	* copyright (U+00A9): X=274.0,Y=0.5 (should be at baseline 0?)

	* copyright (U+00A9): X=274.0,Y=699.5 (should be at cap-height 700?)

	* copyright (U+00A9): X=575.5,Y=699.5 (should be at cap-height 700?)

	* copyright (U+00A9): X=575.5,Y=0.5 (should be at baseline 0?)

	* uni00B9 (U+00B9): X=10.0,Y=702.0 (should be at cap-height 700?)

	* onequarter (U+00BC): X=10.0,Y=702.0 (should be at cap-height 700?)

	* onehalf (U+00BD): X=10.0,Y=702.0 (should be at cap-height 700?)

	* Atilde (U+00C3): X=325.0,Y=773.5 (should be at ascender 774?)

	* Ntilde (U+00D1): X=350.0,Y=773.5 (should be at ascender 774?)

	* Otilde (U+00D5): X=355.0,Y=773.5 (should be at ascender 774?)

	* Oslash (U+00D8): X=279.5,Y=-0.5 (should be at baseline 0?)

	* Oslash (U+00D8): X=490.5,Y=700.5 (should be at cap-height 700?)

	* atilde (U+00E3): X=327.5,Y=701.0 (should be at cap-height 700?)

	* eth (U+00F0): X=335.0,Y=702.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=330.5,Y=701.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=327.5,Y=701.0 (should be at cap-height 700?)

	* yacute (U+00FD): X=234.0,Y=1.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=234.0,Y=1.0 (should be at baseline 0?)

	* OE (U+0152): X=463.5,Y=701.0 (should be at cap-height 700?)

	* OE (U+0152): X=463.5,Y=-1.0 (should be at baseline 0?)

	* tcaron (U+0165): X=370.0,Y=-1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=234.0,Y=1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=370.0,Y=-1.0 (should be at baseline 0?)

	* tilde (U+02DC): X=227.5,Y=701.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=227.5,Y=701.0 (should be at cap-height 700?)

	* uni0431 (U+0431): X=319.0,Y=702.0 (should be at cap-height 700?)

	* uni043B (U+043B): X=144.5,Y=0.5 (should be at baseline 0?)

	* uni0443 (U+0443): X=234.0,Y=1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=144.5,Y=0.5 (should be at baseline 0?)

	* uni045E (U+045E): X=234.0,Y=1.0 (should be at baseline 0?)

	* Gemiddlehookcy (U+0494): X=385.0,Y=-227.0 (should be at descender -226?)

	* Gemiddlehookcy (U+0494): X=321.0,Y=-227.0 (should be at descender -226?)

	* uni04AA (U+04AA): X=266.0,Y=-1.5 (should be at baseline 0?)

	* uni04AB (U+04AB): X=399.0,Y=1.0 (should be at baseline 0?)

	* uni04C3 (U+04C3): X=415.0,Y=-227.0 (should be at descender -226?)

	* uni04C3 (U+04C3): X=351.0,Y=-227.0 (should be at descender -226?)

	* uni04C7 (U+04C7): X=455.0,Y=-227.0 (should be at descender -226?)

	* uni04C7 (U+04C7): X=391.0,Y=-227.0 (should be at descender -226?)

	* uni04EF (U+04EF): X=234.0,Y=1.0 (should be at baseline 0?)

	* uni04F1 (U+04F1): X=234.0,Y=1.0 (should be at baseline 0?)

	* uni04F3 (U+04F3): X=234.0,Y=1.0 (should be at baseline 0?)

	* uni0512 (U+0512): X=361.0,Y=-227.0 (should be at descender -226?)

	* uni0512 (U+0512): X=425.0,Y=-227.0 (should be at descender -226?)

	* uni0513 (U+0513): X=144.5,Y=0.5 (should be at baseline 0?) 

	* And ygrave (U+1EF3): X=234.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* germandbls (U+00DF) contains a short segment L<<275.0,438.0>--<290.0,438.0>>

	* ae (U+00E6) contains a short segment L<<381.0,318.0>--<381.0,340.0>>

	* Eng (U+014A) contains a short segment B<<500.0,-213.0>-<489.0,-213.0>-<475.0,-212.5>>

	* Eng (U+014A) contains a short segment B<<475.0,-212.5>-<461.0,-212.0>-<450.0,-210.0>>

	* Eng (U+014A) contains a short segment B<<450.0,-82.0>-<461.0,-84.0>-<468.5,-84.5>>

	* Eng (U+014A) contains a short segment B<<468.5,-84.5>-<476.0,-85.0>-<480.0,-85.0>>

	* eng (U+014B) contains a short segment B<<320.0,-82.0>-<328.0,-84.0>-<337.5,-84.5>>

	* eng (U+014B) contains a short segment B<<337.5,-84.5>-<347.0,-85.0>-<355.0,-85.0>>

	* uni0402 (U+0402) contains a short segment B<<490.0,147.0>-<498.0,145.0>-<510.0,144.5>>

	* uni0402 (U+0402) contains a short segment B<<510.0,144.5>-<522.0,144.0>-<530.0,144.0>>

	* uni0409 (U+0409) contains a short segment B<<70.0,-13.0>-<62.0,-13.0>-<47.5,-12.5>>

	* uni0409 (U+0409) contains a short segment B<<47.5,-12.5>-<33.0,-12.0>-<25.0,-10.0>>

	* uni0409 (U+0409) contains a short segment B<<25.0,148.0>-<28.0,147.0>-<40.0,147.0>>

	* uni040E (U+040E) contains a short segment B<<170.0,140.0>-<178.0,139.0>-<186.0,138.0>>

	* uni041B (U+041B) contains a short segment B<<25.0,148.0>-<28.0,147.0>-<40.0,147.0>>

	* uni0423 (U+0423) contains a short segment B<<170.0,140.0>-<178.0,139.0>-<186.0,138.0>>

	* uni043B (U+043B) contains a short segment B<<20.0,124.0>-<23.0,123.0>-<35.0,123.0>>

	* uni0452 (U+0452) contains a short segment B<<360.0,-82.0>-<368.0,-84.0>-<377.5,-84.5>>

	* uni0452 (U+0452) contains a short segment B<<377.5,-84.5>-<387.0,-85.0>-<395.0,-85.0>>

	* uni0459 (U+0459) contains a short segment B<<20.0,124.0>-<23.0,123.0>-<35.0,123.0>>

	* gemiddlehookcy (U+0495) contains a short segment B<<290.0,-82.0>-<298.0,-84.0>-<307.5,-84.5>>

	* gemiddlehookcy (U+0495) contains a short segment B<<307.5,-84.5>-<317.0,-85.0>-<325.0,-85.0>>

	* uni049C (U+049C) contains a short segment L<<429.0,423.0>--<454.0,423.0>>

	* uni049C (U+049C) contains a short segment L<<454.0,297.0>--<429.0,297.0>>

	* uni04AA (U+04AA) contains a short segment B<<487.0,0.0>-<478.0,-2.0>-<469.0,-3.5>>

	* uni04AA (U+04AA) contains a short segment B<<469.0,-3.5>-<460.0,-5.0>-<450.0,-7.0>>

	* uni04C4 (U+04C4) contains a short segment B<<290.0,-82.0>-<298.0,-84.0>-<307.5,-84.5>>

	* uni04C4 (U+04C4) contains a short segment B<<307.5,-84.5>-<317.0,-85.0>-<325.0,-85.0>>

	* uni04C8 (U+04C8) contains a short segment B<<320.0,-82.0>-<328.0,-84.0>-<337.5,-84.5>>

	* uni04C8 (U+04C8) contains a short segment B<<337.5,-84.5>-<347.0,-85.0>-<355.0,-85.0>>

	* uni04D5 (U+04D5) contains a short segment L<<381.0,318.0>--<381.0,340.0>>

	* uni04EE (U+04EE) contains a short segment B<<170.0,140.0>-<178.0,139.0>-<186.0,138.0>>

	* uni04F0 (U+04F0) contains a short segment B<<170.0,140.0>-<178.0,139.0>-<186.0,138.0>>

	* uni04F2 (U+04F2) contains a short segment B<<170.0,140.0>-<178.0,139.0>-<186.0,138.0>>

	* uni0512 (U+0512) contains a short segment B<<70.0,-13.0>-<62.0,-13.0>-<47.5,-12.5>>

	* uni0512 (U+0512) contains a short segment B<<47.5,-12.5>-<33.0,-12.0>-<25.0,-10.0>>

	* uni0512 (U+0512) contains a short segment B<<25.0,148.0>-<27.0,147.0>-<40.0,147.0>>

	* uni0513 (U+0513) contains a short segment B<<305.0,-82.0>-<313.0,-84.0>-<322.5,-84.5>>

	* uni0513 (U+0513) contains a short segment B<<322.5,-84.5>-<332.0,-85.0>-<340.0,-85.0>> 

	* And uni0513 (U+0513) contains a short segment B<<20.0,124.0>-<22.0,123.0>-<35.0,123.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<446.0,472.0>--<457.0,603.0>> -> L<<457.0,603.0>--<457.0,700.0>>

	* dcaron (U+010F): L<<642.0,472.0>--<653.0,603.0>> -> L<<653.0,603.0>--<653.0,700.0>>

	* lcaron (U+013E): L<<286.0,472.0>--<297.0,603.0>> -> L<<297.0,603.0>--<297.0,700.0>> 

	* And tcaron (U+0165): L<<295.0,603.0>--<306.0,734.0>> -> L<<306.0,734.0>--<306.0,831.0>> [code: found-colinear-vectors]
</div></details><br></div></details><details><summary><b>[11] GolosTextVF-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 230, but got 220 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (774) and hhea ascent (980) must be equal. [code: ascender]
</div></details><details><summary>⚠ <b>WARN:</b> Description strings in the name table must not exceed 200 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/description_max_length">com.google.fonts/check/name/description_max_length</a>)</summary><div>


* ⚠ **WARN** A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.tab

	- approxequal.tab

	- asciitilde.tab

	- cent.tab

	- currency.tab

	- divide.tab

	- division.tab

	- dollar.tab

	- equal.tab

	- greater.tab

	- greaterequal.tab

	- less.tab

	- lessequal.tab

	- logicalnot.tab

	- minus.tab

	- multiply.tab

	- numbersign.tab

	- plus.tab

	- plusminus.tab

	- radical.tab

	- uni0394.tab

	- uni2060

	- uni20B4.tab

	- uni20B8.tab

	- uni20BD.tab 

	- And yen.tab
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Gbreve	Contours detected: 1	Expected: 2

	- Glyph name: Ubreve	Contours detected: 1	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: gbreve	Contours detected: 2	Expected: 3 or 4

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* f (U+0066) contains a short segment L<<110.0,530.0>--<110.0,540.0>>

	* germandbls (U+00DF) contains a short segment L<<275.0,415.0>--<290.0,415.0>>

	* Eng (U+014A) contains a short segment B<<500.0,-211.0>-<489.0,-211.0>-<475.0,-210.5>>

	* Eng (U+014A) contains a short segment B<<475.0,-210.5>-<461.0,-210.0>-<450.0,-208.0>>

	* Eng (U+014A) contains a short segment B<<450.0,-128.0>-<458.0,-130.0>-<467.5,-130.5>>

	* Eng (U+014A) contains a short segment B<<467.5,-130.5>-<477.0,-131.0>-<485.0,-131.0>>

	* eng (U+014B) contains a short segment B<<330.0,-127.0>-<338.0,-129.0>-<347.5,-129.5>>

	* eng (U+014B) contains a short segment B<<347.5,-129.5>-<357.0,-130.0>-<365.0,-130.0>>

	* florin (U+0192) contains a short segment L<<110.0,530.0>--<110.0,540.0>>

	* uni0402 (U+0402) contains a short segment B<<540.0,-5.0>-<532.0,-5.0>-<515.0,-4.5>>

	* uni0402 (U+0402) contains a short segment B<<515.0,-4.5>-<498.0,-4.0>-<490.0,-2.0>>

	* uni0402 (U+0402) contains a short segment B<<490.0,82.0>-<498.0,80.0>-<510.0,79.5>>

	* uni0402 (U+0402) contains a short segment B<<510.0,79.5>-<522.0,79.0>-<530.0,79.0>>

	* uni0409 (U+0409) contains a short segment B<<25.0,85.0>-<28.0,84.0>-<40.0,84.0>>

	* uni041B (U+041B) contains a short segment B<<25.0,85.0>-<28.0,84.0>-<40.0,84.0>>

	* uni043B (U+043B) contains a short segment B<<25.0,81.0>-<28.0,80.0>-<40.0,80.0>>

	* uni0452 (U+0452) contains a short segment B<<350.0,-127.0>-<358.0,-129.0>-<367.5,-129.5>>

	* uni0452 (U+0452) contains a short segment B<<367.5,-129.5>-<377.0,-130.0>-<385.0,-130.0>>

	* uni0459 (U+0459) contains a short segment B<<25.0,81.0>-<28.0,80.0>-<40.0,80.0>>

	* Gemiddlehookcy (U+0494) contains a short segment L<<337.0,-123.0>--<360.0,-123.0>>

	* gemiddlehookcy (U+0495) contains a short segment B<<289.0,-127.0>-<297.0,-129.0>-<306.5,-129.5>>

	* gemiddlehookcy (U+0495) contains a short segment B<<306.5,-129.5>-<316.0,-130.0>-<324.0,-130.0>>

	* uni049C (U+049C) contains a short segment L<<333.0,395.0>--<350.0,395.0>>

	* uni049C (U+049C) contains a short segment L<<350.0,314.0>--<333.0,314.0>>

	* uni049D (U+049D) contains a short segment L<<278.0,308.0>--<288.0,308.0>>

	* uni049D (U+049D) contains a short segment L<<289.0,232.0>--<278.0,232.0>>

	* uni04C3 (U+04C3) contains a short segment L<<347.0,-123.0>--<370.0,-123.0>>

	* uni04C7 (U+04C7) contains a short segment L<<477.0,-118.0>--<479.0,-118.0>>

	* uni0512 (U+0512) contains a short segment L<<432.0,-118.0>--<433.0,-118.0>>

	* uni0512 (U+0512) contains a short segment B<<25.0,85.0>-<27.0,84.0>-<40.0,84.0>>

	* uni0513 (U+0513) contains a short segment B<<25.0,81.0>-<27.0,80.0>-<40.0,80.0>>

	* Euro (U+20AC) contains a short segment B<<91.0,313.0>-<90.0,321.0>-<90.0,329.0>>

	* Euro (U+20AC) contains a short segment B<<90.0,329.0>-<90.0,337.0>-<90.0,345.0>>

	* Euro (U+20AC) contains a short segment B<<90.0,365.0>-<90.0,373.0>-<90.0,381.0>>

	* Euro (U+20AC) contains a short segment B<<90.0,381.0>-<90.0,389.0>-<91.0,397.0>>

	* Euro (U+20AC) contains a short segment B<<191.0,397.0>-<190.0,389.0>-<190.0,381.0>>

	* Euro (U+20AC) contains a short segment B<<190.0,381.0>-<190.0,373.0>-<190.0,365.0>>

	* Euro (U+20AC) contains a short segment B<<190.0,345.0>-<190.0,337.0>-<190.0,329.0>> 

	* And Euro (U+20AC) contains a short segment B<<190.0,329.0>-<190.0,321.0>-<191.0,313.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Lcaron (U+013D): L<<445.0,506.0>--<456.0,625.0>> -> L<<456.0,625.0>--<456.0,700.0>>

	* dcaron (U+010F): L<<618.0,506.0>--<629.0,625.0>> -> L<<629.0,625.0>--<629.0,700.0>>

	* lcaron (U+013E): L<<271.0,506.0>--<282.0,625.0>> -> L<<282.0,625.0>--<282.0,700.0>> 

	* And tcaron (U+0165): L<<261.0,592.0>--<272.0,711.0>> -> L<<272.0,711.0>--<272.0,786.0>> [code: found-colinear-vectors]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 18 | 55 | 668 | 37 | 509 | 0 |
| 0% | 1% | 4% | 52% | 3% | 40% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
