## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| br_Latn (Breton) | Some base glyphs were missing: CʼH, cʼh |
|  ^  | Shaper produced a .notdef |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| mh_Latn (Marshallese) | Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ |
|  ^  | Some mark glyphs were missing: ◌̣ |
|  ^  | Shaper produced a .notdef |
| qu_Latn (Quechua) | Some base glyphs were missing: CHʼ, Kʼ, Pʼ, Qʼ, Tʼ, chʼ, kʼ, pʼ, qʼ, tʼ |
|  ^  | Shaper produced a .notdef |
| scn_Latn (Sicilian) | Some base glyphs were missing: Ḍ, ḍ |
|  ^  | Shaper produced a .notdef |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
</div></details><br></div></details><details><summary><b>[12] NotoSerifMyanmar[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "brevecomb" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "caroncomb" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "circumflexcomb" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "dieresiscomb" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "dotaccentcomb" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "hungarumlautcomb" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ringcomb" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: math, coptic, syriac, malayalam, tifinagh, tai-le, canadian-aboriginal, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+A92E KAYAH LI SIGN CWI: try adding kayah-li
 * U+FE00 VARIATION SELECTOR-1: try adding one of: phags-pa, yi, manichaean

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `myanmar` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* _e_above
	* _e_above_shn
	* _e_dot
	* _medialNa_mon
	* _medialNa_mon.sub2
	* _tall_aa_asat
	* _tall_aa_asat.spaced
	* a_m
	* a_m.sub
	* ba_shn
	* ba_shn.sub
	* ba_shn.sub2
	* bbe_mon
	* bbe_mon.sub
	* bha_tlg
	* ca
	* ca_khm
	* ca_nya
	* ca_shn
	* ca_shn.sub
	* ca_shn.sub2
	* ca_shn_dot
	* cha_shw
	* cha_shw_medial_wa
	* da_dha_na
	* dda
	* dda.littletail
	* dda.sub
	* dda.sub2
	* dda_dda
	* dda_ddha
	* dda_ga
	* dda_ma
	* dda_medial_ha
	* dda_wa
	* ddha_khm
	* dha_khm
	* e_shn
	* ee_kyh
	* eight_tlg
	* exclam_atn
	* exclam_shn
	* fa_rpg
	* fa_rpg.sub
	* fa_rpg.sub2
	* fa_shn.sub
	* fa_shn.sub2
	* five_m
	* five_shn
	* four_m
	* ga
	* ga_khm_dot
	* gha_khm
	* gha_khm_dot.sub
	* gha_khm_dot.sub2
	* gha_shn
	* gha_tlg
	* great_nnya
	* ha_khm
	* ha_khm_medial_wa
	* ha_khm_uu
	* ha_shn
	* ha_shn.sub
	* ha_shn_medial_ha
	* ha_shn_medial_wa
	* ha_shn_u
	* ha_shn_uu
	* hathi_skn
	* hm_khm
	* ja
	* ja_khm_dot
	* ja_nya
	* ja_tlg
	* jha
	* jha.sub
	* jha.sub2
	* jha_khm_dot
	* jha_mon
	* jha_mon.sub
	* jha_mon.sub2
	* ka_khm
	* ka_khm.sub
	* ka_shn
	* ka_shn.sub
	* ka_shn.sub2
	* ka_shn_dot.sub
	* ka_shn_dot.sub2
	* kha
	* la_khm
	* la_khm.sub
	* la_khm.sub2
	* lla
	* lla.littletail
	* lla.notail
	* lla.sub
	* lla.sub2
	* lla_lla
	* lla_medial_ha
	* locative
	* ma_khm
	* ma_phk.sub
	* ma_phk.sub2
	* medial_ha
	* medial_ha_dot
	* medial_ha_u
	* medial_ha_u_dot
	* medial_ra_wa
	* medial_ra_wa.w2
	* medial_ra_wa.w2_2
	* medial_ra_wa.w2_5
	* medial_ra_wa.w3
	* medial_ra_wa_ha
	* medial_ra_wa_ha.w2
	* medial_ra_wa_ha.w2_2
	* medial_ra_wa_ha.w2_5
	* medial_ra_wa_ha.w3
	* medial_ra_wa_ha_ovl
	* medial_ra_wa_ha_ovl.w2
	* medial_ra_wa_ha_ovl.w2_2
	* medial_ra_wa_ha_ovl.w2_5
	* medial_ra_wa_ha_ovl.w3
	* medial_ra_wa_ha_ovl_tt
	* medial_ra_wa_ha_ovl_tt.w2
	* medial_ra_wa_ha_ovl_tt.w2_2
	* medial_ra_wa_ha_ovl_tt.w2_5
	* medial_ra_wa_ha_ovl_tt.w3
	* medial_ra_wa_ha_ovl_tt2
	* medial_ra_wa_ha_tt
	* medial_ra_wa_ha_tt.w2
	* medial_ra_wa_ha_tt.w2_2
	* medial_ra_wa_ha_tt.w2_5
	* medial_ra_wa_ha_tt.w3
	* medial_ra_wa_ha_tt2
	* medial_ra_wa_ovl
	* medial_ra_wa_ovl.w2
	* medial_ra_wa_ovl.w2_2
	* medial_ra_wa_ovl.w2_5
	* medial_ra_wa_ovl.w3
	* medial_ra_wa_ovl_tt
	* medial_ra_wa_ovl_tt.w2
	* medial_ra_wa_ovl_tt.w2_2
	* medial_ra_wa_ovl_tt.w2_5
	* medial_ra_wa_ovl_tt.w3
	* medial_ra_wa_ovl_tt2
	* medial_ra_wa_tt
	* medial_ra_wa_tt.w2
	* medial_ra_wa_tt.w2_2
	* medial_ra_wa_tt.w2_5
	* medial_ra_wa_tt.w3
	* medial_ra_wa_tt2
	* medial_wa_dotbelow_shn
	* medial_wa_shn
	* medial_ya_i_u
	* medial_ya_i_u.alt1
	* medial_ya_i_u.alt2
	* medial_ya_wa_ha_ovl
	* na
	* na.alt
	* na.for_aa
	* na_dot_below
	* na_khm
	* na_shn
	* na_short.for_aa
	* nga_khm
	* nine_shn
	* nna_dda
	* nna_epk
	* nna_shn
	* nna_shn.sub
	* nna_shn.sub2
	* nna_tta
	* nna_ttha
	* nnya.notail
	* nnya_medial_ha_uu
	* nya.narrow
	* nya.sub
	* nya_ca
	* nya_ca_ya
	* nya_cha
	* nya_cha_ya
	* nya_ja
	* nya_jha
	* nya_khm
	* nya_khm_dot
	* nya_shn_dot
	* nya_shn_dot.sub
	* nya_shn_dot.sub2
	* nya_tlg
	* one_m
	* pa.sub
	* pa.sub2
	* pa_khm
	* pha_shn.sub
	* pha_shn.sub2
	* qay_khm
	* qn_khm
	* quotedblleft
	* quotedblright
	* ra_atn_dot
	* ra_medial_ha
	* ra_medial_ha_obl_uu
	* ra_medial_ha_u
	* ra_medial_ha_uu
	* ra_uu
	* sa.sub
	* sa.sub2
	* saw_shn
	* seven_tlg
	* sha_shw_medial_wa
	* sha_skn
	* sha_skt.sub
	* sha_skt.sub2
	* six_ai
	* six_m
	* six_shn
	* ssa_skt
	* ssa_tta
	* ssa_tta.littletail
	* ssa_tta_medial_ra
	* ssa_ttha
	* ta_khm
	* ta_khm.sub
	* ta_khm.sub2
	* tha_khm
	* tha_khm.sub
	* tha_khm.sub2
	* tha_wpk
	* three_tlg
	* tone2_wpk
	* tone5_rpg
	* tta
	* tta.alt
	* tta.alt.littletail
	* tta.littletail
	* tta.sub
	* tta.sub.alt
	* tta.sub2
	* tta_khm
	* tta_medial_ha
	* tta_tta
	* tta_ttha
	* ttha.sub
	* ttha_medial_ha
	* two_tlg
	* u_m
	* ue_wpk
	* uu
	* vocL_skt
	* vocR_skt
	* vocR_skt.sub
	* vocR_skt.sub2
	* ya.sub
	* ya.sub2
	* ya_khm
	* ya_khm.sub
	* za_khm
	* za_shn
	* za_shn.sub and za_shn.sub2
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _ai_khm

	- asatstem

	- great_nnya.clipped

	- ha_tlg

	- medial_wa_ha_ovl_short

	- medial_wa_ha_short

	- ttha.sub.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 _a_atn (U+109C), aa_shn (U+1083), e_shn (U+1084) and eu_wpk (U+1067) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 _vocLL_skt (U+1059) and _vocL_skt (U+1058) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+1067, U+1083, U+1084 and U+109C [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=314.0,Y=715.0 (should be at cap-height 714?)

	* parenright (U+0029): X=32.0,Y=715.0 (should be at cap-height 714?)

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=328.0,Y=0.5 (should be at baseline 0?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* question (U+003F): X=66.0,Y=712.5 (should be at cap-height 714?)

	* C (U+0043): X=457.5,Y=0.5 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* bracketleft (U+005B): X=239.0,Y=713.0 (should be at cap-height 714?)

	* bracketright (U+005D): X=121.5,Y=713.0 (should be at cap-height 714?)

	* a (U+0061): X=182.0,Y=536.5 (should be at x-height 536?)

	* b (U+0062): X=66.5,Y=713.5 (should be at cap-height 714?)

	* c (U+0063): X=360.0,Y=535.0 (should be at x-height 536?)

	* d (U+0064): X=370.5,Y=713.5 (should be at cap-height 714?)

	* f (U+0066): X=331.0,Y=712.5 (should be at cap-height 714?)

	* g (U+0067): X=394.0,Y=536.5 (should be at x-height 536?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=66.5,Y=713.5 (should be at cap-height 714?)

	* k (U+006B): X=66.5,Y=713.5 (should be at cap-height 714?)

	* l (U+006C): X=66.5,Y=713.5 (should be at cap-height 714?)

	* m (U+006D): X=424.5,Y=537.0 (should be at x-height 536?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* s (U+0073): X=123.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=457.5,Y=1.5 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=126.5,Y=713.0 (should be at cap-height 714?)

	* paragraph (U+00B6): X=522.0,Y=713.0 (should be at cap-height 714?)

	* Ccedilla (U+00C7): X=457.5,Y=0.5 (should be at baseline 0?)

	* Oslash (U+00D8): X=454.5,Y=715.5 (should be at cap-height 714?)

	* Oslash (U+00D8): X=287.0,Y=-1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=352.5,Y=2.0 (should be at baseline 0?)

	* thorn (U+00FE): X=66.5,Y=713.5 (should be at cap-height 714?)

	* Cacute (U+0106): X=457.5,Y=0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=457.5,Y=0.5 (should be at baseline 0?)

	* Ccaron (U+010C): X=457.5,Y=0.5 (should be at baseline 0?)

	* dcaron (U+010F): X=370.5,Y=713.5 (should be at cap-height 714?)

	* dcroat (U+0111): X=370.5,Y=713.0 (should be at cap-height 714?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gcommaaccent (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* gcommaaccent (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* hbar (U+0127): X=66.5,Y=713.5 (should be at cap-height 714?)

	* kcommaaccent (U+0137): X=66.5,Y=713.5 (should be at cap-height 714?)

	* lacute (U+013A): X=66.5,Y=713.5 (should be at cap-height 714?)

	* lcommaaccent (U+013C): X=66.5,Y=713.5 (should be at cap-height 714?)

	* lcaron (U+013E): X=66.5,Y=713.5 (should be at cap-height 714?)

	* lslash (U+0142): X=81.5,Y=713.5 (should be at cap-height 714?)

	* sacute (U+015B): X=123.0,Y=2.0 (should be at baseline 0?)

	* scedilla (U+015F): X=123.0,Y=2.0 (should be at baseline 0?)

	* scaron (U+0161): X=123.0,Y=2.0 (should be at baseline 0?)

	* scommaaccent (U+0219): X=123.0,Y=2.0 (should be at baseline 0?)

	* na (U+1014): X=398.0,Y=-1.5 (should be at baseline 0?)

	* na (U+1014): X=168.5,Y=-1.5 (should be at baseline 0?)

	* uu (U+1026): X=315.0,Y=713.0 (should be at cap-height 714?)

	* uu (U+1026): X=315.0,Y=713.0 (should be at cap-height 714?)

	* _i (U+102D): X=-315.0,Y=715.0 (should be at cap-height 714?)

	* _i (U+102D): X=-315.0,Y=715.0 (should be at cap-height 714?)

	* _ii (U+102E): X=-315.0,Y=713.0 (should be at cap-height 714?)

	* _ii (U+102E): X=-315.0,Y=713.0 (should be at cap-height 714?)

	* _ii_mon (U+1033): X=-315.0,Y=715.0 (should be at cap-height 714?)

	* _ii_mon (U+1033): X=-315.0,Y=715.0 (should be at cap-height 714?)

	* vocLL_skt (U+1055): X=384.5,Y=2.0 (should be at baseline 0?)

	* oe_kyh (U+1072): X=-313.0,Y=715.0 (should be at cap-height 714?)

	* nine_shn (U+1099): X=240.0,Y=-1.0 (should be at baseline 0?)

	* nine_shn (U+1099): X=410.5,Y=-1.0 (should be at baseline 0?)

	* tone3_khm (U+109B): X=278.0,Y=715.5 (should be at cap-height 714?)

	* quoteright (U+2019): X=195.0,Y=716.0 (should be at cap-height 714?)

	* quoteright (U+2019): X=195.0,Y=716.0 (should be at cap-height 714?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=195.0,Y=716.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=195.0,Y=716.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=513.0,Y=716.0 (should be at cap-height 714?)

	* quotedblright (U+201D): X=513.0,Y=716.0 (should be at cap-height 714?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

	* seven_tlg (U+A9F7): X=281.0,Y=716.0 (should be at cap-height 714?)

	* za_khm (U+AA72): X=323.5,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Ebira (Latn, 2,200,000 speakers), Ma’di (Latn, 584,000 speakers), Aghem (Latn, 38,843 speakers), Avokaya (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Gulay (Latn, 250,478 speakers), Igbo (Latn, 27,823,640 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Lugbara (Latn, 2,200,000 speakers), Navajo (Latn, 166,319 speakers), Belarusian (Cyrl, 10,064,517 speakers), Sar (Latn, 500,000 speakers), Koonzime (Latn, 40,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ejagham (Latn, 120,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 10 | 101 | 8 | 133 | 0 |
| 0% | 1% | 4% | 40% | 3% | 52% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
