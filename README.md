# UFOs

## Overview of Project
The purpose of this project is to assist Dana in meeting her goal to create an interactive webpage that allows readers to parse the data around UFO sightings. 

### __Requirements__
She essentially needs to build two things: the webpage that will allow users to view the data `(HTML)` and a dynamic table that will present it `(JavaScript)`.
## Results
Read below on how to use the new webpage to filter UFO sightings using specific search criteria. 

### __Search Filter Criteria__ 
Assume you want to view all entries for stitings with the following criteria:
* Date: `1/1/2010`
* City: `el cajon`
* State: `ca`
* Country: `us`
* Shape (keyword): `triangle`

You will navigate to the filter fields and enter the above mentioned criteria. 

Your filter should look like this:

![filter_criteria](https://github.com/hastyjr/UFOs/blob/main/static/images/filter_criteria.png)
### __Search Filter Table Results__
Once you have entered the criteria, you will select the `Filter Table` button.

The following results with will appear:

![filter_results](https://github.com/hastyjr/UFOs/blob/main/static/images/filter_results.png)

You'll notice that there were two entries for UFO sightings on this date with the above mentioned search criteria. 

The table provides data in all these categories and adds more information within the `Comments` column. 

In this case, there are two different entries and comments for our search criteria:

1. _"On New Years Eve I went outside to hear the celebration and fireworks in my neighbor hood. And noticed 3 red lights above my house and..."_
2. _"3 Red objects hovering over El Cajon CA"_

### __Clear Search Filter Table__
To conduct another search, you will want to to hit the `Clear Table` button to clear out all the search criteria and start fresh. 

![clear_table](https://github.com/hastyjr/UFOs/blob/main/static/images/clear_table.png)

You'll notice that when you hit the `Clear Table` button, the text boxes will clear out and the table will reset to to show all entries by default. 

![default_table](https://github.com/hastyjr/UFOs/blob/main/static/images/default_table.png)

## Summary
In a summary statement, describe one drawback of this new design and two recommendations for further development.

One of the drawbacks of this new design is how the filter on the website is not completely accurtate. While it does filter on some attributes, it does not filter out entries that do not apply to the filter. 

Two recommendations for further development would be to implement some dynamic code that will appropriatley filter content on specific attributes within the text boxes. Another recommendation is to implmenet better user experience by providing a drop-downs for options that are available. One example is providing a dropbown for `city`, `country` and `shape`. This would allow a user to easily identify if the city they are looking or is part of this database. 