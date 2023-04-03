# Diff

Sync overleaf with github (or make a local copy)

1. python3 [latex-flatten.py](https://github.com/rekka/latex-flatten) main.tex main_flat_new.tex
2. [latexdiff](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents) main_flat.tex main_flat_new.tex > main_diff.tex
3. Compile main_diff.tex to get a pdf with all difefrences
