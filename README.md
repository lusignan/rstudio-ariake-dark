# rstudio-ariake-dark
Full RStudio IDE port of [Ryosuke Goto](https://github.com/pathtrk)'s [Ariake Dark theme](https://github.com/pathtrk/ariake-dark-syntax)

<figure>
    <img src="https://github.com/lusignan/rstudio-ariake-dark/blob/main/img/ariake-dark-preview.png"
         alt="Ariake Dark">    
</figure>

## Installation
To install, download the folder, unzip, and open RStudio. From RStudio click Preferences, Appearance, Add, and then navigate to the rstheme for the theme that you'd like to install. Click apply.

If you're comfortable installing from the console and have [Devtools](https://github.com/r-lib/devtools) installed then you can copy and run the following in your console:

```r
rstudioapi::addTheme("https://raw.githubusercontent.com/lusignan/rstudio-ariake-dark/main/ariake-dark.rstheme", apply = TRUE)
```

## Acknowledgements
* Theme by [Ryosuke Goto](https://github.com/pathtrk)
* RStudio port was largely built using [Garrick Aden-Buie](https://github.com/gadenbuie)'s [rsthemes package](https://github.com/gadenbuie/rsthemes)
* Sample code comes from [R for Data Science](https://r4ds.had.co.nz/)
