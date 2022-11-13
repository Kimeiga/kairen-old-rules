# kairen

Kairen is a language with the goal to be intuitively understood by AI and people. The grammar is the important part, so the vocabulary is generated from English using simple rules that you can do in your head quickly. Here are they.

# Vocabulary

The vocab is generated from English in this manner

## Step 1: Write English phonetically

Write with vowels a, e, i, o, u. Remove double consonants.

## Step 2a: If Word is Multisyllabic

Switch syllable 1 with syllable 2, syllable 3 with syllable 4, syllable 5 with syllable 6, etc.

2 syllable examples:
- problem -> prablem -> blempra
- delete -> dilit -> litdi
- about -> abaut -> bauta

3 syllable examples:
- idea -> aidia -> diaia
- alternate -> alternat -> teralnat
- capital -> kapital -> pikatal

4 syllable examples: 
- Veronica -> veronika -> rovekani
- dictionary -> dikshaneri -> shandikrie
- calculator -> kalkyuleitor -> kyukaltorlei

## Step 2b: If Word is Unisyllabic

Depends on the structure of the word

### CVC

Switch the consonant in the beginning with the consonant in the end

2.1  
**C1 V C2 ->**  
**C2 V C1**

- bat -> tab
- cab -> kab -> bak
- yoke -> yok -> koy
- rad -> dar

works for diphthongs too, keep it in the same order.

**C1 V1V2 C2 ->**  
**C2 V1V2 C1**

- bike -> baik -> kaib
- name -> neim -> mein
- coil -> koil -> loik

### CCVCC

Keep the nasal consonants (r/l/m/n/ng) that are attached to the vowel in the same place, switch the other consonants instead and preserve their order.
This rule actually encompasses all the other rules.

2.2  
**C1 C2 (r/l) V1V2 (r/l/n/m/ng) C3 C4 ->**  
**C3 C4 (r/l) V1V2 (r/l/n/m/ng) C1 C2** 

- street -> strit -> st ri t -> t ri st -> trist
- bored -> bord -> b or d -> d or b -> dorb

If you have a nasal before and after the vowel, make sure to keep them both put. 

- clean -> klin -> k lin -> lin k -> link
- bring -> b ring -> ring b -> ringb -> rimb (brim)

(note, you might have noticed that bring -> rimb not ringyb

If this process produces something unpronounceable, add vowel **"y"** between the two consonants. This vowel "y" is pronounced /ɪ/ like the "i" in "sit" or "stick", as opposed to Kairen "i" which is pronounced /i/ like the "ee" in "keep" or "peak".


- spam -> 

Remember, if the nasal consonant is alone then rule 2.1 applies and you just switch it with the other consonant normally.
ex.
- rake -> reik -> r ei k -> k ei r -> keir
- break -> breik -> b rei k -> k rei b -> kreib 

When you have n/m after the vowel, and the translated word has n + b or m + t/k, switch to m + b or n + t/k for ease of pronunciation.

- band -> b an d -> d an b -> danb -> damb
- punk -> pank -> p an k -> k an p -> kanp -> kamp
- 

## Set words
- I = ki
- Eye = ao
- You = vu
- too = ve (ut = to, "ve" from "very")
- a/an = nu 

### Set words for words that normally translate into themselves
Ex: clock -> klak, so we need a set word to make it different from the base English word
- clock = tokei 
- since = ijo

# Grammar

### Articles (both indefinite and definite) are optional.

- The horse is on top of the ground.
- adh sorh zi na pat va adh draung.
- sorhy zi na pat va draung.

### "to" is optional if the verb only has one argument ("go to" -> "go")

- They will drive to their friend's house.
- eidh vraid a ut erth dremf o sauh.
- eidh vraid a erth dremf o sauh.

### e = (previous verb is) past tense (-ed)

- I went to the store.
- I go (-ed) to the store
- ki og e ut orst.
- ki og e orst.



### a = (previous verb is) future tense

- You will find it difficult.
- You find (future) it difficult.
- Vu daimf a ti fidikalt.

### i = (previous verb is) present continuous tense (-ing)

- She is eating a sandwich.
- She is eat -ing a sandwich.
- Ish zi ti i na chiwdans


u = (previous word is) plural
o = 's
ka = sentence final particle for yes/no question
