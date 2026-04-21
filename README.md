# Quarto template for a McMaster thesis proposal

This is a [Quarto](https://quarto.org/) article template that will render a thesis proposal document in .pdf using $\LaTeX$\. You can download Quarto here: [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/).

A recommendation for working on Quarto documents is to use Positron, which can be downloaded here: [https://positron.posit.co/download.html](https://positron.posit.co/download.html).

You can view a sample rendered document [here](examples/proposal.pdf).

## Installation

### Using the terminal

You can create a thesis based on this template with the following
command:

``` bash
quarto use template carterjmike/quarto-mcmaster-proposal
```

This will install the extension and create the files that you can use as a starting place for your thesis.

### Using the R console

You can install extensions with the [`quarto`](https://quarto-dev.github.io/quarto-r/) 📦. Note that this is not Quarto itself and instead provides an R interface to frequently used operations in the Quarto Command Line Interface.

If needed, you can install the `quarto` 📦 in the console with:

``` r
# latest release version 
install.packages("quarto")
```

Once installed, you can then run the following in the console:

``` r
quarto::quarto_use_template("carterjmike/quarto-mcmaster-proposal")
```