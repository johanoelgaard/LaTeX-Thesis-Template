# LaTeX-Thesis-Template
This template was created by Johan Ølgaard and comprises eleven sub-files with text rendered in the final document. The final document is rendered through **main.tex**, which inputs the eleven **.tex** files. As the document is created in the main.tex, one should not use begin{document} and end{document} in the sub-files. The **.tex** files in this template are filled with Lorem ipsum text to illustrate the visual form with text.

Further, there are two additional files. **packages.sty** and **zotero.bib**. The first is a package that stores packages used to render the final document. It currently has most packages you would need and allows for customising spacing. It is recommended to take a look and see what packages are loaded.

The **.bib** file is used for citing. You can do a **textcite** \textcite{fischer_long-term_1977}; a **cite** \cite{calvo_staggered_1983}; or a **footcite** \footcite{taylor_staggered_1979}. See the begnning how the introduction for how these looks.

To properly use references, you need a **.bib** file. In this template, it is called **zotero.bib** and is created through the open-source program [Zotero](https://www.zotero.org/). One's Zotero account can be connected directly to Overleaf, making it possible to pull the references directly from the Zotero library – this is recommended.
