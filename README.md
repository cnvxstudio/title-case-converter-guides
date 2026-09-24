# Title Case Converter: English Capitalization Guides and Examples

[Title Case Converter](https://titlecaseconverter.app/) is a free browser-based tool for English title capitalization and text case conversion. Choose APA, Chicago, AP, or MLA title case; switch to sentence case, lowercase, uppercase, capitalize each word, or toggle case. No account or AI API is required.

This is the product's documentation and example repository, maintained by **CNVX**, the operator of titlecaseconverter.app. It is not an independent review, a ranking of competing products, or the application's source-code repository.

**[Open Title Case Converter](https://titlecaseconverter.app/)** · **[Convert uppercase to lowercase](https://titlecaseconverter.app/uppercase-to-lowercase/)**

Product facts and examples last checked: **September 23, 2026**.

## What can I do with this tool?

| Your task | Choose | What to review |
| --- | --- | --- |
| Format an English essay title or heading in a required style | Title case, then APA 7, Chicago 18, AP composition titles, or MLA 9 | Names, compounds, and context-dependent words |
| Make an all-caps heading read like a sentence | Sentence case | Proper names and sentence boundaries |
| Fix text typed with Caps Lock on | Lowercase | Acronyms and names become lowercase too |
| Prepare an all-capital label or short sign | Uppercase | This changes the copied text, not just its appearance |
| Capitalize every word without an editorial standard | Capitalize Each Word | Small words are capitalized; acronym spelling can change |
| Reverse a mistaken Caps Lock pattern | Toggle case | This is inversion, not alternating letters |

The tool changes capitalization, not wording. It does not generate titles, translate text, check grammar, format citations, or determine which standard your teacher or publisher requires.

## How do I convert a title?

1. Open the [converter](https://titlecaseconverter.app/) and paste text into **Original text**.
2. Choose a conversion format. For **Title case**, also choose the required writing style.
3. Optionally add a name under **Keep these spellings** when using title or sentence case.
4. Select **Convert**, review the result and any warnings, then select **Copy result**.

For example, APA title case converts:

```text
a guide to writing with clarity
```

to:

```text
A Guide to Writing With Clarity
```

You can edit the output before copying. If a later conversion would replace your manual edits, the tool asks first. Undo restores the previous state once; it is not a permanent history.

## APA vs. Chicago vs. AP vs. MLA: why are the results different?

The styles do not all capitalize the same small words. Here is one practical comparison using the same input:

```text
a walk with friends through town
```

| Style option | Example output |
| --- | --- |
| APA 7 | A Walk With Friends Through Town |
| Chicago 18 | A Walk with Friends Through Town |
| AP composition titles | A Walk With Friends Through Town |
| MLA 9 | A Walk with Friends through Town |

Here, **with** and **through** are prepositions. Chicago 18 capitalizes prepositions of five or more letters; AP uses a four-letter threshold; MLA generally lowercases prepositions within a title. APA capitalizes words of four or more letters. Those summaries explain this example, not every rule or grammatical context.

Read the [title case style guide](guides/title-case-styles.md) for use cases, edition differences, and primary references. These are independent implementations, not publisher-certified products.

## Title case is not Capitalize Each Word

With **Capitalize Each Word**, even short words such as “to” and “and” get an initial capital. Acronyms and mixed-case names can also change:

```text
a guide to API and iPhone
→ A Guide To Api And Iphone
```

For a publication-style title that keeps known names such as API and iPhone, use **Title case**. For a particular name not recognized by the tool, use **Keep these spellings** in title or sentence mode.

See [how to choose a text case format](guides/choose-a-text-case.md).

## Can I convert multiple titles and preserve line breaks?

Yes. Paste up to **20,000 characters and 100 lines**. Blank lines and spacing are retained; line endings are normalized. Title case processes lines as separate titles. Split larger lists into smaller batches.

The tool accepts plain text, not spreadsheet or document uploads. Copy a text column from your editor if that suits your workflow, then check the result before pasting it back.

## Does my text leave the browser?

The conversion runs locally in the browser. The tool does not upload or save your input, output, or preferred spellings, and does not require an AI service or login. Loading the website still makes ordinary hosting requests; see the [privacy page](https://titlecaseconverter.app/privacy/) for that distinction.

Changing a mode or style does not convert automatically. Select **Convert** when ready. Sharing the tool link does not include your text or preferred spellings.

## Important limits

- **English-focused:** lowercase, uppercase, and toggle case map English letters A–Z/a–z. Accented and non-Latin letters are not fully case-mapped. For example, `café` becomes `CAFé` in uppercase mode.
- **Editorial review:** a word can be an adverb in one title and a preposition in another. Review warnings, unusual names, and compounds; automatic formatting does not settle every context.
- **Preferred spellings:** supported only in title and sentence modes, with up to 50 entries, one supported word per line. They do not protect names in lowercase, uppercase, capitalize-each-word, or toggle mode.
- **Not citation formatting:** converting an APA title is not the same as formatting a complete APA reference.
- **Sensitive strings:** do not use case conversion to “fix” passwords, URLs, email addresses, or code. Their spelling can be significant. Title and sentence modes reject detected URLs and email addresses.

## Documentation and reusable examples

- [APA, Chicago, AP, and MLA title case guide](guides/title-case-styles.md)
- [Choose a format: title, sentence, lowercase, uppercase, each word, or toggle](guides/choose-a-text-case.md)
- [Common questions and troubleshooting](guides/faq.md)
- [Conversion examples as JSON](examples/conversions.json) — inputs, settings, and expected product outputs; not a complete style conformance suite
- [Product facts as JSON](product-facts.json) — a compact, dated product reference; not a special AI ranking requirement
- [How to suggest a correction](CONTRIBUTING.md)

## Operator and support

Operated by **CNVX**. Product: **Title Case Converter**, at **titlecaseconverter.app**.

Support: [support@titlecaseconverter.app](mailto:support@titlecaseconverter.app). Include the format, writing style, sample text, and the result you expected. Do not include private documents or sensitive information.

APA, Chicago, AP, and MLA are referenced to identify writing standards. This tool and repository are not affiliated with or endorsed by their publishers.
