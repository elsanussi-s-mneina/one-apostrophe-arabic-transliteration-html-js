# The One Apostrophe Arabic Transliteration system project is abandoned.
As of March 19th, I abandon this project because I no longer see any useful development further of this transliteration system.

## Background on the Transliteration System:
The transliteration system is influenced roughly by how Arabic is represented in Anglophone countries (See the ALA-LC system) when written in Latin letters, 
but within the constraint of the letters used for English (no diacritics, limited to ASCII characters).
However, by design, it disagrees with the ALA-LC on its representation of the glottal stop and the voiceless pharyngeal fricative.

It has two innovations: 
- it uses an apostrophe after a Latin character instead of an underdot with the character. This was needed to fulfill the ASCII constraint.
- it uses a dash before "h" when "h" is not part of a digraph.
- it uses a dash then an apostrophe to represent a hamza (glottal stop).
- it uses a dash before "t" to represent taa marbutah.
- it uses a dash before "n" to represent nunation (dammatan, fathatan, kasratan).

## A quick summary of the transliteration system
Pronunciation of the Arabic alphabet with nunation in its usual order but written in the One Apostrophe Arabic Transliteration System:

-'alifu-n, baa'u-n, taa'u-n, thaa'u-n, jiimu-n, h'aa-'u-n, khaa-'u-n, daalu-n, dhaalu-n, raa-'u-n, zaynu-n, 
siinu-n, shiinu-n, s'aadu-n, d'aadu-n, t'aa-'u-n, z'aa-'u-n,
e'aynu-n, ghaynu-n, faa-'u-n, qaafu-n, kaafu-n, laamu-n, miimu-n, nuunu-n, -haa-'u-n, waawu-n, yaa-'u-n

(Note a dash is omitted if it is preceded by a space).

## What I like about the transliteration system.
1. It only requires ASCII characters. This makes it more useful in more situations.
2. It is most similar to English orthography in its digraphs, and at least resembles many systems of Arabic romanization used by anglophone readers.
3. As long as the dashes are used, it is fully unambiguous in pronunciation.

## What I dislike about the transliteration system.
1. The use of z' for ZAH (the letter before 'ain) does not accurately represent the standard pronunciation, but many other transliteration systems do this in order to avoid trigraphs.
2. The use of dashes to prevent ambiguity of digraphs from monographs is likely to be ignored by the general public if ever this system became popular. Thereby defeating the purpose of the system.
3. The use of dashes like this goes against Latin script norms. If we could use the interpunct or "punt volat" as used in Catalan, it would look better, but alas ASCII does not
 support that punctuatin symbol.
4. The use of the apostrophe both for emphatics and glottal stop does not sit well with me. I feel it puts a greater burden on the reader.

## Conclusions I came to before designing this transliteration system.
1. Creating and installing keyboard layouts will prevent adoption of any transliteration system that is not mandated by a nation state.
  - The system for creating keyboard layouts for multiple operating systems is fragmented, and needs standardization.
  - Therefore, only a system that could use a keyboard layout of an already existing popular language using the Latin script has any hope of replacing the Arabic chat alphabet.
2. The representation of the glottal stop and voiceless pharyngeal fricative is needlessly confusing, and designed from a non-Arabic perspective.
3. For this reason, the Arabic chat alphabet works better by using the numerals 2 and 3 respectively.
4. It is impossible to represent Arabic with the 26 characters of the Latin alphabet.
5. The use of capital letters for emphatics, and lowercase letters for non-emphatics can work, but breaks rules of Latin orthography.
6. The use of Arabic numerals to represent certain Arabic sounds can work, but breaks rules of Latin orthography.

## Conclusions I came to after designing this transliteration system.
1. Dashes should not be used to distinguish monographs from digraphs. It does not look right. Some other way must be found. Either a shorter kind of punctuation symbol.
2. The dash for TEH MARBUTEH was a good design.
3. The dash for TANWEEN was a reasonable design, but there is probably a better way.
4. Basing the consonant graphemes on English orthography was a poor design choice. The usual "sh", and "th" which get generalized to "dh", "kh", and "gh" for Arabic transliteration always comes at the cost of representing /h/ unambiguosly or finding systematic representations for the other consonants.

## Final Conclusion
We cannot represent Arabic using English-style digraphs accurately in ASCII without resorting to dashes and apostrophes.
The final result though readable is fairly ugly, and tricky to program.
If all the dashes were included everywhere even where there is no digraph ambiguity nearby, it is far easier to program.

This attempt fails for two reasons:
1. It is not more readable than the Arabic chat alphabet.
2. Although it does not use numerals as letters, its excessive need of dashes and apostrophes makes it seem just as chaotic.

For this reason I abandoned this system in search of a better system that ignores English conventions, but does not require a new keyboard layout.

March 19, 2021
Elsanussi Mneina

