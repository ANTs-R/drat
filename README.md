# ANTsR

Drat repository for ANTsR and dependencies



###install R-package drat
```r
install.packages("drat")
```
###Install ANTsR

```r
drat::addRepo("ANTs-R")
install.packages("ANTsR")
```

###Update ANTsR (together with other R-packages)
```r
drat::addRepo("ANTs-R")
update.packages()
```
You can add the ANTsR repo permanently by adding the line ```drat::addRepo("ANTs-R")``` to ~/.Rprofile.
