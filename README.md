# easyMarkdown.js

## A simple on-the-fly markdown parser/converter

### by Robert Hieger

This repository contains my audacious attempt at writing my first simple
JavaScript library to convert Markdown on-the-fly to standards-compliant
HTML5 elements.

This will be a slow-burner learning project for me. I envision the flow
of data in the following way:

1. Use a standard HTML5 skeleton document to which the developer adds
all needed information to the document header.

2. An app.js script linked to the HTML file.

3. Function calls to the library that will read in the source Markdown
file, parse it line by line, converting the Markdown syntax to matching
HTML5 elements.

4. Append these elements to the existing Document Object Model (DOM).

For further information, consult the [Wiki]().