Stat 521 Final Project by: homoBayesians
========================================================
author: Thomas Fleming, Eden Huang, Blaire Li, Marc Ryser
date: May 1, 2017 
autosize: true

Price By Neighborhood
========================================================
title: false
<img src="Slides-figure/myplot-1.png" title="plot of chunk myplot" alt="plot of chunk myplot" width="1920px" height="1100px" style="display: block; margin: auto;" />

Price By Total Square Footage and Overall Quality
========================================================
title:false
<img src="Slides-figure/myplot1-1.png" title="plot of chunk myplot1" alt="plot of chunk myplot1" width="1920px" height="1100px" style="display: block; margin: auto;" />

Visualizations Rejected by the Group
=========================================================
title:false
<img src="Slides-figure/myplot2-1.png" title="plot of chunk myplot2" alt="plot of chunk myplot2" width="1920px" height="1100px" style="display: block; margin: auto;" />

Rejected Graphic
==========================================================
title:false
<img src="Slides-figure/myplot3-1.png" title="plot of chunk myplot3" alt="plot of chunk myplot3" width="1920px" height="1100px" style="display: block; margin: auto;" />

(Statisticians do it with) Models
==========================================================
- The explanatory variables for our simple model included log(Lot.Area), Neighborhood, Condition.1, Overall.Qual, Overall.Cond, HouseAge, Foundation, Bsmt.Qual, Bsmt.Exposure, log(Total.Bsmt.SF), Central.Air, Baths, Kitchen.AbvGr, Kitchen.Qual, Functional, Fireplaces, Garage.Cars, Paved.Drive, log(TotalSq)
- The explanatory variables for our complex model, complete with interactions, included log(Lot.Area), Condition.1, Overall.Qual, Baths, Neighborhood, Garage.Cars, log(Total.Bsmt.SF), log(TotalSq), Overall.Cond, HouseAge, Foundation, Bsmt.Qual, Bsmt.Exposure, Heating.QC, Central.Air, Bedroom.AbvGr, Kitchen.AbvGr, Kitchen.Qual, Functional, Fireplaces, Paved.Drive, Overall.Qual:Garage.Cars, Overall.Qual:log(TotalSq), Garage.Cars:log(TotalSq), Overall.Qual:Garage.Cars:log(TotalSq)
- And of course, we logged our response variable.

===========================================================

The End

