![Logo](/release/marquee.png)
## LiuChan Chinese Popup Dictionary
LiuChan (*liú chàng*) is an extension for chrome that allows you to mouse-over Chinese to instantly lookup the dictionary.

It started out as a port of RikaiChan (and its Rikai derivatives) and has since grown into an extension that holds its own with new features and improved performance.

### Current Features 

* Instantaneous translation of Chinese characters and words on mouse over
* Synchronized settings across all your devices
* Text input support
* A handy little notepad that you can open on any page :)
* Theme support
* Fuzzy search! Use chrome's omnibox to search the dictionary using hanzi, pinyin or just plain english
* Cantonese support (v1.1.6)

### Usage

**Mouse Over Dictionary:** Simply enable the extension and mouse over Chinese on a page!

**Fuzzy search:** Type 'lc' in the omnibox followed by whatever term you want to look for (Chinese, pinyin or English), the results will show up as suggestions.

### To Do

- [ ] Add word lists/Anki support
- [ ] Move fuzzy search to its own input box as opposed to omnibox so that it can be expanded upon (eg. use rich formatting, etc)
- [x] Improve performance
- [x] Improve fuzzy search to match regular vowels with tonemarked pinyin
- [x] Update CEDICT
- [ ] Add missing Cantonese pronunciations (this may be automated, but can lead to inaccurate entries).
- [ ] Consolidate definitions (some entries have overlapping definitions; in many cases these can be combined).
- [ ] Support for Yale Cantonese romanisation.
- [ ] Rewrite non-default themes to adapt to Cantonese support.
- [ ] Decrease memory use by means of a proper, accurate implementation of traditional -> simplified conversion method.

### Why is it called LiuChan?

流畅 (*liú chàng*) stands for fluency in a language. I kept -Chan as an homage to its origin.

### Troubleshooting

If anything malfunctions, your best bet is disabling and re-enabling the extension and reloading the page you want it to work on.

In case a problem persists please open an issue on github and try to describe as clearly as possible how to recreate the problem.

#### Known issues:

- Currently fuzzy search isn't 'fuzzy' enough to match regular vowels with tonemarked ones.
- Some Cantonese pronunciations missing.