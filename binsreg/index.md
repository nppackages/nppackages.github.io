# BINSREG

The `binsreg` package provides Python, R and Stata implementations of binscatter methods, including partition selection, point estimation, pointwise and uniform inference methods, and graphical procedures. 

This work was supported in part by the National Science Foundation through grants [SES-1947805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947805) and [SES-2019432](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2019432).

## Queries and Requests

Please email: [binsreg@googlegroups.com](mailto:binsreg@googlegroups.com)

## Major Upgrades

This package was first released in Winter 2019, and had one major upgrade in Summer 2021.

- _Summer 2021 new features include_: (i) generalized linear models (logit, Probit, etc.) binscatter; (ii) quantile regression binscatter; (iii) new generic specification and shape restriction hypothesis testing function (now including Lp metrics); (iv) multi-group comparison of binscatter estimators; (v) generic point evaluation of covariate-adjusted binscatter; (vi) speed improvements and optimization. A complete list of upgrades is here: [UPGRADES](https://nppackages.github.io/binsreg/binsreg_upgrades.txt)


## Python Implementation

Coming soon.

## R Implementation

To install/update in R type:
```
install.packages('binsreg')
```

- Help: [R Manual](https://raw.githubusercontent.com/nppackages/binsreg/master/R/binsreg.pdf), [CRAN repository](https://cran.r-project.org/package=binsreg).

- Replication: [R-script](https://raw.githubusercontent.com/nppackages/binsreg/master/R/binsreg_R_illustration.R), [data](https://raw.githubusercontent.com/nppackages/binsreg/master/R/binsreg_sim.csv).

## Stata Implementation

To install/update in Stata type:
```
net install binsreg, from(https://raw.githubusercontent.com/nppackages/binsreg/master/stata) replace
```

- Help: [binsreg](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binsreg.pdf), [binslogit](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binslogit.pdf), [binsprobit](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binsprobit.pdf), [binsqreg](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binsqreg.pdf), [binstest](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binstest.pdf), [binspwc](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binspwc.pdf), [binsregselect](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binsregselect.pdf).

- Replication files: [do-file](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binsreg_illustration.do), [data](https://raw.githubusercontent.com/nppackages/binsreg/master/stata/binsreg_simdata.dta), [speed test](https://raw.githubusercontent.com/nppackages/binsreg/blob/master/stata/binsreg_speedcomparison.do).

## Repository

For source code and related files, visit [`binsreg` repository](https://github.com/nppackages/binsreg/).


## References

### Software and Implementation

- Cattaneo, Crump, Farrell and Feng (2021): [Binscatter Regressions](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2021_Stata.pdf).<br>
Working paper, prepared for _Stata Journal_.

### Technical and Methodological

- Cattaneo, Crump, Farrell and Feng (2021): [On Binscatter](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2021_Binscatter.pdf).<br>
Working paper.<br>
[Supplemental Appendix](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2021_Binscatter--Supplemental.pdf)

<br><br>

