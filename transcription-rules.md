# Transcription Rules
This document outlines the transcription rules applied in this repository. A list of the respective unicode codepoints for distinct characters follows in the final section of these *transcription rules*.

## General principles
### Allographs
Allographs are preserved. This includes:
- Majuscles (uppercase letters) are preserved as distinct from miniscules (lowercase letters),
- < Z/z > may appear alongsinde < Ʒ/ʒ >,
- < u/v/w/f > are transcribed as found in the original document,
- < i/j > are transcribed as found in the original document,
- < ſ > and < s > are kept as distinct characters,
- < ꝛ > may appear next to < r >.

### Ligatures
As a principle, ligatures have been reverted to their constituating base characters. In cases of < ß > where letters appeared fully merged, it was treated as a single character. It has been transcribed as < ſʒ > when the constituating characters appeared to be at least partly distinct.

### Diacritics
Diacritics are preserved only in situations defined by the following rules:
- superscribed vowels have generally been preserved,
- dots above < a, o, u > have been coherently transcribed as single codepoint letters with tremmata, e.g. < ä, ö, ü >,
- any other markings above < a, o, u > have been transcribed as a separate codepoint character < ´ >, e.g. < á, ó, ú >.
- diacritics above any other characters have been omitted.

### Abbreviatures
Owing to the nature of the original manuscript, abbreviatures have been transcribed in three ways:
- nasal shortenings represented through strokes or waves have been transcribed as *macron* < ̅  > (separate codepoint) above the the final letter,
- r-shortenings, appearing as hooks or loops, have been transcribed as < ' > after the final letter,
- a third shortening appears in the document, replacing any syllable of word; this has been transcribed as < * >.

### Punctuation marks
Since there are only three forms of punctuation marks appearing in the original documents, they have been transcribed as true to the document as possible:
- dots appear as elevated points (*punctus elevatus*) < ‧ >,
- *virgula*, strokes serving as proto-commas, have been transcribed as < / >,
- horizontal lines or double lines have been transcribed as < - >.

Additionally, < " > has been used to represent a symbol indicating the inclusion of a superscribed word in the manuscript, where ever such a symbol was originally used.

### Unreadable characters
Unreadable characters have been transcribed as < # >.

## Characters
Character|Description|hex code point|decimal code point|commentary
---|---|---|---|---
a|LATIN SMALL LETTER A|0061|97|
ä|LATIN SMALL LETTER A WITH DIAERESIS|00E4|228|
å|LATIN SMALL LETTER A WITH RING ABOVE|00E5|229|
b|LATIN SMALL LETTER B|0062|98|
c|LATIN SMALL LETTER C|0063|99|
d|LATIN SMALL LETTER D|0064|100|
e|LATIN SMALL LETTER E|0065|101|
f|LATIN SMALL LETTER F|0066|102|
g|LATIN SMALL LETTER G|0067|103|
h|LATIN SMALL LETTER H|0068|104|
i|LATIN SMALL LETTER I|0069|105|
j|LATIN SMALL LETTER J|006A|106|
k|LATIN SMALL LETTER K|006B|107|
l|LATIN SMALL LETTER L|006C|108|
m|LATIN SMALL LETTER M|006D|109|
n|LATIN SMALL LETTER N|006E|110|
o|LATIN SMALL LETTER O|006F|111|
ö|LATIN SMALL LETTER O WITH DIAERESIS|00F6|246|
p|LATIN SMALL LETTER P|0070|112|
q|LATIN SMALL LETTER Q|0071|113|
r|LATIN SMALL LETTER R|0072|114|
ꝛ|LATIN SMALL LETTER R ROTUNDA|A75B|42843
s|LATIN SMALL LETTER S|0073|115|
ſ|LATIN SMALL LETTER LONG S|017F|383
t|LATIN SMALL LETTER T|0074|116|
u|LATIN SMALL LETTER U|0075|117|
ü|LATIN SMALL LETTER U WITH DIAERESIS|00FC|252|
ů|LATIN SMALL LETTER U WITH RING ABOVE|016F|367|
v|LATIN SMALL LETTER V|0076|0076|
w|LATIN SMALL LETTER W|0077|119|
x|LATIN SMALL LETTER X|0078|120|
y|LATIN SMALL LETTER Y|0079|121|
z|LATIN SMALL LETTER Z|007A|122|
ʒ|LATIN SMALL LETTER EZH|0292|658|
A|LATIN CAPITAL LETTER A|0041|65|
Ä|LATIN CAPITAL LETTER A WITH DIAERESIS|00C4|196|
B|LATIN CAPITAL LETTER B|0042|66|
C|LATIN CAPITAL LETTER C|0043|67|
D|LATIN CAPITAL LETTER D|0044|68|
E|LATIN CAPITAL LETTER E|0045|69|
F|LATIN CAPITAL LETTER F|0046|70|
G|LATIN CAPITAL LETTER G|0047|71|
H|LATIN CAPITAL LETTER H|0048|72|
I|LATIN CAPITAL LETTER I|0049|73|
J|LATIN CAPITAL LETTER J|004A|74|
K|LATIN CAPITAL LETTER K|004B|75|
L|LATIN CAPITAL LETTER L|004C|76|
M|LATIN CAPITAL LETTER M|004D|77|
N|LATIN CAPITAL LETTER N|004E|78|
O|LATIN CAPITAL LETTER O|004F|79|
Ö|LATIN CAPITAL LETTER O WITH DIAERESIS|00D6|214|
P|LATIN CAPITAL LETTER P|0050|80|
Q|LATIN CAPITAL LETTER Q|0051|81|
R|LATIN CAPITAL LETTER R|0052|82|
S|LATIN CAPITAL LETTER S|0053|83|
T|LATIN CAPITAL LETTER T|0054|84|
U|LATIN CAPITAL LETTER U|0055|85|
Ü|LATIN CAPITAL LETTER U WITH DIAERESIS|00DC|220|
V|LATIN CAPITAL LETTER V|0056|86|
W|LATIN CAPITAL LETTER W|0057|87|
X|LATIN CAPITAL LETTER X|0058|88|
Y|LATIN CAPITAL LETTER Y|0059|89|
Z|LATIN CAPITAL LETTER Z|005A|90|
Ʒ|LATIN CAPITAL LETTER EZH|01B7|439
´|ACUTE ACCENT|00B4|180|superscribed stroke
'|APOSTROPHE|0027|39|r-shortening
̅ |COMBINING OVERLINE|0305|773|nasal shortening
\*|ASTERISK|002A|42|abbreviation sign
‧|HYPENATION POINT|2027|8231|punctus elevatus
⁄|FRACTION SLASH|2044|8260|virgula
\-|HYPHEN-MINUS|002D|45|word separation etc.
"|QUOTATION MARK|0022|34|
\#|NUMBER SIGN|0023|35|unreadable character(s)

## Useful ressources
[Tool for dermining character encoding, University of Edinburgh](https://www.cogsci.ed.ac.uk/~richard/utf-8.cgi?input=%E2%81%84&mode=char)

[Unicode Character Code Charts](https://www.unicode.org/charts/)