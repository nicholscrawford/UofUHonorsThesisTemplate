# University of Utah Honors Thesis Template
Unofficial LaTeX Template for University of Utah Honors Thesis.

When making this, I tried to follow the format as closely as possible visually. You may need to adjust things, since some of the spacing is done manually. This might be somewhat hard to do if you aren't familiar with LaTeX.

As a note, I only did formatting for:
* Chapter
* Section
* Subsection

So for something like a subsubsection or otherwise, you may need to do some additional leg work.

I made some design decision with the sections and subsections, which aren't specified as part of the formatting.
Personally, I think if you're using sections and subsections, you should do numbering, since it more clearly conveys the level of depth. It's a bit hard when we're avoiding font size changes/bolding, but I think either option should be functional.

## If you aren't familiar with LaTeX
The simplest way to use this template is to upload these files to overleaf, or to find them in the templates gallery. From there, look in the main.tex file and each place where you need to change things is noted. 

For better organization, my reference.bib file is created from my Zotero library, and it's linked directly so I can just add items to my library and then cite them in the text. Additionally, I have many of my sections in seperate .tex files, so they aren't all in one megafile. You can do this by creating a new file, say introduction.tex, and then where you want it in the thesis write `\input{introduction.tex}`. 

Created by: A. Nichols Crawford Taylor, March, 2024. a.nichols.taylor@gmail.com
