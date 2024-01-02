# QuartoReport
Template to make a quarto document that makes interactive plots from Perseus files.

## Instructions

1) Download either the quarto (.qmd) or RMarkdown (.rmd) file.
2) Open the file and edit project-specific information:
       a) Put the file path of the Perseus report inside quotation marks after PerseusR::read.perseus on line 68.
       b) Put the user's last namne (the name in the raw file) inside quotation marks after user_name on line 74.
       c) Put the work order number inside quotation marks after  work_order on line 75.
3) Press the dropdown arrow next to "Knit" and select "Knit to HTML".
