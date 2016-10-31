#### Purpose of project:

In season two of Dexter, Dexter was wanted by the Miami Metro police department for hunting and killing murderers.  Considering the fact that the death penalty is legal in the state of Florida when it comes to capital offences, including murder in the first degree, I set out to understand what the underlying differences were between the death penalty and Dexter’s murders.

Specifically, I was interested in how Dexter’s victims compared to inmates executed on death row.  This inquiry led me to analyze demographic information (including sex, age and occupation) of these two groups.  Eventually, I discovered that I also had access to information regarding the final words of, both, inmates about to be executed on death row and some of Dexter’s victims.  I decided to conduct a comparative linguistic analysis of the tones of the final words of each of these groups.

#### Existing Datasets Used:
* http://www.tdcj.state.tx.us/death_row/dr_executed_offenders.html 
  * __Description__: A list of executed offenders in the state of Texas and their final words

#### Datasets Created & Available:
* Dexter’s Victims
  * Description: A list of Dexter’s known victims and relevant information
  * Column Headings: (age, name, number of victims, occupation, sex, last words, age range)
  * Length: 107 rows
  * Where data was collected from:
   * http://dexter.wikia.com/wiki/Dexter's_Kill_List 
    * __Description__: A list of links leading to pages describing Dexter’s victims
   * http://www.dexterwiki.com/page/Dexter's+Victims 
    * __Description__: A list of some of Dexter’s victims and their final words

#### How data was collected:
* For this project I programmed three separate web scrapers, in order to create two primary datasets (one for information regarding Dexter’s victims and the other for information regarding the inmates who were executed on Texas’s death row).
* I imported bs4-BeautifulSoup, urllib-request and pandas in order to collect the relevant information and create the dataframes.

#### Analysis:
* I used the pandas library to aid in my analysis of the data, alongside bokeh in order to create some rudimentary visualizations.

#### Visualizations:
* I created a total of four visualizations 
* The first two were created using the bokeh library
  * The first was a bar chart with images
  * The second was an interactive visualization with a hover effect
* The final two visualizations were created using mainly the wordcloud and the PIL libraries
  * Both graphics were word cloud representations of text

#### Journal Entries:
* I had the chance to create three web scrapers for this project.  I ran into some unclean data, especially when scraping the wiki blogs, but I have been finding that the ‘try’ and ‘except’ statements in python are becoming my besties.
* This project allowed me to play with making visualizations from the bokeh library for the first time.  Everything was pretty easy going, however I did run into some problems when I tried to embed my interactive visualization into my wordpress blog.  Luckily, I was able to figure it out in the end.  I’m definitely looking forward to experimenting with more advanced interactive visualizations.
* When I created the first draft of my bar graph I was really put off by how uninspired it looked.  I decided to do some research into data journalism and came across two Vox journalists who incorporate creative visualizations into their pieces and my creative juices started trickling.
  * http://www.vox.com/authors/zachary-crockett
  * http://www.vox.com/authors/alvin
   Which is why I decided to add some images to, both, my visualizations and my blog post.  I’m definitely going to make an effort to look for creative inspiration like the two guys I have already found.
* This was my very first blog post and I was surprised to find that the creative writing aspect turned out to be more difficult than anticipated.  Coming from a degree in psychology, I am very used to reading and writing academic papers on experimental procedures.  Unfortunately, upon reading my rough draft I discovered that while writing academically has become second-nature, my ability to write colloquially has taken a mega hit.  So it seems as though I’m going to need to take the extra step of switching my reading habits from google scholar to google. 
