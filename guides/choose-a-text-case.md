# Title Case vs. Sentence Case vs. Uppercase and Lowercase

The right conversion depends on the result you need. A publication title, a sentence-like heading, and an all-caps label are different tasks. This guide uses the six formats available in [Title Case Converter](https://titlecaseconverter.app/), maintained by CNVX.

## Title case: follow a writing standard

For an essay title, book title, or editorial heading, choose **Title case**, then the required APA, Chicago, AP, or MLA option. Small words are handled by the selected standard instead of all being capitalized mechanically.

For APA:

```text
a guide to writing with clarity
→ A Guide to Writing With Clarity
```

This changes capitalization only. It does not improve the wording of a title or validate an entire citation. See the [four-style guide](title-case-styles.md).

## Sentence case: make a heading read like a sentence

Use sentence case when a slide heading, interface label, or short paragraph should look like a sentence rather than a book title.

```text
A GUIDE TO WRITING. START HERE.
→ A guide to writing. Start here.
```

The product treats each line as a new heading and also capitalizes after sentence-ending punctuation and a colon. Known names and preferred spellings are protected. This is a practical heading-oriented implementation, not a universal sentence parser. Check personal names, abbreviations, initials, and unusual punctuation.

## Uppercase to lowercase: fix Caps Lock text

Use the [uppercase-to-lowercase converter](https://titlecaseconverter.app/uppercase-to-lowercase/) when a workflow requires all English letters to be lowercase.

```text
HELLO iPhone API!
→ hello iphone api!
```

Names and acronyms change too. Numbers, spaces, punctuation, and blank lines remain. Line endings are normalized. Accented letters are not case-mapped: `ÉCOLE` becomes `École`.

This is useful for plain-text labels and Caps Lock mistakes. It is not a safe normalization step for case-sensitive code, credentials, addresses, or URLs.

## Uppercase: produce all-capital text

Use uppercase for a short sign, label, or heading whose design requires all-capital English letters.

```text
Hello iPhone API!
→ HELLO IPHONE API!
```

This changes the text you copy. If you are styling a website and want only its appearance to change, CSS styling is a different solution. This tool does not fully uppercase every language: `café` becomes `CAFé`.

## Capitalize Each Word: a display format, not a style guide

Choose this when every English word should begin with a capital regardless of grammar. Hyphen-separated parts are handled separately.

```text
a guide to API and iPhone
→ A Guide To Api And Iphone
```

“To” and “And” receive capitals, and API/iPhone spelling changes. Preferred spellings are not applied in this mode. Use title case if you need an editorial standard and protected name spellings.

## Toggle case: reverse the existing pattern

Choose toggle to make lowercase English letters uppercase and uppercase letters lowercase.

```text
hELLO wORLD!
→ Hello World!
```

Toggle does not create an alternating `aLtErNaTiNg` pattern. Applying it twice restores the original English-letter capitalization, although the tool still normalizes line endings.

## Keep a brand name exactly as written

In **title case or sentence case**, enter a preferred spelling under **Keep these spellings**, one supported word per line. For example, enter `zetaCloud` and use APA title case:

```text
a guide to zetaCloud
→ A Guide to zetaCloud
```

Up to 50 entries are supported. Each entry must fit the supported one-word format; this is not a multiword find-and-replace dictionary. A preferred spelling overrides the style rule, so use it deliberately.

## What happens when I switch modes?

Changing a format or style marks the old output as needing conversion. It does not silently replace it. Select **Convert** to apply the new setting. If you manually edited the result, you can cancel replacement or accept it; **Undo** can restore the previous state once.

**[Open the converter](https://titlecaseconverter.app/)** · [Common questions](faq.md) · [Back to the documentation](../README.md)
