## Paragraphs
To create paragraphs, use a blank line to separate one or more lines of text. You should not indent paragraphs
with spaces or tabs.

## Line Breaks
To create a line break, end a line with two or more spaces, and then type return.

## Headings
To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. 

### Alternate Syntax
Alternatively, on the line below the text, add any number of equal sign (=) for heading level 1 or hyphens (-) for heading level 2.

## Blockquotes
To create a blockquote, add a right angle bracket (>) in front of a paragraph.

### Blockquotes with Multiple Paragraphs
Blockquotes can contain multiple paragraphs. Add > on the blank lines between the paragraphs.
### Nested Blockquotes
Blockquotes can be nested. Add >> in front of the paragraph you want to nest.
### Blockquotes with Other Elements
Blockquotes can contain other Markdown formatted elements. Not all elements can be used -- you'll need to experiment to see which ones work.

## Lists
You can organize items into ordered and unordered lists.

### Unordered Lists
To create an unordered list, add hyphens (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.
### Ordered Lists
To create an ordered list, add line items with numbers followed by one or more spaces and a dot (.). The numbers don't have to be in numerical order. You should start with the number one, as Markdown may support starting ordered lists at an arbitrary number at some point in the future.
### Adding Elements in Lists
To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab.

## Task Lists
Task lists allow you to create a list of items with checkboxes. To create a task list, add hyphen (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

## Code
To denote a word or phrase as code, enclose it in tick marks (\`).

### Escaping Tick Marks
If the word or phrase you want to denote as code includes one or more tick marks, you can escape it by enclosing the word or phrase in double tick marks.
### Code Blocks
To create code blocks, indent every line of the block by at lease four spaces or one tab. When they're in a list, indent them eight spaces or two tabs.
### Fenced Code Blocks
Depending on your Markdown processor or editer, you can use three tick marks (\`\`\`) or three tildes (\~\~\~) on the lines before and after the code block. 
### Syntax Highlighting
This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the tick marks before the fenced code block.

## Horizontal Rules
To create a horizontal rule, use three or more asterisks (*), hyphens(-), or underscores (_) on a line by themselves.

## Tables
To add a table, use three or more hyphens to create each column's header, and use pipes (|) to separate each column. You can optionally add pipes on either end of the table. Cell widths can vary, the rendered output will look the same.

### Alignment
You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.
### Formatting Text in Tables
You can format the text within tables. For example, you can add links, code (words or phrases in tick marks (\`) only, not code blocks), and emphasis. But you can't add headings, blockquotes, lists, horizontal rules, images, or HTML tags.
### Escaping Pipe Characters in Tables
You can display a pipe (|) character in a table by using its HTML character code (`&#124;`).

## Emphasis
You can add emphasis by making text bold or italic.

### Bold
To bold text, add two asterisks or underscores before and after a world or phrase. To bold the middle of a world for emphasis, add two asterisks without spaces around the letters.
### Italic
To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.
### Bold and Italic
To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.
### Strikethrough
You can "strikethrough" words by putting a horizontal line through the center of them. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols (~~) before and after the words.

## Links
To create a link, enclose the link text in brackets and then follow it immediately with the URL in parentheses.

### Adding Titles
You can optionally add a title for a link. This will appear as a tootip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.
### URLS and Email Addresses
To quickly turn a URL or email address into a link, enclose it in angle brackets.
### Automatic URL Linking
Many Markdown processors auto matically turn URLs into links even though you haven't used brackets.
### Reference-style Links
Reference-style links are a special kind of link that make URLs easier to display and read in Markdown. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file to keep the text easy to read.

1. Formatting the First Part of the Link

	The first part of a reference-style link is formatted with two sets of brackets. The first set of brackets surrounds the text that should appear linked. The second set of branckets display a lable used to point to the link you're storing elsewhere in your document.

	Althought not required, you can include a space between the first and second set of branckets. Also, the label in the second set of brackets is not case sensitive and can include letters, numbers, spaces, or punctuation.
2. Formatting the Second Part of the Link

	The second part of a reference-style link is formatted with the following attributes:
	* The label, in brackets, followed immediately by a colon and at least one space.
	* The URL for the link, which you can optionally enclose in angle brackets.
	* The optional title for the link, which you can enclose in double quotes, single quotes, or parentheses.

	You can place this second part of the link anywhere in your Markdown document.

## Images
To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.

### Linking Images
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

## Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\\) in front of the character.

### Characters You can Escape
You can uses a backslash to escape the following characters.

| Character | Name |
| ---       | ---  |
| \\ | backslash |
| \` | tick mark |
| \* | asterisk |
| \_ | underscore |
| \{\} | curly braces |
| \[\] | brackets |
| \(\) | parentheses |
| \# | pound sign |
| \+ | plus sign |
| \- | minus sign (hyphen) |
| \. | dot |
| \! | exclamation mark |
| \| | pipe |

## Footnotes
Footnotes allow you to add notes and references without cluttering the body of the document. When you create a footnote, a superscript number with a link appears where you added the footnote reference. Readers can click the link to jump to the content of the footnote at the bottom of the page.

To create a footnote reference, add a caret and an identifier inside brackets ([^1]). Identifiers can be numbers or words, but they can't contain spaces or tabs. Identifiers only correlate the footnote reference with the footnote itself —— in the output, footnotes are numbered sequentially.

Add the footnote using another caret and number inside brackets with a colon and text ([^1]:My footnote.). You don't have to put footnotes at the end of the document. You can put them anywhere except inside other elements like lists, block quotes, and tables.