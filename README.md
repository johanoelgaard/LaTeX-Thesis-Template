# LaTeX-Thesis-Template
LaTeX Template for Thesis
This template comprises eleven sub-files with text rendered in the final document. The final document is rendered through \textbf{main.tex}, which inputs the eleven \textbf{.tex} files. As the document is created in the main.tex, one should not use begin{document} and end{document} in the sub-files. The rest of the \textbf{.tex} files in this template are filled with Lorem ipsum text to illustrate the visual form with text.

Further, there are two additional files. \textbf{packages.sty} and \textbf{zotero.bib}. The first is a package used to store packages used to render the final document. It currently has most packages you would need and allows for customizing spacing. It is recommended to take a look and see what packages are loaded.

The \textbf{.bib} file is used for citing. You can do a \textbf{textcite} \textcite{fischer_long-term_1977}; a \textbf{cite} \cite{calvo_staggered_1983}; or a \textbf{footcite}\footcite{taylor_staggered_1979}.

To properly use references, you need a \textbf{.bib} file. In this template, it is called \textbf{zotero.bib} and is created through the open source program \hyperlink{https://www.zotero.org/}{Zotero}. One's Zotero account can be connected directly to Overleaf, making it possible to pull the references directly from the Zotero library – this is recommended.
