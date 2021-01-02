# Newcastle-BibTeX
A BibTeX template that ensures references follow [Newcastle University Guidelines](https://libguides.ncl.ac.uk/managing/harvard)
## Usage
* Add newcastle.bst to `local-texmf\bibtex\bst\` (Using MikTeX this would be in your data directory at `MiKTek\bibtex\bst\`)
* In your .tex file you must include:

  ```tex
  % Required to use \citep since Newcastle University requires (Name, Year) style
  \usepackage[comma]{natlib} 
  % Required for ccorrect url formatting
  \usepackage{url}
  
  \begin{document}
  ...
  
  \bibliography{BIBLIOGRAPHY} % Replace BIBLIOGRAPHY with name of your .bib file (without extension)
  \bibliographystyle{newcastle}
  
  \end{document}
  
  
  ```
