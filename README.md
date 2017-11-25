### Introduction

There are 2 csv files and a subfolder:<br>
•db500.csv<br>
•itemGenres.csv<br>
•treemap<br>

Let's describe each of these elements.

###THE DATABASE

db500.csv is a database with the 500 biggest movie production budgets of Hollywood. <br>
The database was initially made with data from [the Numbers](http://www.the-numbers.com/movie/budgets/all), then I added data from wikipedia and IMBd.
Let´s describe the 30 variables:<br>

**Release.Date** the release Date of a movie in the format: mm/dd/yy from the numbers  <br>
**Movie** The name of the movie from the numbers<br>
**Production.Budget**  the production budget in dollars from the numbers<br>
**Domestic.Gross** the domestic gross revenue in dollars from the numbers<br>
**Worldwide.Gross**  the worldwide gross revenue in dollars from the numbers<br>
**Rate** the rate that a movie received from imbd<br>
**Raters**  the number of persons that gave a rate to a movie from imbd<br>
**Genres** the movie genre from imbd<br>
**imdbUrl**  the imbd url of the movie            <br>
**Directed.by** the name of the person that directed the movie<br>
**Produced.by**  the name of the person that produced the movie<br>
**Written.by** the name of the person that write the story of the movie<br>
**Starring**  the list of actors that participate to the movie <br>
**Music.by** the name of the author of the music<br>
**Cinematography**       <br>
**Edited.by** the name of the editor<br>
**Production.company** the name of the production company<br>
**Distributed.by** the name of the distributor company<br>
**Release.date**  the release date from wikipedia<br>
**Running.time** the length of movie in minutes from wikipedia<br>
**Country**  the country where the movie was produce<br>
**Language** The original language of the movie from wikipedia<br>
**Budget** the production budget in dollars from wikipedia <br>
**Box.office** The box office (worldwide gross revenue) in dollars from wikipedia<br>
**wikiUrl** The wikipedia url from wikipedia<br>
**image** the url of the movie affiche from wikipedia<br>
**Screenplay.by**        <br>
**Story.by** the name of the person that wrote the original (story). <br>
If the story comes from a book. Here the book author will be displayed.
**Based.on**  the name of the original story. <br>
If the story comes from a book. Here the name of book will be displayed.    <br>
**Production.companies** the name of the production company if there is more than just 1.<br>

###TRANSACTION DATA

In the file itemGenres.csv, you will find the different combination of genres that we find in the database db500.csv. <br>
This file has been made to use association rules with R (you can use the package `arules`).<br>

#TREEMAP

In this folder, you will find the different composent to display an interactive treemap like [this one](https://codepen.io/wooza/pen/eeEjLw).<br><br>


Enjoy this script and if you have any issues to make it work correctly, you can always contact me via [my blog](www.blog.rdata.lu) or [my mail](mailto:kevin.rosamont@rdata.lu).