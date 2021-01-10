# Movie Plot Sentiments

*The idea is to plot the emotion of the story in a graph. So that we can literally "see" the roller coaster of emotions the movie has to offer.*
___

### Procedure

* A python program that uses the text-blob library to gauge the sentiments of the movie plot one sentence at a time.

* We just copy the plot from wikipedia and paste the plot of as a string variable in python.

* Then clean the string for numbers, special characters and citation numbers that are usually present in a wikipedia content.

* Split the large string into single sentences using fullstops as the divider.

* Import TextBlob and input the whole plot pragraph line by line in a FOR loop and let TextBlob do its magic. Copy the resulting list of numbers(sentiments value) to an excel/csv file and plot the graph.
___

### Some Examples

```X axis: Nth sentence in the plot```

```Y axis: Polarity of the sentence (1.0=positive, 0.0=neutral, -1.0=negative)```

* [Avatar](https://en.wikipedia.org/wiki/Avatar_(2009_film)) (English)
<img src="https://raw.githubusercontent.com/sarathsajan/movie-plot-sentiments/master/avatar.JPG">
<br>
<br>

* [Drishyam](https://en.wikipedia.org/wiki/Drishyam) (Malayalam)
<img src="https://raw.githubusercontent.com/sarathsajan/movie-plot-sentiments/master/drishyam.JPG">
<br>
<br>

* [Joker](https://en.wikipedia.org/wiki/Joker_(2019_film)) (English)
<img src="https://raw.githubusercontent.com/sarathsajan/movie-plot-sentiments/master/joker.JPG">
<br>
<br>

* [Lucifer](https://en.wikipedia.org/wiki/Lucifer_(film)) (Malayalam)
<img src="https://raw.githubusercontent.com/sarathsajan/movie-plot-sentiments/master/lucifer_malayalam.JPG">
<br>
<br>

* [Manichitratazhu](https://en.wikipedia.org/wiki/Manichitrathazhu) (Malayalam)
<img src="https://raw.githubusercontent.com/sarathsajan/movie-plot-sentiments/master/manichitrathazhu.JPG">
<br>
<br>

* [Titanic](https://en.wikipedia.org/wiki/Titanic_(1997_film)) (English)
<img src="https://raw.githubusercontent.com/sarathsajan/movie-plot-sentiments/master/titanic.JPG">
