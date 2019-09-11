## OVERVIEW

### Philosophy

Markdown is intended to be easy-to-read and easy-to-write as is feasible.

Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text. 

Markdown's syntax is comprised entirely of punctuation characters, which punctuation characters have been carefully chosen so as to look like what they mean.

### Inline HTML

Markdown's syntax is intended for one purpose: to be used as a format for writing for the web.

Markdown is not a replacement for HTML, or even close to it. HTML is a publishing format; Markdown is a writing format. 

Markdown's syntax is very small, corresponding only to a very small subset of HTML tags. For any markup that is not covered by Markdown's syntax, you simply use HTML itself. 

The only restrications are that block-level HTML elements must be separated from surrounding content by blank lines, and the start and end tags of the block should not be indented with tabs or spaces.

Note that Markdown formatting syntax is not processed within block-level HTML tags. That is, you can't use Markdown-style inside an HTML block. Unlike block-level HTML tags, Markdown syntax is processed within span-level tags.

### Automatic Escaping for Specail Characters

In HTML, there are two characters that demand special treatment: < and &. Markdown allows to use these characters naturally, taking care of all the necessary escaping for you.


## [SYNTAX](syntax.md)

### Block Elements

* Paragraphs and Line Breaks
* Headers
* Blockquotes
* Lists
* Code Blocks
* Horizontal Rules
* Task lists

### Span Elements

* Emphasis
* Code
* Links
* Images

### Miscelaneous

* Backslash Escapes
* Automatic Links


## [STYLE GUIDE](style_guide.md)

Much of what makes Markdown great is the ability to write plain text, and get great formatted output as a result.

We seek to balance three goals:

1. Source text is readable and portable.
2. Markdown files are maintainable over time and across teams.
3. The syntax is simple and easy to remember.


## SEE ALSO

* https://daringfireball.net/projects/markdown/syntax
* https://www.markdownguide.org/basic-syntax
* https://www.markdownguide.org/extended-syntax
* https://github.com/google/styleguide/blob/gh-pages/docguide/style.md
* https://spec.commonmark.org/
