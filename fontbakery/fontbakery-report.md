## FontBakery report

fontbakery version: 0.12.1



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] SplineSansMono[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>

<details><summary>[1] SplineSansMono-Italic[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[9] SplineSansMono[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The OpenType spec recomments at <a href="https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table">https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table</a> that hhea.numberOfHMetrics be set to 3 but this font has 555 instead.
Please read <a href="https://github.com/fonttools/fonttools/issues/3014">https://github.com/fonttools/fonttools/issues/3014</a> to decide whether this makes sense for your font.</p>
 [code: bad-numberOfHMetrics]



* ⚠️ **WARN** <p>Font is monospaced but 8 glyphs (1.44%) have a different width. You should check the widths of: ['uni2155.ss18', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow']</p>
 [code: mono-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- IJ_acutecomb

- commaturnedabove

- ij_acutecomb
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* dollar (U+0024): X=622.0,Y=1.0 (should be at baseline 0?)

* dollar (U+0024): X=622.0,Y=1.0 (should be at baseline 0?)

* nine (U+0039): X=394.0,Y=1452.0 (should be at cap-height 1454?)

* question (U+003F): X=1051.0,Y=1453.0 (should be at cap-height 1454?)

* C (U+0043): X=790.0,Y=0.5 (should be at baseline 0?)

* J (U+004A): X=346.5,Y=2.0 (should be at baseline 0?)

* U (U+0055): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* U (U+0055): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* f (U+0066): X=214.0,Y=1092.0 (should be at x-height 1091?)

* f (U+0066): X=985.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=702.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=901.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=308.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=901.0,Y=1092.0 (should be at x-height 1091?)

* l (U+006C): X=941.0,Y=0.5 (should be at baseline 0?)

* m (U+006D): X=83.0,Y=1092.0 (should be at x-height 1091?)

* m (U+006D): X=231.0,Y=1092.0 (should be at x-height 1091?)

* n (U+006E): X=192.0,Y=1093.0 (should be at x-height 1091?)

* n (U+006E): X=353.0,Y=1093.0 (should be at x-height 1091?)

* p (U+0070): X=177.0,Y=1092.0 (should be at x-height 1091?)

* p (U+0070): X=360.0,Y=1092.0 (should be at x-height 1091?)

* p (U+0070): X=362.0,Y=-1.0 (should be at baseline 0?)

* r (U+0072): X=106.0,Y=1093.0 (should be at x-height 1091?)

* r (U+0072): X=426.0,Y=1093.0 (should be at x-height 1091?)

* r (U+0072): X=331.0,Y=1093.0 (should be at x-height 1091?)

* r (U+0072): X=492.0,Y=1093.0 (should be at x-height 1091?)

* s (U+0073): X=458.0,Y=-0.5 (should be at baseline 0?)

* t (U+0074): X=916.5,Y=0.5 (should be at baseline 0?)

* t (U+0074): X=134.0,Y=1092.0 (should be at x-height 1091?)

* t (U+0074): X=962.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=181.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=366.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=824.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=1011.0,Y=1092.0 (should be at x-height 1091?)

* uni00B2 (U+00B2): X=815.0,Y=1455.0 (should be at cap-height 1454?)

* uni00B2 (U+00B2): X=388.0,Y=1453.0 (should be at cap-height 1454?)

* uni00B2 (U+00B2): X=235.0,Y=1453.0 (should be at cap-height 1454?)

* onequarter (U+00BC): X=358.0,Y=1454.5 (should be at cap-height 1454?)

* onequarter (U+00BC): X=397.0,Y=-2.0 (should be at baseline 0?)

* onequarter (U+00BC): X=1036.0,Y=-2.0 (should be at baseline 0?)

* onequarter (U+00BC): X=793.0,Y=-2.0 (should be at baseline 0?)

* onehalf (U+00BD): X=358.0,Y=1454.5 (should be at cap-height 1454?)

* threequarters (U+00BE): X=397.0,Y=-2.0 (should be at baseline 0?)

* threequarters (U+00BE): X=1036.0,Y=-2.0 (should be at baseline 0?)

* threequarters (U+00BE): X=793.0,Y=-2.0 (should be at baseline 0?)

* Ccedilla (U+00C7): X=790.0,Y=0.5 (should be at baseline 0?)

* Ugrave (U+00D9): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Ugrave (U+00D9): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Uacute (U+00DA): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Uacute (U+00DA): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Ucircumflex (U+00DB): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Ucircumflex (U+00DB): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Udieresis (U+00DC): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Udieresis (U+00DC): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* thorn (U+00FE): X=362.0,Y=-1.0 (should be at baseline 0?)

* Cacute (U+0106): X=790.0,Y=0.5 (should be at baseline 0?)

* Cdotaccent (U+010A): X=790.0,Y=0.5 (should be at baseline 0?)

* Ccaron (U+010C): X=790.0,Y=0.5 (should be at baseline 0?)

* lacute (U+013A): X=941.0,Y=0.5 (should be at baseline 0?)

* uni013C (U+013C): X=941.0,Y=0.5 (should be at baseline 0?)

* lcaron (U+013E): X=941.0,Y=0.5 (should be at baseline 0?)

* ldot (U+0140): X=941.0,Y=0.5 (should be at baseline 0?)

* lslash (U+0142): X=941.0,Y=0.5 (should be at baseline 0?)

* sacute (U+015B): X=458.0,Y=-0.5 (should be at baseline 0?)

* scedilla (U+015F): X=458.0,Y=-0.5 (should be at baseline 0?)

* scaron (U+0161): X=458.0,Y=-0.5 (should be at baseline 0?)

* uni0163 (U+0163): X=916.5,Y=0.5 (should be at baseline 0?)

* tcaron (U+0165): X=916.5,Y=0.5 (should be at baseline 0?)

* tbar (U+0167): X=908.5,Y=-1.0 (should be at baseline 0?)

* Utilde (U+0168): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Utilde (U+0168): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Umacron (U+016A): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Umacron (U+016A): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Ubreve (U+016C): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Ubreve (U+016C): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Uring (U+016E): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Uring (U+016E): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Uhungarumlaut (U+0170): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* Uhungarumlaut (U+0170): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* Uogonek (U+0172): X=139.0,Y=1456.0 (should be at cap-height 1454?)

* Uogonek (U+0172): X=330.0,Y=1456.0 (should be at cap-height 1454?)

* uni018F (U+018F): X=427.0,Y=1455.0 (should be at cap-height 1454?)

* uni0219 (U+0219): X=458.0,Y=-0.5 (should be at baseline 0?)

* uni021B (U+021B): X=916.5,Y=0.5 (should be at baseline 0?)

* uni1EE4 (U+1EE4): X=115.0,Y=1456.0 (should be at cap-height 1454?)

* uni1EE4 (U+1EE4): X=302.0,Y=1456.0 (should be at cap-height 1454?)

* quoteleft (U+2018): X=495.0,Y=1453.5 (should be at cap-height 1454?)

* quotesinglbase (U+201A): X=671.0,Y=-2.0 (should be at baseline 0?)

* quotesinglbase (U+201A): X=488.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=442.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=259.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=858.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=675.0,Y=-2.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dan (Latn, 1,099,244 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ekpeye (Latn, 226,000 speakers), Mango (Latn, 77,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ejagham (Latn, 120,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Bafut (Latn, 158,146 speakers), Nzakara (Latn, 50,000 speakers), Ma’di (Latn, 584,000 speakers), Mfumte (Latn, 79,000 speakers), Dii (Latn, 71,000 speakers), Kom (Latn, 360,685 speakers), Basaa (Latn, 332,940 speakers), Sar (Latn, 500,000 speakers), Aghem (Latn, 38,843 speakers), Mundani (Latn, 34,000 speakers), Nateni (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), South Central Banda (Latn, 244,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ebira (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Navajo (Latn, 166,319 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, malayalam, tai-le, canadian-aboriginal, syriac, tifinagh, coptic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, cherokee, gothic, syriac, tifinagh</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+2080 SUBSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss03 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss04 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss05 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss06 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss07 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss08 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss09 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss10 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss11 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss12 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss14 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss15 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss16 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss17 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss18 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss19 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>
</div>
</details>

<details><summary>[9] SplineSansMono-Italic[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.name.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The OpenType spec recomments at <a href="https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table">https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table</a> that hhea.numberOfHMetrics be set to 3 but this font has 626 instead.
Please read <a href="https://github.com/fonttools/fonttools/issues/3014">https://github.com/fonttools/fonttools/issues/3014</a> to decide whether this makes sense for your font.</p>
 [code: bad-numberOfHMetrics]



* ⚠️ **WARN** <p>Font is monospaced but 18 glyphs (2.87%) have a different width. You should check the widths of: ['a', 'aacute', 'abreve', 'acircumflex', 'adieresis', 'agrave', 'amacron', 'aogonek', 'aring', 'aringacute', 'atilde', 'plus.alt', 'equal.alt', 'greaterarrow', 'exclamequal', 'lessergreater', 'greatergreaterarrow', 'equalequalarrow']</p>
 [code: mono-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- IJ_acutecomb

- commaturnedabove

- ij_acutecomb

- uni2153.ss19

- uni2154.ss19

- uni2159.ss19
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* dollar (U+0024): X=543.0,Y=1.0 (should be at baseline 0?)

* dollar (U+0024): X=543.0,Y=1.0 (should be at baseline 0?)

* C (U+0043): X=735.0,Y=0.5 (should be at baseline 0?)

* U (U+0055): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* U (U+0055): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* a (U+0061): X=988.0,Y=1091.5 (should be at x-height 1091?)

* d (U+0064): X=1016.5,Y=1091.5 (should be at x-height 1091?)

* f (U+0066): X=239.0,Y=1092.0 (should be at x-height 1091?)

* f (U+0066): X=1063.0,Y=1092.0 (should be at x-height 1091?)

* i (U+0069): X=911.5,Y=0.5 (should be at baseline 0?)

* j (U+006A): X=710.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=909.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=313.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=909.0,Y=1092.0 (should be at x-height 1091?)

* j (U+006A): X=998.0,Y=1456.0 (should be at cap-height 1454?)

* n (U+006E): X=248.0,Y=1093.0 (should be at x-height 1091?)

* n (U+006E): X=411.0,Y=1093.0 (should be at x-height 1091?)

* p (U+0070): X=340.5,Y=-1.0 (should be at baseline 0?)

* p (U+0070): X=230.0,Y=1092.0 (should be at x-height 1091?)

* p (U+0070): X=413.0,Y=1092.0 (should be at x-height 1091?)

* p (U+0070): X=281.0,Y=-1.0 (should be at baseline 0?)

* q (U+0071): X=1006.5,Y=1091.5 (should be at x-height 1091?)

* r (U+0072): X=165.0,Y=1093.0 (should be at x-height 1091?)

* r (U+0072): X=555.0,Y=1093.0 (should be at x-height 1091?)

* r (U+0072): X=555.0,Y=1093.0 (should be at x-height 1091?)

* s (U+0073): X=406.5,Y=-0.5 (should be at baseline 0?)

* t (U+0074): X=147.0,Y=1092.0 (should be at x-height 1091?)

* t (U+0074): X=999.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=252.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=437.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=895.0,Y=1092.0 (should be at x-height 1091?)

* u (U+0075): X=1082.0,Y=1092.0 (should be at x-height 1091?)

* ordfeminine (U+00AA): X=862.0,Y=1456.0 (should be at cap-height 1454?)

* uni00B2 (U+00B2): X=896.0,Y=1455.0 (should be at cap-height 1454?)

* uni00B5 (U+00B5): X=426.0,Y=2.0 (should be at baseline 0?)

* onequarter (U+00BC): X=325.0,Y=-2.0 (should be at baseline 0?)

* onequarter (U+00BC): X=970.0,Y=-2.0 (should be at baseline 0?)

* onequarter (U+00BC): X=727.0,Y=-2.0 (should be at baseline 0?)

* threequarters (U+00BE): X=325.0,Y=-2.0 (should be at baseline 0?)

* threequarters (U+00BE): X=970.0,Y=-2.0 (should be at baseline 0?)

* threequarters (U+00BE): X=727.0,Y=-2.0 (should be at baseline 0?)

* Ccedilla (U+00C7): X=735.0,Y=0.5 (should be at baseline 0?)

* Ugrave (U+00D9): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Ugrave (U+00D9): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Uacute (U+00DA): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Uacute (U+00DA): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Ucircumflex (U+00DB): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Ucircumflex (U+00DB): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Udieresis (U+00DC): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Udieresis (U+00DC): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* germandbls (U+00DF): X=390.5,Y=1452.5 (should be at cap-height 1454?)

* igrave (U+00EC): X=911.5,Y=0.5 (should be at baseline 0?)

* iacute (U+00ED): X=911.5,Y=0.5 (should be at baseline 0?)

* icircumflex (U+00EE): X=911.5,Y=0.5 (should be at baseline 0?)

* idieresis (U+00EF): X=911.5,Y=0.5 (should be at baseline 0?)

* Cacute (U+0106): X=735.0,Y=0.5 (should be at baseline 0?)

* Cdotaccent (U+010A): X=735.0,Y=0.5 (should be at baseline 0?)

* Ccaron (U+010C): X=735.0,Y=0.5 (should be at baseline 0?)

* itilde (U+0129): X=911.5,Y=0.5 (should be at baseline 0?)

* imacron (U+012B): X=911.5,Y=0.5 (should be at baseline 0?)

* ibreve (U+012D): X=911.5,Y=0.5 (should be at baseline 0?)

* iogonek (U+012F): X=911.5,Y=0.5 (should be at baseline 0?)

* dotlessi (U+0131): X=911.5,Y=0.5 (should be at baseline 0?)

* ij (U+0133): X=591.5,Y=0.5 (should be at baseline 0?)

* sacute (U+015B): X=406.5,Y=-0.5 (should be at baseline 0?)

* scedilla (U+015F): X=406.5,Y=-0.5 (should be at baseline 0?)

* scaron (U+0161): X=406.5,Y=-0.5 (should be at baseline 0?)

* Utilde (U+0168): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Utilde (U+0168): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Umacron (U+016A): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Umacron (U+016A): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Ubreve (U+016C): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Ubreve (U+016C): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Uring (U+016E): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Uring (U+016E): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Uhungarumlaut (U+0170): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Uhungarumlaut (U+0170): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Uogonek (U+0172): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* Uogonek (U+0172): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* Uogonek (U+0172): X=562.0,Y=1.0 (should be at baseline 0?)

* Uogonek (U+0172): X=701.0,Y=1.0 (should be at baseline 0?)

* uni0219 (U+0219): X=406.5,Y=-0.5 (should be at baseline 0?)

* uni1ECB (U+1ECB): X=911.5,Y=0.5 (should be at baseline 0?)

* uni1EE4 (U+1EE4): X=232.0,Y=1456.0 (should be at cap-height 1454?)

* uni1EE4 (U+1EE4): X=418.0,Y=1456.0 (should be at cap-height 1454?)

* quoteleft (U+2018): X=617.0,Y=1453.0 (should be at cap-height 1454?)

* quotesinglbase (U+201A): X=574.0,Y=-2.0 (should be at baseline 0?)

* quotesinglbase (U+201A): X=391.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=371.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=188.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=788.0,Y=-2.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=605.0,Y=-2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=26.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=845.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=436.0,Y=2.0 (should be at baseline 0?)

* uni2078 (U+2078): X=860.5,Y=1453.0 (should be at cap-height 1454?)

* uni2080 (U+2080): X=293.0,Y=-2.0 (should be at baseline 0?)

* uni2083 (U+2083): X=543.0,Y=2.0 (should be at baseline 0?)

* uni2083 (U+2083): X=415.0,Y=2.0 (should be at baseline 0?)

* uni2086 (U+2086): X=335.0,Y=-1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ j̦̀ j̦́ ĵ̦ j̦̃ j̦̄ j̦̆ j̦̇ j̦̈ j̦̊ j̦̋ ǰ̦ j̦̒ į̆ į̇ į̈</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dan (Latn, 1,099,244 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ekpeye (Latn, 226,000 speakers), Mango (Latn, 77,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ejagham (Latn, 120,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Igbo (Latn, 27,823,640 speakers), Bafut (Latn, 158,146 speakers), Nzakara (Latn, 50,000 speakers), Ma’di (Latn, 584,000 speakers), Mfumte (Latn, 79,000 speakers), Dii (Latn, 71,000 speakers), Kom (Latn, 360,685 speakers), Basaa (Latn, 332,940 speakers), Sar (Latn, 500,000 speakers), Aghem (Latn, 38,843 speakers), Mundani (Latn, 34,000 speakers), Nateni (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), South Central Banda (Latn, 244,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ebira (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Navajo (Latn, 166,319 speakers), Fur (Latn, 1,230,163 speakers), Ngbaka (Latn, 1,020,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, math, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, malayalam, tai-le, canadian-aboriginal, syriac, tifinagh, coptic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: caucasian-albanian, cherokee, gothic, syriac, tifinagh</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2070 SUPERSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2076 SUPERSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2079 SUPERSCRIPT NINE: not included in any glyphset definition</li>
<li>U+2080 SUBSCRIPT ZERO: not included in any glyphset definition</li>
<li>U+2081 SUBSCRIPT ONE: not included in any glyphset definition</li>
<li>U+2082 SUBSCRIPT TWO: not included in any glyphset definition</li>
<li>U+2083 SUBSCRIPT THREE: not included in any glyphset definition</li>
<li>U+2084 SUBSCRIPT FOUR: not included in any glyphset definition</li>
<li>U+2085 SUBSCRIPT FIVE: not included in any glyphset definition</li>
<li>U+2086 SUBSCRIPT SIX: not included in any glyphset definition</li>
<li>U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition</li>
<li>U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition</li>
<li>U+2089 SUBSCRIPT NINE: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gsub.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss03 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss04 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss06 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss07 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss08 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss09 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss10 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss11 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss12 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss14 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss15 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss16 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss17 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss18 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss19 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 0 | 20 | 187 | 13 | 260 | 0 | 
| 0% | 0% | 0% | 4% | 39% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
