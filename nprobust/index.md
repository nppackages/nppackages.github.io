# NPROBUST

The `nprobust` package provides R and Stata implementations of bandwidth selection, point estimation and inference procedures for nonparametric kernel-based density and local polynomial methods.

This work was supported by the National Science Foundation through grant [SES-1459931](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1459931) and [SES-1947805](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1947805).

## Queries and Requests

Please email: [nprobust@googlegroups.com](mailto:nprobust@googlegroups.com)

## R Implementation
To install/update in R type:
```
install.packages('nprobust')
```

- Help: [R Manual](https://cran.r-project.org/web/packages/nprobust/nprobust.pdf), [CRAN repository](https://cran.r-project.org/package=nprobust).

- Replication: [R-script](https://github.com/nppackages/nprobust/blob/master/R/nprobust_illustration.R), [nprobust_data](https://github.com/nppackages/nprobust/blob/master/R/nprobust_data.csv).

## Stata Implementation

To install/update in Stata type:
```
net install nprobust, from(https://raw.githubusercontent.com/nppackages/nprobust/master/stata) replace
```

- Help: [kdrobust](https://github.com/nppackages/nprobust/blob/master/stata/kdrobust.pdf), [kdbwselect](https://github.com/nppackages/nprobust/blob/master/stata/kdbwselect.pdf), [lprobust](https://github.com/nppackages/nprobust/blob/master/stata/lprobust.pdf), [lpbwselect](https://github.com/nppackages/nprobust/blob/master/stata/lpbwselect.pdf).

- Replication: [do-file](https://github.com/nppackages/nprobust/blob/master/stata/nprobust_illustration.do), [nprobust_data](https://github.com/nppackages/nprobust/blob/master/stata/nprobust_data.dta).

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

- Calonico, Cattaneo and Farrell (2022): [Coverage Error Optimal Confidence Intervals for Local Polynomial Regression](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2022_Bernoulli.pdf).<br>
_Bernoulli_, forthcoming.<br>
[Supplemental Appendix](https://nppackages.github.io/references/Calonico-Cattaneo-Farrell_2022_Bernoulli--Supplement.pdf).

<br><br>
