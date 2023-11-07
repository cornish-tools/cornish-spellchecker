# Cornish Spell-Checker

> [!NOTE]
> For Non-Commercial Use. See license below.

This is a spell-checker for the Cornish language. It uses word lists in the Standard Written Form that cover both Middle and Late Cornish combined. The spell-checker is based on Hunspell and but is also packaged for other applications that use the Hunspell framework: LibreOffice, Firefox and Thunderbird (email client).

The main part of the spell-checker is derived from the Akademi Kernewek word list provided by the Cornish Language Office. 

Thanks to the Cornish Language Office and Akademi Kernewek for their support in creating this spell-checker, particularly  to Sam Rogerson for his help and advice thoughout this project. Cornish Tools is not affiliated with either Cornish Language Office or Akademi Kernewek.

## Limitations

This spell-checker checks each word independently and does not check grammar. For example, the spell-checker can check whether a word is a valid mutation. For example, *kath* (cat) soft mutates *gath* so the spell-checker will report both words as correct. However, the spell-checker cannot tell whether the mutation is valid in the context of the sentence. For example, *an kath* and *an gath* (the cat) both have correctly spelled words so the spell-checker would report both as correct, but only *an gath* is gramatically correct.

> [!NOTE]
> The spell-checker is not complete, there is still coverage to improve (see the scores below). Some of the known gaps in coverage are listed [under issues](https://github.com/cornish-tools/cornish-spellchecker/issues). If you encounter an issue, please help us by [raising it here](https://github.com/cornish-tools/cornish-spellchecker/issues).

### Scores

Current scores:
![](badge/test-total-words.svg)
![](badge/test-unique-words.svg)
![](badge/test-unique-noneng-words.svg)

The scores show an approximation of the coverage of the spell-checker. They are calculated from sample text in Standard Written Form. The total word coverage is the proportion of words from the text that pass the spell-checker. The unique words coverage is the proportion of words that pass the spell-checker by unique spelling. The non-English percentage uses the Ubuntu Hunspell dictionary to exclude words that appear in English, since the sample includes people and company names that are common in English. Scores are out of 1000.

# Install

The latest releases can be found in the [Releases](https://github.com/cornish-tools/cornish-spellchecker/releases) section.

Note that, due to the licensing on this spell-checker (see below), it is not compatible with extension marketplaces so the packages need to be obtained here, from Github.

## LibreOffice

- Ensure LibreOffice is installed.
- Download the [latest](https://github.com/cornish-tools/cornish-spellchecker/releases) LibreOffice OXT file.
- Double-click on that and the spell-checker will be installed into LibreOffice.

## Firefox

- Ensure Firefox is installed.
- Download the [latest](https://github.com/cornish-tools/cornish-spellchecker/releases) Mozilla XPI file.
- Double-click on that and the spell-checker will be installed into Firefox or drag the XPI file into Firefox.

## Thunderbird

Thunderbird is an email client. Instructions can be found on [their website](https://support.mozilla.org/en-US/kb/installing-addon-thunderbird#w_a-slightly-less-ideal-case-install-from-a-downloaded-xpi-file).

- Ensure Thunderbird is installed.
- Download the [latest](https://github.com/cornish-tools/cornish-spellchecker/releases) Mozilla XPI file.
- In Thunderbird, go to Settings &#x2699; > Add-ons and Themes &#129513; > Drag the downloaded Mozilla XPI file into the Add-ons and Themes area.

(Alternatively, in the Add-ons and Themes area: go to Dictionaries &#128213; > Manage Your Dictionaries &#x2699; > Install Add-on From File. Select the downloaded XPI file.)

# License

Copyright (c) 2023 Cornish Tools, Akademi Kernewek

The main part of the spell-checker is derived from the Akademi Kernewek word list provided by the Cornish Language Office, released under Creative Commons Attribution NonCommercial 4.0. This spell-checker is released under the same license <https://creativecommons.org/licenses/by-nc/4.0/>.

# Bibliography

The majority of the word list is provided by the Akademi Kernewek. Additional materials were referenced to apply the rules of the language to the word list.

* An Outline of the Standard Written Form of Cornish. (2021). Third ed. [online] Cornwall: Akademi Kernewek. Available at: https://www.akademikernewek.org.uk/panels?locale=en [Accessed 13 Jul. 2023].
* Brown, W. (2001) *[A Grammar of Modern Cornish](https://kesva.org/publications/grammar-modern-cornish)*. Third ed. Saltash, Cornwall: Kesva an Taves Kernewek.
* Hak, T. (2019) *[Cornish Verbs in the Standard Written Form](https://kesva.org/publications/cornish-verbs)*. First ed. Hayle, Cornwall: Kesva an Taves Kernewek.
* Page, J. (2010) *[Cornish Grammar for Beginners](https://kesva.org/publications/cornish-grammar-beginners-and-auxiliary-verbs)*. Revised Standard Written Form ed. Hayle, Cornwall: Kesva an Taves Kernewek.
* Kernewek Dre Lyther. (2019). SWF ed. [online] Cornwall: Kesva an Taves Kernewek. Available at: https://kesva.org/kdl [Accessed 13 Jul. 2023].

All of the materials above use the Standard Written Form of Cornish with the exception of _A Grammar of Modern Cornish_ (2001).
