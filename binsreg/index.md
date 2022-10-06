# BINSREG

The `binsreg` package provides Python, R and Stata implementations of binscatter methods, including partition selection, point estimation, pointwise and uniform inference methods, and graphical procedures. 

This work was supported in part by the National Science Foundation through grants [SES-1947805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947805) and [SES-2019432](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2019432).

## Queries and Requests

Please email: [binsreg@googlegroups.com](mailto:binsreg@googlegroups.com)

## Major Upgrades

This package was first released in Winter 2019, and had one major upgrade in Summer 2021.

- _Summer 2021 new features include_: (i) generalized linear models (logit, Probit, etc.) binscatter; (ii) quantile regression binscatter; (iii) new generic specification and shape restriction hypothesis testing function (now including Lp metrics); (iv) multi-group comparison of binscatter estimators; (v) generic point evaluation of covariate-adjusted binscatter; (vi) speed improvements and optimization. A complete list of upgrades is here: [UPGRADES](https://nppackages.github.io/binsreg/binsreg_upgrades.txt)


## Python Implementation

To install/update in Python type:
```
pip install binsreg
```

- Help: [PyPI repository](https://pypi.org/project/binsreg/).

- Replication: [py-script](https://github.com/nppackages/binsreg/blob/master/Python/binsreg_illustration.py), [plot illustration](https://github.com/nppackages/binsreg/blob/master/Python/binsreg_illustration_plot.py), [data](https://github.com/nppackages/binsreg/blob/master/Python/binsreg_sim.csv).

## R Implementation

To install/update in R type:
```
install.packages('binsreg')
```

- Help: [R Manual](https://github.com/nppackages/binsreg/blob/master/R/binsreg.pdf), [CRAN repository](https://cran.r-project.org/package=binsreg).

- Replication: [R-script](https://github.com/nppackages/binsreg/blob/master/R/binsreg_illustration.R), [plot illustration](https://github.com/nppackages/binsreg/blob/master/R/binsreg_illustration_plot.R), [data](https://github.com/nppackages/binsreg/blob/master/R/binsreg_sim.csv).

## Stata Implementation

To install/update in Stata type:
```
net install binsreg, from(https://raw.githubusercontent.com/nppackages/binsreg/master/stata) replace
```

- Help: [binsreg](https://github.com/nppackages/binsreg/blob/master/stata/binsreg.pdf), [binslogit](https://github.com/nppackages/binsreg/blob/master/stata/binslogit.pdf), [binsprobit](https://github.com/nppackages/binsreg/blob/master/stata/binsprobit.pdf), [binsqreg](https://github.com/nppackages/binsreg/blob/master/stata/binsqreg.pdf), [binstest](https://github.com/nppackages/binsreg/blob/master/stata/binstest.pdf), [binspwc](https://github.com/nppackages/binsreg/blob/master/stata/binspwc.pdf), [binsregselect](https://github.com/nppackages/binsreg/blob/master/stata/binsregselect.pdf).

- Replication files: [do-file](https://github.com/nppackages/binsreg/blob/master/stata/binsreg_illustration.do), [plot illustration](https://github.com/nppackages/binsreg/blob/master/stata/binsreg_illustration_plot.do), [data](https://github.com/nppackages/binsreg/blob/master/stata/binsreg_simdata.dta), [speed test](https://github.com/nppackages/binsreg/blob/master/stata/binsreg_speedcomparison.do).

## Repository

For source code and related files, visit [`binsreg` repository](https://github.com/nppackages/binsreg/).


## References

### Software and Implementation

- Cattaneo, Crump, Farrell and Feng (2022): [Binscatter Regressions](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2022_Stata.pdf).<br>
Working paper, prepared for _Stata Journal_.

### Technical and Methodological

- Cattaneo, Crump, Farrell and Feng (2022): [On Binscatter](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2022_Binscatter.pdf).<br>
Working paper.<br>
[Supplemental Appendix](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2022_Binscatter--Supplemental.pdf)

<br><br>

