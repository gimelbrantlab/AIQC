
# QCumber (v0.3.2) - obsolete (replaced with renamed version [Qllelic](https://github.com/gimelbrantlab/Qllelic), due to naming conflict with already existing QCumber software)

**QCumber** is a set of R tools for quantification of allele-specific expression. It relies on two or more technical replicate RNA-seq libraries to calculate Quality Correction Constant (QCC) and use it to correct for allelic imbalance overdipserion.
**QCumber** analysis starts with a table of allelic counts per gene, calculated from RNA-seq data using any analysis pipeline such as **[ASEReadCounter*](https://github.com/gimelbrantlab/ASEReadCounter_star)**.

Mendelevich A.\*, Vinogradova S.\*, Gupta S., Mironov A., Sunyaev S., Gimelbrant A.  _"Unexpected variability of allelic imbalance estimates from RNA sequencing"_. [bioRxiv link](https://www.biorxiv.org/content/10.1101/2020.02.18.948323v1)

## Installation

To install current version of this package in R:

``` r
devtools::install_github("gimelbrantlab/QCumber")
```
Installation takes less than 1 minute. To install a specific version: `devtools::install_github("gimelbrantlab/QCumber@v0.3.1")`


## Manual

Full documentation: [pdf document](https://github.com/gimelbrantlab/QCumber/wiki/documentation/QCumber_documentation.pdf).

Please see walk-through examples on the [Wiki page](https://github.com/gimelbrantlab/QCumber/wiki)
* for [QCC calculation and CI estimation](https://github.com/gimelbrantlab/QCumber/wiki/Use-case-1:-One-biological-sample)
* for [AI differential analysis for two samples](https://github.com/gimelbrantlab/QCumber/wiki/Use-case-2:-Differential-AI-analysis)

## Reporting bugs

Please report bugs to the Github [issues](https://github.com/gimelbrantlab/QCumber/issues) page.

## License

[GNU General Public License v3.0](https://github.com/gimelbrantlab/QCumber/blob/master/LICENSE)



