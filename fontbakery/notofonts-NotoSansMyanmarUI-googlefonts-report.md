## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[11] NotoSansMyanmarUI[wdth,wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.copyright.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2021 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following spacing glyphs may be in the GDEF mark glyph class by mistake:
_a_atn (U+109C)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
i_gkn (U+1071), oe_kyh (U+1072) and u_kyh (U+1073)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check GDEF mark glyph class doesn't have characters that are not marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following non-mark characters should not be in the GDEF mark glyph class:
U+109C and U+A9E6</p>
 [code: non-mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 point 31 in glyph 'medial_ra_bt3' has a kink between location wght=100,wdth=100 and location wght=900,wdth=100

- Contour 0 point 31 in glyph 'medial_ra_bt3' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 0 point 21 in glyph 'medial_ra_tt_bt3' has a kink between location wght=100,wdth=100 and location wght=900,wdth=100

- Contour 0 point 21 in glyph 'medial_ra_tt_bt3' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 0 point 21 in glyph 'medial_ra_tt_bt3' has a kink between location wght=100,wdth=62 and location wght=900,wdth=62

- Contour 0 point 21 in glyph 'medial_ra_tt_bt3.w2' has a kink between location wght=100,wdth=100 and location wght=900,wdth=100

- Contour 0 point 21 in glyph 'medial_ra_tt_bt3.w2' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 0 point 11 in glyph 'nnya.notail' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62

- Contour 0 point 11 in glyph 'nnya.notail' has a kink between location wght=100,wdth=62 and location wght=900,wdth=62

- Contour 0 point 31 in glyph 'medial_ra_bt3.w2' has a kink between location wght=100,wdth=100 and location wght=900,wdth=100

- Contour 0 point 31 in glyph 'medial_ra_bt3.w2' has a kink between location wght=900,wdth=100 and location wght=100,wdth=62
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- _tall_aa.alt

- _tall_aa_asat.alt

- tall_aa_ai.alt

- tall_aa_anusvara.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansMyanmarUI/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: hebrew, old-permic, canadian-aboriginal, tai-le, syriac, math, coptic, malayalam, tifinagh, duployan, todhri</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+FE00 VARIATION SELECTOR-1: try adding one of: phags-pa, yi, manichaean</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>myanmar</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Mango (Latn, 77,000 speakers), Ma’di (Latn, 584,000 speakers), Cicipu (Latn, 44,000 speakers), Ebira (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Heiltsuk (Latn, 300 speakers), Navajo (Latn, 166,319 speakers), Yala (Latn, 200,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Vute (Latn, 21,000 speakers), Koonzime (Latn, 40,000 speakers), Makaa (Latn, 221,000 speakers), Igbo (Latn, 27,823,640 speakers), Ekpeye (Latn, 226,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers), Mundani (Latn, 34,000 speakers), Gulay (Latn, 250,478 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Bafut (Latn, 158,146 speakers), Ejagham (Latn, 120,000 speakers), Fur (Latn, 1,230,163 speakers), Han (Latn, 6 speakers), Aghem (Latn, 38,843 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Nateni (Latn, 100,000 speakers), Southern Kisi (Latn, 360,000 speakers), Kaska (Latn, 125 speakers), South Central Banda (Latn, 244,000 speakers), Dan (Latn, 1,099,244 speakers), Nzakara (Latn, 50,000 speakers), Lugbara (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMyanmarUI/googlefonts/variable-ttf/NotoSansMyanmarUI[wdth,wght].ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 3 | 9 | 95 | 7 | 137 | 0 | 
| 0% | 0% | 1% | 4% | 38% | 3% | 55% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG