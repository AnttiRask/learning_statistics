![](img/youcanbeapirate-wb-sparkline.jpg)
 
# Learning ggplot2

I'm learning __statistics__ by reading the book __Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python (2nd ed.)__ by __Peter Bruce, Andrew Bruce & Peter Gedeck__.

The idea of this repo is to host a modified version of the R code provided in the book and in the [official GitHub repo](https://github.com/gedeck/practical-statistics-for-data-scientists).

So why have my own version of the code for something already available through that link I shared?

1. __Fixing Broken Code__: Some of the code that is repo only (as in not in the book) had obvious bugs in it. References to missing variables etc. The code I have here works (at least at the time of writing, you know how it is).
2. __Readability__: I take readability seriously. I try to adhere to the [Tidyverse Style Guide](https://style.tidyverse.org/), but I don't claim to be perfect about it. Always room to grow!
3. __Tidyverse__: Although some code is already written with __{tidyverse}__, I've translated the rest of the base R code to a tidier format. Where it was possible and/or made sense, that is. I've taken special care to recreate the plots using __{ggplot2}__ instead of the _plot()_ function from base R.

Although I like the [__{tidymodels}__](https://www.tidymodels.org/) framework, I decided not to use it for the Machine Learning (ML) examples in this book. You know, to keep the focus on the statistics part. If you're interested, check out my other repo, [Learning Machine Learning](https://github.com/AnttiRask/learning_machine_learning).

## Disclaimer!
This repo is not meant to replace the book in any way. You should definitely read the book. It will help you understand the concepts much better than looking at the code or playing with it.

Also, I would recommend you buy the book. Here's a direct [link](https://www.oreilly.com/library/view/practical-statistics-for/9781491952955/) to __O'Reilly__'s (the publisher) website.
