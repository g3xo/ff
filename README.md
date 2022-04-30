# Name Influence in Songs

**## Authors**
Kalvin Lee (kalvintlee@hotmail.com)
Thomas Lee (tqlee@uw.edu)
Nicole Han (han1223@uw.edu)
Grace Yim (gyyim@uw.edu)

**## Abstract**
Our main question focuses on whether the use of specific names mentioned in songs increases or decreases a song's popularity. In our society, the name value is something of important representation, and often, the names create a particular image of what it is mentioned in, drastically influencing the general public opinions. We will look into some of the most popular songs that include names and see if the name value of that person had a possible correlation with how the song charted.

**## Keywords**
Names-in-songs, Popularity, Streams, Name Influence

**## Introduction**
For our project, we will be looking at how the name mentioned in the song lyrics had a possible correlation to how well the song charted and if the audience of the song listeners had a correlation. The main questions we want to look more into are:

- Does the name included in a song boost or decrease a song's popularity?
- Does the name bring in a specific listening audience?
- Is the short part of the name being mentioned have a strong influence on the overall image and connotation of the song?
- Finally, what type of name is the most preferred in song lyrics?

Firstly, we will look at songs that have famous and prominent names and look at the data of how each song with that name charted and got streamed overall. Then, we will utilize the database from The Pudding to dig deeper and do further research on the overall ties. Our team was motivated to explore this area after recalling how the rapper Drake mentioned the names of famous footballers Lionel Messi and Cristiano Ronaldo in his song, which led to a wave of interest from football fans to be interested in this released song.

Names and words have a lot of power and influence, and we believe it will be meaningly and essential to research how this can also translate to the music industry specifically.

**## Related Work**
	For our topic, we wanted to find various trends within song lyrics, in particular, the use of names within song lyrics. Artists throughout the decades have used lyrics to portray emotion, and provide understanding. Those artists can influence listeners, creating positive or negative perceptions, through their lyrics. Hopefully, through our findings we are able to see trends in names throughout the decades. The related work to our topic consists of understanding brand names within music, the influence of media as a whole on names, and understanding the obsession with names starting with the letter J, in music.

The first related work comes from a research study by Clay Craig, Mark Flynn, and Kyle Holody. They researched name dropping brands or celebrities within song lyrics, and how male artists used those terms more frequently, and that the genre of rap contained the most mentions. This is related to our topic because we are looking to understand similar ideas but instead of brands, we are searching through the use of names within lyrics. The next related work comes from a research study by Heidi Vandebosch, trying to associate names to various social characteristics, seeing if media has consciously or unconsciously influenced the perception of various names. This work is related to our focus because there could be a correlation on why certain names appear more than others in lyrics. The last related work comes from an article by Ben Blatt, where he suggests reasons to why music is obsessed with names starting with the letter J. Hopefully, through our research, we can confirm this point, but it is also interesting to see if certain names are distinct to certain genres of music.

## The Dataset
The dataset we decided to use is called names-in-songs, which we found on The Pudding. The data was collected by self-proclaimed ‘data lover, storyteller, and pro question asker’ Amber Thomas, for an article she wrote for the Pudding in May 2019. The article analyzes the trends of names that appear in lyrics of the songs that appear on the US Billboard Hot 100 list.
The songs that were chosen for this dataset appeared on the US Billboard Hot 100 list at least once since it began in 1958. The lyrics of these songs were then extracted from Metro Lyrics and analyzed for containing a name. Out of the over 15,000 songs that made an appearance on the top 100, 5,195 contained a name. To identify names within the lyrics, Amber cross examined the lyrics with the US national-level baby name data from the Social Security Administration, using only the names that have appeared at least 5,000 times since 1950. This resulted in 3,607 names to be searched for. Using a R package called ‘udpipe’, Amber was able to eliminate names that appeared as parts of speech, for example the name “Will” would not be accidentally counted when the phrase “I will do…” appeared. However, there is always the chance that song lyrics being grammatically incorrect could have caused some names to slip through this filter. Additionally, a few more corrections were manually made and audited to ensure the quality of the data.
The dataset has 20,626 rows, each representing a single line in a song, and 8 columns. When working with this data set, it is important to keep in mind the source of the song list. The songs that the lyrics are pulled from are from the Top 100 charts of the US market, and the songs that make that list are generally influenced mostly by sales. Thus, this dataset leaves out tens of thousands of songs that are published by smaller artists.

**## Implications**
Firstly, by identifying the most used or popular names in songs, the most basic question we can answer is how popular specific names are. Then, we can find what names are preferable. If technologists go deeper into the data, they can also find which names are popular across different cultures. One interesting thing that can be used with the names is to see whether the names have positive or negative connotations linked to them. Especially from rap music all the way to ballad music, we can see that names are associated with specific actions like drugs, sex, love, etc…and these can be seen as stereotypes but with the data, technologists can try to confirm if these stereotypes are true or false. From these findings of popular names appearing in songs, we can also try to find which names are on the rise and which names are also getting less popular.

**## Challenges & Limitations**
Even though the data set is fairly up to date with the dataset including the Hot 100 US Billboard List , the popularity of music is something that keeps constantly changing and evolving. The songs that were once popular in 2019 is drastically different than the songs that are popular now. In addition, the refernces and names mentioned in 2022 are also very different.  This might lead to inaccurate data if we wanted to use it to draw and make conclusions about the usage of names in popular songs. US songs are not the only popular songs that are listened to globally and nationally in the US. For example, Asian countries like South Korea and Hispanic countries that produce Spanish songs are just an example of popular music that include names in their songs. If this was part of the dataset, the variety of the data set would be more accurate.

**## Acknowledgments**
Blatt, B. (2014, July 29). Which names appear the most in pop songs? we have the data. Slate Magazine. Retrieved April 29, 2022, from https://slate.com/culture/2014/07/most-common-names-in-songs-why-is-pop-music-obsessed-with-songs-about-johnny-jenny-and-jane.html
Flynn, M. A., Holody, K. J., & Craig, C. (2017, February 6). Name dropping and product mentions: Branding in popular music lyrics. Taylor & Francis. Retrieved April 29, 2022, from https://www.tandfonline.com/doi/full/10.1080/10496491.2016.1267679
Vandebosch, H. (2013, July 19). The influence of media on given names. Taylor & Francis. Retrieved April 29, 2022, from https://www.tandfonline.com/doi/abs/10.1179/nam.1998.46.4.243
