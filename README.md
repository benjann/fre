# fre
Stata module to display one-way frequency table

`fre` displays, for each specified variable, a univariate
frequency table containing counts, percent, and cumulative
percent. Variables may be string or numeric. Labels, in full
length, and values are printed. By default, `fre` only tabulates
the smallest and largest 10 values (along with all missing
values), but this can be changed. Furthermore, values with zero
observed frequency may be included in the tables. The default
for `fre' is to display the frequency tables in the results
window. Alternatively, the tables may be written to a file on
disk, either tab-delimited or LaTeX-formatted.

Stata version 9.2 or newer is required.

Installation from the SSC Archive:

    . ssc install fre, replace

Installation from GitHub:

    . net install fre, replace from(https://raw.githubusercontent.com/benjann/fre/main/)

---

Main changes:

    26may2021 (version 1.2.5)
    - fre released on GitHub
