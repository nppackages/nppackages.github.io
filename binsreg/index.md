# BINSREG

The `binsreg` package provides Stata and R implementations of binscatter methods, including partition selection, point estimation, pointwise and uniform inference methods, and graphical procedures. 

This work was supported in part by the National Science Foundation through grants [SES-1947805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947805) and [SES-2019432](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2019432).

## Queries and Requests

Please email: binsreg.package@gmail.com

## Major Upgrades coming in Fall 2020:

- L2 and other metrics for hypothesis testing.

- New command/function binsreglincom for testing of linear combinations across subgroups (e.g., H0: mu1(x)=mu2(x) for all x). For now, see option by() for joint plotting of marginal confidence bands.

- New command/function binsxtreg for panel data estimation, inference and binned scatter plots. For now, in Stata use the command i. or ib(). for incorporating fixed effects (as with the regress command).

- Handling of formulas in R package.

- Recentering of binscatter estimate of \mu(x) to account for additional covariates. For now, the package sets additional covariates at zero.

- Backwards compatibility with Stata 13. For now, Stata 14 or better is needed.

## Stata Implementation

To install/update in Stata type:
```
net install binsreg, from(https://raw.githubusercontent.com/nppackages/binsreg/master/stata) replace
```

- Help: [binsreg](https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata/binsreg.pdf), [binsregtest](https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata/binsregtest.pdf), [binsregselect](https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata/binsregselect.pdf).

- Replication files: [do-file](https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata/binsreg_illustration.do), [data](https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata/binsreg_simdata.dta), [speed test](https://raw.githubusercontent.com/rdpackages/rdlocrand/master/stata/binsreg_speedtest.do).

## R Implementation

To install/update in R type:
```
install.packages('binsreg')
```

- Help: [R Manual](https://cran.r-project.org/web/packages/binsreg/binsreg.pdf), [CRAN repository](https://cran.r-project.org/package=binsreg).

- Replication: [R-script](R/binsreg_R_illustration.R), [data](R/binsreg_sim.csv).


## References

### Software and Implementation

- Cattaneo, Crump, Farrell and Feng (2019): [Binscatter Regressions](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2019_Stata.pdf).<br>
Working paper.

### Technical and Methodological

- Cattaneo, Crump, Farrell and Feng (2019): [On Binscatter](references/Cattaneo-Crump-Farrell-Feng_2019_Binscatter.pdf).<br>
Working paper.<br>
[Supplemental Appendix](https://nppackages.github.io/references/Cattaneo-Crump-Farrell-Feng_2019_Binscatter--Supplemental.pdf).

<br><br>

