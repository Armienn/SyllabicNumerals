# Syllabic Numerals

Syllabic numerals are a system of compact number words. In this system, numbers from 0 to 99 each correspond to a word of a single syllable. They are designed primarily for making big numbers easier to remember, rather than for counting. A number like 2022 would in english number words be "two thousand and twenty two", but is in syllabic numerals "fafi".

## The System

Syllabic numerals might be seen as either a base-100 system, or perhaps a mixed base-5 and base-20 system. The numbers 0 to 4 correspond to the five vowels 'a', 'e', 'i', 'o' and 'u', while the consonants "bcdfghjklmnprstvwxz" (all but 'q') correspond to 5, 10, 15, 20 et cetera. So 0 is "a", 1 is "e", 5 is "ba", 6 is "be", 10 is "ca" and so forth.

Numbers of a hundred and above work are constructed by adding additional syllables; 1 is "e", 100 is "ea", 10000 is "eaa".

n alternate, more procedural description is this: A number `n` between 0 and 99 is converted to a syllable by finding `c = floor(n / 5)` and `v = n % 5`. A syllable is then constructed by taking first the character at index `c` in: `_bcdfghjklmnprstvwxz`, and then the character at index `v` in: `aeiou`, and finally removing `_` if present. Thus from 19 we get `c = 3` and `v = 4`, which results in the syllable "du", and from 3 we get "o".

## Why?

In modern life we deal with a lot of long numbers: telephone numbers, IP addresses, credit card numbers, national ID numbers et cetera. All of these numbers are a pain to remember and to communicate, since traditional number words weren't designed for such large numbers. Some common numbers, like years, are already often shortened, such as saying nineteen-hundred-sixty-four or just nineteen-sixty-four for 1964 instead of the "proper" one-thousand-nine-hundred-sixty-four. Now compare that with the syllabic numeral: "dupu".

Where syllabic numerals can really help is with long numbers, such as credit cards. Imagine trying to remember a credit card number like 4574-4874-0535-1567 as opposed to lasu-losu-baja-dari. Syllables are just much easier for humans to remember.

## Pronunciation

If you need to communicate numbers, pronunciation is important, especially for syllabic numerals. Common numbers words are longer, but they are also further from each other soundwise, so big mistakes are needed to be misheard. Syllabic numerals are much more "packed together", which comes at the prices of distinctness, so there's a bigger need for careful and clear pronunciation. Add to that the fact that letters may often represent the same sound ('c' is sometimes 's', sometimes 'k'), and that different languages and dialects distinguish different sounds; there is definitely a need for some standardisation. That said, if you happen to be speaking a language that clearly distinguish the sounds for all the letters used in syllabic numerals, feel free to just use those when communicating in that language.

### Standard Pronounciation

Letter | [IPA](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) | English description
--|--|--
a | [\[a\]](https://en.wikipedia.org/wiki/Open_front_unrounded_vowel) | like 'a' in "bra"
e | [\[e\]](https://en.wikipedia.org/wiki/Mid_front_unrounded_vowel) | like 'e' in "yes"
i | [\[i\]](https://en.wikipedia.org/wiki/Close_front_unrounded_vowel) | like 'ee' in "bee"
o | [\[o\]](https://en.wikipedia.org/wiki/Close-mid_back_rounded_vowel) | a bit like 'oo' in "book"
u | [\[u\]](https://en.wikipedia.org/wiki/Close_back_rounded_vowel) | like 'ou' in "you"
b | [\[b\]](https://en.wikipedia.org/wiki/Voiced_bilabial_plosive) | like 'b' in "bee"
c | [\[t͡ʃ\]](https://en.wikipedia.org/wiki/Voiceless_postalveolar_affricate) | like 'ch' in "char"
d | [\[d\]](https://en.wikipedia.org/wiki/Voiced_dental_and_alveolar_plosives) | like 'd' in "do"
f | [\[f\]](https://en.wikipedia.org/wiki/Voiceless_labiodental_fricative) | like 'f' in "fair"
g | [\[g\]](https://en.wikipedia.org/wiki/Voiced_velar_plosive) | like 'g' in "go"
h | [\[h\]](https://en.wikipedia.org/wiki/Voiceless_glottal_fricative) | like 'h' in "hi"
j | [\[j\]](https://en.wikipedia.org/wiki/Voiced_palatal_approximant) | like 'y' in "you"
k | [\[k\]](https://en.wikipedia.org/wiki/Voiceless_velar_plosive) | like 'c' in "cow"
l | [\[l\]](https://en.wikipedia.org/wiki/Voiced_dental,_alveolar_and_postalveolar_lateral_approximants) | like 'l' in "lie"
m | [\[m\]](https://en.wikipedia.org/wiki/Voiced_bilabial_nasal) | like 'm' in "me"
n | [\[n\]](https://en.wikipedia.org/wiki/Voiced_dental,_alveolar_and_postalveolar_nasals#Alveolar) | like 'no' in "no"
p | [\[p\]](https://en.wikipedia.org/wiki/Voiceless_bilabial_plosive) | like 'p' in "pee"
r | [\[r\]](https://en.wikipedia.org/wiki/Voiced_alveolar_and_postalveolar_approximants#Postalveolar) | like 'r' in "red"
s | [\[s\]](https://en.wikipedia.org/wiki/Voiceless_alveolar_fricative) | like 's' in "so"
t | [\[t\]](https://en.wikipedia.org/wiki/Voiceless_dental_and_alveolar_plosives) | like 't' in "tea"
v | [\[v\]](https://en.wikipedia.org/wiki/Voiced_labiodental_fricative) | like 'v' in "vat"
w | [\[w\]](https://en.wikipedia.org/wiki/Voiced_labial%E2%80%93velar_approximant) | like 'w' in "way"
x | [\[ks\]](https://en.wikipedia.org/wiki/X) | like 'x' in "axe"
z | [\[ts\]](https://en.wikipedia.org/wiki/Z) | like 'tz' in "hertz"









