
# Changelog

### 5.2.0

- Renamed output file from `facts.tsv` to `notes.tsv`.
- Fixed "ü" being rendered as "u:" in vocabulary words.
- Wording improved for the cases where the "meaning" field gets patched, and also now patching instances of "same as..." that display an alternative to the main character.
- Pinyin column reduced to a single reading, the one that the Unihan documentation says is preferred for traditional writing. Sound column also reflects this change.

### 5.1.0

- Where the simplified variant was the same as the traditional character, it was removed.
- Some characters with more than one simplified variant now list all of them instead of just one.

### 5.0.0

- Added vocabulary hanzi and pinyin columns.
- Improved character sequence by adopting Gavin Grover's CJK Decomposition Data.

### 4.0.0

- Conflated characters:
    - 艷 (in Heisig & Richardson, frequency #3377) and 艶 (in TOCFL, not in freq. list) into 豔 (T, f#2553).
    - 啓 (H&R, no f.) into 啟 (T, f#962).
- As a result of the above, the character count was reduced by 3, and the sequence was altered.
- Added 'Variants' field, to make note of conflated characters.

### 3.0.0

- Output .tsv file had not been updated correctly! Oops. Order changed again, thus major-revision update.
- Some code improvements.

### 2.0.0

- Improved study order, by integrating data from `ids-analysis.txt`. Still not ideal in some cases, like as with the precedence of 肉 before 人.
- Fixed some wrong sound filenames.

### 1.0.0

- First public release.
