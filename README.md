
# Nikhil Kaza's Academic CV

## Enhancements Compared to the default `vitae` package:

* This is a fork of  [JooYoung Seo's CV repository](https://github.com/jooyoungseo/jy_CV)
* Modified the awesome-cv.cls slightly 
* Removed the list numbering for publications.
* Focusing on updating the cv using csvs and bib files.
* I only relied on "cv entries" of the "vitae" pacakge minimally. I found relying on more descriptive column names in data files more useful. Feel free to adapt the code as necessary. 
* Styling your publications using given csl file in `YAML`.
* Printing as many bibliographic sections and corresponding entries as you want in your CV (e.g., journal publication, conference proceedings, software developments, etc. etc.).
* Highlighting your name in printed bib entries using bold format (see and change the content in `lua/strong.lua`).
* Easily managing your CV following `bookdown` style (e.g., each separate Rmd file according to their own categories like chapters).



## Descriptions

This repo has been created to systematically manage my academic CV. This is reproducible for those who have basic knowledge of R and R Markdown.

## Known Issues

- The CV is formatted using awesomecv.cls. As such it is focused on generating a pdf. In the near future, I want to make this output format independent (or at least generate html, docx in addition). Some hardcoded Latex tags need to be amended (especially in xtable code)

- On the previous note, "&" in any of data creates a problem because of extensive use of tabular format in the formatting. At the moment, the workaround is to replace it with "and". (e.g. Environmental Science & Technology vs. Environmental Science and Technology). I need to figure out how to sanitize the text in different output formats. xtable should handle this. 


