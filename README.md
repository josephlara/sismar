# sismar <a href="https://usaid-mozambique.github.io/sismar/"><img src="man/figures/logo.png" align="right" height="120" alt="sismar website" /></a>

Criar quadros de dados analíticos a partir de dados brutos do MISAU

## Overview

A análise eficiente de dados rectangulares exportados dos sistemas de informação de saúde do MISAU requer acções de processamento tais como pivotagem, eliminação/coerção de variáveis e engenharia de caraterísticas de dados úteis na análise. O pacote sismar fornece um conjunto de funções que executam essas acções e preparam os quadros de dados para análise no R ou em software analítico alternativo.


## Installation

`sismar` não está no CRAN, então os usuários terão que instalá-lo directamente do GitHub usando o código abaixo.

``` r

    ## SETUP

    # install from GitHub using remotes
      install.packages("remotes")
      remotes::install_github("usaid-mozambique/sismar")
    
    # load the package
      library(sismar)
      
    ## LIST FUNCTIONS INCLUDED WITH PACKAGE
      ls("package:sismar")
    
```

---

*Disclaimer: The findings, interpretation, and conclusions expressed herein are those of the authors and do not necessarily reflect the views of United States Agency for International Development. All errors remain our own.*
