# NPROBUST

The `nprobust` package provides Stata and R implementations of bandwidth selection, point estimation and inference procedures for nonparametric kernel-based density and local polynomial methods.

This work was supported by the National Science Foundation through grant [SES-1459931](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1459931) and [SES-1947805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947805).

## Stata Implementation

To install/update in Stata type:
```
net install nprobust, from(https://raw.githubusercontent.com/nppackages/nprobust/master/stata) replace
```

- Help: [kdrobust](https://raw.githubusercontent.com/nppackages/nprobust/master/stata/kdrobust.pdf), [kdbwselect](https://raw.githubusercontent.com/nppackages/nprobust/master/stata/kdbwselect.pdf), [lprobust](https://raw.githubusercontent.com/nppackages/nprobust/master/stata/lprobust.pdf), [lpbwselect](https://raw.githubusercontent.com/nppackages/nprobust/master/stata/lpbwselect.pdf).

- Replication: [do-file](https://raw.githubusercontent.com/nppackages/nprobust/master/stata/nprobust_illustration.do), [nprobust_data](https://raw.githubusercontent.com/nppackages/nprobust/master/stata/nprobust_data.do).

## R Implementation
To install/update in R type:
```
install.packages('nprobust')
```

- Help: [R Manual](https://cran.r-project.org/web/packages/nprobust/nprobust.pdf), [CRAN repository](https://cran.r-project.org/package=nprobust).

- Replication: [R-script](https://raw.githubusercontent.com/nppackages/nprobust/master/R/nprobust_illustration.r), [nprobust_data](https://raw.githubusercontent.com/nppackages/nprobust/master/R/nprobust_data.csv).

## Repository

For source code and related files, visit [`nprobust` repository](https://github.com/nppackages/nprobust/).


## References

### Software and Implementation

- Calonico, Cattaneo and Farrell (2019): [nprobust: Nonparametric Kernel-Based Estimation and Robust Bias-Corrected Inference](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2019_JSS.pdf).<br>
_Journal of Statistical Software_ 91(8): 1-33.

### Technical and Methodological

- Calonico, Cattaneo and Farrell (2018): [On the Effect of Bias Estimation on Coverage Accuracy in Nonparametric Inference](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2018_JASA.pdf).<br>
_Journal of the American Statistical Association_ 113(522): 767-779.<br>
[Supplemental Appendix](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2018_JASA--Supplement.pdf).

- Calonico, Cattaneo and Farrell (2020): [Coverage Error Optimal Confidence Intervals for Local Polynomial Regression](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2020_CEopt.pdf).<br>
Working paper.<br>
[Supplemental Appendix](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2020_CEopt--Supplemental.pdf).

<br><br>
