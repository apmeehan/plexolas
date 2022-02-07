# Plexolas
A coding font based on Consolas, with a touch of [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono).


## Features

* All font variants (regular/italic/bold/bold-italic) have slightly thinner weights
* The cursive style of the italic lower-case `l` has been made more consistent with the other characters (such as `i`), by shortening its lower serif and giving it an upper serif
* Uses the following symbols from Plex Mono: `?`, `{`, `}`, `<`, `>`

|                | COMPARISON |
|----------------|:----------:|
| **Italic 'L'** | ![](/images/comparison-ls.gif)      |
| **Symbols**    | ![](/images/comparison-symbols.gif) |
| **All**        | ![](/images/comparison.gif) |


## Why

I'm a big fan of Consolas, for its readability, lovely subtly cursive italics, and its highly-distinguishable punctuation marks such as commas and backticks. But a few things have always bugged me:
- The slightly thicker weight compared to other similar typefaces
- That italic `l` is an eyesore
- Its question-mark is unnecessarily stylised
- Its curly brackets aren't so easy to distinguish from the round ones, compared to other typefaces

And while personally I don't find Plex Mono quite as effortlessly readable as Consolas, I do love its style, weight and [heritage](https://www.ibm.com/ibm/history/ibm100/us/en/icons/selectric/), and actively prefer many of its symbols (such as its no-nonsense question-mark and extra-curly curly brackets).

So Plexolas is basically an attempt to have my cake and eat it.


## Possible future updates

* Fix the global character sizing (on Macs, the sizing of Consolas seems a bit off compared to most other fonts, such that to look comparable to other fonts at `fontSize: 13` and `lineHeight: 1.5`, Plexolas needs to be set at `fontSize: 14` and `lineHeight: 1.4`)
* Add more of the symbols
* Would like to have a go at actually redesigning the letters so that rather than just being "Consolas but thinner and with a few borrowed symbols", it would look more like an actual "Plex + Consolas" hybrid (eg "Plex + the readability of Consolas" somehow)