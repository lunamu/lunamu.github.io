---
layout: single
title: "Easy and correct way to write markdown on Blogger"
catorgries: Blogging
---


I'm only just started using blogger, but using markdown suddenly become the first obstacle on the road.

It took me half a day to explore different ways of writing markdown on Blogger. I've tried these methods already:

1. Use StackEdit or other online markdown editor, and use the built-in function to publish articles on Blogger.
2. Use StackEdit or other online markdown editor, then use their "Export to HTML" function to get the HTML source code of the document, then paste to Blogger.
3. Use MarkdownPad/Mou or other desktop markdown editor to write and edit, then copy & paste the HTML source code to Blogger.
4. Use Sublime Text 3 and markdown related packages (markdown review, etc.), then copy & paste the HTML source code to Blogger.

All of them failed in someway. Somehow I get different rendering result from the "previewed" version and the final blog, especially when syntax highlighting is involved in the document.

Finally I provided the way that do work with me: use *Atom* and the package *Markdown Preview*. The workflow looks like following:

1. Download and install [Atom](https://atom.io/).
2. Open Atom, press *ctrl+shift+p* (on windows), then input *ipat*, press enter to enter the *install package* screen.
3. Search for *Markdown Preview* and install the package.
4. While editing the *.md* file, press *ctrl+shift+p* and input *Markdown Preview*, choose to toggle the preview on.
5. Focus on the preview window, and right click.
6. Select "Save as HTML..." (Do not select the "Copy as HTML"), and select the filename and directory to save the file.
7. The HTML file will appear in Atom, select all the text and copy the HTML code.
8. Paste the code to Blogger, and it works like a charm.
