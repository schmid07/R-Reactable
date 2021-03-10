# Which women's programs have been most successful during the NCAA Tournament era?

### **March 10, 2021**  
[Code](https://github.com/schmid07/R-Reactable/blob/main/2020_41_bball_react.rmd) | [Interactive Version](https://schmid07.github.io/R-Reactable/2020_41_bball_react.html)

The first table below was adapted from my Week 41/2020 TidyTuesday post (2nd table) that I also submitted as part of the [R Studio Table Contest](https://blog.rstudio.com/2020/12/23/winners-of-the-2020-rstudio-table-contest/). I had been wanting to explore Greg Lin's `reactable` package and figured using my original post, which used the `gt` package, would be a good starting point.

For anyone just getting started with the `reactable` package, I'd recommend checking out the numerous examples and demos Greg Lin put together [here](https://glin.github.io/reactable/index.html) and also Kyle Ciulla's `reactablefmtr` [package](https://kcuilla.github.io/reactablefmtr/articles/color_scales.html#using-span-1), which helps to simplify implementing various components of `reactable`. Unfortunately, I was about mid-way through putting this table together before coming across `reactablefmtr` (otherwise I would have used it more, especially for adding in the images), but I did use it for the conditional formatting. The `reactablefmtr` package has a ton of other useful features that I'd like to explore in the future.

Some other resources that I found particularly helpful in getting started with `reactable` were Thomas Mock's [blog](https://themockup.blog/) posts [here](https://themockup.blog/posts/2020-05-13-reactable-tables-the-rest-of-the-owl/) and [here](https://themockup.blog/posts/2020-05-29-client-side-interactivity-do-more-with-crosstalk/) and the following TidyTuesday and R Studio Table Contest posts from: 

* Amit Levinson [(Table)](https://amitlevinson.github.io/TidyTuesday/2021/week3_tate/tate_art.html) [(Code)](https://github.com/AmitLevinson/TidyTuesday/blob/master/2021/week3_tate/tate_art.Rmd) 

* Georgios Karamanis [(Table)](https://github.com/gkaramanis/table-contest) [(Code)](https://github.com/gkaramanis/table-contest/blob/main/table-contest.Rmd)   

For anyone interested in learning more about the `crosstalk` aspects of the table which allows for the interactivity between the slider and the search box and the table, again Greg Lin has several helpful examples in his demos (linked above). Emily Riederer also has a really helpful tutorial [here](https://emilyriederer.netlify.app/post/crosstalk/) for getting started with `crosstalk`. A couple other well-done `crosstalk` examples that I came across on Twitter:

* Sue Wallace [(Table)](https://sue-wallace.github.io/fatal-force-with-crosstalk/)
[(Code)](https://github.com/sue-wallace/fatal-force-with-crosstalk/blob/master/01.%20crosstalk.Rmd)   

* Long Nguyen [(Table and Code)](https://rpubs.com/long39ng/702061)

<p align = "center">
<img src = "http://g.recordit.co/9nNMwUNuhW.gif" width = "700">
</p>



### Original TidyTuesday post from Week 41/2020 (using `gt` package) 

[Code](https://github.com/schmid07/TidyTuesday_Weekly_Data_Viz_Challenge/blob/main/Code/2020_41_bball.R)

<p align = "center">
<img src = "https://github.com/schmid07/TidyTuesday/blob/main/plots/2020_41.png" width = "700">
</p>

