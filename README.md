# Web-Design-Challenge
## Assignment and Coding Notes
### I use bootstrap a lot at work, but haven't used version 5 yet. Some of the compoennts I use at work (Like Jumbotron) aren't available. Also, I use some jquery to copy and reformat some of the page elements, and bootstrap 5 removed jquery support.
### This was a good opportunity for me to use some of the new bootstrap 5 features that I haven't used yet 

### All pages
#### Left side of menu
* The "Web Design Challenge" text on the top left always returns the user to the home page (index.html)

#### Right side of menu
* The "Home" text returns the user to the home page (index.html)
* The four plots are listed in a drop-down menu
* The comparisons link takes the user to that page
* The data page takes the user (you guessed it) to the data page

### Index.html
* Used bootstrap 5 cards on the left side of the page. The pics in each card are thumbnails, and take you to each respective analysis page
* I gave each element a shadow background, for appearance
* The text on the right side is a recreation of the Jumbotron component that was available in Bootstrap version 4

### plot1.html (and 2-4)

* The picture and text is a bootstrap card. The text moves to the bottom as the screen resolution is lowered

### comparisons.html
* the four plots and supporting text are added to the page in bootstrap 5 cards, embedded in a bootsrap grid. The page displays two columns for wide/normal screens, and changes to one for smaller resolutions

### data.html
* the data page displays the html that was imported into a dataframe and exported as html using the html_export.ipynb file. I used some bootstrap formatting to alternate the color of the bars, and the hover effect for each bar
