# High speed fluorescence image-enabled cell sorting

This R package contains documented R markdown files to reproduce data figures in the paper "High-speed fluorescence image-enabled cell sorting" by Schraivogel et al., 2022 (DOI: 10.1126/science.abj3013).

## Installation

The package can then be installed using R/devtools. 

```{r}
devtools::install_github('benediktrauscher/ICS2022')
```

or from the command line after cloning the repository:

```{sh}
git clone https://github.com/benediktrauscher/ICS.git
cd ICS2022/
R CMD INSTALL
```

To view the analyses in R, type

```{r}
browseVignettes('ICS')
```

## Contact

Should you encounter any issues or have any questions please contact [Benedikt Rauscher](https://www-db.embl.de/EMBLPersonGroup-PersonPicture/MailForm/?recipient=CP-60033565) or [Daniel Schraivogel](https://www-db.embl.de/EMBLPersonGroup-PersonPicture/MailForm/?recipient=CP-60023563).
