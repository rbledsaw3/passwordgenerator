# passwordgenerator

Utilizes random.org's TRNG and a combined wordlist of 1,466,238 unique european words to generate passphrases. The small version of the wordlist contains 144,889 words that are 3 to 6 characters long.

## Languages

This script uses a unique list of words from American, British, and Canadian English, Spanish, Italian, Portuguese, Ecclesial Latin, French, and Swedish. All utf8 and iso-8859-15 encoded characters have been transliterated to a simple ASCII equivalent.

## Usage

To use, simply run:

```bash
./pphgen n
```

or

```bash
./pphgensmall n
```

where *n* is the number of words you wish to have in your passphrase.
