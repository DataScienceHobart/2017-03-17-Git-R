# 2017-03-17-Git-R

Git, GitHub, and R

Wondering what this Git thing is?   https://www.rstudio.com/resources/videos/happy-git-and-gihub-for-the-user-tutorial/

## Getting Help

Local

* Data Science Hobart https://twitter.com/DataScienceHbt, https://datasciencehobart.github.io/  
* R Ladies Hobart https://twitter.com/hashtag/RLadiesHobart?src=hash
* Gentle R http://australianantarcticdatacentre.github.io/GentleR/About/
* HRUG Hobart R Users Group https://www.meetup.com/Hobart-R-Users-Group/


Worldwide

* [Twitter #rstats](https://twitter.com/search?q=rstats)
* [Stackoverflow #r topic](http://stackoverflow.com/questions/tagged/r)
* [Stackoverflow #ggplot2 topic](http://stackoverflow.com/questions/tagged/ggplot2)
* [Spatial StackExchange](http://gis.stackexchange.com/)
* [R spatial mailing list](https://stat.ethz.ch/mailman/listinfo/r-sig-geo)
* [R help mailing list](https://stat.ethz.ch/mailman/listinfo/r-help)


## The Good Stuff

[BOOK Happy Git and GitHub for the useR](http://happygitwithr.com/)

[VIDEO Happy Git and GitHub ](https://www.rstudio.com/resources/videos/happy-git-and-gihub-for-the-user-tutorial/)

[BOOK R Packages (Chapter git)]( http://r-pkgs.had.co.nz/)

## Cheatsheets

[RStudio IDE Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2016/01/rstudio-IDE-cheatsheet.pdf)

[Package Development Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2015/06/devtools-cheatsheet.pdf)

## RStudio and devtools

https://cran.r-project.org/web/packages/devtools/README.html

* RStudio and GitHub together are very powerful
* install_github
* check out package 
* create package, start version control, link to GitHub
* Travis, Appveyor, covr, badges, R-hub, 

Key tricks

```R
devtools::create("../newpkg")

devtools::use_readme_rmd()

devtools::use_vignette("")

devtools::build()  ## Ctrl/Cmd-SHIFT-B

devtools::check()  ## Ctrl/Cmd-SHIFT-E

devtools::release()
```
