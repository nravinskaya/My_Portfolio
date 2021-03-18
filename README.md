Welcome to my simple data science portfolio ))

## [Project 1: Predicting the correctness of exercise performance](https://github.com/nravinskaya/practicalMachineLearning)

The goal of this project is to predict how people performed exercises based on data about personal movement that were collected from accelerometers on their bodies.

I built four models, two for each algorithm **random forest** and **decision tree**, using several R packages (`caret`, `randomForest`, `rpart`). Based on the results of the accuracy assessment, the first of the considered models was selected to complete the final test. As a result of applying my machine learning algorithm to the test data, **all cases were predicted correctly**.

### [**View full report**](https://nravinskaya.github.io/practicalMachineLearning/index.html)

![](/images/rpart1-1.png)

## [Project 2: Next word prediction (Pitch)](https://rpubs.com/NRavinskaya/707928)

My Shiny App suggests one or more words that could continue your phrase, based on the words you typed in English. 

I used the bag of words method: the text is analyzed as a multiset of its words, disregarding grammar and word order but keeping multiplicity. The frequency of occurrence of each word or some combinations of words used as a feature for training a classifier.

The original [dataset](https://d396qusza40orc.cloudfront.net/dsscapstone/dataset/Coursera-SwiftKey.zip) contains snippets of text from Twitter, blogs and news. They've been cleaned up, combined and tokenized. Then generated sets of n-grams were sorted, leaving only those variants that occurred at least twice, and saved for the purposes of prediction. These sets are loaded each time the application starts and are used to create lists of what entries each word appears in. The intersection of the sets for the words you typed gives predictions.

I am not allowed to publish the complete code of this project, but here you can see my [milestone report](https://rpubs.com/NRavinskaya/671485) on a small amount of data. In the final version, no sampling was done and the complete dataset was cleaned up and tokenized using more efficient techniques to avoid memory overload and at the same time build and index as many n-grams as possible. 

### [**View my app**](https://nravinskaya.shinyapps.io/capstoneapp/)

![](/images/CapstoneApp.png)

## [Project 3: Web page created with Leaflet](https://github.com/nravinskaya/WebPageCreatedWithLeaflet)

Here is an interactive map of Berlin with filming locations of some of my favorite movie.


- Each movie has its own color for the circles on the map.
- Each circle is a specific place in the city, and if you click on it, the name of the place will pop up.
- All place and movie names are links to wiki articles.

Zoom it!  
Click on everything!

Berlin is an incredibly interesting city. Discoveries can be made around every turn. And there are many fascinating stories everywhere.  

### [**View Web Page**](https://nravinskaya.github.io/WebPageCreatedWithLeaflet/index.html)

![](/images/WebpageLeaflet.png)

