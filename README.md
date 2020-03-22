# Sligeach font - A reprint font of a 19th Gaelic type font.

Sligeach (Irish name for Sligo) font is a revived version of the Gaelic font used in some books. The font is mainly adapted from *
A practical grammar of the Irish language* (by Owen Connellan in 1844), and the name is named from the linguist's birthplace.

The font is referenced from:
 - A Practical Grammar of the Irish Language (Owen Connellan, 1844, main source)
 - Focloir Gaoidhilge - Sacs-bearla, or an Irish - English dictionary (Thomas De Vere Coneys, 1849).

The's three version of it:

 - sligeach_orig.ttf : the small u is like v, and it doesn't contain some ligatures (eg. ea, rr) listed in A Practical Grammar of the Irish Language, p.13.
 - sligeach_round_u.ttf : the small u is round, like roman-type u, and it doesn't contain some ligatures (eg. ea, rr) listed in APGIL, p.13.
 - sligeach_ligature.ttf : the small u is like v, and it contains all ligatures (including ea, rr) listed in APGIL, p.13.

It contains some punctuations(:;*,.?!‘’“”'-), but contains no numbers.

Demos
============
![Demo with "Is fearr Gaeilge bhriste ná Béarla cliste" in archaic form](/image/demo1.png)
![Demo with a Irish pangram](/image/demo2.png)

Ligatures
============

ligatures in all fonts
-------------------------


| Contraction for | Picture     | How to type (Unicode)  |
| --------------- | ------------|------------------------|
| ae    | ![ae](/image/ae.png)   | æ (U+00E6)            |
| an    | ![an](/image/an.png)  | ā (U+0101)             |
| agus  | ![agus](/image/agus.png) | ⁊ (U+204A)          |
| acht or cht | ![cht](/image/cht.png) | s̄ (s + U+0304)  |
| go    | ![go](/image/go.png) | ḡ (s + U+0304)          |
| gur    | ![gur](/image/gur.png) | g᷒ (s + U+1DD2)        |
| na    | ![na](/image/na.png) | ṉ (U+1E49)              |
| nn    | ![nn](/image/nn.png) | n̄ (n + U+0304)          |


ligatures only in sligeach_ligature.ttf
-----------------------------------------

| Contraction for | Picture     | How to type  | Notice |
| --------------- | ------------|--------------|--------|
| ar    | ![ar](/image/ae.png)  | ar          | ligaturized only between spaces (eg. " ar ") |
| air    | ![air](/image/an.png)| air         | ligaturized only between spaces (eg. " air ") |
| ea  | ![ea](/image/ea.png)  | ea          |        |
| rr | ![rr](/image/cht.png)    | rr          |        |
| si | ![si](/image/si.png)    | si          |        |
| ui | ![ui](/image/ui.png)    | ui          |        |
| .i. | ![eadhon](/image/eadhon.png)| .i.          |        |

Issues
----------------------------------------
 - ar & air are only ligaturized after some non-space characters and space(s).
 - the font height is too high.
