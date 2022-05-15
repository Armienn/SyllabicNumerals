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

Letter | IPA | description
--|--|--
a | a | a
e | a | a
i | a | a
o | a | a
u | a | a
b | a | a
c | a | a
d | a | a
f | a | a
g | a | a
h | a | a
j | a | a
k | a | a
l | a | a
m | a | a
n | a | a
p | a | a
r | a | a
s | a | a
t | a | a
v | a | a
w | a | a
x | a | a
z | a | a
