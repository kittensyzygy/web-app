---
title: Formatting Guide
parent:
  title: Documentation
  href: '/documentation'
---

Definitions on *Self-Defined* are formatted using the markup language Markdown. This is pretty easy to use. The version of Markdown used on *Self-Defined* is a simplified form of [CommonMark](https://commonmark.org/help/).

## Table of content

* [Formatting](#)
  * [Paragraphs](#)
  * [Styling text](#)
  * [Subheadings](#)
  * [Links](#)
  * [Lists](#)
* [Ignoring Markdown formatting](#)
* [Troubleshooting](#)
* [Resources](#)

## Formatting

These are the Markdown annotations you'll likely need when formatting content for the dictionary:

## Paragraphs

There isn't a special annotiation for paragraphs. However, to distinguish paragraphs from each other, you need one blank line between them. When writing a definition, your code will look like this, for instance:

```
This is the first paragraph. It's followed by one blank line to separate it from the next paragraph.

This is the second paragraph. There is a blank line before it to separate it from the previous paragraph.
```

## Styling text

### Italics

Type one asterisk `*` on either side of the text you want to italicise.

Type this: | ... to get this:
--------------|-----------------
`*This is italic*` | *This is italic*

### Bold

Type two asterisks `**` on either side of the text you want to make bold.

Type this: | ... to get this:
--------------|-----------------
`**This is bold**` | **This is bold**


## Subheadings

You might want to use subheadings in a definition, like *Issues*, *Impact*, *Usage tips*. To format text as a subheading, type two hash symbols and a space `## ` before the text. There also needs to be a blank line before and after the subheading to make it render properly. For example:

```

## Usage tips

```

## Links

Type square brackets `[]` around words you want to be links. Immediately after the closing square bracket `]`, insert the link URL wrapped in round-brackets `()`. Note, there is no space between the closing square bracket and the opening round bracket: `](`.

Type this: | ... to get this:
-----------|----------------
`[Self-Defined](https://www.selfdefined.app)` | [Self-Defined](https://www.selfdefined.app)

If you are linking to a page within the *Self-Defined* site, you can link to it using its shorter, relative URL (i.e., missing of the start of the absolute URL). For example:

Type this: | ... to get this:
-----------|----------------
`[Polyamory](/definitions/polyamory)` | [Polyamory](/definitions/polyamory)

To reiterate, when linking to a page within the *Self-Defined* site, you can miss off the start of the URL — i.e., you can miss off `https://www.selfdefined.app`.

## Lists

For any list, you need a blank line before and after the list to make it render properly.

### Unordered lists

An unordered list is a list with bullet points. Type an asterisk and space `* ` before each list item, and put each list item on its own line.

**Type this**:

```

* List item
* List item
* List item

```

... **to get this**:

* List item
* List item
* List item

### Ordered lists

For each list item, type its number followed by a full-stop/period. Each item needs to be on its own line.

**Type this**:

```

1. First list item
2. Second list item
3. Third list item

```

... **to get this**:

1. First list item
2. Second list item
3. Third list item

## Ignoring Markdown formatting

To format text, Markdown uses symbols that have different meanings in other contexts. For example, the hash symbol `#` is used to format headings in Markdown, but outside of Markdown it has other uses: among other things, it's sometimes used to mean "number" or is used to make hashtags on social media. Occasionally, you might write a symbol and Markdown will confuse it for a formatting annotation. If this occurs, you might be able to make Markdown "ignore" the symbol. To do this, type a backslash `\` before the symbol you want Markdown to ignore. For example:

Type this: | ... to get this:
--------------|-----------------
`\* This has an asterisk before it, not a bullet point.` | \* This has an asterisk before it, not a bullet point.

You can use this "backslash escape" to, ignore formatting, on the following symbols:

Symbol | Name
-------|------
\ | backslash
\` | backtick
\* | asterisk
_ | underscore
{} | curly braces
\[] | square brackets
() | round brackets/parentheses
\# | hash mark
\+ | plus sign
\- | minus sign (hyphen)
. | dot
! | exclamation mark

## Troubleshooting

When trying to add or update a page on the site, you might encounter an error message if the formatting is not right. For example, if you don't include a blank line before a list, you will receive an error message like this: "MD032 - Lists should be surrounded by blank lines". The error message might give you enough information to correct the problem; otherwise, you can check for the error code in this [list of Markdown lint-tool rules](https://github.com/markdownlint/markdownlint/blob/master/docs/RULES.md)* and read the information there. If you're still having trouble, ask for help in the [Slack group](https://join.slack.com/t/selfdefined/shared_invite/zt-fczgm8b6-8ZZgHvLutNDXo~NjwaL7Iw).

\* A lint tool check to see if code in a file is written correctly. It's useful to help developers find and correct errors before a webpage is made public.

## Resources

This guide should help you write definitions for *Self-Described*. However, should you want to know more about Markdown, see the following resources:

* [CommonMark website](https://commonmark.org/)
  * [Learn Markdown in 60 seconds](https://commonmark.org/help/)
  * [Ten minute Markdown tutorial](https://commonmark.org/help/tutorial/)
* GitHub's [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* GitHub's [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
* John Gruber's [Markdown](https://daringfireball.net/projects/markdown/) guide (John invented Markdown with Aaron Swartz)
