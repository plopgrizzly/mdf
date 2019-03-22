# Document Format (.df)
Document format is based on Markdown, but with the intent of having all the functionality of a
webpage.

Lets say we are making a webpage:
```md
My Website's Title (In Titlebar)
================================

My Webpage's Title (On Page)
--------------------------------

# Section Heading (Biggest heading)
## Section Subheading
### Mini-Section Heading
#### Mini-Section Subheading (Smallest heading)
This is a paragraph.  Links work differently than in MarkDown:

:plopgrizzly.com/main.df
[Link/Clickable Text]:plopgrizzly.com/main.df
{Image Alt Text}:url/to/image.svg
[{Link Image Alt Text}:url/to/image.svg]:plopgrizzly.com/main.df
[Button that runs a function when clicked]:{
    // Nahar Function Code.
}
{Something that runs a function right before it's shown}:{
    // Nahar Function Code.
}

Title of next page (Optional for Pagebreak)
===========================================

Here's a table:
| # Column Heading | # Column Heading |
| Paragraph        | Paragraph        |
| Paragraph        | Paragraph        |
| Paragraph        | Paragraph        |

`unsyntaxhighlighted_code`
``rust rust_syntax_highlighted_code``
``nahar
nahar_syntax_highlighted_code
``
````_nahar
// This will make an executable code block (2 or more backticks to open/close).
````

__italic__
**bold**

You can escape markdown syntax with a `\`: \# \[ \*.  Horizontal rule (2 or more -):
==
--
~~
== A thick horizontal rule with text in the middle of it ==
-- A thin horizontal rule with text in the middle of it --
~~ A fancy horizontal rule with text in the middle of it  ~~

. An ordered list
. Item 2

; An unordered list.
; Item 2

[# Centered Section Heading ?c]
[Centered Paragraph. ?c]
[Centered Image !image.svg ?c]

Escaping different syntaxes (only needed after newline):
\| | |
\#
\##
\###
\####
\.
\;
\==
\===
\--
\---
\~~
\~~~

Escaping different syntaxes (always needed):
\[]
\{}
\`
\``
\__
\**
\\
```

# Markdown Document Format (.mdf)

