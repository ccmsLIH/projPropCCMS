SAP folder

Go to 02-Process\Programs\ and run the R script "DocumentCreation_Git.R" 
in order to create an Statistical Analysis Plan in Rmarkdown and word.

For citation in rmarkdown, a bib TeX file is needed in the same folder as the rmarkdown file. 
In EndNote go to File --> Export --> Choose File name "*.bib" --> Save as type "Text file (*.txt)
--> Output style: Bib TeX Export --> save

in rmarkdown add "bibliography: *.bib" in header and
use [@RN] and the according number to cite in text