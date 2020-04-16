# wealthreport

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

Contains the R Markdown code for the Wealth and Assets in Scotland 2006-2018 report at [http://www.wealthandassets.scot/2020report.html](http://www.wealthandassets.scot/2020report.html).

Files:
- WealthUpdate_tidycode.Rproj (R project file)
- 2020report.Rmd (main Rmd file which calls the chapter files)
- _chapter0.Rmd (introduction text)
- _chapter1.Rmd (Chapter 1)
- _chapter2.Rmd (Chapter 2)
- _chapter3.Rmd (Chapter 3)
- _chapter4.Rmd (Chapter 4)
- _chapter5.Rmd (Chapter 5)
- _chapter6.Rmd (Chapter 6)
- _site.yml (file that organised this and other html files into the website www.wealthandassets.scot)


Notes:
- the datasets required to produce the charts and tables are not included in this repository
- the logo is also not included in this repository
- when building the website, the main file (2020report.Rmd) needed to be renamed to index.Rmd, although this is not required when knitting to html.
