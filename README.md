# Cornish Spell-Checker

This is a spell-checker for the Cornish language. It uses word lists in the Standard Written Form that cover both Middle and Late Cornish combined. The spell-checker is based on Hunspell and but is also packaged for other applications that use the Hunspell framework, such as LibreOffice and Firefox.

## Scores

Current scores:
![](badge/test-total-words.svg)
![](badge/test-unique-words.svg)
![](badge/test-unique-noneng-words.svg)

Total word coverage weights words by their frequency in examples. Unique words coverage is just what score by unique spelling. Scores are out of 1000. The non-English percentage uses the Ubuntu Hunspell dictionary to exclude words that appear in English, since the sample includes people and company names that are common in English. 

# Install

The latest releases can be found in the [Releases](https://github.com/cornish-tools/cornish-spellchecker/releases) section.

## LibreOffice

- Ensure LibreOffice is installed.
- Find the [latest release](https://github.com/cornish-tools/cornish-spellchecker/releases).
- Download the LibreOffice OXT file.
- Double-click on that and the spell-checker will be installed into LibreOffice.

## Firefox

- Ensure Firefox is installed.
- Find the [latest release](https://github.com/cornish-tools/cornish-spellchecker/releases).
- Download the Mozilla XPI file.
- Double-click on that and the spell-checker will be installed into Firefox or drag the XPI file into Firefox.

## Thunderbird

Thunderbird is an email client. Instructions can be found on [their website](https://support.mozilla.org/en-US/kb/installing-addon-thunderbird#w_a-slightly-less-ideal-case-install-from-a-downloaded-xpi-file).

- Ensure Thunderbird is installed.
- Find the [latest release](https://github.com/cornish-tools/cornish-spellchecker/releases).
- Download the Mozilla XPI file.
- In Thunderbird, go to Settings &#x2699; > Dictionaries &#128213; > Manage Your Dictionaries &#x2699; > Install Add-on From File. Select the downloaded XPI file.

# Run

## Hunspell

A helpful tool is to use the `-m` flag to run morphological analysis:
* po - part of speech
* ds - cause of the affix

# Feedback

This is a maintained project. It will benefit from feedback on issues identified with the spell-checker, please [raise issues here](https://github.com/cornish-tools/cornish-spellchecker/issues).

# License

Copyright (c) 2023 Cornish Tools, Akademi Kernewek

The data herein is derived from the Akademi Kernewek word list provided by the Cornish Language Office, released under [Creative Commons Attribution NonCommercial](https://creativecommons.org/licenses/by-nc/4.0/). As such, this spell-checker is released under the same licence and without warranty:

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

# Bibliography

The majority of the word list is provided by the Akademi Kernewek. Additional materials were referenced to apply the rules of the language to the word list.

* An Outline of the Standard Written Form of Cornish. (2021). Third ed. [online] Cornwall: Akademi Kernewek. Available at: https://www.akademikernewek.org.uk/panels?locale=en [Accessed 13 Jul. 2023].
* Brown, W. (2001) *[A Grammar of Modern Cornish](https://kesva.org/publications/grammar-modern-cornish)*. Third ed. Saltash, Cornwall: Kesva an Taves Kernewek.
* Hak, T. (2019) *[Cornish Verbs in the Standard Written Form](https://kesva.org/publications/cornish-verbs)*. First ed. Hayle, Cornwall: Kesva an Taves Kernewek.
* Page, J. (2010) *[Cornish Grammar for Beginners](https://kesva.org/publications/cornish-grammar-beginners-and-auxiliary-verbs)*. Revised Standard Written Form ed. Hayle, Cornwall: Kesva an Taves Kernewek.
* Kernewek Dre Lyther. (2019). SWF ed. [online] Cornwall: Kesva an Taves Kernewek. Available at: https://kesva.org/kdl [Accessed 13 Jul. 2023].

All of the materials above use the Standard Written Form of Cornish with the exception of _A Grammar of Modern Cornish_ (2001).
