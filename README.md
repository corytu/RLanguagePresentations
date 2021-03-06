# R Language Presentations
Hello! My name is Yu-Zhen Tu. I am currently a data engineer at [Health2Sync](https://www.health2sync.com/?lang=en-us).

I love R language because it is so powerful in data analyses and in presenting meaningful results. This repository is built to share my works done in R language.

# Project Demonstration

## Personal side projects
* __[Currency Dashboard of NTD](https://corytu.shinyapps.io/currency-dashboard/)__ (Jul 2017)<br>
    * Parse from [Bank of Taiwan](http://www.bot.com.tw/Pages/default.aspx) and present
        1. the latest currency information, and
        2. the latest interest information with interactive plots and tables
    * Compare the exchanges prices between that of today and that of last week
    * Calculate the return of investment if additional information provided
    * [currency-dashboard](https://github.com/corytu/currency-dashboard) is my GitHub repository sharing the source code.
* __[Old Population Proportions in Districts in Taiwan](https://corytu.shinyapps.io/old-population-proportions/)__ (Mar 2017)<br>
This Shiny app illustrates the percentages of old population in every district in Taiwan. It is widely referred in local health authorities in Taiwan, helping the promotion of primary health and creating an elder-friendly society. Last updated in Febuary 2018. The source codes are in another repository of mine: [old-population-proportions](https://github.com/corytu/old-population-proportions).
* [Relationships between Visitor Numbers and Taiwan Economics (Flash Player required)](https://corytu.github.io/r-language-presentations/docs/Relationships_between_Visitor_Numbers_and_Taiwan_Economics.html) (Mar 2017)<br>
The webpage implements `googleVis` package of R and demonstrates the relationships between visitor numbers and multiple economics indexes in Taiwan. Taiwan's economic system seems to have been strongly affected by China. We need to find our way to guarantee our economy growth without China's support if we want independence of our country.

## Assignment of [Practical Machine Learning](https://www.coursera.org/learn/practical-machine-learning/home/info) on Coursera
* [Predicting “How Well” People Perform Dumbbell Lifts](https://github.com/corytu/predict-dumbbell-lifts)<br>
I used support vector machine, decision tree, and random forests techniques to predict whether participants are executing dumbbell lifts correctly. The data were generated from sensors on arm, forearm, belt, and dumbbell respectively. The cross-validations show that random forests have the best accuracy, and the results of random forests have 20/20 correct predictions for the testing dataset.

## Assignments of [Developing Data Products](https://www.coursera.org/learn/data-products/home/info) on Coursera
* [Air quality in New York in 1973](https://corytu.shinyapps.io/airquality/) (Feb 2017)<br>
My first Shiny application uses `airquality` data frame in R and plots the relationship between selected variables. Details are available from [this Slidy presentation](https://corytu.github.io/r-language-presentations/docs/Air_Quality_in_New_York_in_1973.html). [The source code](docs/airquality_app.R) are also uploaded.
* [Taiwan National Parks](https://corytu.github.io/r-language-presentations/docs/Taiwan_National_Parks.html) (Feb 2017)<br>
It shows all nine national parks in Taiwan with `leaflet`. The hyperlinks to each national park are provided once users click the markers.
* [Playing mtcars dataset](https://corytu.github.io/r-language-presentations/docs/play_mtcars_dataset.html) (Feb 2017)<br>
It is a rather simple presentation with `plotly` tool. The data are from R built-in `mtcars` dataset.

# Given Tutorial Slides and Website
* __[Data Viz with R - Shiny](https://corytu.github.io/r-language-presentations/docs/Shiny_Intro.html)__ (Oct 2018)<br>
Hosted an event and shared my Shiny experiences on [Taiwan R User Group / MLDM Monday Meetup](https://www.meetup.com/Taiwan-R/events/254369159/).
* [Coursera Mentoring Records](https://corytu.github.io/coursera-r-mentoring/) (Sep 2018)<br>
Mentoring records and my helping articles on "R Programming", Coursera.
* [R tutorial](https://corytu.github.io/r-language-presentations/docs/R-Tutorial.html) (Jul 2017)<br>
New tutorial slides created with R markdown. Additional practices are provided, compared with the tutorial last year.
* <a href="https://corytu.github.io/r-language-presentations/docs/Plotting_with_R_ggplot2.html">Plotting with R: ggplot2</a> (Mar 2017)<br>
After a brief introduction of R plotting systems, a guidance for creating scatter plots and bar plots including legends and facets for conditions is provided. It also covers methods to add error bars and regression lines. Practices come along so that people can apply their newly learned skills. Slides are done with R markdown.
* <a href="https://github.com/corytu/r-language-presentations/blob/master/docs/R_Tutorial_20161012_BLP.pdf">R Programming tutorial</a> (Oct 2016)<br>
An R tutorial which covers the history and overview of R, the characteristics of various R objects, and vectorized operations. It also contains the functions people use to input/output the data or scripts. The control structures and function writing in R are introduced in the end.

# Other Code Files
* __[my-grid-arrange-shared-legend.R](https://github.com/corytu/r-language-presentations/blob/master/docs/my-grid-arrange-shared-legend.R)__: Arrange grobs with a shared legend. Shared axes are also allowed. Detailed discription is in the .R file. The only needed preparation is downloading and `source` it in R. Required packages will be installed if they cannot be found in library paths.
* [Taiwan-tourism-economics.R](https://github.com/corytu/r-language-presentations/blob/master/docs/Taiwan-tourism-economics.R): Create a motion chart by `googleVis` package, showing some economic indexes and tourist numbers in Taiwan in recent years.

Last update: September 30, 2018