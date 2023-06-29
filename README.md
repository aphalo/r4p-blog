# r4p-blog
Web site sources using [Quarto](https://quarto.org).

The rendered website is published at [https://www.r4photobiology.info/](https://www.r4photobiology.info/).

The site looks o.k. when built with Quarto 1.2.x (and Quarto included in RStudio 2023.03.0), quite bad with Quarto 1.3.x (and Quarto included in RStudio 2023.06.0), but is again o.k. with the pre-release of Quarto 1.4.x. The problem is that Quarto 1.3.x does not pass the Mermaid directive "htmlLabels" and so HTML markup shows up in the final flowcharts.
